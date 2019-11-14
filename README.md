# test
https://video.ultra-zone.net/watch?v=FEdXUv02Dbg&list=PL
win_dsc
win_package
win_chocolatey
win_reboot
wait_for_connection
win_updates:
  category_names: CriticalUpdates
  reboot: yes
  blacklist:
    -kb22222
    
    
    powershell
    get-WmiObject -class Win32_Share


Product id of the installed package (used for checking if already installed)
You can find product ids for installed programs in the windows registry either 
in HKLM:Software\Microsoft\Windows\CurrentVersion\Uninstall or for 32 bit programs HKLM:Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall'
