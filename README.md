# pyms
*Minimal command-line music player written in Python.*
<br><br>

<h4 align="center">Designed with elegance and minimalism.</h4>
<p align="center">  
  <img width="772" src="https://i.imgur.com/IdqmRCL.png">
</p>
<br>

<h4 align="center">Resizes dynamically with your terminal.</h4>
<p align="center">  
  <img width="772" src="https://s10.gifyu.com/images/Resizing.gif">
</p>
<br>

## Dependencies
pyms uses [pygame](https://pypi.org/project/pygame/), [pynput](https://pypi.org/project/pynput/) & [cursor](https://pypi.org/project/cursor/), which can be installed by executing:
```
pip3 install pygame
pip3 install pynput
pip3 install cursor
```
It has been tested with Python 3.8.10, results may vary if other versions are used.
<br><br>

## Installation
The following commands will download the latest version of pyms from this repository 
and install it in your `/usr/bin/` directory:
```
git clone https://github.com/Julynx/pyms
cd pyms
chmod +x pyms
sudo cp pyms /usr/bin/
```
The program can now be ran from a terminal with the command `pyms`.
<br><br>

## Usage
Execute the following command to play the song passed as an argument:
```
pyms <song.mp3>
```
