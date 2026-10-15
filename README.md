# MikroTik Toolbox All-in-One by BartovBee

Website bertema putih-biru dengan generator konfigurasi yang berjalan lokal di browser. Tidak ada backend atau build step.

## Website
- [Toolbox utama](https://bartovbee.github.io/Toolbox-All-in-One-/)
- [PCC Load Balancing Generator (halaman khusus)](https://bartovbee.github.io/Toolbox-All-in-One-/pcc-generator.html)

## Tools yang tersedia
- Auto Internet / DHCP Client
- Burst Limit Calculator
- PCC Load Balancing
- NAT Masquerade
- DHCP Server Template
- DNS & Cache
- Backup & Export
- Hotspot Basic
- Firewall Filter Dasar
- PCC Generator khusus: mangle PCC 2-WAN, routing mark/table RouterOS v6/v7, NAT dan route dasar; hasil harus ditinjau dan disesuaikan dengan gateway ISP.

## Menjalankan offline
Unduh repository sebagai ZIP lalu buka `index.html` atau `pcc-generator.html` langsung di browser. CSS dan JavaScript tertanam di masing-masing file; tidak perlu CDN atau paket eksternal. Poppins akan memakai fallback font sistem bila font lokal belum tersedia.

## GitHub Pages
Repository ini memakai GitHub Pages dari branch `main` dan folder root. URL project: https://bartovbee.github.io/Toolbox-All-in-One-/

## Catatan penting
Semua output adalah template awal, bukan jaminan konfigurasi siap produksi. Periksa nama interface, subnet, gateway, routing table, urutan firewall, FastTrack, DNS dan versi RouterOS. Buat backup dan uji dahulu di perangkat/lab aman. Generator PCC tidak pernah diuji langsung pada router fisik.
