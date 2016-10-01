Open a terminal
May require root permissions
Using brew (recommended) or macports install dfu-util (brew install dfu-util or port install dfu-util and port install libusb)
Enter DFU Flash Mode (e.g. press flash button), the debug led will turn on.
Flash using dfu-util -D <.dfu.bin>
Debug led will turn off
Keyboard is ready!
