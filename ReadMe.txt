mkdmg version 1.2.1

USAGE
    mkdmg [options] <source> <output.dmg>

    Create a read-only disk image for MacOS.
    The dmg file stores all contents of a directory or a file.

    Some sources are treated as files:
      [!.]*.{app,bundle,dictionary,framework,kext,plugin}

OPTIONS
    -h, --help        Show this manual.
    --volname <name>  Set the name of the mounted volume.
    --volicon <path>  Set the icon of the mounted volume.
    --no-compression  Keep the image data uncompressed.

NOTE
    THIS PROGRAM ONLY WORKS ON MAC OS.
