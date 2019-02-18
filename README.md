# ffmpeg-mp4-aif-merger
Simple ffmpeg unix based mp4 aif merger
This program will combine aif and mp4 files with the same name and creates a ${file}_output.mp4 (i.e. foo.mp4 foo.aif will be combined and outputted to foo_output.mp4) it will do this for all the mp4 and aif files which have a opposite with the same name in a folder, making it usable for "mass merging"

How to use:
1. make sure your ffmpeg-mp4-aif-merger file is runnable in unix using the command "sudo chmod +x ffmpeg-mp4-aif-merger"
2. run the script in the folder with the aif and mp4 files and wait for the merging to complete
3. you are done, there sould be (multiple) output files for each mp4/aif combination
