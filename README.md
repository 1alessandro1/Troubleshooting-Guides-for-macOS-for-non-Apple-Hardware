# Troubleshooting Guides - macOS on non Apple Hardware

This repository is a collection of sporadic guides across the network. Please note that many of this guides include other guides embedded as well. Please note that I do NOT own this guides, but I find them useful for educational purposes only.
This list may be incomplete or defective, we are going to maintain this list as much as we can.

# Bootloaders

## Source Code

* [Clover](https://github.com/cloverhackycolor/CloverBootloader)
* [OpenCore](https://github.com/acidanthera/OpenCorePkg)

## Guides
#### OpenCore

* [OpenCore - Main Guide by Khronokernel](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
* [OpenCore - Main Guide by Khronokernel - Black Version](https://khronokernel.github.io/Opencore-Vanilla-Desktop-Guide)
* [IT guide by macOS86.it](https://macos86.gitbook.io/guida-opencore)
* [Configuration.pdf from source code repo](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf)
* [Difference](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Differences/Differences.pdf)
* [Changelog](https://github.com/acidanthera/OpenCorePkg/blob/master/Changelog.md)
* [InsanelyMac - Development topic](https://www.insanelymac.com/forum/topic/338527-opencore-development)

##Intel Deskies

* [r/Hackintosh Vanilla Desktop Guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide)
* [OpenCore - Main Guide by Khronokernel](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)

## AMD Deskies

* [Vanilla AMD-OSX](https://vanilla.amd-osx.com)
* [All-in-one Vanilla AMD Hackintosh Guide](https://kb.hackintoshisfun.ml/clover)
* [AMD Ryzen USB FIX](https://github.com/XLNCs/ryzenusbfix/blob/master/ManualGuide.md)
* [audio_cloverALC for AMD Ryzen CPUs](https://github.com/AlGreyy/AMD_Ryzen-audio_CloverALC)

## Harware Selection

* [Anti-Hackintosh Buyers Guide](https://khronokernel-5.gitbook.io/anti-hackintosh-buyers-guide)
* [macOS Catalina supported GPUs](https://khronokernel-3.gitbook.io/catalina-gpu-buyers-guide)
* [Disable unsupported GPUs](https://khronokernel-4.gitbook.io/disable-unsupported-gpus)

## Wireless Hardware (PCIe, mini PCIe, M.2, Express Card, USB)

* [Wireless Buyers Guide](https://khronokernel-7.gitbook.io/wireless-buyers-guide)

* [Wireless USB Adapters](https://github.com/chris1111/Wireless-USB-Adapter-Clover)


####*(Old mojave GPU buyers guide - Deprecated)*

* [Mojave GPU Buyers Guide from r/hackintosh](https://www.reddit.com/r/hackintosh/comments/b91vf5/mojave_gpu_buyers_guide)
* [Mojave GPU Buyers Guide](https://github.com/khronokernel/Mojave-GPU-Buyers-Guide)

## Reddit

* [r/Hackintosh](https://www.reddit.com/r/hackintosh/wiki/faq#wiki_guides)

## What's new... 

* [...in macOS Catalina 10.15](https://github.com/khronokernel/What-s-new-in-macOS-Catalina/blob/master/README.md)

## Downloading macOS Installer and security checksums

* [Reddit thread](https://www.reddit.com/r/hackintosh/comments/efjy5g/how_to_download_macos_from_apples_official/)
* [MacAdmin scripts- check docs folder](https://github.com/munki/macadmin-scripts)
* [Apple Installer Checksums](https://github.com/notpeter/apple-installer-checksums/blob/master/readme.md#mac-osx-installers-sha1-checksums)

## Boot Flags (Old guides, needs more research/checking)

* [Cnet](https://www.cnet.com/news/boot-argument-options-in-os-x/)
* [InsanelyMac](https://www.insanelymac.com/forum/topic/99891--/)


## Making the bootlable USB from scratch

* [gibMacOS](https://internet-install.gitbook.io/macos-internet-install)
* [InsanelyMac thread](https://www.insanelymac.com/forum/topic/329828-making-a-bootable-high-sierra-usb-installer-entirely-from-scratch-in-windows-or-linux-mint-without-access-to-mac-or-app-store-installerapp)


## ACPI

* [ACPI from Khronokernel guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/extras/acpi)
* [outdated 2014 - InsanelyMac Thread](https://www.insanelymac.com/forum/topic/298027-guide-aio-guides-for-hackintosh/?tab=comments#comment-2027250)
[Official Documentation (1200+ pages, Good Luck)](https://uefi.org/sites/default/files/resources/ACPI_6_3_May16.pdf)

## Fixes 

[Power Management](https://www.reddit.com/r/hackintosh/comments/bnimcj/power_management_101)

### Audio

* [AppleHDA patching guide](https://osxlatitude.com/forums/topic/1946-complete-applehda-patching-guide)
* [Fix Combojack noise](https://osxlatitude.com/forums/topic/11316-how-to-fix-static-noisedistortioncrackling-sound-and-combojack-in-laptops)
* [Migrating to AppleALC](https://www.reddit.com/r/hackintosh/comments/4sil5p/audio_mechanic_old_patchfix_removal_applealc)
* [Guide AppleALC](https://www.reddit.com/r/hackintosh/comments/4e23w6/guide_native_audio_with_clover_applealckex)


## Intel Laptop (Main Guide)

* [Fewtarius](https://fewtarius.gitbook.io/laptopguide)

## Rehabman/Tonymac (usually outdated, try to avoid if possible)

* [Booting macOS installer on laptops with Clover](https://www.tonymacx86.com/threads/guide-booting-the-os-x-installer-on-laptops-with-clover.148093)
* [Laptop Rehabman FAQ](https://www.tonymacx86.com/threads/faq-read-first-laptop-frequent-questions.164990/)
* [Laptop common issues](https://www.tonymacx86.com/threads/readme-common-problems-changes-fixes-on-mojave.255823/)
* [Laptop backlight](https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightinjector-kext.218222/)
* [Laptop PM](https://www.tonymacx86.com/threads/guide-native-power-management-for-laptops.175801/)
* [Laptop trackpad](https://www.tonymacx86.com/threads/wip-voodooi2c-i2c-trackpad-limited-support.204227/)
* [Laptop USB SSDT](https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/)
* [Laptop USB SSDT Power](https://www.tonymacx86.com/threads/guide-usb-power-property-injection-for-sierra-and-later.222266/)
* [Laptop dual GPU issues](https://www.tonymacx86.com/threads/guide-disabling-discrete-graphics-in-dual-gpu-laptops.163772/)
* [Laptop DSDT/SSDT patching](https://www.tonymacx86.com/threads/guide-patching-laptop-dsdt-ssdts.152573/)
* [Laptop DSDT patching for battery](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/)
* [Laptop Clover Hotpatch: [only after successful DSDT patching]](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/)
* [IT - Patch (Key Brightness)](https://hackintoshitalia.altervista.org/patch-dsdt-tasti-luminosita)
* [IT - InsanelyMac Brightness key](https://www.insanelymac.com/forum/topic/341703-guida-laptop-come-configurare-il-controllo-della-luminosità-pnlf/?tab=comments#comment-2700467)
* [Specific for X299 boards](https://www.insanelymac.com/forum/topic/334343-imac-pro-x299-live-the-future-new-with-macos-1014-mojave-successful-buildsuccessful-guide/)

## Framebuffer patches (needs to be checked again)

* [WhateverGreen FAQ Intel](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md)
* [IT - macOS86.it](https://www.macos86.it/topic/849-weg-come-applicare-le-relative-patch/)
* [Olarila - Hackintool](https://olarila.com/forum/viewtopic.php?t=9275)
* [OSXLatitude - Understanding Haswell Framebuffer patching](https://osxlatitude.com/forums/topic/10267-understanding-and-patching-framebuffer-haswell/)
* [TonyMacX86 - WhateverGreen Intel Framebuffer patching](https://www.tonymacx86.com/threads/guide-intel-framebuffer-patching-using-whatevergreen.256490)
* [TonyMacX86 - Fix HDMI Black screen](https://www.tonymacx86.com/threads/guide-general-framebuffer-patching-guide-hdmi-black-screen-problem.269149/)
* [InsanelyMac - WhateverGreen patching guide](https://www.insanelymac.com/forum/topic/334899-intel-framebuffer-patching-using-whatevergreen)


## USB
Map your USB ports so that you dont need the USB kext patch (and may probably fix sleep/wake for some)


* [Olarila - Native USB Fix for Desktops - No Injector/Kext Required - SkyLake+](https://olarila.com/forum/viewtopic.php?f=28&t=10171)
* [USBMap Guide](https://usb-map.gitbook.io/project)
* [IT - macOS86.it](https://www.macos86.it/topic/9-mappatura-porte-usb)

## Tools 

* [ProperTree](https://github.com/corpnewt/ProperTree)
* [TINU](https://github.com/ITzTravelInTime/TINU)
* [macserial](https://github.com/acidanthera/MacInfoPkg/blob/master/macserial/FORMAT.md)
* [IORegistryExplorer v2.1](https://github.com/vulgo/IORegistryExplorer)
* [DPCIManager](https://github.com/MuntashirAkon/DPCIManager/releases)
* [ssdtPRGen.sh](https://github.com/Piker-Alpha/ssdtPRGen.sh/releases/tag/v17.0)
* [Hackintool from Headsoft](http://headsoft.com.au/download/mac/Hackintool.zip)
* [Hackintool from GitHub](https://github.com/headkaze/Hackintool)
* [SSDTTime](https://github.com/corpnewt/SSDTTime)
* [Some useful scripts](https://github.com/XLNCs/UsefullScripts)
* [USBMap](https://github.com/corpnewt/USBMap)

## Tips 

* [Differences between 0x67 and 0x3E7](https://github.com/khronokernel/Differences-between-0x67-and-0x3E7/blob/master/README.md)
* [KALSR fix](https://github.com/khronokernel/Opencore-Vanilla-Desktop-Guide/blob/master/extras/kalsr-fix.md)


## Automatically compiled Kexts

* [OLD but GOLD](https://onedrive.live.com/?authkey=%21APjCyRpzoAKp4xs&id=FE4038DA929BFB23%21455036&cid=FE4038DA929BFB23)

## Virtualization

* [macOS Simple KVM](https://github.com/foxlet/macOS-Simple-KVM)
* [Hackintosh Virtualization FAQ](https://github.com/khronokernel/Hackintosh-Virtulization-FAQ/blob/master/README.md)
* [macOS VMWare Workstation](https://www.aioboot.com/en/macos-vmware-workstation)

### VMware AMD

* [VMWare AMD-OSX Guide](https://vmware.amd-osx.com)
* [AMD VM](https://amd-vm.hackintosh-guides.ml)
* [MojaveAMD2.vmdk](https://amdosx.kellynet.nl/MojaveAMD2.vmdk)


## Multiboot Guides

* [macOS86.it - Multiboot](https://www.macos86.it/topic/1897-guide-netgear/)
* [Hackintosh Multiboot](https://hackintosh-multiboot.gitbook.io/hackintosh-multiboot/)
