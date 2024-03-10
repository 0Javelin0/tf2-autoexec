### CONTENTS
- [Installing](#()-installation)
- [What will happen](#()-this-config-will)
- [Future improvements](#()-future-updates)
- [Extra tips for more fps](#()-extra-fps-tips)
- [Didn't work?](#()-config-file-did-not-work)

## (+) INSTALLATION:
  1. Download the config file -> [autoexec.cfg](./autoexec.cfg)

  2. Move the file to TF2's config folder
     - Windows: C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg\
     - Linux: ~/.local/share/Steam/steamapps/common/Team Fortress 2/tf/cfg/
     - NOTE: These locations are default. Even if you have changed the location where steam is configured, the folders/directories following 'Steam' above still apply.

  4. Done!
     - If no changes to your game have happened, [try these things](#()-config-file-did-not-work)
     
## (!) THIS CONFIG WILL:
  - Remove ragdolls & gibs
  - Significantly lower textures for weapon skins(will nuke), map textures, & player model detail
  - Remove map details such as grass
  - Remove the 3D sky effect
  - Remove almost all shading/gradients
  - Remove shadows
  - Remove particles such as dust from walls being shot at, bullet shells when reloading, etc.
  - Remove teammate outlines after respawn
  - Shorten killfeed display duration
  - Change cl_interp to 0.0303
  - Remove water splashes
  - Reduce water graphics & allow you to hear better underwater
  - Remove player face movement such as blinking, lip & eye movement, etc.
  - Reduce # of player decals to 9
  - Disable weather effects

Despite large amounts of graphics trimming, this config still allows the game to look half decent, all the while increasing fps significantly.
If you would like to add/edit/remove things from the config, feel free to do so. (see )

## (+) FUTURE UPDATES:
As of now the commands are labeled & grouped together by their general purposes.
I understand this isn't very readable/neat, as well as some commands can have multiple purposes, making this config convoluted & difficult to tweak to your specific preferences.
Please check this repo occasionally, as I plan on fine-tuning the way the commands are sorted as well as explain what each command does/how it effects the gameplay.

## (+) EXTRA FPS TIPS:
  - Using a custom HUD rather than the default such as Toonhud will drastically improve fps(for me it was by 20) and looks better IMO.
  - Using Steam launch options such as these will trim bloat to improve performace:
     - -nosteamcontroller
     > Disables compatibility with steam deck.
     - -nojoy
     > Disables controller compatibility.
     - -nohltv
     > Disables broadcasting.
     - -no-browser
     > Disables Steam overlay browser. (source of the cancerous Steam Webhelper processes)
     - -vrdisable
     > Disables compatibility with VR headsets.
     - -fps_max #
     > '#' being the amount of fps to cap. Capping your fps increases stability and keeps it more consistent. I suggest your monitor's refresh rate, but some would argue set it higher due to hit register advantages.
     - fullscreen
     > Usually default. If game isn't fullscreen, your desktop environment must display other things such as your wallpaper, shortcuts, taskbar, etc., using minute amounts of ram, but every last bit counts.
     - noquicktime
     - softparticlesdefaultoff
     - particles 1
     - precachefontchars
    
     (options past this point are optional & do not increase performance but improve user experience)
    
     - -noforcemaccel
     > Disables mouse acceleration
     - -novid
     > Skips the Valve intro when booting TF2
  - Disabling the Steam overlay
  - Removing useless Windows services & drivers (ex. printers, text-to-speech, tips, many more -- !!BUT BE CAREFUL NOT TO REMOVE ESSENTIALS!!)
  - No hats mod
  - If you are familiar with Linux, then play on Linux. TF2 has many issues for me on Debian 12 so I switch over to Windows 11 to play, but if you are able to play on Linux do so. Windows is half the reason you get poor performance, due to massive amounts of bloat. Manually removing bloat or powershell scripts help with this, but is nearly impossible to remove all bloat from Windows machines.

## (!) CONFIG FILE DID NOT WORK


