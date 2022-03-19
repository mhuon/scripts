# scripts

# create iso in osx

disktutil list
sudo diskutil unmount /dev/disk1
dd if=/dev/disk1 of=~/myCD.iso bs=2048 conv=sync,notrunc
