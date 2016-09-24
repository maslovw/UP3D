# UP3D [![License](http://img.shields.io/:license-gpl2-blue.svg?style=flat-square)](http://www.gnu.org/licenses/gpl-2.0.html) [![Build Status](https://travis-ci.org/UP3D-gcode/UP3D.svg?branch=master)](https://travis-ci.org/UP3D-gcode/UP3D) 
[![Downloads](https://img.shields.io/github/downloads/UP3D-gcode/UP3D/total.svg?maxAge=3600)](https://github.com/UP3D-gcode/UP3D/releases/latest)
UP 3D Printer Tools

Download: [![Release](https://img.shields.io/github/release/UP3D-gcode/UP3D.svg?maxAge=60)](https://github.com/UP3D-gcode/UP3D/releases/latest)

Instructions: [up3dtools-how-to](http://stohn.de/3d/index.php/2016/03/10/up3dtools-little-how-to)

---

## up3dtranscode: 

G-Code to UpMachineCode (UMC) converter
```
Usage: up3dtranscode machinetype input.gcode output.umc nozzleheight

          machinetype:  mini / classic / plus / box
          input.gcode:  g-code file from slic3r/cura/simplify
          output.umc:   up machine code file which will be generated
          nozzleheight: nozzle distance from bed (e.g. 123.45)

example: up3dtranscode mini input.gcode output.umc 123.1
```
See list of supported G-Commands in wiki page [G-Command Overview](https://github.com/UP3D-gcode/UP3D/wiki/Supported-G-Code-Commands)
---

## up3dload: 

UpMachineCode (UMC) uploader, sends the umc file to printer and starts a print
```
Usage: up3dload output.umc
```
---

## up3dshell: 

Interactive printer monitor and debugging tool, use to watch printing
```
Usage: up3dshell
```
---

## up3dinfo: 

Program to show the details of the connected UP printer
```
Usage: up3dinfo
```
