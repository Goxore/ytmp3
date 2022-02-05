# ytmp3
A simple shell script that downloads a song with youtube-dl/yt-dlp, renames it and adds artist and album names with id3tool.

example: 

```
ytmp3 -o "Devil Trigger" -r "Casey Edwards" -a "DMC" "https://www.youtube.com/watch?v=-WpnPSChVRQ"
```
use ytmp3 -h to get the list of flags.

the best use case of the script is to use it as follows:

```
ytmp3 -c -o "Name of the song"
```

If you want to type in the name of the song with rofi use theese flags: 

```
ytmp3 -c -rofi
```

I recommend putting this script in any folder, ~/scripts for example, and exporting it in .zshrc or .bashrc.
```
export PATH=$HOME/scripts/:$PATH
```

Warning: Calling the script with rofi from i3 for some reason results in i3 crashing on my system for no apparent reason.
