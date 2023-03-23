
This is my keymap for the Kyria. I use a common set of keys in the thumb clusters, bottom row, and outside columns, with four total layers for different functionality.

The common keys are mostly modifiers like Ctrl/Shift or extremely common keys like Space, Backspace, Return, Tab, Esc, etc. Also single quote. Don't worry about it. The bottom leftmost and bottom rightmost keys are the layer shifting keys. Layer 0 is default, holding the left key is layer 1, holding the right is layer 2, and holding both is layer 3.

1. Layer 0 is a basic QWERTY
2. Layer 1 has arrows and PgUp/PgDn; Home/End on the left hand and a numpad arrangement with some other symbols on the left hand. The numbers use their normal shift symbols instead of the numpad symbols for easier access
3. Layer 2 has braces and parens on the left hand and currently nothing on the right, although I might move the F keys there
4. Layer 3 has bluetooth controls on th eleft hand, and the F keys on the right

##### Guide to update the keymap

1. update the kyria.keymap file
   a. check [https://zmk.dev/docs/codes](https://zmk.dev/docs/codes) for the keypress codes
2. git push
3. wait for the github action to complete
4. download the generated firmware.zip file
5. extract it into the two firmware files for each side
6. copy each file into the kyria
7. then, for each side of the board:
   a. enter bootloader mode by double-pressing the reset key
   b. connect the keyboard to the laptop with a cable
   c. mount it as a USB drive
   d. copy the firmware file to the drive
   e. wait for the drive to show up as empty/disconnected
   f. unplug the keyboard
7. done!
