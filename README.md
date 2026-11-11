# The-Inquisitor-VR
WIP not finish VR mod for The Inquisitor


<img width="1025" height="1535" alt="The Inquisitor_ Cathedral of Shadows" src="https://github.com/user-attachments/assets/7a0d1af2-de35-4cb7-9446-be4883cbe014" />



THE INQUISITOR VR  -  VR mod for "The Inquisitor" (Unity 2022.3, IL2CPP x64, HDRP, BepInEx 6)
==============================================================================================
Version 0.1.14 (test build)

INSTALL
unzip to game folder, only tested with virtual desktop XR,

 Steam > Properties > Launch Options:  -force-d3d11

VIEW
  * Play: THIRD PERSON (default) - you stand behind Mordimer and look around freely; the view follows him and turns
    only when you turn (right stick). FIRST PERSON - through his eyes.
  * HOLD R3 (RIGHT STICK CLICK) 1.3 s = switch 1st / 3rd person (in play). Outside play the same hold re-centres;
    a short click of BOTH sticks re-centres too.
  * Where you look is where the game camera looks, so the left stick walks where you look.
  * Cut-scenes, dialogue and finishers use the game's camera (you stand where it is).
  * Menus / book / map / pause: the game's picture on a big screen in front of you.
  * The HUD floats in front of you in play (its black is see-through).

ARMS
  * First person: Mordimer's arms follow your controllers (what he holds goes with his hand). Only the picture is
    changed - the game's own hits and animations are untouched. Third person: off by default (VR menu).

SWINGS
  * In FIRST PERSON FIGHTS: **swing the RIGHT controller = X (light attack), the LEFT controller = Y (heavy attack)**.
    The X / Y buttons still work too. ([Swing] OnlyInFirstPersonFights = false: swings work everywhere in play.)
    VR menu / config [Swing]: which button each swing presses, how fast a swing must be, the wait between swings.

CONTROLS (the VR controllers act as an Xbox gamepad - the game's own gamepad controls)

  Left stick ........... move   
  
  Right stick ...... left / right = turn, up / down = the game's
  
  Left stick click ..... L3 (sprint)
  
  Hold R3 1.3 s .... 1st / 3rd person
  
  X + Y together ....... Start (pause) 
  
  A + B together ... Back / View (journal)
  
  BOTH stick clicks .... click = re-centre;  HOLD 1 s = VR settings menu
                         (stick up / down = choose, left / right = change, A = switch, B = close)

                         
Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.

