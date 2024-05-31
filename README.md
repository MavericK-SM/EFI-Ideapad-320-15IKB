# Lenovo Ideapad 320 15IKB
Lenovo Ideapad 320 15IKB (81BG Type) EFI

:information_source: **La versión actual es totalmente compatible con macOS en función del hardware de mi laptop.**
¡OpenCore, drivers y kexts están actualizados a la versión 1.0.0!

:information_source: La EFI ha sido probada en macOS Sonoma 14.5

<br/>

:warning: **IMPORTANTE** :warning:

Esta no es una guía, por favor consulte [Dortania](https://dortania.github.io/getting-started) antes de hacer nada. No soy responsable de ningún daño. Esta configuración de OpenCore está optimizada para mi hardware específico, así que utilícela solo como referencia o si tiene el mismo hardware o similar.

<br/>

<img src="assets/sonoma.png">
    
## :computer: Hardware:

| **Componentes** | **Especificaciones**               |
| ------------ | ------------------------------------- |
| **CPU**      | 1.6GHz Intel Core i5-8250U            |
| **GPU**      | Intel UHD 620                         |
| **RAM**      | 12GB (4GB non-removable) 2133MHz DDR4 |
| **SSD**      | 256GB SATA SSD (Kingston SKC600)      |
| **Display**  | 15,6" 1366x768 LCD non-touch display  |
| **Wi-Fi/BT** | Intel Dual Band Wireless-AC 3165 + BT |
| **Ethernet** | Realtek RTL8111                       |
| **Audio**    | Realtek ALC230 (layout-id=20)         |
| **Input**    | PS2 Keyboard & ELAN TrackPad          |

## :white_check_mark: Working:

- [x] CPU power management.
- [x] Graphics acceleration.
- [x] Battery read-out.
- [x] Keyboard & trackpad with all macOS gestures.
- [x] Wi-Fi.
- [x] Bluetooth.
- [x] USB ports.
- [x] HDMI video & audio output.
- [x] Ethernet.
- [x] Audio (Internal speakers, 3.5mm headphone jack).
- [x] Internal microphone.
- [x] VGA WebCam.
- [ ] AirDrop & Handoff.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.

## :x: Not working:

Only AirDrop and Handoff are not working since the Intel card are not fully compatible with macOS. To make these things works you need to replace with a native card one, like the Fenvi cards.

For Wifi Connection you can install Heliport.Due to its faster connection and speed I've replaced it with Airport.

For Ethernet you can use USB Ethernets too!

## BIOS setup:

- Security / Intel Platform Trust Technology - Disabled
- Security / Intel SGX - Disabled
- Security / Secure Boot - Disabled
- Boot / Boot Mode - UEFI


## Credits:

[**Apple**](http://apple.com/)

[**Dortania**](https://dortania.github.io/getting-started/)

[**Milad Tahanian**](https://github.com/mtahanian)
