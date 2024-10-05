### XKB version >= 2.43
The RuIntl keyboard layouts set is already built-in in your Linux operation system (OS).

### XKB version < 2.43
Please follow the installation instructions below to add those layouts to your OS.

Installation instructions:

1. Copy the **ru** file from the **Linux** folder in .zip archive to the **Home** folder of your OS;
2. In terminal execute the following command to add those layouts to your OS layouts file:
   
   **sudo cat ~/ru >> /usr/share/X11/xkb/symbols/ru**;
4. Then use the following command to set those layouts:
   
   **setxkbmap -layout "ru,ru" -variant "ruintl_en,ruintl_ru"**.
