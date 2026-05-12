# delete-linux-mint-from-dual-boot-windows-10
## linux mint
```
sudo fdisk -l
```
## windows 10
```
bcdedit /enum firmware
bcdedit /delete {identifier}
diskpart
list disk
sel disk 0
list part
```
