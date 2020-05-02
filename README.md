# SoftwOrt-Mediaplayer

SoftwOrt-Mediaplayer is a Media- & Webradioplayer.

## Installation

- Download [ZIP-Container](https://github.com/SoftwOrt-Engineering/SoftwOrt-Mediaplayer/raw/master/SoftwOrt-Mediaplayer.zip) and save to youer local drive.
- Restore ZIP file and start SO-Mediaplayer Setup.exe file
- Have fun with this MediaPlayer!

## Updates

<b>1.0.0.2</b> - Issue with saving new Radiostations to the Mediaplayer fixed

1.0.0.1 - Issue with installing version fixed

## Sourcecode

[GitHub So-Eng](https://github.com/SO-Eng/SO-MediaPlayer)
See "Contributing"

## Features

Besides the normal features you know about a simple mediaplayer like:

- Open folders
- Drag&Drop files into Player
- Show them in a list to select
- Controll player with keyboard and mouse
	- Up-, Down arrowkeys = Skip For-, Backward
	- Left, Right arrowkeys = jump 10sec. For-, Backward
	- Space = Play and Pause track
	- Mousewheel Up, Down = Volumecontrol
- Thumbbuttons in Taskbar for Play/Pause, skip For- and Backward
- Loop, Loop 1 and Shuffle

<b>A big feature is the Webradioplayer with following features:</b>

- Big list of radiostations
- Create and manage a list of your favourites
- Add radiostations of your choice
- Search in internal list

<b>Settings:</b>

- Choose between 3 languages
	- English, German, Spanish
- Choose between 2 viewmodes
	- Light-, Darkmode
- Choose between 3 controlbutton designs
	- Blue, Futuristic, Gray

- Collapse lists for individual listcontrol

## Information

When adding a radiostation be sure to use directlinks.
	For example, a link like this won't work:
	https://www.radio.de/s/hr3
	
	Please try to find directlinks like this:
	http://metafiles.gl-systemhaus.de/hr/hr3_2.m3u
Because it is smoetimes hard to find correct link, there is a "Prelisten" function implemented.
Also SSL URLs won´t work properly, mostly you can reach radiostation per URL when trim to <i>http://</i> instead of <i>https://</i>

Added wrong Radiostaion or you have a typo? You can uncheck <b>"Save Webstation-list at exit"</b> before closing
the player, your new list won´t be saved!
You can also editing the list by jump into folder "RadioStations" where application is installed and open
"RadioStation-List.csv" file.

<b>Be sure to never delete headerrow and have no empty rows before last row.</b>

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

[GNU](https://choosealicense.com/licenses/gpl-3.0/)
