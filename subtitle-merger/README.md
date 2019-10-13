# Subtitle Merger

## Backstory
I was sick of having cluttered video folders with separate video and subtitle files: 

```
s01_e01.mkv
s01_e01.srt
s01_e02.mkv
s02_e02.srt
s01_e03.mkv
s01_e03.srt
s01_e04.mkv
s01_e04.srt
s01_e05.mkv
s01_e05.srt
s01_e06.mkv
s01_e06.srt
...
```

This script will combine video and subtitle files with the same name into a single file.

## Usage

```
./merge_subtitles [-l -i -o]
```

- `-l` to define a custom video location (defaults to working directory)
- `-i` to define a custom input directory (defaults to working directory)
- `-o` to define a custom output directory (defaults to working directory)

### Running without flags

Since the default is to merge files in the current working directory, by moving `merge_subtitles.sh` file and `video_extensions` file to the directory with videos, the script can be run with no additional flags.