# Charify #

This is a python script for turning a picture into a picture made of characters.

To use you need python3, numpy, and PIL

Maybe this will work
```
pip3 install numpy pillow
```

Then try this
```
./charify -i example.png -o example_out.png
```

You can add more chars to the chars folder. Just call them [char].png and it will be cool.

## manual ##
```
Usage: charify [options]

Options:
  -h, --help            show this help message and exit
  -i INPUT, --input=INPUT
  -o OUTPUT, --output=OUTPUT
  -c CHARS, --chars=CHARS
                        comma-separated list of characters to use
  -d, --disjoint        whether should be disjoint or not
  -n NUM_CHARS, --num_chars=NUM_CHARS
                        number of characters to add
  -m MAX_FAILS, --max_fails=MAX_FAILS
                        number consecutive failed attemps to add a char before
                        quitting
  -s SIZE_RANGE, --size_range=SIZE_RANGE
                        colon-separated range for character size
  -u, --use_color       color chars with original
```
