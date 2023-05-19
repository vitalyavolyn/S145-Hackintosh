# Lenovo Ideapad S145 OpenCore

## My specs

| Specs | Details |
|------------|-------------------------------|
| Model | Lenovo Ideapad S145 |
| OS | macOS Ventura 13.3 |
| CPU | Intel(R) Core(TM) i5-1035G1 |
| RAM | 12 GB |
| iGPU | Intel Iris Plus Graphics G1 |

### Works

- [x] Intel Integrated Graphics
- [x] USB
- [x] Webcam
- [x] Brightness controls
- [x] Battery percentage
- [x] TouchPad w/ Advanced Gestures
- [x] WiFi w/ USB Adapter
  - [x] Internet via USB with Android
- [x] Speakers
- [x] P2 Audio Jack w/ Microphone
- [x] Integrated Microphone
- [x] Apple Services (iCloud, Apple Music, Apple TV, others..)

### Doesn't work

- [ ] Bluetooth
  - [ ] Airdrop + Handoff (haven't tested)
- [ ] HDMI
- [ ] SD Card Reader (haven't tested)
- [ ] Sleep

## Guide

### BIOS Setup

- Set "Supervisor Password"
- Set "Password on Boot"
- Disable "Secure Boot"

### Setup

- Copy this EFI folder
- Generate your own SMBIOS

### Credits

- joaodematejr (https://github.com/joaodematejr/S145-Hackintosh)
