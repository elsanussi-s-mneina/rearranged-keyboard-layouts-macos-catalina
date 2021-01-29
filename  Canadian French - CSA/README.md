# About the rearranged Canada CSA keyboard layouts.

## Requirements
Mac OS

## How I generated these files.

I got the original Keyboard Layout via Ukelele's generate keyboard from Current input source.
Then I added
 Keymaps 0, 1, 2, 3, 4, 5, and 6 which have been converted to Colemak. I did not convert 7, 8, or 9 because I am unsure of their purpose.

I converted to Colemak by copying those keymaps into a file titled "qwertyKeyMapsInput.txt" in the same folder as the script and run through a Python script that rearranges the keys (specifically I ran the command 

python3 workshopForMultipleKeymaps.py

Then I copied the contents of one of the **Output.txt files.

The Python script is available at https://github.com/elsanussi-s-mneina/keyboard-layout-translation
