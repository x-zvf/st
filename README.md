# XZVF's custom st build v2

This is the st build I use in my current rice.
The old one can be found in the v1 branch.

It uses the "Hack Nerd Font Mono". 
To build and install, run:
```
cd src
sudo make install
```


## Patches
_(Can be found in /patches)_
- Scrollback (w mouse)
- Solarized dark
- Alpha
- Anysize
- iso14755


# Default ST readme

st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

