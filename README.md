# AHK-ER-simulator
This program is meant to play an ER triage simulator with MYR using AutoHotKey

MYR
--
MYR is a VR sandbox developed by Fred Martin's research lab at University of Massachusetts Lowell. https://learnmyr.org

Moving the character or changing the camera angle will cause AutoHotKey to no longer work, refreshing the page will fix this. The link to the ER simulator is https://learnmyr.org/scene/62f7f6af47bad400196ba4e0

AutoHotKey
--
AutoHotKey can be download from https://www.autohotkey.com/

There are 7 AutoHotKey scripts in this project, all the scripts must be in the same folder as the PNGs to run

The following are used to chose which door you choose, and will give you a new situation if you are correct

,left.ahk

,center.ahk

,right.ahk

The following are used as start and stop buttons, respectively

.reset.ahk

.end.ahk

The following measurement tools that are not required to play

.search.ahk is a tool to find png locations

.xyposition.ahk is a tool that moves the mouse to given coordinates

Important Note: All AutoHotKey scripts are calibrated for a 4k display, the measurement tools can be used to find coordinates for different reolutions

AntiMicroX
--
AntiMicroX can be installed from https://github.com/AntiMicroX/antimicrox/releases/tag/3.2.5

This game can optionally be played with a controller using AntiMicroX by using myr.gamecontroller.amgp
