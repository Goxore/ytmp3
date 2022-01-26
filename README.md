# ytmp3
A simple POSIX shell script that downloads a song with youtube-dl/yt-dlp, renames it and adds artist and album names with id3tool.

example: 

```
ytmp3 -o "Devil Trigger.mp3" -r "Casey Edwards" -a "DMC" "https://www.youtube.com/watch?v=-WpnPSChVRQ"
```
use ytmp3 -h

I recommend putting this script in any folder, ~/scripts for example, and exporting it in .zshrc or .bashrc.
```
export PATH=$HOME/scripts/:$PATH
```
