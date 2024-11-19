BITRATE NORMALIZATION SCRIPT

USAGE
    ./normalize-bitrate [-h] [directory]

DESCRIPTION
    the script analyzes all .mp3 and .wav files in the specified directory and its child
    directories for files with bitrates between 48kbps and 276kbps, converting the
    qualifying files to 320kbps.

    * To analyze all files (including files within child directories) from current directory
        ./normalize-bitrate

    * To analyze all files (including files within child directories) from target directory
        ./normalize-bitrate target

    at every execution, a .csv log of all files processed is created in the directory of execution.

OPTIONS

    -h  outputs help text displaying usage

DEPENDENCIES
    this script requires the ffmpeg library.

LICENSE
    GNU GPLv3
    https://chlf.dev/gnu-gplv3

LCHEN // 2024