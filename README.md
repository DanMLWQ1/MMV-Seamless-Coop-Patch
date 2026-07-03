## Note
- If you have me3, MMV and Seamless Co-op already installed and set up, you only need to put the "MMV Seamless.me3" file inside the MMV folder and hit Replace if prompted. 
- Otherwise, see the **DIY** section.

--------------------------------------------------------------------------------------------------------------------------------------
**Full Installation**

1. Install me3.
2. Download and extract MMV to a folder of your choice.
3. Download Seamless Co-op.
4. Copy the SeamlessCoop folder into the MMV mod folder.
5. Download the "MMV Seamless.me3" file and copy it into the MMV folder.
6. Double-click the .me3 file to launch.


**Download links**

- me3: https://www.nexusmods.com/eldenringnightreign/mods/213?tab=files
- MMV: https://www.nexusmods.com/eldenringnightreign/mods/578
- Seamless Co-op: https://www.nexusmods.com/eldenringnightreign/mods/3?tab=files
- MMV Seamless.me3: https://github.com/DanMLWQ1/MMV-Seamless-Coop-Patch/releases/download/buh/MMV.Seamless.me3
--------------------------------------------------------------------------------------------------------------------------------------

**DIY**
If you don't want to download the MMV Seamless.me3, you can edit the existing .me3 file in the MMV folder.

1. Right-click the .me3 file.
2. Open with any text editor.
3. Replace its content with the following and save it:
```
profileVersion = "v1"
start_online = true

[[supports]]
game = "nightrein"

[[packages]] 
path = 'mod'

[[natives]] 
path = 'mod/SeamlessCoop/nrsc.dll'
load_early = true
```

# **Credits**
- Yui, Nightreign Seamless Co-op
- MMV team, More Map Variations & Weapons Mod
- garyttierney, Mod Engine 3
- Church Guard, Server Redirector

### --MMV team, More Map Variations & Weapons Mod--
### The Daybreak Team:
- Dragonblade, Team Lead
- Blabla, Event Scripter & Programmer
- TerraMag, Port Design Team
- Vivid / Mrsakana, Port Design Team
- Godfrey, Enemy AI & Fight Design
- Kevin, Map & TAE Specialist
