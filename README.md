Portable-VirtualBox
===================

Portable-VirtualBox is a free and open source software tool that lets you run any operating system from a USB stick without separate installation.

More info is available at http://www.vbox.me/


### Installation ###

**Universal (semi-manual):**
1) Unpack **Portable-VirtualBox-6-5-11.7z** to any folder for example "D:\Portable-VirtualBox\".
2) Download VirtualBox from official website: https://www.virtualbox.org/wiki/Downloads. For example **VirtualBox-6.1.28-147628-Win.exe**.
3) Execute **Portable-VirtualBox.exe**, press **Search** button and navigate to **VirtualBox-6.1.28-147628-Win.exe**.
4) Activate **Extract the files for 64-bit system** checkbox. Press OK and follow instructions.

**Automatic is for version 6.1.28 (147628) currently:**
1) Unpack **Portable-VirtualBox-6-5-11.7z** to any folder for example "D:\Portable-VirtualBox\".
2) Execute **Portable-VirtualBox.exe**, activate **Extract the files for 64-bit system** checkbox and then press **Download installation files of VirtualBox**.
4) Press OK and follow instructions.


Man can use VirtualBox v5 or even v4 with 32-bit support.
32-bit is deprecated in VirtualBox v6.


### Manual Update ###

1) Download latest **VirtualBox-6.x.x-xxxxxx-Win.exe** from official website.
2) Put it to **Portable-VirtualBox** dir.
3) Open **UnpackPortable_6.cmd** in notepad and edit first four lines: VER, MAJOR, MINOR, BUILD.
4) Execute **UnpackPortable_6.cmd**.
5) Directory **VirtualBox-6.x.x-xxxxxx-Win** will be created. Move it's contents to **Portable-VirtualBox** dir. Replace old files.

### Building ###

1) Download and install **AutoIt** from official website: https://www.autoitscript.com/site/autoit/downloads/. Current stable is v. 3.3.14.5.
2) Right click **Portable-VirtualBox.au3** -> Compile with options -> Compile Script.
That's it!

Or see original instruction for information on how to build from source: [BUILDING](BUILDING.md).
