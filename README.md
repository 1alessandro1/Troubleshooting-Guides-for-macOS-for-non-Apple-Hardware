# Troubleshooting-Guides-for-macOS-for-non-Apple-Hardware

This repository is a collection of sporadic guides across the network. Please note that many of this guides include other guides embedded as well. Please note that I do NOT own this guides, but I find them useful for educational purposes only.
This list may be incomplete or defective, we are going to maintain this list as much as we can.

Main Guide from Corpnewt (Intel Desktop)

-https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide

AMD (Desktop Only)

-https://vanilla.amd-osx.com
-https://kb.hackintoshisfun.ml/clover/

Harware Selection:

-https://khronokernel-5.gitbook.io/anti-hackintosh-buyers-guide
-https://khronokernel-3.gitbook.io/catalina-gpu-buyers-guide
-https://khronokernel-4.gitbook.io/disable-unsupported-gpus 

(can be useful if you cannot remove your actual GPU, but a physical disconnection is much better)


Wireless Hardware (PCIe, mini PCIe, M.2, Express Card, USB)

-https://khronokernel-7.gitbook.io/wireless-buyers-guide/
-https://github.com/chris1111/Wireless-USB-Adapter-Clover

(Old mojave GPU buyers guide - Deprecated)

-https://www.reddit.com/r/hackintosh/comments/b91vf5/mojave_gpu_buyers_guide
-https://github.com/khronokernel/Mojave-GPU-Buyers-Guide


What's new in catalina

-https://github.com/khronokernel/What-s-new-in-macOS-Catalina/blob/master/README.md


Downloading macOS Installer and security checksums

-https://www.reddit.com/r/hackintosh/comments/efjy5g/how_to_download_macos_from_apples_official/
-https://github.com/munki/macadmin-scripts (check the docs folder in the documentation)
-https://github.com/notpeter/apple-installer-checksums/blob/master/readme.md#mac-osx-installers-sha1-checksums


Boot Flags

-https://www.cnet.com/news/boot-argument-options-in-os-x/
-https://www.insanelymac.com/forum/topic/99891--/


Making the bootlable USB from scratch:

-https://internet-install.gitbook.io/macos-internet-install/
-https://www.insanelymac.com/forum/topic/329828-making-a-bootable-high-sierra-usb-installer-entirely-from-scratch-in-windows-or-linux-mint-without-access-to-mac-or-app-store-installerapp/


OpenCore (official gihub repo: https://github.com/acidanthera/OpenCorePkg)

-https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide (Black Version - identical)
-https://khronokernel.github.io/Opencore-Vanilla-Desktop-Guide/

Guida MacOS86 (In Italian)

-https://macos86.gitbook.io/guida-opencore/

Manual (configuration.pdf)

-https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf
-https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Differences/Differences.pdf

Changelog between versions
https://github.com/acidanthera/OpenCorePkg/blob/master/Changelog.md

DSDT/SSDT (a bit outdated, 2014)
https://www.insanelymac.com/forum/topic/298027-guide-aio-guides-for-hackintosh/?tab=comments#comment-2027250


Specific X299

https://www.insanelymac.com/forum/topic/334343-imac-pro-x299-live-the-future-new-with-macos-1014-mojave-successful-buildsuccessful-guide/



Power Management
https://www.reddit.com/r/hackintosh/comments/bnimcj/power_management_101/

Audio Fixes

https://osxlatitude.com/forums/topic/1946-complete-applehda-patching-guide

https://osxlatitude.com/forums/topic/11316-how-to-fix-static-noisedistortioncrackling-sound-and-combojack-in-laptops

https://www.reddit.com/r/hackintosh/comments/4sil5p/audio_mechanic_old_patchfix_removal_applealc

https://www.reddit.com/r/hackintosh/comments/4e23w6/guide_native_audio_with_clover_applealckex


Intel Laptop
https://fewtarius.gitbook.io/laptopguide

Rehabman/Tonymac (usually outdated, try to avoid if possible)

https://www.tonymacx86.com/threads/guide-booting-the-os-x-installer-on-laptops-with-clover.148093

Laptop Rehabman FAQ: https://www.tonymacx86.com/threads/faq-read-first-laptop-frequent-questions.164990/

Laptop common issues: https://www.tonymacx86.com/threads/readme-common-problems-changes-fixes-on-mojave.255823/

Laptop backlight: https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightinjector-kext.218222/

Laptop PM: https://www.tonymacx86.com/threads/guide-native-power-management-for-laptops.175801/.

Laptop trackpad: https://www.tonymacx86.com/threads/wip-voodooi2c-i2c-trackpad-limited-support.204227/

Laptop USB SSDT: https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/

Laptop USB SSDT Power: https://www.tonymacx86.com/threads/guide-usb-power-property-injection-for-sierra-and-later.222266/

Laptop dual GPU issue: https://www.tonymacx86.com/threads/guide-disabling-discrete-graphics-in-dual-gpu-laptops.163772/

Laptop DSDT/SSDT patching: https://www.tonymacx86.com/threads/guide-patching-laptop-dsdt-ssdts.152573/

Laptop DSDT patching for battery: https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/

Laptop Clover Hotpatch: [only after successful DSDT patching]: https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/

Patch (Key Brightness)

https://hackintoshitalia.altervista.org/patch-dsdt-tasti-luminosita

https://www.insanelymac.com/forum/topic/341703-guida-laptop-come-configurare-il-controllo-della-luminosità-pnlf/?tab=comments#comment-2700467


Framebuffer patches (needs to be checked again)

-https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md
-https://www.macos86.it/topic/849-weg-come-applicare-le-relative-patch/
-https://olarila.com/forum/viewtopic.php?f=28&t=10171
-https://olarila.com/forum/viewtopic.php?f=28
-https://olarila.com/forum/viewtopic.php?t=9275
-https://osxlatitude.com/forums/topic/10267-understanding-and-patching-framebuffer-haswell/
-https://www.tonymacx86.com/threads/guide-intel-framebuffer-patching-using-whatevergreen.256490
-https://www.tonymacx86.com/threads/guide-general-framebuffer-patching-guide-hdmi-black-screen-problem.269149/
-https://www.insanelymac.com/forum/topic/334899-intel-framebuffer-patching-using-whatevergreen

Tools 
-https://github.com/corpnewt/ProperTree
-https://github.com/ITzTravelInTime/TINU
-https://github.com/acidanthera/MacInfoPkg/blob/master/macserial/FORMAT.md
-https://github.com/vulgo/IORegistryExplorer
-https://github.com/MuntashirAkon/DPCIManager/releases
-https://github.com/Piker-Alpha/ssdtPRGen.sh/releases/tag/v17.0
-http://headsoft.com.au/download/mac/Hackintool.zip
-https://github.com/headkaze/Hackintool

Map your USB ports so that you dont need the USB kext patch (and may probably fix sleep/wake for some)

Guide [first]: https://usb-map.gitbook.io/project/
Tool [second]: https://github.com/corpnewt/USBMap
(Italian): https://www.macos86.it/topic/9-mappatura-porte-usb/

Tips 
https://github.com/khronokernel/Differences-between-0x67-and-0x3E7/blob/master/README.md
https://github.com/khronokernel/Opencore-Vanilla-Desktop-Guide/blob/master/extras/kalsr-fix.md

Automatically compiled Kexts

https://onedrive.live.com/?authkey=%21APjCyRpzoAKp4xs&id=FE4038DA929BFB23%21455036&cid=FE4038DA929BFB23
https://1drv.ms/f/s!AiP7m5LaOED-m-J8-MLJGnOgAqnjGw


Virtualization

-https://github.com/foxlet/macOS-Simple-KVM
-https://github.com/khronokernel/Hackintosh-Virtulization-FAQ/blob/master/README.md
-https://www.aioboot.com/en/macos-vmware-workstation

VMware AMD

-https://vmware.amd-osx.com/
-https://amd-vm.hackintosh-guides.ml
-https://amdosx.kellynet.nl/MojaveAMD2.vmdk

Multiboot Guides

-https://www.macos86.it/topic/1897-guide-netgear/
-https://hackintosh-multiboot.gitbook.io/hackintosh-multiboot/
