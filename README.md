# Qemu-practice
qemu practice
[docs](https://wiki.qemu.org/Documentation)

## build
[download](https://www.qemu.org/download/)
```
wget https://download.qemu.org/qemu-8.0.0-rc3.tar.xz
tar xvJf qemu-8.0.0-rc3.tar.xz
cd qemu-8.0.0-rc3
./configure
make
```
## install
```
apt-get install qemu
```
## commane
```
qemu-system-x86_64 -smbios help
```
qemu-system-x86_64: -smbios help: Must specify type= or file=
```
qemu-system-x86_64 -device help
```
