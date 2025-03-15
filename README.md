<br/><br/>
<div align="center"> 
  <img src="https://profile-counter.glitch.me/Zhodisov/count.svg" alt="Visitor's Count" />
</div>
<br/><br/>

<div align="center">
  
[![YOUTUBE](https://img.shields.io/badge/Youtube-fc0000?style=for-the-badge&logo=YOUTUBE&logoColor=white)](https://www.youtube.com/@Jodis974)
[![Discord](https://img.shields.io/badge/Discord-6a85b9?style=for-the-badge&logo=discord&logoColor=white)](https://safemarket.xyz/discord)
[![Safemarket Email](https://img.shields.io/badge/safemarket_email-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:support-checkout@safemarket.xyz)
[![safemarket.xyz](https://img.shields.io/badge/safemarket.xyz-0077B5?style=for-the-badge&logo=internet&logoColor=white)](https://safemarket.xyz/)

</div>





# mutante
Windows kernel-mode hardware identifier (HWID) spoofer. It does not use any hooking, so it can be completelly unloaded after use. Tested on Windows 10 x64 2004 (19041.264).

## Features
- Disk serials (works on both SATA and NVMe drives)
- Disable S.M.A.R.T functionality
- SMBIOS (tables 0-3) modification (not zeroing)

## Credits
- Me (@SamuelTulach) - Putting it all together
- n0Lin (@Alex3434) - [Static disk spoofing without hooks](https://github.com/Alex3434/wmi-static-spoofer)
- IChooseYou - [Disable S.M.A.R.T functionality](https://www.unknowncheats.me/forum/2441916-post67.html) and [finding SMBIOS physical address](https://www.unknowncheats.me/forum/2436698-post9.html)
- btdt (@btdt) - [Finding SMBIOS physical address (again)](https://github.com/btbd/hwid/blob/master/Kernel/main.c#L558) and [signanture scanning functions](https://github.com/btbd/hwid/blob/master/Kernel/util.c#L112)