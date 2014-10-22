#Windows 7 Pro/Lubuntu Dual-Boot

###System Specs

    CPU - Intel Core i7-3820 Sandy Bridge-E 3.6GHz
    MOBO - ASUS Sabertooth X79 LGA 2011 Intel X79 SATA - BIOS: 2.14.1219 v3501
    MEMORY - CORSAIR Vengeance Pro 16GB (2 x 8GB)
    SSD- SanDisk Extreme II SDSSDXP-120G-G25 2.5"
    HDD - Seagate Barracuda ST1000DM003 1TB 7200 RPM

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

