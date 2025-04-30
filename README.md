# 5skyes-resolume-plugs
A collection of plugins for the live events media server & mograph authoring tool Resolume, under the MIT License. Many are wire plugs, which should be editable. If we've uploaded a non-editable version (.cwired and not .wired), open an issue.


##INSTALATION:

[WINDOWS]
To install these with presets, drop the folder for the effect you want in C:\Users\<USER>\Documents\Resolume Wire\Patches and Arena should automagically see them. 

[MAC]
Don't have a test case for this one, but it should be pretty similar.. check your documents folder.


## PLUGS:

- [Effect] Destroy Alpha (v2)        : A no-frills one-click solution for zeroing out the alpha channel. Might have funny results with straight alpha.

- [Effect] Reaction Diffusion (v1.4) : A versitile, feature-rich (read:heavy) effect implementing a reaction-diffusion inspired feedback system. Having more than a couple concurent instances makes our 3090 chug. Use with caution. Some settings (thresholds especially) can easily black the output. 

- [Source] Reaction Diffusion (v1.4) : A versitile, feature-rich (read:heavy) generator implementing a reaction-diffusion inspired feedback system. This is essentially the effect on top of a light weight perlin noise generator. Having more than a couple concurent instances makes our 3090 chug. Use with caution. Some settings (thresholds especially) can easily black the output. 

- [Effect] R3color (v5)              : A lightweight recolor effect that gamut maps three colors onto the incoming video stream. Includes a phasor, gamut warping, hue expansion, gamut clipping, and step smoothing.