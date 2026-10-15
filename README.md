# MikroTik Toolbox All-in-One by BartovBee

Website satu halaman bertema putih-biru, dengan Poppins/fallback font system, dan generator yang dijalankan lokal di browser. Tidak ada build step atau backend.

## Fitur awal
- Auto Internet MikroTik: template dasar WAN DHCP, bridge LAN, IP gateway, DHCP pool/server, DNS, NAT, NTP opsional.
- Kalkulator Burst Limit: membentuk parameter queue dari max-limit, threshold, limit, dan time.
- PCC Generator: template mangle PCC; lengkapi gateway, routing marks, dan route sebelum diterapkan.
- Login Page Maker: membuat template hotspot HTML yang bisa diunduh.
- Copy output dan download .rsc / .html.

## Menjalankan offline
Unduh repository sebagai ZIP lalu buka `index.html` langsung di browser. Tampilan dan generator menggunakan CSS/JavaScript yang tertanam di file; tidak perlu CDN atau paket eksternal. Poppins akan menggunakan fallback font sistem bila font lokal belum disertakan.

## Publish dengan GitHub Pages
1. Buka **Settings → Pages** di repository.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu deployment selesai di tab **Actions** atau halaman Pages. Karena repo ini bernama `Toolbox-All-in-One-`, URL proyek biasanya berbentuk `https://bartovbee.github.io/Toolbox-All-in-One-/`.

## Keamanan
Periksa dan sesuaikan semua nama interface, subnet, gateway, dan sintaks sesuai RouterOS v6/v7 sebelum mengimpor konfigurasi. Generator adalah titik awal, bukan pengganti backup, firewall review, atau pengujian di perangkat uji. PCC sengaja memberi kerangka mangle saja karena perlu gateway/route ISP dari jaringan masing-masing.
