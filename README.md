# Magnetodynamics

[![DOI](https://zenodo.org/badge/247707301.svg)](https://zenodo.org/badge/latestdoi/247707301)

This package adds magnetic forces and fields to the [Unity Game Development Platform](https://unity.com/). It used to be in Unity's [Asset Store](https://assetstore.unity.com/), though it was removed when Unity stopped supporting its custom Javascript variant ("UnityScript"). I had written the _demos_ for Magnetodynamics in that language (for accessibility), but the main functions that provide magnetic forces and fields are written in C# and (reportedly) still work.

Magnetodynamics is now free in all senses of the word: see its [BSD-3 license](LICENSE). Use it however you like, including commercial products, but note that there is no warantee. Version 1.1 is the last version that I will write, though you're free to fork the repository and even put it on the Asset Store if you're willing to maintain it.

You can see a [demo of magnetic interactions here](http://coffeeshopphysics.com/magnetodynamics/), assuming that you have a compatible version of the Unity Web Player installed. Since this package was last updated in 2013, you might need a very old version of the Unity Web Player.

The C# source code is in the [src](src) directory. In a modern Unity project, you might need to include the source code directly, rather than importing the [Unity package](Magnetodynamics-1_1.unitypackage).

The documentation is in [Magnetodynamics_v1_0_Documentation.pdf](Magnetodynamics_v1_0_Documentation.pdf) (all 40 pages of it).
