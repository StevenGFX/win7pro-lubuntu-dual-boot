#Windows 7 Pro/Lubuntu Dual-Boot

###System Specs

    CPU - Intel Core i7-3820 Sandy Bridge-E 3.6GHz
    MOBO - ASUS Sabertooth X79 LGA 2011 Intel X79 SATA - BIOS: 
    COOLER - CORSAIR Hydro Series H100i Extreme Performance
    MEMORY - CORSAIR Vengeance Pro 16GB (2 x 8GB)
    SSD- SanDisk Extreme II SDSSDXP-120G-G25 2.5"
    HDD - Seagate Barracuda ST1000DM003 1TB 7200 RPM
    GPU - SAPPHIRE 100352-3L Radeon HD 7950 3GB 384-bit (11196-19)
          SAPHHIRE XXXXXX-XX Radeon R9 280X 3GB 384-bit GDDR5
    PSU - Cooler Master Silent Pro M2 - 720W Power Supply
    CASE - Corsair Carbide Series 330R

####SSD - 120GB


| Partition | FS | Label | Size | Flags | Mount Point |
| :-------- | :--- | :-------------- | ---------: | :--- | :--- |
| /dev/sdb1 | ntfs | System Reserved | 100.00 MiB | boot |  |
| /dev/sdb2 | ntfs | Windows 7 Pro 64 | 68.26 MiB |  |  |
| /dev/sdb3 | extended |  | 43.43 GiB |  |  |
| /dev/sdb5 | ext4 | root / | 43.43 GiB |  | / |


####HDD - 1TB

| Partition | FS | Label | Size | Flags | Mount Point |
| :-------- | :--- | :-------------- | ---------: | :--- | :--- |
| /dev/sda1 | linux-swap | swap | 15.62 GiB |  |  | 
| /dev/sda2 | ext4 | home | 292.97 GiB |  | /home |
| /dev/sda3 | ntfs | shared | 622.92 GiB | msftdata | /windows |

###Peripherals

    KEYBOARD - Corsair K95
    MOUSE - SteelSeries Sensei
    HEADSET - GameCom 780
    JOYSTICK - Logitech Extreme 3D Pro
    HEAD TRACKING - TrackIR 3
    DUAL MONITORS
