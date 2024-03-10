(!) THIS CONFIG WILL:
  - Remove ragdolls & gibs
  - Significantly lower textures for weapon skins(even more), map textures, & player model detail
  - Remove map details such as grass
  - Remove the 3D sky effect
  - Remove shading/gradients
  - Remove shadows
  - Remove particles such as dust from walls being shot at, bullet shells when reloading, etc.
  - Remove teammate outlines after respawn
  - Shorten killfeed display duration
  - Change cl_interp to 0.0152
  - Remove water splashes
  - Reduce water graphics & allow you to hear better underwater
  - Remove player face movement such as blinking, lip & eye movement, etc.
  - Reduce # of player decals to 12
  - Disable weather
  - cause noticable lighting defects such as ubered players looking darker

Despite large amounts of graphics trimming, this config still allows the game to look half decent, all the while increasing fps significantly.

(+) EXTRA FPS TIPS:
  - Using a custom HUD rather than the default such as Toonhud will drastically improve fps(for me it was by 20) and looks better imo.
  - Using Steam launch options such as these will trim bloat to improve performace:
     - -high                 //  Sets game priority to high so TF2 won't have to fight against other applications for cpu/ram 
     - -nosteamcontroller    //  Disables compatibility with steam deck
     - -noipx                //  An unused networking protocol
     - -nojoy                //  Disables controller compatibility
     - -nohltv               //  Disables broadcasting
     (options past this point are optional & do not increase performance but improve user experience)
     - -noforcemaccel        //  Disables mouse acceleration
     - -novid                //  Skips the Valve intro when booting TF2
  - Disabling the Steam overlay
  - Removing useless Windows services & drivers (ex. printers, text-to-speech, tips, many more -- !!BUT BE CAREFUL NOT TO REMOVE ESSENTIALS!!)
  - Nohats mod
  - If you are familiar with Linux, then play on Linux. TF2 has many issues for me with with Debian 12 so I switch over to Windows 11 to play, but if you are able to play on Linux do so.
    Windows is more than half the reason you get poor performance, due to massive amounts of bloat. Manually removing bloat or powershell scripts help with this, but is nearly impossible to remove all bloat from Windows machines.
