# Project Title

Simple overview of use/purpose.

## Description

`lsblk

cryptsetup luksFormat /dev/nvme0n1p1

cryptsetup luksOpen /dev/nvme0n1p1 nvme


mkfs.ext4 /dev/mapper/nvme

mkdir /mnt/nvme
mount /dev/mapper/nvme /mnt/nvme

cryptsetup luksDump /dev/nvme0n1p1`



## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

    * Initial Release



