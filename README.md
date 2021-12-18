# Titanfall2-DDS-Tool
script to automatically apply dds textures to pc_stream.starpak 

**I do not plan to continue updating this tool.  
There are better alternatives available**

**This tool does not create backups**

Currently supported DDS textures:

| NAME              | FILE ENDING  | 
| :-------------    | :----------: |
|  base color       | col          | 
|  normal           | nml          |
|  gloss            | gls          |
|  specular         | spc          |
|  illuminance      | ilm          |
|  ambient occlusion| ao           |
|  cavity           | cav          |

INSTRUCTIONS:

1. Copy pc_stream starpak into the same folder as the exe.
2. Put DDS files in their appropriate folders. (dds2048, dds_1024, dds_512)
3. Rename the dds file so that the last 3 characters match match the texture type,
   see above table.
4. Run the program.
5. Follow instructions on the menu to select what gun you want to apply to.
6. Review files and confirm selection.
7. Move pc_stream.starpak back to its original directory
