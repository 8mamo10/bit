# bit

```
$ brew install --cask gcc-arm-embedded
$ brew install make
$ brew install qemu
```

```
$ arm-none-eabi-gcc --version
$ arm-none-eabi-objcopy --version
$ arm-none-eabi-gdb --version
$ qemu-system-arm --version
```

```
$ ls /dev/cu.usbmodem*
$ screen /dev/cu.usbmodem2102 115200
```

```
$ brew install picocom lrzsz
$ picocom -b 115200 --send-cmd "lsx -vv" /dev/cu.usbmodem*
```
