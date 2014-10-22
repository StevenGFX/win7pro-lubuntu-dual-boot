#Windows 7 Pro/Lubuntu Dual-Boot

###System Specs

    CPU - Intel Core i7-3820 Sandy Bridge-E 3.6GHz
    MOBO - ASUS Sabertooth X79 LGA 2011 Intel X79 SATA - BIOS: 2.14.1219 v3501
    COOLER - CORSAIR Hydro Series H100i Extreme Performance
    MEMORY - CORSAIR Vengeance Pro 16GB (2 x 8GB)
    SSD- SanDisk Extreme II SDSSDXP-120G-G25 2.5"
    HDD - Seagate Barracuda ST1000DM003 1TB 7200 RPM

####SSD - 120GB


| Partition | FS | Label |  Size | Used | Unused | Flags |
| :-------- | :--- | :-------------- | ---------: | --------: | --------: | :--- |
| /dev/sdb1 | ntfs | System Reserved | 100.00 MiB | 24.13 MiB | 75.87 MiB | boot |
| /dev/sdb2 | ntfs |  | 68.26 MiB | 35.09 MiB | 33.17 MiB |  |
| New Partition #1 | extended |  |  43.43 GiB | -- | -- |  | 
| New Partition #2 | ext4 | root / | 43.43 GiB | -- | -- |  |


####HDD - 1TB

| Partition | FS | Label |  Size | Used | Unused | Flags |
| :-------- | :--- | :-------------- | ---------: | --------: | --------: | :--- |
| New Partition #3 | ext4 | swap | 15.62 GiB | -- | -- |  | 
| New Partition #4 | ext4 | home | 292.97 GiB | -- | -- |  |
| New Partition #5 | ntfs | shared | 622.92 GiB | -- | -- |  |

