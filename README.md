# pyms
*Minimal command-line music player written in Python.*
<br><br>

<h4 align="center">Regular extended view</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/DlI6U2g.png">
</p>
<br>

<h4 align="center">Interface when collapsed</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/4hC3hmk.png">
</p>
<br>

## Dependencies
pyms uses [pygame](https://pypi.org/project/pygame/), [pynput](https://pypi.org/project/pynput/), [cursor](https://pypi.org/project/cursor/) & [mutagen](https://pypi.org/project/mutagen/), with version numbers provided in the file `requirements.txt`.

It has been tested with Python 3.8.10, results may vary if other versions are used.
<br><br>

## Installation
The following commands will download the latest version of pyms from this repository 
and install it in your `/usr/bin/` directory:
```
git clone https://github.com/Julynx/pyms
```
```
cd pyms
```
```
pip3 install -r requirements.txt
```
```
chmod +x pyms
```
```
sudo mv pyms /usr/bin/
```
The program can now be ran from a terminal with the command `pyms`.
<br><br>

## Usage
Execute the following command to play the song passed as argument:
```
pyms path/to/song.mp3
```
You can also specify a path to a directory and `pyms` will play a random file from that directory.
<br><br>

## TODO
- [x] [1.1.6] Reduce polling rate to 2 fps to reduce flickering on some terminal emulators.
- [x] [1.1.7] Reintroduce the SIGWINCH signal handler to allow for instant UI redraws when the window is resized instead of having to wait for the next redraw to take place.
- [ ] [1.1.8] Implement a configuration file to store the update interval, the redraw strategy, the keybindings and other relevant options.
