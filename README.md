<h1 align="center">
  🏮 TawBot - By ItzAurel 🏮
</h1>

<p align="center">
  <img src="https://media.tenor.com/hmYVvHn6-McAAAAi/genshin-impact-hu-tao.gif" width="200" alt="Hu Tao">
</p>

<p align="center">
  <strong>Bot Discrod Khusus Private Server, Dirancang Untuk Penggunaan Pribadi yh... Bukan Public :v</strong>
</p>

--- 

## 🚀 Perkenalan
Halo bg! **TawBot** adalah bot Discord pribadi yang dibangun menggunakan **discrod.js!**. Dibuat oleh anak kemaren sore yg baru aja pegang **vsCode** 4 bulan, ya wajarin kalo lu liatnya aga-aga, wong aku aja masih pemula kok 

## 📊 Informasi Bot
* **Versi saat ini**: `v25.12.2` (Latest)
* **Library**: `Discord.js v14`
* **Database**: `MongoDB`

## 🛠️ Changelog v25.12.2
- ✨ **New**: `/ban, /warn dll` buat moderasi
- 💤 **System**: penambahan custom prefix untuk bersihin log orang ke banned di `MongoDB`
- 🔧 **Internal**: Pembersihan kodingan agar lebih ringan.

---

## 📖 Tutorial Cara Pasang & Menjalankan

### 1. Persyaratan ⚙️
Pastikan sudah terinstal:
* [Node.js v16.x atau lebih baru](https://nodejs.org/)
* [Git](https://git-scm.com/)
* [MongoDB](https://www.mongodb.com/) (Untuk database)

### 2. Kloning Repositori 📂
```bash
git clone [https://github.com/ItzAurel/Bot-Discord.git](https://github.com/ItsLiyd/Bot-Discord.git)
cd Bot-Discord
```

### 3. Instal Dependensi 📦
```Bash
npm install
npm install cron
```

### 4. Jalankan Bot 🚀
```Bash
node deploy-commands.js
node index.js
```

### 5. Information 📃
Pindahin codingan `reminder-scheduler.js` di folder `depencies` ke folder `node-cron-main` agar command bekerja dengan baik

Jika kamu coba kembangin botnya sendiri, lalu menemui command yg dobel/ganda, kamu bisa...

```Bash
node reset-command.js
```
ini buat hapus semua slash command yg terdaftar, lalu daftarin ulang menggunakan tutorial di nomor **4** yh

---
<h3 align="center">📜 Lisensi</h3>
<p align="center">Proyek ini menggunakan lisensi GPL-3.0. Kamu bebas edit dan kembangkan lagi kodingannya! (kecuali buat bitma)</p>
<p align="center"> Dibuat dengan ❤️ oleh <b>Pesatir_Handal</b> </p>
