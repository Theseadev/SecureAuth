# SecureAuth: Solusi Autentikasi Modern (Android & Kotlin Compose)

[![Status Build](https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square)](https://github.com/Theseadev/SecureAuth/actions)
[![Lisensi](https://img.shields.io/github/license/Theseadev/SecureAuth?style=flat-square)](LICENSE)
[![Versi](https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square)](#)
[![Stack Teknologi](https://img.shields.io/badge/Stack-Android%20%7C%20Kotlin%20%7C%20Compose-752EFF?style=flat-square)](README.md)

**SecureAuth** adalah aplikasi seluler Android yang dirancang untuk mendemonstrasikan implementasi autentikasi dan manajemen keamanan pengguna yang aman menggunakan **Kotlin** dan **Jetpack Compose**. Proyek ini berfokus pada pengalaman pengguna yang modern dan penggunaan fitur keamanan bawaan perangkat seperti biometrik.

## 🚀 Fitur Utama

* **Autentikasi Aman:** Login & register menggunakan penyimpanan akun yang aman.
* **Dukungan Biometrik:** Otentikasi sidik jari/wajah via `BiometricUtils.kt`.
* **Arsitektur MVVM:** ViewModel modern untuk state management.
* **Jetpack Compose:** UI deklaratif dan responsif.
* **Pengaturan Keamanan:** Mengelola profil & opsi keamanan pengguna.

## 🖼️ Tampilan Aplikasi
🌞 Light Mode
| Login                                                                                                                                                              | Register                                                                                                                                                              | Home                                                                                                                                                              | Security                                                                                                                                                              | Settings                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/LoginScreen.jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/RegisterScreen.jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/HomeScreen.jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/SecurityScreen.jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/SettingsScreen.jpeg" height="220" width="120" style="object-fit:cover;"/> |


🌙 Dark Mode
| Login                                                                                                                                                                        | Register                                                                                                                                                                        | Home                                                                                                                                                                        | Security                                                                                                                                                                        | Settings                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/LoginScreen(DarkMode).jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/RegisterScreen(DarkMode).jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/HomeScreen(DarkMode).jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/SecurityScreen(DarkMode).jpeg" height="220" width="120" style="object-fit:cover;"/> | <img src="https://raw.githubusercontent.com/Theseadev/SecureAuth/master/ScreenshootAplikasi/SettingsScreen(DarkMode).jpeg" height="220" width="120" style="object-fit:cover;"/> |




## 📂 Struktur Direktori

```
SecureAuth/
├── app/
│   ├── manifests/
│   │   └── AndroidManifest.xml
│   ├── kotlin+java/
│   │   └── id.antasari.p7_modern_ui_230104040057/
│   │       ├── ui/
│   │       │   ├── auth/
│   │       │   ├── components/
│   │       │   ├── navigation/
│   │       │   └── theme/
│   │       ├── AccountStorage.kt
│   │       ├── BiometricUtils.kt
│   │       ├── CreateAccountScreen.kt
│   │       ├── LoginScreen.kt
│   │       ├── MainActivity.kt
│   │       └── SettingsScreen.kt
│   ├── ScreenshootAplikasi/
│   └── test/ androidTest/
├── res/
│   ├── mipmap/
│   └── values/
├── Gradle Scripts/
└── README.md
```

## 🛠️ Instalasi & Setup

### Prasyarat
* Android Studio (versi terbaru)
* JDK
* Koneksi internet

### Langkah-Langkah

```bash
git clone https://github.com/Theseadev/SecureAuth.git
cd SecureAuth
```

1. Buka project di Android Studio  
2. Tunggu Gradle sync selesai  
3. Tekan **Run (▶️)** untuk menjalankan aplikasi  

## 🤝 Kontribusi

1. Fork repositori  
2. Buat branch baru  
3. Commit & push  
4. Ajukan Pull Request  

## 📄 Lisensi

Proyek ini menggunakan lisensi **<MIT / Apache 2.0>**.
