# armbian-multiboot
Shell script for Armbian Linux which allows to boot several boards
with a single SD card. Installing files for a new board can only
be done from a running Armbian system, while switching between the
boards can be done from any computer running a reasonably recent Linux.

# Usage

    sunxi-boot <boardname>

This command will switch the boot target to a given board, installing
necessary files on the first run. Running without arguments will
display the list of supported boards.
