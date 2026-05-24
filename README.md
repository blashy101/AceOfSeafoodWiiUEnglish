# AceOfSeafoodWiiUEnglish
Incredibly simple language check bypass performed by changing region code in meta.xml:

Must be using latest update, ver 32

Navigate to usr/title/0005000e/10207a00/meta and replace your xml with the one from the repo or do the following:

Change:

 region type="hexBinary" length="4">00000001

  to 

region type="hexBinary" length="4">00000004

Save and game will automatically load English string data/text asset inside of game assets.
