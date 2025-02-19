---
title: Hardware Issues
category: Misc
---

# Hardware Issues

While these issues are not specific to 351ELEC, there are a few issues with the RG351 hardware that come up a lot during support.

## Low Battery

RG351 devices have a tendency to act strangely below 35% battery. This can cause all kinds of issues, one of which is the "No Gamepads Detected" Error. If you're at low battery and start experiencing strange behavior, please try charging up the console as your first debugging step.

## Sleep

RG351 devices have issues with sleep when running standalone emulators or games. Sleep should work fine from EmulationStation (the main menu of the device), or from any RetroArch emulator. Sleeping in a standalone emulator or game is likely to cause the "No Gamepads Detected" error, or to simply cause the controls to stop working.

RG351 systems use an internal USB hub to connect to their gamepad. If USB isn't disabled when the device goes to sleep, it causes a kernel error when the device wakes up that messes up the gamepad connection. Unfortunately, there's currently no solution to this issue, so please only use sleep in EmulationStation and RetroArch.

## RG351P/M Permanent "No Gamepads Detected" Error

Before continuing on with this section, please read the [Low Battery](#low-battery) and the [Sleep](#sleep) section to make sure that neither of those matches the issues you are having.

While all consoles will give the "No Gamepads Detected" error at certain times, there are reports of some P and M devices that display this message the first time they are turned on, and where the issue is not solved by charging the console. We've had a report that one person has solved this issue by completely discharging the console (running the console out of battery and then continuing to turn the console back on until it stops responding), but other people have tried this solution and not had any luck.

With the possible exception of draining the console, this problem doesn't currently have any known solution. If you have this issue, you will probably need to exchange your console for a new one. If you've gotten the device from a questionable seller, it may be best to try to get your money back and order it from Anbernic's official site or AliExpress page, or to find a distributor with a very high seller rating.

If you do open an issue with AliExpress or Amazon, please do not close the issue until your console is replaced or you get your money back. Some sellers will try to get you to close the issue preemptively, and then not follow through with the agreed fix.

## RG351V Black Lines

Some recent RG351V handhelds have shipped with a different screen that forms black lines and smears on the screen as the device heats up. Fortunately, there is a solution to this issue. It's implemented in the current [Beta build](Contributing-to-351ELEC#beta-builds), and will be incorporated into the next stable release of 351ELEC.
