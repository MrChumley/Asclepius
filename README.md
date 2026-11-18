Asclepius - a kopernicus planet - SSTO playground
For Kerbal Space Program
Asclepius (v5.1.0) for KSP 1.12.x
REQUIRES Kopernicus and ModuleManager!
(Updated 11-17-2026)

Asclepius Github: https://github.com/MrChumley/Asclepius
This build lives on the ksp-1.12 branch: https://github.com/MrChumley/Asclepius/tree/ksp-1.12
KSP forum thread for Asclepius: https://forum.kerbalspaceprogram.com/topic/113949-15x-asclepius-a-kopernicus-planet-ssto-playground/

## KSP 1.12 build (ksp-1.12 branch)

This is the KSP 1.12 build of Asclepius and its moon Kruel. The `master` branch is still the older release.

What's new on this branch:
- Support for Kerbal Space Program 1.12.x and current Kopernicus
- Cliff texture fix (`steepBumpMap` now uses the built-in `brown_cliff` texture)
- Kruel's Mount Kurley white biome restored
- Asclepian sandstorms are back, as Blackrack V5 raymarched volumetric clouds via EVE-Redux
- A Scatterer atmosphere for Asclepius
- Kruel eclipse shadows

### Requirements

Required:
- Kerbal Space Program 1.12.x
- Kopernicus for KSP 1.12.x (https://github.com/Kopernicus/Kopernicus, maintained by R-T-B), including the ModularFlightIntegrator and Harmony packages it ships with
- Module Manager (https://github.com/sarbian/ModuleManager)

This repo does not pin a specific Kopernicus version. Use a current Kopernicus release made for KSP 1.12.x.

Optional visuals (not included in this repo):
- Blackrack's True Volumetric Clouds V5 (paid, via his Patreon). V5 bundles EVE-Redux 3.2.2.0 and Scatterer 0.908. Do not also install CKAN EVE or Scatterer alongside the V5 pack.
- Deferred 1.3.5.0, which requires Shabby (https://github.com/KSPModdingLibs/Shabby)

This repo contains only our configs and assets. None of Blackrack's paid files are included. You need your own V5 pack to see the volumetric sandstorm.

The planet and moon still work without the visual packs. The sandstorm and eclipse-shadow configs (`ASCclouds.cfg`, `ASCshadows.cfg`) only apply if Environmental Visual Enhancements is installed (`:NEEDS[EnvironmentalVisualEnhancements]`). The Scatterer atmosphere (`ASC_Scatterer.cfg`) only applies if Scatterer is installed (`:NEEDS[Scatterer]`).

### Install

1. Copy the `GameData/Asclepius` folder into your `KSP/GameData` folder.
2. Install Kopernicus (with ModularFlightIntegrator and Harmony) and Module Manager.
3. Optional: install Blackrack's True Volumetric Clouds V5, plus Deferred and Shabby, as listed above.

Tested in KSP 1.12.5 on 2026-11-17, including a landing through the sandstorm.

## Other optional mods (not included)

These compatibility patches are included, but most have not been re-verified on KSP 1.12 yet (the V5 sandstorm and Scatterer atmosphere above have been tested):

Contract Configurator: https://forum.kerbalspaceprogram.com/topic/91625-1101-contract-configurator-v1305-2020-10-05
Distant Object Enhancement: https://forum.kerbalspaceprogram.com/topic/205063-ksp-131-distant-object-enhancement-doe-l-under-new-management-21116-2024-0428/
DMagic Orbital Science: https://forum.kerbalspaceprogram.com/topic/59009-18x-dmagic-orbital-science-new-science-parts-v143-1122019
New Horizons (compatibility patch included): https://forum.kerbalspaceprogram.com/topic/102776-13-kopernicus-new-horizons-v201-2jun17-its-back/
Final Frontier (ribbons, and compatibility patch included): https://forum.kerbalspaceprogram.com/topic/61065-1100-final-frontier-kerbal-individual-merits-1100-3485/
Research Bodies (compatibility patch included): https://forum.kerbalspaceprogram.com/topic/139473-112x-researchbodies-v1130-15th-may-2022
Planetshine (compatibility patch included): https://forum.kerbalspaceprogram.com/topic/173138-112x-planetshine-0266-feb-22-2022

Kopernicus: https://github.com/Kopernicus/Kopernicus
Kopernicus KSP forum thread: https://forum.kerbalspaceprogram.com/topic/200143-112x-kopernicus-stable-branch-last-updated-february-25th-2026/

Module Manager: https://github.com/sarbian/ModuleManager
Module Manager KSP forum thread: https://forum.kerbalspaceprogram.com/topic/50533-18x-112x-module-manager-423-july-03th-2023-fireworks-season/

CC0- Full text @ http://creativecommons.org/publicdomain/zero/1.0/
To the extent possible under law, MrChumley has waived all copyright and related or neighboring rights to "Asclepius" including Asclepius.cfg, Kruel.cfg, ASCclouds.cfg, ASCshadows, ASC_Scatterer.cfg, ASC ScienceDefs.cfg, AscNewHorizPatch.cfg, ASC_Planetshine.cfg,  celesbod.cfg, Asc DMagicDefs.cfg, ASC_ResearchBodies.cfg, CelestialBodies.info, and associated images. This work is published from: United States.

(ksp-1.12 branch)
(11-17-2026)
KSP 1.12 build docs: listed V5 volumetric sandstorm, Scatterer atmosphere, Deferred/Shabby, and install requirements. Cliff texture fix and Mount Kurley's white biome are included on this branch.
The planet was play-tested in KSP 1.12.5 with a landing through the sandstorm.

(v5.1.0)
(11-10-2026)
KSP 1.12.x update: removed stale Kopernicus cache files, merged duplicate PQS Material blocks, added a KSP-AVC .version file, and updated documentation links.
The optional compatibility patches and EVE clouds config are unchanged and unverified on 1.12.

(v5.0)
(11-5-2018)
Localization update for science files
Various cfg updates
Kruel reworked

(v3.0)
(8-23-17)
Terrain updates for new kopernicus (v1.3.0-5), and updates for EVE clouds and shadows.

(v1.3)
(5-31-17)
Landcontrol, and PQS refinements.

(v1.5)  
(2-19-15)  
remove flightGlobalsIndex  

(v1.4)
(12-11-15)
Updated BoulderCo folder to be compatible with the new EVE [1-05-4]

(11-18-15) Removed Landclasses for Kopernicus 0.5 compatibility

(v1.1)
(10-9-15)
Reworked Ocean for kopernicus 0.4-beta compatibility, AND SMOOTH FPS! (really fixed this time!)

(v1.0)
(10-9-15)
Renamed ocean to AsclepiusOcean for Kopernicus 0.4 compatibility

(v0.88)___
(8-25-15)
Flipped .dds images vertically

(v0.85)___
(8-25-15)
Textures converted into .dds format

(v0.8)___
(8-10-15)
Added flat spot to Gooba Flats.
Added Research Bodies support.
Added Final Frontier ribbons.
Added PlanetShine support.

(v0.75)____
(8-8-15)
Added clouds texture

(v0.7)_____
(8-7-15)
Fixed "splashed" science definitions.
Reduced normal map size (still looks great, but uses less memory!)
"unbundled" Contract Configurator, E.V.E. Clouds, and distant object enhancement in Kerbalstuff download.

(v0.6)_______
Texture pass
Updated Kopernicus to 0.2.4
Bundled with: Contract Configurator, E.V.E. clouds, and Distant object enhancement. (licenses included)

(v0.5)_________
(8-1-15)
Added New_Horizons compatibility patch
Added DMagic science definitions
Updated contract configurator contracts
Changed Mean anomaly of Asclepius (now 120 days until first Asclepius transfer window instead of 2 years)
Reduced scatter density on Asclepius (Even More FPS!)

(v0.4)___________
Changelog:
(7-30-15)
Finished FULL CUSTOM science definitions for Kruel.
Lowered atmosphere ceiling from 55km to 22km.
Fixed spelling mistakes.

(v0.3)_____________
(7-27-15)
New Contract Configurator contracts - Contract Configurator: https://forum.kerbalspaceprogram.com/topic/91625-1101-contract-configurator-v1305-2020-10-05
Kessler Run - Set a new record for Canyon flight!
Rescue - Fly a spaceplane home from the surface of Asclepius!
Find a derelict Mining vessel, and attempt salvage!
Distant object enhancement support added
Cleaned up messy code

(v0.2)_____________
(7-22-15)

Updated to latest Kopernicus version.  
Added terrain scatter  
Now includes support for Contract Configurator D/L link Adds "easter egg contract"  
(v0.1)_____________
(7-14-15) -Updated Kopernicus, Full RELEASE! (0.1) on kerbalstuff.com
(7-13-15) -Added clouds! optional, REQUIRES E.V.E
(7-11-15) -Visual atmospheric improvements.
(7-8-15) -Small terrain changes. -Added 2 new biomes to Asclepius. -Added all new custom biomes for Kruel. -Added even MORE custom science.
(7-1-15) - Added Kruel (small mountainous moon)
(6-29-15) -Refined atmosphere appearance -Darkened terrain -Science definitions added. -Restructured folder directory structure -.zip download now comes bundled with Kopernicus, and modulemanager .dll's (along with associated licenses) for convenience.
(6-25-15) -increased planet radius (to reduce terrain "spikiness"), and adjusted mass numbers to keep gravity relatively low (0.4g's). - Now has 1337m/s escape velocity
(6-24-15) -Fixed atmospheric rimPower & rimBlend so that atmosphere lens doesn't shine through planet during scaledspace transition. -Added North and south pole ocean craters with biomes.
(6-23-15) -Bug causing ships to clip through Terrain and blow up fixed -Darkened the blue in cracks
(6-17-15) -Planet created from a picture of dried mud (and mad photoshop skillz yo), and a little help from NormalMap-Online for the normal texture files -Added Biomes (Major Cracks, Minor Cracks, Dunes) -Atmosphere characteristics complete
