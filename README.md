𝙈𝙖𝙠𝙚 𝙨𝙪𝙧𝙚 𝙮𝙤𝙪 𝙝𝙖𝙫𝙚 𝙈𝙤𝙙𝙚𝙧𝙣 𝙒𝙖𝙧𝙛𝙖𝙧𝙚 𝙍𝙚𝙢𝙖𝙨𝙩𝙚𝙧𝙚𝙙 (2017) 𝙖𝙣𝙙 𝙈𝙤𝙙𝙚𝙧𝙣 𝙒𝙖𝙧𝙛𝙖𝙧𝙚 3 (2011) 𝙞𝙣𝙨𝙩𝙖𝙡𝙡𝙚𝙙 𝙤𝙣 𝙨𝙩𝙚𝙖𝙢

-Modern Warfare 3

Download MW3 from Steam
Download MW3 Jam Files (I can paste link to the files)
Paste Usermaps and Mods folder into MW3 steam directory
Open MW3 Directory on Steam
Open Usermaps from the MW3
Drag FF file you want into zone (The FF files will be in usermaps in MW3 directory)
Open IW5 Zonetool
"dumpzone mp_" of the FF file that you want from the usermaps folder
Let the map dump and open the dump folder in MW3
Drag folder from dump in MW3 folder into zonetool at MWR

- Modern Warfare Remastered

Open H1 Zonetool
"buildzone MP_"
If any errors open notepad ++
Copy the error that it gives you when you try to buildzone and paste it into Notepad ++
Copy the first line of code after "stateinfo for techset"
CTRL H
Look at search results under line and find the line that only has 1 comma 
Copy the "techset" line that only has 1 comma in it
Open H1 zone tool again and paste "dumpzone techset_"
Let it dump
Once it is done dumping open both "zonetool_paths" and "dump" folder in your MWR directory 
CTRL + X to copy from dump folder and CTRL + V in the "zonetool_paths" folder 
Run the "buildzone mp_" again and let it build
If you get another error of missing assets, rinse and repeat the same process in notepad ++ and H1 zone tool

If you cannot find the last techset right click at the codes and press clear all and re do process of searching

if dumping the techset does not work do loadzone techsets_common. That means its a singleplayer techset 
After that run the "dumpzone techset" command line 

- Creating the CSV 
Copy your CSV in your "zonetool" folder and paste it in "zone_source" folder
Open your CSV in notepad or visual studio code and paste the template. I will provide that
Edit the command line called "mp_template" and replace it as your map name. Make sure nothing is misspelt 
Save the file and your CSV is created 

- How to make the zone tools work
You will need the zonetool exe and zonetool.dll from H1 and IW4X. I will provide those
Drag and drop the H1 zone tool and zone tool.dll into MWR directory 
Drag and drop the IW5 zone tool and zonetool.dll into the MW3 directory

