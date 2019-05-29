# submerge

A script that uses mkvmerge to merge a subtitle to an mkv

The ISO-8859-2 (central european standard) and the $old_filename.ROSUB.$extension format are hardcoded (contributions are welcome)

## installation 

### ubuntu,debian

`git clone git@github.com:lucian-vasile/submerge.git`

`ln -s /path/to/submerge/submerge /usr/bin/submerge`

## usage

`cd` into a directory containing at least an .mkv and a .sub or a .srt file

run `submerge`

## output

./$old_filename.ROSUB.$extension
