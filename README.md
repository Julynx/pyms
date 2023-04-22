# pyms
*Minimal command-line music player written in Python.*
<br><br>

<br>
<p align="center">  
  <img width="640" src="https://i.imgur.com/lXdISlv.png">
</p>
<br>

## Dependencies
pyms uses [pygame](https://pypi.org/project/pygame/), [pynput](https://pypi.org/project/pynput/), [cursor](https://pypi.org/project/cursor/) & [mutagen](https://pypi.org/project/mutagen/), with version numbers provided in the file `requirements.txt`.

It has been tested with Python 3.10.6, results may vary if other versions are used.
<br><br>

## Installation
The following commands will download the latest version of pyms from this repository 
and install it in your `/usr/bin/` directory:
```
git clone https://github.com/Julynx/pyms
cd pyms
```
```
pip3 install -r requirements.txt
```
```
sudo chmod +x pyms
sudo mv pyms /usr/bin/
```
The program can now be ran from a terminal with the command `pyms`.
<br><br>

## Usage
```
Usage: 
    pyms [FILE] [OPTIONS]   Play a specific song.
    pyms [DIR.] [OPTIONS]   Play a random song from a directory.

OPTION:
    --update-interval=<X>   Redraw the UI every X seconds.
    --no-infinite-queue     Stop playback when the song ends.
    --no-clear              Don't clear the screen between UI updates.
                              This may help prevent flickering on 
                              some terminals.
    -h, --help              Print this message and exit.
    -v, --version           Print version information and exit.
```
<br>

## Changelog
- [x] [1.1.7] Reduce polling rate to 2 fps to reduce flickering on some terminal emulators.
- [x] [1.1.8] Reintroduce the SIGWINCH signal handler to allow for instant UI redraws when the window is resized instead of having to wait for the next redraw to take place.
- [x] [1.1.9] Implement ~~a configuration file~~ command line flags to ~~store~~ set the update interval, the redraw strategy, ~~the keybindings~~ enable / disable the infinite queue ~~and other relevant options.~~
- [x] [1.2.0] ~~Configurable keybindings and maybe some other stuff.~~ Fast fwd/bwd buttons + improved UI sprites!
- [x] [1.2.1] Fixed some issues with the infinite queue and folders with only one song.
- [x] [1.2.2] Improved the error messages.
