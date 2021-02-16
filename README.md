# ASUS Z170-DELUXE - i7-6700K - HD 530 & RX 5700 - [From macOS El Capitan 10.11.6 to Big Sur 11 - Windows 10]
 ## Clover EFI for ASUS Z170-Deluxe - macOS Big Sur
 ## Insanelymac GUIDE: https://www.insanelymac.com/forum/topic/342082-guide-asus-z170-deluxe-i7-6700k-hd-530-rx-5700-from-macos-el-capitan-10116-to-big-sur-11-windows-10/
 <p align=center>
    <img src="https://www.asus.com/media/global/products/x2NF8IZy4dM3NgLH/P_setting_fff_1_90_end_500.png">
</p>

<p align="center"><b>ASUS Z170-DELUXE</b></p>
<p align=center>macOS Install Instructions (Clover v5130)</p>
<p>For specs, notes, other informations see the linked Insanelymac guide</p>


## Installation:
- Create a macOS USB Installer with any method you now.
    - For Sierra and older you need to use the official .dmg from Apple’s website.
- Mount your USB’s EFI and paste my CLOVER and BOOT folder from my bootpack
folder to it
    - On Windows you can mount your USB’s EFI with MiniTool Partition Wizard
        - Open MiniTool, select your USB drive’s EFI partition, right click, select “Change Letter”, Click OK, Apply, OK
    - After that you can manage the EFI using Explorer++ in administrator mode
    - On macOS you can use Terminal to mount, or use EFI Mountain Snow.app to mount your USB EFI
    - If there is no EFI folder inside the EFI partition you need to create that first
 
Example Structure:
<p align=center>
    <img src="https://i.ibb.co/5FZthw6/Picture-1.png">
</p>

- After finished, next step is to boot the Installer USB
    - I suggest to boot with config_debug.plist because if anything will go wrong you’ll see the logs of what causing that. 
    - In Clover press NUM 0 or select “Options” below the partitions, select “Configs”, then select “config_debug.plist” 
- Install macOS 
    - Don’t forget to boot from your USB after restarts 
        - If you install Big Sur boot from Preboot only! 
- After installing you need to mount your USB’s EFI and your System Drive’s EFI then copy the CLOVER and BOOT folder to your System Drive’s EFI  
    - (again, if there is no EFI folder, you need to create it first) 
- Unmount and remove your USB Installer and restart your system 

<p align=center>That’s it!</p>
<p align=center><b> Happy Hackintoshing!  </b></p>
<p align=center>2021</p>
<p align=center>Insanelymac - <a href="https://www.insanelymac.com/forum/profile/2210435-kushwavez/">@kushwavez</a></p>
<p align=center>GitHub - <a href="https://github.com/kushwavez">kushwavez</a></p>
<p align=center>Reddit - <a href="https://www.reddit.com/user/kushwavez">u/kushwavez</a></p>
<p align=center>Hungary 🇭🇺</p>
