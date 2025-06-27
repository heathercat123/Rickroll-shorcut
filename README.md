# Archived
This is garbage. No, this isn't getting migrated to Codeberg.

# Rickroll-shorcut
Send this LNK file to someone to rickroll them! \
Tip: Rename it to make it less obvious!

Only works on Windows, so if your friend uses Unix, NeXTSTEP, macOS, Linux, BSD, ChromeOS, MS-DOS, Microsoft BASIC, Minix, TempleOS, CP/M, OS/2, AmigaOS, BeOS or Haiku, just send a rickroll link I guess. Even if they are on Windows, don't use this. It's garbage.

## Explanation

C:\Windows\System32\cmd.exe /c 
- Opens cmd and execute this command:

@echo off && cd %userprofile% && start https://www.youtube.com/watch?v=dQw4w9WgXcQ && echo X=MsgBox("Rickrolled LOL!",0+48, "RICKROLLED") > msg.vbs & cscript msg.vbs & del msg.vbs
- && = new command, so it's more like this:

@echo off
- Makes it so the commands can't be seen in the CMD window.

cd %userprofile%
- Goes to userprofile because we add a file and delete it later and you cannot make/delete a file without admin priveleges in the default cmd directory (System32).

start https://www.youtube.com/watch?v=dQw4w9WgXcQ
- Opens never gonna give you up.

echo X=MsgBox("Rickrolled LOL!",0+48, "RICKROLLED") > msg.vbs & cscript msg.vbs & del msg.vbs
- Makes a file called msg.vbs that makes a message box, opens it and when you click ok, deletes the file.
