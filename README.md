# 🚀 Connect Presensi

### *Smart Attendance System with Multi-Factor Authentication & AI Assistant*

<div align="center">

<img src="https://img.shields.io/badge/Status-Development-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Web-success?style=for-the-badge">
<img src="https://img.shields.io/badge/AI-Gemini_API-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Security-MFA-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Firebase-Cloud-yellow?style=for-the-badge">
<img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge">

<br><br>

<h3>🔐 Smart • Secure • Intelligent Attendance System</h3>

<p>
Connect Presensi adalah sistem presensi pintar berbasis web yang mengintegrasikan<br>
Face Recognition, Dynamic QR Code, Multi-Factor Authentication (MFA),<br>
dan AI Assistant berbasis Gemini API.
</p>

</div>

---

# 🌟 Tentang Project

**Connect Presensi** dikembangkan untuk meningkatkan keamanan dan efisiensi sistem presensi sekolah melalui integrasi teknologi modern seperti:

* 🔐 Multi-Factor Authentication (MFA)
* 👤 Face Recognition
* 📱 Dynamic QR Code
* 🤖 AI Assistant
* ☁️ Firebase Cloud System
* ⚡ Real-time Synchronization

Sistem ini dirancang agar dapat berjalan langsung melalui browser tanpa instalasi tambahan.

---

# ✨ Fitur Utama

<table>
<tr>
<td width="50%">

## 🔐 Multi-Factor Authentication

Menggabungkan:

* Face Recognition
* Dynamic QR Code
* Session Validation
* Real-time Verification

Untuk mencegah:

* Titip absen
* Replay attack
* QR forwarding
* Fake authentication

</td>

<td width="50%">

## 🤖 AI Assistant

Asisten AI mampu:

* Menjawab pertanyaan presensi
* Analisis pola kehadiran
* Statistik kelas
* Insight akademik
* Monitoring siswa
* Rekomendasi intervensi

</td>
</tr>
</table>

---

# 🖼️ Preview System

## 👨‍🏫 Dashboard Guru

```text
┌─────────────────────────────────────┐
│ Dashboard Presensi Real-Time        │
├─────────────────────────────────────┤
│ Total Hadir : 31                    │
│ Terlambat  : 4                      │
│ Tidak Hadir: 2                      │
├─────────────────────────────────────┤
│ AI Insight:                          │
│ Kehadiran kelas meningkat 12%       │
└─────────────────────────────────────┘
```

---

## 👨‍🎓 Dashboard Siswa

```text
┌────────────────────────────┐
│ Face Recognition Active    │
├────────────────────────────┤
│ QR Code Status : Valid     │
│ Verification : Success     │
│ Attendance : Recorded      │
└────────────────────────────┘
```

---

# 🧠 Teknologi yang Digunakan

<div align="center">

| Teknologi               | Fungsi                |
| ----------------------- | --------------------- |
| HTML5                   | Struktur Website      |
| CSS3                    | Styling Interface     |
| JavaScript              | Logic System          |
| Firebase Authentication | Authentication        |
| Cloud Firestore         | Database              |
| Firebase Hosting        | Hosting               |
| face-api.js             | Face Recognition      |
| TensorFlow.js           | AI Processing         |
| Gemini API              | AI Assistant          |
| Apache JMeter           | Load Testing          |
| WebGL                   | Hardware Acceleration |

</div>

---

# 🛡️ Security Architecture

```text
             ┌─────────────────┐
             │     User        │
             └────────┬────────┘
                      │
          ┌───────────▼───────────┐
          │ Face Recognition MFA  │
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │ Dynamic QR Validation │
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │ Firebase Authentication│
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │ Cloud Firestore DB    │
          └───────────┬───────────┘
                      │
          ┌───────────▼───────────┐
          │ Gemini AI Assistant   │
          └───────────────────────┘
```

---

# 🔒 Security Features

## ✅ Dynamic QR Security

* Token rotation setiap 30 detik
* Timestamp validation
* Session binding
* Replay attack prevention
* Token expiration

---

## ✅ Face Recognition Security

* Real-time verification
* Descriptor matching
* Cosine similarity
* Threshold authentication
* Negative sample filtering

---

## ✅ Security Testing

Sistem diuji terhadap:

| Attack Type         | Result            |
| ------------------- | ----------------- |
| Replay Attack       | Blocked           |
| Token Guessing      | Blocked           |
| Cross-device Replay | Blocked           |
| Session Hijacking   | Blocked           |
| Face Spoofing       | Partial Detection |

---

# 📊 Benchmark Result

## 🎯 Face Recognition Performance

| Kondisi Cahaya           | F1-Score |
| ------------------------ | -------- |
| Optimal (300–500 lux)    | 96.9%    |
| Reduced Light            | 92.5%    |
| Very Low Light (<30 lux) | 81.0%    |

---

## ⚡ Scalability Testing

| Concurrent Users | Error Rate |
| ---------------- | ---------- |
| 10 Users         | 0.00%      |
| 20 Users         | 0.18%      |
| 50 Users         | 1.82%      |
| 100 Users        | 8.54%      |

---

## 🤖 NLP Evaluation

| Metric             | Score |
| ------------------ | ----- |
| Accuracy           | 87%   |
| BLEU-4             | 0.64  |
| ROUGE-L            | 0.75  |
| BERTScore F1       | 0.85  |
| Hallucination Rate | 8%    |

---

# 🤖 AI Assistant Features

### AI mampu melakukan:

✅ Rekap kehadiran siswa

✅ Statistik kelas otomatis

✅ Analisis keterlambatan

✅ Monitoring absensi

✅ Analisis pola kehadiran

✅ Insight akademik berbasis AI

✅ Natural language attendance query

---

# 📂 Struktur Project

```bash
ConnectPresensi/
│
├── public/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── models/
│
├── firebase/
│   ├── firestore.rules
│   └── firebase-config.js
│
├── ai/
│   ├── gemini-api.js
│   ├── rag-system.js
│   └── prompt-engineering.js
│
├── attendance/
│   ├── face-recognition.js
│   ├── qr-system.js
│   └── attendance-handler.js
│
├── dashboard/
│   ├── teacher-dashboard.js
│   └── student-dashboard.js
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/connect-presensi.git
```

---

## 2️⃣ Masuk ke Folder

```bash
cd connect-presensi
```

---

## 3️⃣ Install Dependency

```bash
npm install
```

---

## 4️⃣ Jalankan Project

```bash
npm start
```

---

# ☁️ Firebase Configuration

Tambahkan konfigurasi Firebase:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

---

# 🧪 Testing Features

## 🔬 System Testing

* Black-box testing
* Security testing
* Latency testing
* Scalability testing
* NLP evaluation
* Hallucination analysis

---

# 🚀 Future Development

## Planned Features

* 🧠 Passive Liveness Detection
* 🎭 Anti-Spoofing AI
* ⚡ Edge AI Optimization
* 🌐 Cross-School Deployment
* 🔍 Advanced RAG System
* 📊 Predictive Attendance Analytics
* 📱 Mobile Version

---

# 📈 Research Contribution

Project ini mengeksplorasi integrasi:

* Multi-Factor Authentication
* Browser-based Face Recognition
* Dynamic QR Authentication
* Conversational AI
* Cloud-based Attendance System
* Educational AI Analytics

ke dalam satu sistem pendidikan modern.

---

# 🧑‍💻 Author

<div align="center">

# Ricardo Karu

Department of Information Technology and Computer Education (PTIK)
Universitas Negeri Manado

</div>

---

# ⭐ Support Project

Jika project ini menarik:

🌟 Star Repository
🍴 Fork Project
🛠️ Contribute

---

<div align="center">

# 🚀 Connect Presensi

### Smart • Secure • Intelligent Attendance System

</div>
