# Pixel 7 series 32-bit support

The Pixel 7 line of phones from Google has the same hardware support as the previous Pixel 6 series for 32-bit app support, however Google disabled it in the OS. This may be different in custom ROMs, but not in the stock (or stock rooted) Android.


## Installation
Just download the latest release on the [release page](https://github.com/Puglover011/Pixel-7-32bit-KernelSU/releases/tag/Release) and install it the same way you would with other modules.

## How does it work?

The module is very simple and utilises the KernelSU system.prop feature to modify Androids system properties during boot. The module modifies *'ro.zygote'*, *'ro.vendor.product.cpu.abilist'*, and *'ro.vendor.product.cpu.abilist32'* to allow 32-bit programs.

## Update support
I probably won't update this as there's not much to really add or change. It works.

## Warning
Use at your own risk. I have only tested this on Android 17 on my Pixel 7 Pro with SukiSU-Ultra. It worked fine and runs as expected. There is no way for me to test it on other devices or configuration, but it should theoretically work fine on all Pixel 7 phones.


