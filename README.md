# Details

This repo contains quotes from the game ZeroRanger as a string/datfile pair, which can be used with [fortune-mod](https://github.com/shlomif/fortune-mod).

# Install

Run `make install` in the project folder. You will need sudo permissions as it will copy the datfile pair into `/usr/share/fortune/`.

Alternatively, you can manually copy the pair of files in `datfiles` to your `fortune` directory (typically `/usr/share/fortune/`).

You could also just have the pair of files in some directory and call `fortune oranges` to get a random quote. This will only work if the files are in your current working directory.
