# xgodpack
## play unreal tournament announcer voice samples on Xcode build success/fail

Press CMD B. Success? "ultrakill!" Fail? "humilating!"

## video demo

https://www.youtube.com/watch?v=_aNKd-SlHtc

## Setup:

1. clone this repo
2. edit 'play-fail' line 3 to point to the location where you cloned this repository to
3. edit 'play-success' line 3 to point to the location where you cloned this repo to
4. open Xcode, go to preferences -> behaviors, select 'Succeeds' from the Build category, on the bottom make Xcode execute the 'play-suceed' script
5. do the same for 'Fails' but point Xcode to 'play-fail'

enjoy.

Please note that I didn't find a way but hard-coding the path in line 3 to make this script work properly when run from Xcode. If you know a smart way that removes the hard coded path please don't hesitate to issue a pull request (or just message me).

## Legal note

This repo contains samples which I'm not really allowed to put up here. If you got any problems with that just contact me and I'll remove them.

## License

Public Domain (except the sound files of course)
