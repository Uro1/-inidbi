iniDBI(IMPROVED) - A simple server-side database extension using INI files

Authors:
inidbi - v1.4 x64 uro - https://github.com/Uro1
inidbi - v1.4 code34 - nicolas_boiteux@yahoo.fr
inidbi - v1.3 code34 - nicolas_boiteux@yahoo.fr
inidbi - v1.2 code34 - nicolas_boiteux@yahoo.fr
inidbi - v1.1 code34 - nicolas_boiteux@yahoo.fr
inidb - v1.0 SicSemperTyrannis http://raiderbattalion.enjin.com/

How to use:
To use "iniDBI" in your mission, install the extension in your ARMA2 or ARMA3 directory by copying the entire "@inidbi" folder included in the download to your root directory.
Don't forget to copy over over or create the /db/ folder.
It should look like: /Arma 3/@inidbi/iniDB.dll
It should look like: /Arma 3/@inidbi/iniDB_x64.dll
It should look like: /Arma 3/@inidbi/db/
It should look like: /Arma 3/@inidbi/Addons/inidbi.pbo

Then in your mission init.sqf, somewhere before you want to use the functions do this:
call compile preProcessFile "\inidbi\init.sqf";

It should be noted that when you install the @inidbi folder you can delete the /examples/ directory from there if you please, they serve no purpose in that folder.

You have permission to use, upload or otherwise distribute this as please, just mention differents authors.

----------------------------------------------------------------------------------------------

CHANGELOG
13-june-2017
- updated to vs2015 platform
- added x64 build options for Arma3_x64.exe compatability

06-february-2014 - inidbi
- add deletekey method
- fix private declaration

14-Decembrer-2013 - inidbi
- add deletesection feature
- fix buffer size

12-December-2013 - inidbi
- fix string serialize

16-November-2013 - inidbi
- check input/output data type
- add log messages

01-November-2013 - inidbi
- increase buffer 8k
- check size of written data
- change output function

13-March-2013
- Module
- Initial Release
- init.sqf
- Initial Release 


----------------------------------------------------------------------------------------------
For KillzoneKid's updates to make_file.dll he created a page on his blog containing x64 versions of his DLL's, you can find those on his website @ http://killzonekid.com/arma-64-bit-extensions/

For users looking for x64 versions of other common extensions used along with inidb such as make_file you should check the appropriate authors website.
----------------------------------------------------------------------------------------------
