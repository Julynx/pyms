# pyms
*Minimal command-line music player written in Python.*
<br><br>

<p align="center">  
  <img width="772" src="https://i.imgur.com/DlI6U2g.png">
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
cd pyms
pip3 install -r requirements.txt
chmod +x pyms
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
