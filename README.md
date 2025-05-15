# SmallTime

This is a fork of https://github.com/unsoluble/smalltime. HUGE thanks for them for all of the work that they put in.

The purpose of this fork is just to add a third time step.
https://github.com/unsoluble/smalltime/issues/226

## Quick Summary

- Drag the sun/moon or click the forward/back buttons to change the time.
- Shift-click the buttons to double the amount. Alt for half.
- Bottom of the window is a repositioning drag handle.
- Button steps and various other things are changeable in Module Settings.
- Shift-click the moon to cycle the moon's phase. If you're running Simple Calendar, your phase will be synced from there.
- Toggle show/hide button is in Journal Notes.
- Darkness link toggle and Player visibility controls are in Scene Config.
- With a calendar-providing module enabled, click the time to display the date.
- If a module or game system provides a realtime clock, Shift-click the time to toggle it.

Video overview: (somewhat out of date now, but it covers the main bits :) [https://www.youtube.com/watch?v=XShiobMvatE](https://www.youtube.com/watch?v=XShiobMvatE)

### How to Use

There's a show/hide toggle in the Journal Notes tool layer:

![Toggle Control](doc/Toggle_Control.png)

Use the forward/back buttons to change the time, or drag the sun/moon icon (non-GM users will not have these controls):

![Basic Operation](doc/Basic_Operation.gif)

You can position the window anywhere you like with the drag handle at the bottom, or pin it just above the Players list:

![Placement](doc/Placement.gif)

For each scene, you can choose how much of the display can be seen by Players, and whether or not to link the time to the scene's Darkness Level:

![Scene_Config](doc/Scene_Config.webp)
![Darkness_Link](doc/Darkness_Link.gif)

If you have a calendar-providing module (or game system) enabled, SmallTime will sync with its date. Clicking on the time will toggle the date display; Shift-clicking the time will toggle the realtime clock (if provided by your other modules or game system).

![About_Time_Integration](doc/About_Time_Integration.gif)

If you have [Simple Calendar](https://foundryvtt.com/packages/foundryvtt-simple-calendar) enabled, make sure its Game World Time Integration setting is on "Mixed". Calendar and time info from there should now sync up, though SmallTime doesn't currently support nonstandard time divisions. You can enable Sunrise/Sunset sync from Simple Calendar in the SmallTime settings screen.

### Settings

There are a number of settings you can change:

![Settings](doc/Settings.webp)

(if your SmallTime window ever gets stuck in a weird location, Shift-click the "Resting Opacity" header in the settings screen to reset it.)

...including custom sunrise/sunset times, and global maximum & minimum darkness levels:

![Darkness Config](doc/Darkness_Config.gif)

### Languages

Full support for:

- English
- Japanese (thanks @BrotherSharp!)
- German (thanks @kdomke!)
- Spanish (thanks @masr!)
- Korean (thanks @jbblily!)
- French (thanks @DarKDinDoN!)
- Portuguese (thanks @Castanho!)
- Chinese/Taiwan (thanks @zeteticl!)
- Italian (thanks @bertolinimarco!)
- Polish (thanks @Lioheart!)

I added the medium step translation with google translate, please let me know if they are incorrect.

I'm happy to accept and implement more translations!

### Need Help?

If something's not working right, or you've got other questions or comments, feel free to hit me up on the [Discord](https://discord.gg/foundryvtt) (@havocscall), or file a [ticket](https://github.com/HavocsCall/smalltime/issues).
