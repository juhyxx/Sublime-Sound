Sublime-Sound
=============

Sublime-Text plugin to play event sounds.
Fun :smile:

__Supported Platforms__

||osx|linux|windows|
|:----:|:----:|:----:|:----:|
|Sublime Text 2|:small_red_triangle:|:small_red_triangle:|:x:|
|Sublime Text 3|:o:|:o:|:o:|

If you use ST2 Build 2091(29 July 2011) or more newer one, we cannot play any sounds because of its change of threading policy.:cry:

##Installation

You can install from [Package Control](https://sublime.wbond.net/).

__Package Control: Install Package__ > Select __Sound__

##Event Lists

+ __on_new__: played when new file buffer is created.
+ __on_load__: played when the file is finished loading.
+ __on_save__: played when file view has been saved.
+ __on_close__: played when a file view is closed.
+ __on_clone__: played when a file view is cloned from an existing one.
+ __on_modify__: played when a file view is changed.

##Custom Sounds

You can customize playing sounds by replace file. (only supports wav file now)

Replace wav file on __Preference > Package Settings > Sound > Open sounds > event_name__ directory.

If you put some files in a event_name directory, this plugin randomly choice a file and play on each event triggered.

Check [Sublime-SoundSets](https://github.com/airtoxin/Sublime-SoundSets)

##Settings

+ volume{1~100}: only osx support
