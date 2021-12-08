# Nintendo Switch button remap

As an old Playstation and Xbox player, I've always been playing with the "classic" gamepad buttons layout,
i.e. "X" or "A" being the confirm/jump action and located down and in the center, "B" or "O" doing "cancel"
and located at the right, etc.

Unfortunately, for Nintendo Switch this layout has traditionally been reversed, and I always had troubles
using it, I tried many times to "adjust", but I simply would press a wrong button all the time so playing
was not comfortable.

Luckily, if you're using standard Nintendo Switch joycons, you can still remap the buttons to your liking,
despite the ugly remainder popup at every console boot or wakeup from sleep, this worked for me.

## The problem

Recently I've purchased a Hori Split Pad Pro, and to my surprise, remapping simply doesn't work in this case:

![Alt text](https://raw.githubusercontent.com/stunndard/Nintendo_Switch_Button_Remap/main/hori1.jpg)

![Alt text](https://raw.githubusercontent.com/stunndard/Nintendo_Switch_Button_Remap/main/hori2.jpg)

## The solution

Using some information from [Joycon Reverse Engineering](https://github.com/dekuNukem/Nintendo_Switch_Reverse_Engineering)
I was able to create an [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) patch to swap the A-B and X-Y buttons.

## Features

* Works with standard Joycons, Hori Split Pad pro, or any other 3rd party controllers that connect to the Switch
standard console rails.
* The nasty reminder popup is now gone for good.

## Cons

* Requires a patched Switch, with [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) installed.
* Doesn't work with Bluetooth or USB controllers. I believe [Misson Control](https://github.com/ndeadly/MissionControl)
allows to remap buttons for such controllers.

## Installation and requirements

Just unzip the files downloaded from [Releases](https://github.com/stunndard/Nintendo_Switch_Button_Remap/releases)
to the root of your SD card and reboot.

## System firmware support

* 13.1.0
* 13.2.0

## Questions and requests

Please make a post in the [issue section](https://github.com/stunndard/Nintendo_Switch_Button_Remap/issues).
For example, for other system firmware version support.
