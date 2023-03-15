# TallWood_GoPro
EXE for processing GoPro video data from 2023 NHERI TallWood test.

Contents:
trim_video.zip - Compressed version of folder trim_video

How to use:
Open config.json.
Variables:
	Output Filename:	Output mp4 will be named "date_" + Output Filename + ".mp4".
  	Start Time:		Start time in HH:MM:SS. GoPros should be synced to Pacific Time.
  	Duration:		Duration of output in HH:MM:SS.
  	Input Folder:		Directory where mp4s are located. Backslashes must be doubled.
  	Output Folder:		Directory where processed file will appear. Backslashes must be doubled. Does not need to already exist.
  	Delete Originals:	true or false. Will delete original files if true. Leave as false unless you are sure.
Save config.json.
Double-click run.bat.