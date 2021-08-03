# Titanfall-2-DDS-skin-application
script to automatically apply dds textures to pc_stream.starpak 

IMPORTANT:

This tool requires ~11gb of free space to write a new starpak file.
In its current iteration it may (read: will) use upto 16gb of ram. I hope to reduce 
this in the future but until than some computers may struggle to run the application.

Currently supported DDS textures:

 NAME                FILE ENDING
-base color          col
-Normal              nml
-gloss               gls
-specular            spc
-ambient occlusion   ao

INSTRUCTIONS:

1. Copy/move pc_stream starpak into the same folder as the exe.
2. Put DDS files in their appropriate folders. (dds2048, dds_1024, dds_512)
3. Rename the dds file so that the last 3 characters match match the texture type,
   see above table.
4. Run the program.
5. Follow instructions on the menu to select what gun you want to apply to.
6. Review files and confirm selection.
7. A new file name NEW_pc_stream.starpak will be created in the main folder,
   rename this file to pc_stream.starpak when you move it to the titanfall 2 pak
   directory. You can delete your original pc_stream.starpak or keep it as a backup.
