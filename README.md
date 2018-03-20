# Low-Cost EEG
___Repo for storing files related to the Low-Cost EEG project at Stellenbosch University during the 2018 Global Health Technologies exchange with Northwestern University.___

---

Hardware is modified from the [OpenBCI Ganglion](https://github.com/OpenBCI/Ganglion_Hardware_Design_Files), firmware is copied directly from the [Ganglion library](https://github.com/OpenBCI/OpenBCI_Ganglion_Library) with no modification.

All design files were made with [KiCad](http://kicad-pcb.org/) EDA software.

Tested with Arduino IDE v1.8.5, utilizing Simblee library v1.1.4 from [https://www.simblee.com/package_simblee166_index.json](https://www.simblee.com/package_simblee166_index.json). See [this page](https://www.simblee.com/support.html) for instructions on adding an external board to your board manager.

Programmed using an [FTDI cable](https://www.adafruit.com/product/70). FTDI drivers are not yet supported on macOS versions 10.11.0 and above, so programming was done in a Windows 10 virtual machine.

The OpenBCI GUI, used for visualizing and analyzing the output data, can be downloaded from [OpenBCI's downloads page](http://openbci.com/index.php/downloads). OpenBCI also provides documentation for the [Ganglion](http://docs.openbci.com/Tutorials/02-Ganglion_Getting%20Started_Guide) and the [GUI](http://docs.openbci.com/OpenBCI%20Software/01-OpenBCI_GUI).
