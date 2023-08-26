# RG353V
Knowledge for Handheld Device RG353V

CPU / Architecture: Rockchip RK3566 (ARM), same as Anbernic RG353P/M/V/VS, RG503, and Powkiddy RK2023, x55  
Kernel: Rockchip BSP 4.19  
GL driver: Mali  
Interface: KMS/DRM + EmulationStation  

OS:
1. Stock OS (Batocera rip): https://win.anbernic.com/download/233.html  
2. JELOS: https://github.com/JustEnoughLinuxOS/distribution
3. Ark OS: https://github.com/christianhaitian/arkos/wiki  

Full BIOS for Batocera 37:  
http://theminicaketv.free.fr/bios.html  

Set device for the first time:  

Press `START` -> `MAIN MENU` -> `NETWORK SETTINGS`  
`ENABLE WIFI` : change to `ON`  
`WIFI SSID` : change to ``  
`WIFI KEY` : change to ``  

Open ssh IP ADDRESS (192.168.1.X) and execute this command:  
`wget https://raw.githubusercontent.com/andreasgr/RG353V/main/rg353v_setup_batocera_es.sh -O - | /bin/bash`  

## Apps for RG353V
Mini File Manager (Enhanced) : https://github.com/leonkasovan/351Files  
Custom Emulation Station : https://github.com/leonkasovan/batocera-emulationstation
