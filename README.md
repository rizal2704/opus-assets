# 📂 Opus Assets Library

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Aset Type](https://img.shields.io/badge/Aset-Audio_SFX-blue)

Repositori ini berfungsi sebagai pusat penyimpanan aset otomatis (Cloud Assets) untuk aplikasi **OpusBake**. Aset yang tersimpan di sini digunakan untuk fitur *Auto-SFX*, *Auto-Repair*, dan *Transition Audio* dalam pengolahan video otomatis.

## 🎵 Daftar Aset SFX
Aset berikut akan diunduh secara otomatis oleh aplikasi jika tidak ditemukan di folder lokal `library_sfx`:

* **Impacts:** `boom.mp3`, `fail.mp3`
* **Interactions:** `pop.mp3`, `pop_1.mp3`, `pop_2.mp3`, `notification.mp3`
* **Success:** `money.mp3`
* **Transitions:** `transition_1.mp3`, `transition_2.mp3`, `transition_3.mp3`, `transition_4.mp3`

## 🛠️ Integrasi Aplikasi
Aplikasi menggunakan **Direct Raw URL** dari repositori ini untuk memastikan pemulihan aset berjalan lancar tanpa memerlukan intervensi manual dari pengguna.

```python
BASE_URL = "[https://raw.githubusercontent.com/rizal2704/opus-assets/main/](https://raw.githubusercontent.com/rizal2704/opus-assets/main/)"
