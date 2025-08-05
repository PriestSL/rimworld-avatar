Some experiments with AI Generation prompts
For now it's: 
- Added some more prompts as haircolor, headtype, bodytype etc (just attempt to see how it's will work, so **WIP**)
- Increased resolution of vanilla portrait when using it on generation
**ACHTUNG** I have coding experience, but never coded on C#, so it's mostly AI Generated!!! (By using Github Copilot with Claude Sonnet 4)
On this repo published version is tested with game launch and portrait generation

------========ORIGINAL DESCRIPTION=======------


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
