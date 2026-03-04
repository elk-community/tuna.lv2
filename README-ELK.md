# X42 Tuna plugin

Modified for headless plugin build for [Elk Audio OS](https://elk.audio)

## Building Instructions

1. Set up the cross-compilation toolchain with:

   ```bash
   $ unset LD_LIBRARY_PATH
   $ source /path/to/environment-setup
   ```

2. Cross compile the plugin using:

   ```bash
   $ MOD=TRUE make
   ```

