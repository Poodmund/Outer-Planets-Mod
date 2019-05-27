# Outer Planets Mod v2.2.4

- Improved asteroids config to allow them to spawn before a vessel has visited said body and also tweaked the spawn settings to allow for more intelligent asteroid orbits.

# Outer Planets Mod v2.2.3

- Fixed Eeloo's normal map texture
- Corrected a localization string on one of Wal's biomes
- Bumped version file to give compatibility with KSP 1.7.*

# Outer Planets Mod v2.2.2

- Converted all biome maps to Palette 4bpp/8bpp .dds formats to improve loading time and OD functionality.
- Removed Custom Asteroids integration in favor of using Kopernicus' Asteroids module.
- Included configs for "Classic Stock" resource system if present.

# Outer Planets Mod v2.2.1

- Fixed errors in Slate and Wal's normal map paths causing them not to use OnDemand loading effectively.

# Outer Planets Mod v2.2.0

- Incorporated all changes from OPM_Galileo branch.
- Upscaled and redefined all biome maps to 4096x2048px.
- Changed biome map formats to .png and clamped color palettes to only those colors in the configs.
- Redefined Tekto's liquid coasts (added ocean and land where necessary) in the color map, land/sea mask and adjust biome map to suit.
- Added Inland Lagoons biome to Tekto to account for inland liquid regions.
- Fixed Science Definitions file to correctly assign experiments.
- Moved Eeloo's new description string to the localization file.
- Removed antenna and DSN multiplier patches and introduced a Level 4 Tracking Station upgrade to give the extended range required for communications.
- Removed Stock Science Multipliers patch and redid Science Values for all OPM bodies to fall in line with stock body value consistency. Users can now adjust the Science Multiplier in their Difficulty Settings to suit their preference.

# OPM_Galileo v1.2.6

- Update for 1.4.X
- Corrected localization sytax
- Fixed Biomes for Polta and Wal

# OPM_Galileo v1.2.5

- Added Kopernicus asteroids
- Resources for Far Future Technologies
- Fixed MM syntax for science definitions
- Fixed Nissee localization error
- No longer includes MM dll
- OPM's Planetshine deactivates if GPP is present. Evidently Planetshine doesn't work well or at all for planets orbiting stars other than Sun.
- Updated ResearchBodies part upgrade config.
- Arranged Optional Mods folder: contains FinalFrontier support
- Rearranged and converted textures for better use of LoadOnDemand
- Removed a file that was breaking OPM's FinalFrontier support

# OPM_Galileo v1.2.4

- Fixes missing Eeloo when installed with GPP
- Fixes ResearchBodies in-game text

# OPM_Galileo v1.2.3

- Update version file for 1.3.1

# OPM_Galileo v1.2.2

- Moved CTTP outside of OPM folder to facilitate better compatibility in the future.
- Amended Tekto Colour Map to include Ocean Mask on the Alpha channel. (Thanks @Poodmund )

# OPM_Galileo v1.2.1

- Fixed Neidon and Nissee descriptions
- Fixed smart quote symbols in science defs and descriptions
- Changes to resource cfgs. KerbNet now works fine.

# OPM_Galileo v1.2.0

- Completed necessary localization: ResearchBodies is now supported, Kopernicus Biome displayName enabled
- Karbonite resource configs have been updated
- KerbNet is not functioning correctly. I beleive this to be a Kopernicus issue
- Restructured texture paths. Should speed up loading time by a few seconds

# OPM_Galileo v1.1.0

- Updated for 1.3
- Completed necessary localization: Covers displayName, Descriptions and ScienceDefs, Does NOT cover ResearchBodies (maybe in the future)
- Fixed Urlum's and Sarnus' rings for Kopernicus' ring shader
- Enabled Kopernicus' ring shader ^ hey whatta ya know?
- Added support for KopernicusExpansions footprints on all rocky bodies

# OPM_Galileo v1.0.0

- This just moves the textures out of the PluginData folders, letting Mac and Linux users use DDS textures

# Outer Planets Mod v2.1.0

- Redid normals for all bodies expect Ovok
- Fixed ASL pressure readouts in the body overview in map mode
- Removed support for the outdated KopernicusExpansion
- Added MM config that fixes white texture issue for Scatterer users
- Added a config that adapts the new antenna functionality of KSP 1.2 to work with the greater distances
- Redid all timewarp levels to transition more quickly to useful speeds
- Rebalanced science payout adjustments
- Adapted the Karbonite configs to the biome revamp
- Redid all existing OPM biomes
- Adjusted the science descriptions to account for the new/different biomes
- Added biomes and science blurbs to Plock, Karen, Sarnus, Neidon and Urlum
- Gave the biome maps more pleasant color palettes

# Outer Planets Mod v2.0.0

Gameplay:

- Overhauled Hale's terrain, making it a bit more detailed and the cliffs slightly more imposing
- Set Ovok'smin- and maxLevel to 1 to greatly reduce the spikiness by forcing the most simple terrain setting to always be active
- Overhauled Eeloo's terrain, adding procedural craters and improving terrain detail in general
- Overhauled Slate's terrain, making the volcano and mountains more imposing, adding procedural craters, improving terrain detail in general
- Overhauled Tekto's terrain, making the terrain a bit smoother, more detailed and lining up the ocean better with the color map
- Overhauled Polta's terrain, adding procedural craters and improving terrain detail in general
- Overhauled Priax's terrain, slightly changing the shape and increasing terrain detail to create a more chaotic, Hyperion-like feel
- Overhauled Wal's terrain, making the central ridge's height a bit shorter (more realistic), adding procedural craters, improving terrain detail in general
- Overhauled Tal's terrain, radically reducing spikiness and making it a more detailed and smooth body
- Overhauled Thatmo's terrain, adding 
- Overhauled Nissee's terrain, radically reducing spikiness and making it a more detailed and smooth body
- Overhauled Plock's terrain, reducing spikiness, adding procedural craters and increasing detail in general
- Overhauled Karen's terrain, reducing spikiness, adding procedural craters and increasing detail in general
- Added improved terrain scatter to all solid OPM bodies
- Reduced Slate's gravity from 0.85 to 0.692, to make it the Tylo Lite that it was intended to be

Visual:

- Added an community sub-mod to the download called CTTP that contains high-quality terrain textures
- Added custom terrain textures to all solid OPM bodies
- Added better quality height maps for Plock and Karen with less artifacts
- Added better quality color map to Tekto with less artifacts
- Replaced Slate's color map with a 4K version
- Re-imported height maps for Plock, Karen and Tal from source files to remove artifacts that had appeared through editing
- Downsized Nissee's height map from 2K to 1K to produce smoother terrain
- Downsized Thatmo's color map from 4K to 2K, as the moon did not need the extra resolution to look good
- Redid all ScaledSpace/PQS fades to make the transition smoother
- Removed cache files to save space, replacing them with a method to generate them on first launch at the cost of a few extra seconds loading time
- Redid normal maps for all solid OPM bodies
- Redid the contrasts for the OPM bodies to make the transition from ScaledSpace to PQS smoother

Interface:

- Added KSPedia entries for Outer Planets Mod, courtesy of Poodmund

Mod support:

- Added missing text for discovering Karen in the ResearchBodies config
- Redid all the existing OPM discovery texts in the ResearchBodies config

Bugfixes:

- Fixed a typo in the temperatureSeaLevel variable in Tekto'scfg
- Fixed Ovok's strange ScaledSpace lighting swirl at the poles
- Fixed Wal's normal map cutting off before the top of the equatorial ridge
- Fixed Nissee's North polar mountain
- 
Miscellaneous:

- Changed the orders of the PQSMods to 10, 20, 30, etc. in order to make it easier to understand
- Shuffled the PQSMods in the cfgs so they matched their order
- Switched template of Slate, Tekto, Polta, Priax, Tal, Nissee, Thatmo, Plock and Karen to Moho to make the terrain overhaul easier
- Removed unnecessary PQSMods that were inherited by OPM bodies from their templates
- Updated the AVC version file
- Removed the Kopernicus license, since it is no longer bundled with the mod

# Outer Planets Mod v1.9.5.1

- Fixed an issue with the game loading the wrong normals for the OPM gas giants
- Updated the AVC version file

# Outer Planets Mod v1.9.5

- Removed Module Manager from download (please use the MM version included with Kopernicus)
- Added FlyingAltitudeThresholdvalues to Thatmo's Science Values
- Added SpaceAltitudeThresholdvalues to Plock's Science Values
- Add a custom gravity value to Karen
- Added ScienceValues to Karen
- Added timewarpAltitudeLimits to Karen
- Removed duplicate value tidallyLocked in Thatmo's cfg
- Redid some older FinalFrontier badges to fix some issues they had
- Fixed two errors in the science blurbs
- Redid the SigmaBinary support as it now has a new plugin-based work flow
- Removed PlockKaren.cfg since it's been made obsolete because of the SigmaBinary changes
- Reworked the temperature and pressure curves of OPM's atmospheric bodies to give them more realistic atmospheres, courtesy of OhioBob
- Switched Sarnus, Urlum and Neidon to use Jool as a template to fix issues with lighting present since 1.1.1
- Removed some values in the ScaledSpace section of the OPM gas giants to account for the switch to the Jool template
- Sarnus, Urlum and Neidon now use the same cloudy normal map that Jool uses
- Updated the AVC version file

# Outer Planets Mod v1.9.2

- Added procedural asteroid moons to Jool, Sarnus, Urlum, Neidon and Plock through the CustomAsteroids mod
- Updated PlockKaren.cfg to latest version of the SigmaBinary template
- Changed the texture paths/locations to allow for LoadOnDemand functionality
- Made Karen's description a bit vaguer to account for the optional nature of the SigmaBinary mod
- Redid the FinalFrontier ribbons for Plock to reflect its new look
- Added FinalFrontier ribbons for Karen
- Fixed the incorrectly sized ScaledSpace .bins for Plock and Karen
- Updated Module Manager to version 2.6.17
- Updated the AVC version file

# Outer Planets Mod v1.9.1

- Re-added the FlightGlobalIndex variables to the various bodies to maintain save game compatibility and prevent save game breaking from occurring in the future

# Outer Planets Mod v1.9.0

- Redid Plock, changing it from a Vall look-a-like into a unique body
- Added a moon to Plock called Karen
- Redid the gas giant's rings to adjust for changes made to the ways rings are rendered now
- Flipped the biome maps of Thatmo and Karen, so that they correctly follow the terrain
- Changed Plock's orbital color, PlanetShine and DistantObject color to a light greenish brown
- Removed the FlightGlobalIndex variables, due to obsolescence
- Fixed an error in Plock's description
- Updated ModuleManager to version 2.6.13
- Updated AVC version file

# Outer Planets Mod v1.8.1

- Add biomes to Thatmo and Nissee
- Added science blurbs for Thatmo and Nissee
- Added science blurbs to earlier bodies
- Added an actually working version of the AVC version file
- Updated resource configs for Community Resource Pack compatibility, courtesy of Olympic1
- Added discovery messages for the ResearchBodies mod, courtesy of Olympic1
- Rebalanced the time warp limits for the OPM bodies, courtesy of Olympic1
- Changed adiabatic index of OPMs atmospheric bodies for better FAR compatibility
- Fixed a spelling error in the description for Nissee
- Updated ModuleManager to version 2.6.8

# Outer Planets Mod v1.8.0

- Added two moons to Neidon: Thatmo and Nissee
- Added support for Kopernicus Expansion's procedural gas giants feature, adding it to the OPM giants and Jool
- Updated the Karbonite configs for Tal
- Fixed a spelling error in Tekto's description and added a 'or her' after 'his' to include female Kerbals
- Removed a duplicate entry for Wal from the DAE config
- Converted the ring textures to PNG format for Kopernicus Expansion compatibility
- Updated ModuleManager to 2.6.7

# Outer Planets Mod v1.7.2

- Added custom water textures to Tekto as well as other ocean tweaks
- Removed the double color textures (color/map), because they were no longer needed by Kopernicus
- Added support for ResearchBodies
- Artificially enlarged the SOI of Hale and Ovok
- Reduced Hale and Ovok's gravity to more realistic levels
- Fixed the issue with not being able to stand on Tal
- Fixed the issue with Tal becoming gray scale when transitioning between terrain and ScaledSpace
- Fixed Tekto's dark terrain
- Flipped Tal's biome map to the correct orientation
- Moved the version file from the GameData to the OPM folder
- Reduced the spikiness of Ovok

# Outer Planets Mod v1.7.1

- Made Ovok egg-shaped again
- Added biomes and science descriptions to Tal
- Removed all mass values from the configs, as it was unnecessary to include when GeeASL was also included
- Changed all PluginData textures from .png format to .dds format
- Renamed the FinalFrontier file back to CelestialBodies.info, as it was needed for the OPM ribbons to show up
- Corrected spelling mistake in the science descriptions
- Updated the Module Manager plugin to version 2.6.6
- Updated the Module Manager license included

# Outer Planets Mod v1.7.0

- Moved the Texture Replacer cfg to the OPM folder and removed the TextureReplacer folder
- Updated the Karbonite configs, courtesy of Olympic1
- Updated the ModuleManager plugin to version 2.6.5
- Changed Wal's template back to Moho, since the black body bug was fixed by Kopernicus
- Tekto is much more playable now, since the dark terrain bug is fixed by Kopernicus
- Changed the AntennaRange config to reflect changes in the mod's recent updates
- Changed the rotational periods of the gas giants to make them more realistic
- Tweaked the atmospheres even further to create smoother transitions similar to stock atmospheres
- Balanced Tekto's atmosphere to make it less tedious during descent
- Changed Tekto's atmospheric ambient color from reddish to the correct green
- Rounded the atmospheric heights of all OPM bodies, to match the new style of the stock bodies
- Corrected Priax's mass
- Added relative paths for the .bin files in the OPM bodies' cfg files
- Adjusted the SOIs of Ovok and Hale to make scanning and orbiting less problematic
- Removed the Kopernicus folder, the mod can now be downloaded separately, making combining OPM with other planet packs easier

# Outer Planets Mod v1.7.0 Beta 2

- Added about a dozen extra science descriptions to Urlum's moons
- Fixed a description that was about Priax, but was listed for Wal
- Corrected the spelling in Neidon's description as well as a science description for Polta
- Moved Eeloo's ribbons and config info into the OPM/Ribbons folder and removed the Nereid folder
- Removed the useless svn files and folders from the Ribbons folder
- Fixed a compatibility problem with ATM through a config/moving the ring textures to a separate folder
- Converted the ring textures to DDS format
- Renamed the configs in the OPM folder for clarity's sake
- Changed a value in the antenna distance config to account for a change in RemoteTech
- Moved the PlanetShine config into the OPM folder and removed the PlanetShine folder
- Added Tal to the PlanetShine config
- Updated the ModuleManager plugin to version 2.6.3
- Fixed Priax's biome definitions not matching the actual biome map
- Tweaked the atmospheres in OPM to make them work better and to make them more unique from one another
- Temporarily made Dres the template for Wal instead of Moho, to prevent the black body bug

# Outer Planets Mod v1.7.0 Beta 1

- Added a moon around Wall called Tal
- Added biomes to Urlum's moons
- Added a couple more science descriptions to Tekto
- Rebuilt the mod to only use the new Kopernicus
- Removed KopernicusTech because it's no longer used
- Converted all gas giants to work without a template
- Removed DDSLoader because it's obsolete since 1.0
- Removed CustomAsteroids support since it hasn't been updated in months and is buggy
- Removed the solar power curve config because it is obsolete since 1.0.1
- Updated ModuleManager to version 2.6.2
- Rotated Priax so that its lighter side is facing the orbital direction
- Added FinalFrontier ribbons for the Urlum moons
- Enabled Plock's ribbons in the FinalFrontier config
- Rebalanced the prestige you get for each OPM ribbon
- Changed Wal's orbital color to make it more distinct from Tal's color
- Changed Wal's description to fit the inclusion of Tal
- Made Wal's orbit larger to realistically allow subsatellite Tal to exist
- Added custom timewarp limits to the existing OPM bodies
- Redid some of the normal maps for the existing OPM bodies
- Integrated OPM with the new stock resource system
- Renamed the RegolithConfigs folder to KarboniteConfigs, to reflect Karbonite mod dropping Regolith for the stock resource system

# Outer Planets Mod v1.6.5

- Added a ScaledSpace .bin for Plock
- Removed tidal locking from Plock
- Added a rotational period to Plock
- Tweaked the mass and gravity of Plock slightly to make them more consistent with each other
- Made Urlum's rotation prograde to fix issues the retrograde rotation caused for some people
- Changed the descriptions for Slate and Eeloo to make their lore more realistic
- Fixed the incorrect height map for Slate
- Made Slate's normal map more detailed
- Updated the KittopiaTech license to the most recent version
- Updated DDSLoader to version 1.9.0
- Updated ModuleManager to version 2.5.13
- Updated KopernicusTech to version 0.13

# Outer Planets Mod v1.6.0

- Added three new moons to Urlum: Polta, Priax and Wal
- Added licenses to the download as per the rules
- Added AVC support with a .version file
- Resized Slate's color map to reduce memory use at a negligible loss in in-game quality
- Tweaked Tekto's atmosphereAmbient in the PlanetShine config to make it as much as other atmospheric bodies

# Outer Planets Mod v1.5.5.1

- TextureReplacer incompatibility fixed

# Outer Planets Mod v1.5.5

- Updated the plugins to KopernicusTech 0.121
- Updated ModuleManager to 2.5.10
- Removed the Kopernicus Cache .bin files
- Added the Kittopia ScaledSpace .bin files
- Added the DDSLoader plugin
- The Sarnus texture has been given Saturn-like polar hexagons
- Ovok has been made more egg-shaped and several body characteristics have been changed to account for the new shape
- The Ovok biome map and the science descriptions have been changed to reflect the changes to Ovok
- Switched all textures back to DDS format
- Made some textures smaller (gas giants, small moons) as their high resolutions only increased memory use and didn't improve the in-game quality much
- Fixed Tekto's ScaledSpace ocean not matching the real ocean and tweaked the color a bit
- Moved the new planets and moons out of Systems.cfg and into their own config files for increased modularity
- Fixed the knowledge base atmosphere height of Tekto not matching the real atmosphere height
- Removed the rotation periods for Hale and Ovok as they're tidally locked now and don't need that info
- Tidally locked Eeloo as well, just like its inspiration Enceladus
- Changed the distances of Eeloo, Slate and Tekto to be more similar to the relative distances in the Saturn system
- Tweaked Tekto's atmospheric color
- Added biomes and science descriptions to Tekto
- Added some science descriptions to the older planets and moons
- Corrected some descriptions of the older planets and moons
- Removed AVP configs and moved them to a separate download in the forum thread OP
- Reduced the temperature multiplier for OPMs gas giants to prevent issues with DRE/FAR
- Moved the atmosphere handling for the gas giants from Kopernicus to Kittopia
- Tweaked the atmospheric colors of the gas giants to make them look better

# Outer Planets Mod v1.5.2

- Included the correct DLL for Kopernicus 0.4, so that the biome bug is now actually fixed
- Added a missing cloud layer in the AVP config for Sarnus
- Added biome-specific resources for Sarnus' moons to the Regolith config
- Added resources on Tekto to the Regolith config

# Outer Planets Mod v1.5.1

- Removed unused Tekto ocean textures
- Mirrored the textures for Hale, Slate and Ovok vertically so they look like they did in 1.4
- Updated Kopernicus to version 0.4, which fixes the biome bug
- Removed the now obsolete biome enabling/disabling config
- Removed the ScaledSpace folder in KittopiaSpace as Kopernicus can now handle that
- Set ModScaledAtmoShader to false for Sarnus, Urlum and Tekto so that atmospheric gradient once again displays correctly

# Outer Planets Mod v1.5.0

- Added a new moon to Sarnus called Tekto
- Updated ModuleManager to version 2.5.9
- Switched the Kopernicus and KittopiaTech plugins to the KopernicusTech fork
- Moved terrain handling from RSS to KopernicusTech; RSS is now no longer included
- Switched textures to PNG, since KopernicusTech does not support DDS; DDSLoader is now no longer included
- Tweaked the rings of Sarnus and Urlum a bit, adjusted Hale and Ovok's orbits to compensate
- Increased the gravity of Hale and Ovok to enlarge the SoI to make it easier to get an encounter with the moons
- Tidally locked Hale and Slate to Sarnus
- Added a specialized Regolith/Karbonite config
- Added a way to disable biomes on the new bodies, as a bug applies the new biomes to the template bodies too. To disable these biomes, remove Kopernicus/Config/OPMBiomes.cfg
- Rebalanced the science multipliers of all bodies to compensate for the added planets and moons. The rebalanced multipliers for the stock planets can be disabled by removing Kopernicus/Config/StockScienceMultipliers.cfg
- Adjusted Plock's characteristics to make it less like Vall and more like Pluto
- Made Neidon start farther along in its orbit, so that it and Plock will never come too close
- Added a config for AntennaRange and RemoteTech that extends the range of the longest-range dishes to compensate for the expanded Kerbol system
- Added Astronomer's Visual Pack-compatible cloud configs for the planets and moons with atmospheres

# Outer Planets Mod v1.4.0

- Upgraded KittopiaTech to version 0.192
- Added biomes for Hale, Ovok and Slate
- Added science blurbs for the new moons
- Added atmospheric science blurbs for the gas giants
- Removed the RSS time warp tweak as it was causing issues
- Tweaked some of the orbital and body characteristics of OPM planets and moons
- Made Slate's terrain smoother in places
- Changed the default textures from 4K/8K to 2K/4K. Low and high res packs can be downloaded separately

# Outer Planets Modv 1.3.0

- Updated KittopiaTech to version 0.19
- Moved Eeloo to an orbit around Sarnus
- Made a new Pluto analog called Plock
- Added three brand new moons to Sarnus: Hale, Ovok and Slate
- Changed Sarnus' ring texture to realistically fit Hale in
- Added support for FinalFrontier
- Changed Urlum from a retrograde orbit to a prograde orbit
- Made Urlum rotate in a retrograde direction and changed description to reflect that
- Switched from PNG to DDS textures
- Redid time warp speeds using RSS, it can now go from x1-x1,000,000
- Changed scale heights and max altitude of the new gas giant's atmospheres
- Halved the spawn rates of OPMs procedural asteroid moonlets
- Updated ModuleManager to version 2.5.8
- Moved the PlanetShine config into the base one, to get it to work correctly

# Outer Planets Mod 1.2.1

- Reduced Urlum's shepherd moon spawn rate from its extremely high value (which I used for testing) to its intended value

# Outer Planets Mod v1.2.0

- Added a few science blurbs for the new planets, but only orbital experiments for now
- Gave custom science multipliers to each of the new planets and upped Eeloo's to reflect its more distant orbit
- Added support for PlanetShine and Distant Object Enhancement
- Added a new type of procedural moonlets: Urlum ring shepherds
- Tweaked the values of the existing moonlet types to be more realistic/less random
- Changed the ring texture of Urlum to make it less identical to Uranus'
- Changed the atmospheric heights of the new planets
- Changed the description of Neidon

# Outer Planets Mod v1.1.1

- Updated PFUtilityAddon.dll (courtesy of Thesonicgalaxy) and capitalized the first letter of the ring textures' filenames to ensure rings show properly on Linux

# Outer Planets Mod v1.1.0

- Added support for CustomAsteroids: this will allow procedural asteroids to spawn around Jool, Sarnus, Urlum and Neidon and represent their very small moonlets
- Added planetary rings to Sarnus and Urlum
- Gave the new planets unique rotational speeds
- Included the correct resolution textures for Urlum and Neidon, accidentally released them with half-res textures
- Updated ModuleManager to version 2.5.6
- Removed Sarnus_rim.png, an unused texture
 
# Outer Planets Mod v1.0.0

- Initial release