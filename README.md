# Uptech Automation Testing

![Selenium](https://img.shields.io/badge/Selenium-4.x-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-20+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Allure Report](https://img.shields.io/badge/Allure-Report-orange?style=for-the-badge)

Framework **Automation Testing End-to-End** menggunakan **Selenium WebDriver** dan **JavaScript** dengan menerapkan konsep **Page Object Model (POM)**.

---

# Tentang Project

Repository ini berisi kumpulan automation testing untuk aplikasi **ERP** menggunakan Selenium WebDriver.

Framework dikembangkan untuk membantu proses regression testing sehingga pengujian dapat dilakukan secara otomatis, konsisten, dan lebih cepat dibandingkan pengujian manual.

---


# Struktur Project

```text
UPTECH-AUTOMATION/
│
├── allure-report/
│   └── Hasil generate Allure Report
│
├── node_modules/
│
├── src/
│   │
│   ├── pages/
│   │   ├── Helper.js
│   │   ├── Login.js
│   │   └── Logout.js
│   │
│   └── test/
│       ├── Inventory.js
│       ├── Purchase.js
│       ├── Sales.js
│       └── User.js
│
├── .gitignore
└── package.json
```

---

# Persiapan

Pastikan perangkat Anda telah menginstal software berikut.

- Node.js versi 18 atau lebih baru
- npm
- Google Chrome
- Git

Untuk memastikan instalasi berhasil, jalankan perintah berikut.

```bash
node -v
npm -v
git --version
```

---

# Instalasi

Clone repository

```bash
git clone https://github.com/hast99/uptech-automation.git
```

Masuk ke folder project

```bash
cd uptech-automation
```

Install seluruh dependency

```bash
npm install
```

---

# Menjalankan Automation

Menjalankan seluruh automation test

```bash
npm test
```

atau

```bash
node src/test/User.js
```

---

# Allure Report

Generate report

```bash
allure generate allure-results --clean
```

Membuka report

```bash
allure open
```

---

# Author

**Hafidh Syahputra**

QA Engineer

GitHub:
https://github.com/hast99