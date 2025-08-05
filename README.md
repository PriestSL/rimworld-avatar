## Experiments with AI Generation Prompts

I tried to reproduce generating portraits as explained in [guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3219670725), but with locale StableDiffusion I got only some cringe and not something similar as showed ingame. 
So I managed to do some changes in code to provide better auto prompt, that depends on pawn. 

### Recent Additions
- **Enhanced Prompts**: Added support for additional character attributes
  - Hair color variations
  - Head type options  
  - Body type configurations
  - **Note**: This is currently a work in progress (WIP) to test functionality
- **Improved Resolution**: Increased vanilla portrait resolution when using it for generation

### Development Notice
**ACHTUNG**: While I have coding experience, I have never coded in C#, so this project is mostly AI Generated using GitHub Copilot with Claude Sonnet 4.

### Testing Status
The published version in this repository has been tested with:
- Game launch compatibility
- Portrait generation functionality

## TODO LIST
- Generating better basic prompts
- Using better vanilla portrait as input image
- Exploring how is all works and improving it
- Exploring [Python Script](https://github.com/deadmanIsARabbit/RimworldAvatarToStableDiffusion/) and StableDiffusion WebUI API to do better control over generating

## ORIGINAL DESCRIPTION


![avatar](https://raw.githubusercontent.com/bolphen/rimworld-avatar/master/About/Preview.png)

Show a pixel-art style avatar for pawns.

[Download](https://github.com/bolphen/rimworld-avatar/releases/latest/download/rimworld-avatar.zip)

[Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3111373293)

-----

- Requires [Harmony](https://github.com/pardeike/HarmonyRimWorld).
- Currently covers most vanilla and DLC contents:
  - hairs, tattoos, genes
  - life stages: newborn, child, adult, corpse
  - gear
- Check the workshop page for a list of supported mods.

-----

**Note.** The repo no longer contains the assembly files. You should either download the zip from the "Releases" section (here's a [download](https://github.com/bolphen/rimworld-avatar/releases/latest/download/rimworld-avatar.zip) button again), or build them yourself by running the following
```bash
nuget restore Source/Avatar.csproj; msbuild -v:m -clp:summary Source
```
