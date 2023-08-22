# Qemu-practice
qemu practice
[docs](https://wiki.qemu.org/Documentation)

## build
[download](https://www.qemu.org/download/)
```
# install the dependency
sudo apt-get install git libglib2.0-dev libfdt-dev libpixman-1-dev zlib1g-dev ninja-build
wget https://download.qemu.org/qemu-8.0.0-rc3.tar.xz
tar xvJf qemu-8.0.0-rc3.tar.xz
cd qemu-8.0.0-rc3
./configure
make
```
## install
```
apt-get install qemu-system
apt-get install qemu-user-static
```
## command
```
qemu-system-x86_64 -smbios help
```
qemu-system-x86_64: -smbios help: Must specify type= or file=
```
qemu-system-x86_64 -device help
```

    qemu-system-x86_64 -cpu ?
    qemu-system-x86_64 -M ?
