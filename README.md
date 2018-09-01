# pycons
A small GTK application that allows you to mix and match different Linux icon themes

## Installation
pycons is written in Python 3 / PyGObject and can easily be installed via pip/pip3:
    
    pip install pycons
or
    
    pip3 install pycons
depending on how your Linux distribution handles Python 3.

## Usage
Example: I use Gnome 3 with the Dash to Dock extension and I like the "Numix Circle" icons for my dock, but I'd rather have the Folder and Mimetype Icons from the "Paper" icon theme. 

pycons let's you mix and match different icon-themes. It checks for installed icon-themes in <code>/usr/share/icons</code> and copies the newly created ones to <code>~/.local/share/icons</code>.
