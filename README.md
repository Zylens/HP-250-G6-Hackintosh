\# HP-250-G6-macOS-Opencore

This repository contains the files needed to successfully boot macOS on HP 250 G6 with Opencore.

After installing Mac OS 12 and 13, which work well with the current setup, I decided to use <b>Mac OS 11</b> because it guarantees the best compatibility with bluetooth services (handoff, universal clipboard, sidecar...).

<p align="center"><img src="" alt="HP 250 G6" width="40%" align="Right"><a href=""><img src="https://img.shields.io/badge/BIOS-1.41-blue"></a> \&nbsp;\&nbsp;<a href="https://github.com/acidanthera/OpenCorePkg"><img src="https://img.shields.io/badge/OpenCore-0.9.1-blue"></a> \&nbsp;\&nbsp;<img src="https://img.shields.io/badge/MacOS-11-blue"></p>

The project is stable. Mac OS 11 works with Windows 11 in dual boot. There are probably things that can be improved, so feel free to open issues or even PRs with suggestions or observations.<br> <b>This is not a support forum</b>, I won't be able to give individual support. I suggest to use the <a href="https://dortania.github.io/OpenCore-Install-Guide/">Dortania's Opencore Install Guide</a> to build your EFI folder, then compare with this EFI for the last improvements.

<h2>Configuration</h2>
<div align="center">

| Specifications      | Details                                          |
| :--- | :--- |
| Processor           | Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz (2.70 GHz)         |
| Memory              | 8 GB DDR4 2400 MHz                             |
| Hard Disk           | 512 GB SanDisk SD8SN8U-512G-1006  |
| Integrated Graphics | Intel UHD Graphics 620 |
| Screen              | 13.3 inch @ 1920 x 1080         |
| Sound Card          | Realtek                                  |
| Wireless/BT Card       | Intel Dual Band Wireless-AC 3168/IntelWirelessBluetooth           |
