# polytrack
polytrack offline port


# WINDOWS
## standalone - 140 MB, easier, looks less like a virus
download the one called polytrack-standalone, and run the exe inside.
## not standalone - 2 MB, moderately harder, looks more like a virus
download the one not called polytrack-standalone, run the bat inside, and go to http://localhost:8000
this one requires python to be installed.

# OTHER OS
## standalone - 140 MB, harder, looks less like a virus
download the once called polytrack-standalone, and run the exe inside using something like wine, probably works, im on windows so i dont need to test it 😝
## not standalone - 2 MB, easier, looks more like a virus
download the one not called polytrack-standalone, go to the files folder, and then find some way to locally host the directory. if youre on linux you can just use python which is the easiest. if you use mac go ask apple intelligence or something idk. maybe try download python for mac if that exists and run "python -m http.server 8000" in like any terminal. unless youre in the python terminal. then just run http.server 8000 maybe. also go to http://localhost:8000 after.
