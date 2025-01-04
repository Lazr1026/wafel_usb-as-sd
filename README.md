# Stroopwafel plugin to use a FAT32 USB drive as the SD Card

This plugin for [stroopwafel](https://github.com/shinyquagsire23/stroopwafel) to mount a FAT32 USB drive to 
## How to use

Put the `wafel_usbassd.ipx` in `sd:/wiiu/ios_plugins` . If you plan to put the plugin on the SLC, rename it to `3usbsd.ipx` and copy it to `slc:/sys/hax/ios_plugins`, or copy it with haxcopy.

## Building

```bash
export STROOPWAFEL_ROOT=/path/to/stroopwafel
make
```

## Thanks

- [**rw-r-r-0644**](https://github.com/rw-r-r-0644) for isfshax.
- [**GaryOderNichts**](https://github.com/GaryOderNichts) for isfshax contributions.
- [**shinyquagsire23**](https://github.com/shinyquagsire23) for de_Fuse and Stroopwafel.
- [**jan-hofmeier**](https://github.com/jan-hofmeier) for the patch.
