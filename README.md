# bs1770gain_fixes
Fixes for http://bs1770gain.sourceforge.net/ (version 0.4.10)

Matroska test videos are available here: https://sourceforge.net/projects/matroska/files/test_files/matroska_test_w1_1.zip/download

test5.mkv has multiple audio streams.

Multiple audio channel test files: http://download.openbricks.org/sample/HD-Audio/

----
Fixes an issue where --audio and --video options are not used.

Fixes an issue where on files with multipe audio tracks, the last stereo audio track is used for replaygain calculation (instead of the first).

Fixes a stack smashing issue when a audio file with more than 5 audio channels is analyzed.
