# 🌿 ZenSpace | Ambient Focus Mixer

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)
![Technology](https://img.shields.io/badge/React-Vite-blue)

**ZenSpace** adalah aplikasi produktivitas berbasis web yang menggabungkan *ambient sound mixer* dengan *Pomodoro Timer*. Aplikasi ini dirancang untuk membantu pengguna mencapai kondisi "Deep Work" atau relaksasi dengan menciptakan lingkungan suara yang dipersonalisasi.

<img width="955" height="729" alt="Screenshot 2025-11-29 095914" src="https://github.com/user-attachments/assets/af0037b5-f2c1-42d5-ada6-d59f62c5c041" />


🔗 **Live Demo:** [Klik di sini untuk mencoba](https://azfaribn.github.io/ZenSpace/) *(Ganti link ini setelah deploy)*

---

## ✨ Fitur Utama

* 🎧 **Custom Audio Mixer:** 5 channel suara terpisah (Hujan, Hutan Malam, Kafe, Mengetik ASMR, Lo-Fi Beat) dengan kontrol volume independen.
* 🍅 **Pomodoro Timer:** Timer fokus terintegrasi dengan mode "Focus" (25 menit) dan "Break" (5 menit).
* 🎨 **Glassmorphism UI:** Antarmuka modern yang tenang dengan efek kaca (*blur*) dan tema gelap (*Dark Mode*) yang nyaman di mata.
* 📱 **Responsif:** Berjalan mulus di Desktop dan Mobile.
* ⚡ **Real-time State:** Pengaturan volume dan timer yang responsif tanpa lag.

---

## 🛠️ Teknologi

Project ini dibangun menggunakan ekosistem **React** modern:

* **React** (CDN, Hooks-based components)
* **Tailwind CSS via CDN** (Styling & Responsive Design)
* **Single-file HTML** (tanpa bundle)


---

## 🚀 Cara Menjalankan (Lokal)

Karena menggunakan React & Vite, Anda memerlukan Node.js terinstall di komputer.

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/azfaribn/zenspace.git](https://github.com/azfaribn/zenspace.git)
    cd zenspace
    ```

2.  **Install Dependencies:**
    ```bash
    npm install
    ```

3.  **Jalankan Server Lokal:**
    ```bash
    npm run dev
    ```
    * Buka browser di link yang muncul (biasanya `http://localhost:5173`).

---

## ☁️ Cara Deploy ke Vercel (Rekomendasi)

Cara termudah untuk men-deploy aplikasi React/Vite adalah menggunakan Vercel:

1.  Push kode Anda ke repository GitHub.
2.  Buka [Vercel](https://vercel.com).
3.  **Add New Project** -> Import repository `zenspace` tadi.
4.  Vercel akan otomatis mendeteksi **Vite**.
5.  Klik **Deploy**.

*(Alternatif: Bisa juga menggunakan GitHub Pages melalui menu Settings -> Pages -> Source: GitHub Actions).*

---

## 📝 Lisensi

Project ini dilisensikan di bawah **MIT License**.
Dibuat dengan ❤️ oleh **[Azfaribn](https://github.com/azfaribn)**.
