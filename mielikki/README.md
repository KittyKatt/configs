# mielikki

These are the configs for my main desktop.

## zsh

![zsh config]
(https://u.teknik.io/ywmgO.png)

##Current setup is as follows:

```
System:
  Host: mielikki Kernel: 4.15.10-1-ARCH x86_64 bits: 64 compiler: gcc v: 7.3.1 
  Desktop: Gnome 3.26.2 info: gnome-shell dm: gdm Distro: Arch Linux 
Machine:
  Type: Desktop Mobo: ASUSTeK model: ROG CROSSHAIR VI HERO (WI-FI AC) v: Rev 1.xx 
  serial: N/A UEFI [Legacy]: American Megatrends v: 1201 date: 05/09/2017 
Memory:
  RAM Report: permissions: Unable to run dmidecode. Are you root? 
PCI Slots:
  Permissions: Unable to run dmidecode. Are you root? 
CPU:
  Topology: 8 Core model: AMD Ryzen 7 1700 type: MT MCP arch: Zen rev: 1 
  L2 cache: 4096 KB 
  flags: lm nx pae sse sse2 sse3 sse4_1 sse4_2 sse4a ssse3 svm bogomips: 95824 
  Speed: 1495 MHz min/max: 1550/3000 MHz Core speeds: 1: 1856 2: 1836 3: 2562 4: 
2977 
  5: 2564 6: 2569 7: 2456 8: 1899 9: 2981 10: 2914 11: 2735 12: 2572 13: 1297 14: 
1274 
  15: 2562 16: 2567 
Graphics:
  Card-1: NVIDIA GP104 [GeForce GTX 1070] driver: nvidia v: 390.42 bus ID: 29:00.0 
  chip ID: 10de:1b81 
  Display Server: x11 (X.Org 1.19.6) driver: nvidia 
  unloaded: nouveau,fbdev,vesa,modesetting,nv 
  resolution: 1920x1200~60Hz, 1920x1200~60Hz, 1920x1080~144Hz 
  OpenGL: renderer: GeForce GTX 1070/PCIe/SSE2 version: 4.6.0 NVIDIA 390.42 
  direct render: Yes 
Audio:
  Card-1: NVIDIA GP104 High Definition Audio Controller driver: snd_hda_intel 
  v: kernel bus ID: 29:00.1 chip ID: 10de:10f0 
  Card-2: Advanced Micro Devices [AMD] Family 17h (Models 00h-0fh) HD Audio 
Controller 
  driver: snd_hda_intel v: kernel bus ID: 2b:00.3 chip ID: 1022:1457 
  Card-3: Blue Microphones Yeti Stereo Microphone type: USB driver: snd-usb-audio 
  bus ID: 1:3 chip ID: b58e:9e84 
  Sound Server: ALSA v: k4.15.10-1-ARCH 
Network:
  Card-1: Intel I211 Gigabit Network Connection driver: igb v: 5.4.0-k port: e000 
  bus ID: 23:00 chip ID: 8086:1539 
  IF: enp35s0 state: up speed: 1000 Mbps duplex: full mac: <filter> 
  IP v4: <filter> virtual: noprefixroute enp35s0 scope: global broadcast: <filter> 
  IP v6: <filter> virtual: noprefixroute scope: link 
  Card-2: Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter 
  driver: ath10k_pci v: kernel bus ID: 24:00 chip ID: 168c:003e 
  IF: wlp36s0 state: down mac: <filter> 
  WAN IP: <filter> 
Drives:
  HDD Total Size: 1.60 TB used: 105.76 GB (6.4%) 
  ID-1: /dev/nvme0n1 model: Samsung_SSD_960_EVO_250GB size: 232.89 GB serial: 
<filter> 
  ID-2: /dev/sda model: SAMSUNG_SSD_PM80 size: 238.47 GB serial: <filter> rev: 
AD1Q 
  ID-3: /dev/sdb model: MTFDDAK256MAM-1K size: 238.47 GB serial: <filter> rev: 
040H 
  ID-4: /dev/sdc model: ST31000528AS size: 931.51 GB serial: <filter> rev: CC3E 
  Message: No Optical or Floppy data was found. 
RAID:
  Message: No RAID data was found. 
Partition:
  ID-1: / size: 78.62 GB used: 49.73 GB (63.3%) fs: ext4 dev: /dev/sda1 label: N/A 
  uuid: ccd8d06d-5185-429f-99ec-de53979ea2d6 
  ID-2: /home size: 138.29 GB used: 56.02 GB (40.5%) fs: ext4 dev: /dev/sda3 
  label: N/A uuid: 3808e49b-0210-4dad-be72-f3bf8be11766 
  ID-3: swap-1 size: 6.00 GB used: 0 KB (0.0%) fs: swap dev: /dev/sda2 label: N/A 
  uuid: 9b0f8ec6-3398-4441-b24f-f188853948c4 
Unmounted:
  ID-1: /dev/nvme0n1p1 size: 499.0 MB fs: root required label: Recovery 
  uuid: 5230247F30246BE3 
  ID-2: /dev/nvme0n1p2 size: 100.0 MB fs: root required label: N/A uuid: 1825-5E58 
  ID-3: /dev/nvme0n1p3 size: 16.0 MB fs: root required label: N/A uuid: N/A 
  ID-4: /dev/nvme0n1p4 size: 175.18 GB fs: root required label: N/A 
  uuid: C258319558318965 
  ID-5: /dev/sdb1 size: 500.0 MB fs: root required label: System Reserved 
  uuid: EA5A71895A7152F5 
  ID-6: /dev/sdb2 size: 237.13 GB fs: root required label: N/A uuid: 
A8A4CDC7A4CD9868 
  ID-7: /dev/sdb3 size: 869.0 MB fs: root required label: N/A uuid: 
3EC274C7C2748545 
  ID-8: /dev/sdc1 size: 1.95 GB fs: root required label: N/A 
  uuid: 014a132b-8b1d-4f54-9014-61b08eef1783 
  ID-9: /dev/sdc2 size: 336.91 GB fs: root required label: mydata 
  uuid: 275208d9-a832-46f8-86b5-53f72960e272 
  ID-10: /dev/sdc3 size: 592.65 GB fs: root required label: Shared 
  uuid: E4BA3187BA315770 
USB:
  Hub: 1:1 usb: 2.00 type: Full speed (or root) hub chip ID: 1d6b:0002 
  Device-1: ASUSTek Qualcomm Bluetooth 4.1 bus ID: 1:2 usb: 1.10 type: Bluetooth 
  chip ID: 0b05:1825 
  Device-2: Blue Microphones Yeti Stereo Microphone bus ID: 1:3 usb: 1.10 type: 
Audio 
  chip ID: b58e:9e84 
  Hub: 2:1 usb: 3.10 type: Full speed (or root) hub chip ID: 1d6b:0003 
  Hub: 2:2 usb: 3.00 type: VIA Labs VL812 Hub chip ID: 2109:0812 
  Hub: 2:3 usb: 3.00 type: VIA Labs VL812 Hub chip ID: 2109:0812 
  Hub: 3:1 usb: 2.00 type: Full speed (or root) hub chip ID: 1d6b:0002 
  Hub: 4:1 usb: 3.10 type: Full speed (or root) hub chip ID: 1d6b:0003 
  Hub: 5:1 usb: 2.00 type: Full speed (or root) hub chip ID: 1d6b:0002 
  Device-3: Razer USA Ltd BlackWidow Chroma bus ID: 5:2 usb: 2.00 type: Keyboard 
  chip ID: 1532:0203 
  Device-4: Corsair bus ID: 5:3 usb: 2.00 type: Mouse chip ID: 1b1c:1b2e 
  Hub: 6:1 usb: 3.00 type: Full speed (or root) hub chip ID: 1d6b:0003 
Sensors:
  System Temperatures: cpu: 32.2 C mobo: N/A 
  Fan Speeds (in RPM): cpu: 0 
Repos:
  Active Pacman repo servers in: /etc/pacman.d/mirrorlist 
  1: http://cosmos.cites.illinois.edu/pub/archlinux/$repo/os/$arch
  2: http://muug.ca/mirror/archlinux/$repo/os/$arch
  3: http://mirror1.hackingand.coffee/arch/$repo/os/$arch
  4: http://mirrors.rit.edu/archlinux/$repo/os/$arch
  5: http://mirror.yellowfiber.net/archlinux/$repo/os/$arch
  6: http://mirror.math.princeton.edu/pub/archlinux/$repo/os/$arch
Processes:
  CPU  % used - Command - pid - Memory: MB / % used - top: 5 
  1: cpu: 8.5% command: chromium pid: 1548 mem: 314.8MB (1.9%) 
  2: cpu: 4.8% command: chromium pid: 28808 mem: 232.7MB (1.4%) 
  3: cpu: 2.8% command: gnome-shell pid: 1029 mem: 289.2MB (1.8%) 
  4: cpu: 2.1% command: gnome-keyring-daemon pid: 980 mem: 11.3MB (0.0%) 
  5: cpu: 2.0% command: discordcanary pid: 2165 mem: 186.3MB (1.1%) 
  Memory MB/% used - Command - pid - CPU: % used - top: 5 
  1: mem: 328.3 MB (2.0%) command: chromium pid: 20080 cpu: 2.0% 
  2: mem: 314.8 MB (8.5%) command: chromium pid: 1548 cpu: 1.9% 
  3: mem: 314.5 MB (1.5%) command: chromium pid: 6061 cpu: 1.9% 
  4: mem: 296.1 MB (1.6%) command: chromium pid: 2239 cpu: 1.8% 
  5: mem: 289.2 MB (2.8%) command: gnome-shell pid: 1029 cpu: 1.8% 
Info:
  Processes: 391 Uptime: 18 min Memory: 15.65 GB used: 5.53 GB (35.3%) Init: 
systemd 
  v: 238 Compilers: gcc: 7.3.1 clang: 5.0.1 Shell: zsh 5.4.2 running in: urxvt 
  pinxi: 2.9.01-1-p 
```
