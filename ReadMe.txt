mkdmg version 1.0.0

USAGE
    mkdmg [OPTION]... <SRC_FILE|SRC_DIR> <DMG_FILE>

    Create a read-only disk image for MacOS.
    The image contains a single file or contents of a directory.
    An application bundle will be recognized as a single file.

OPTIONS
    -h, --help        Show this manual.
    --volname <name>  Set the name of the mounted volume.
    --volicon <path>  Set the icon of the mounted volume.
    --no-compression  Keep the image data uncompressed.

NOTE
    THIS PROGRAM ONLY WORK ON MAC OS.
