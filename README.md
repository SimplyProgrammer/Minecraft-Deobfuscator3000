# About
Deobfuscator3000 is a universal tool for deobfuscating minecraft mods! It meant to be upgraded and improved variant of BON that was abandoned by its authors a long time ago.
Compare to BON this one allows you to choose obfuscation mappings by your self and it can decompile and deobfuscate your mod all at once!
Deobfuscator3000 can also deobfuscate individual java files and it can also works with zip files not only jars!
It also has more user-friendly UI with tooltips, logging console and other things! <br>
Deobfuscator3000 perfect choice for minecraft modders that lost their source code or for anyone that is interested in sources of other mods!

# How to use
1. As well as BON, Deobfuscator3000 is programmed in Java so you need Java to run it!
2. First you need to select deobfuscation mappings! These are excel files that tell the deobfuscator what to do with your mod! Defaulty there are mappings for 1.7.10 and 1.12.X and all what you need to do is write/select path to one of these folders into the first text field. If your mod is on a different version, then you need to obtain mappings for this certain version! In this case the best thing you can do is download them from [MCP](http://www.modcoderpack.com/), unpack the downloaded zip and select "conf" folders path into first the text field!
3. Now you need to decompile your mods jar! For this, I recommend to use Procyon on this online [Java decompiler](http://www.javadecompilers.com/).
4. After decompiling your mod, all what you need to do is select the path of the downloaded zip into the second text field and hit "Deobfuscate" button that supposed to be active by this time. If it is not there is most likely something wrong with deobfuscation mappings path or mods zip path. In this case the path in the text area will be red otherwise there should be no problem!
5. After clicking on "Deobfuscate" button program will take a while to deobfuscate the selected mod using selected mappings. Unzipped folder with deobfuscated mod sources will appear on your desktop. Now you have decompiled and deobfuscated mod sources to work with.
## Since 1.2.0
Since application was wrapped into installer and procyon decompiler was implemented, using procedure is now far easier!
1. Download and install deobfuscator from [here](https://download-deobfuscator3000.netlify.app/files/Deobfuscator3000%20setup.exe)!
2. Select deobfuscation mappings or download them from [MCP](http://www.modcoderpack.com/)!
3. Select your mods .jar file and make sure that checkbox is checked!
4. Click on "Deobfuscate", wait for it to finish and you are basically done (decompiled and deobfuscate mod sources will appear in the same folder as you mod jar file)!

# Valid deobfuscation mappings composition
Deobfuscation mappings are instructions for deobfuscator! They supposed to be a .csv (excel format) file or group of 3 files, the fields, methods, and params (each is optional since 1.0.5 but must be at least one of them) in one folder! Inside these files there supposed to be some sort of map with keys and values! These keys supposed to be in the first column of excel file and must contains at last one "\_" or since 1.1.0, can alternatively starts with "#" and then do not need to contains "\_"! And second column in excel file supposed to be the values for the keys. These values can be anything, there are no limits! But value should not be the same as key is and also should not be empty!

# Info
1. If your mods files were not deobfuscated correctly it is most likely not the deobfuscators fault but invalid mappings! Make sure your mappings are for same minecraft version as your mod is! If you have encountered some other issues please feel free to report it! Also always download the latest version of deobfuscator! 
2. Deobfuscator will unzip your .jar files while creating folders in process and during deobfuscation it will be editing created files in your system or even changing their extensions (.class -> .java) which is something that your antivirus might not like! In such a case, I would recommend disabling your antivirus or add Deobfuscator app as scan exception!
