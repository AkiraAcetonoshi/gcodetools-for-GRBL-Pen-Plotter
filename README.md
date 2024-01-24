# Gcodetools for GRBL Pen Plotter

Gcodetools is an Inkscape extensions for generating [G-Code](https://en.wikipedia.org/wiki/G-code) for a [GRBL](https://github.com/grbl/grbl) pen plotter. It has been tested only on a GRBL pen plotter with a motor-actuated Z axis. It will likely not work for a servo-actuated pen plotter. 
It is based on [Gcodetools](https://github.com/cnc-club/gcodetools) by Nick Drobchenko, Vladimir Kalyaev, John Brooker, Henry Nicolas, Chris Lusby Taylor. No much was done apart from unifying "orientation points", "tools library" and "path to g code" into one extension. And messing with the *.py file.

# Installation

For windows put both .inx and .py files in the extensions folder :

`C:\Program Files\Inkscape\share\inkscape\extensions\other\Gcodetools-for-GRBL-Pen-Plotter` 

Please create a separate folder from Gcodetools, as the *.py file was modified otherwise you risk breaking the original Gcodetools.


# Warning

This extension will probably not be maintained by me. Use at your own risk.