#  File Structure

#### This is the file structure for EmeraldOS.
------
#### Table View:

File Name | File Path | File Description
------ | ------ | ------
boot.seq   | /efi   | Boot sequence 
bootmenu.sys   | /efi   | Boot menu
setup.bin | /efi | Important binary for setup
setup.exe   | /boot   | First time setup (CANNOT be accessed after setup.)
accmgr.conf   | /root   | Config for managing accounts (use admin perms to view SYSTEM managed accounts.)
editreg.exe   | /root   | Registry Editor
fileman.exe   | /root   | File manager
mempool.mem   | /boot   | Memory pool file
swapman.sys   | /swap   | Swap manager (system managed)
envvm.exe   | /root   | Environment Variables Manager
memman.sys | /swap | Memory manager (system managed) - Controls what memory goes into SWAP when needed
denv.sys | /root | Desktop environment runtime
terminal.exe | /root | Code terminal
preferences.exe | /root | Settings
poweredit.exe | /root | Power plan editor
timedate.sys | /root | Time and Date editor
contpan.exe | /root | Control panel
search.sys | /root | Search for files and whatnot on the system (NO WEB RESULTS)
emerald_browser.exe | /root | Default internet browser

#### List View:


------------

- /efi
   - boot.seq
   - bootmenu.sys
   - setup.bin
------------


   - /boot
      - setup.exe
	  - mempool.mem
	  

------------
- /swap
    - swapman.sys
	- memman.sys

------------
- /root
   - accmgr.conf
   - editreg.exe
   - fileman.exe
   - envvm.exe
   - denv.sys
   - terminal.exe
   - preferences.exe
   - poweredit.exe
   - timedate.sys
   - contpan.exe
   - search.sys
   - emerald_browser.exe
