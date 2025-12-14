# IntelliView: AI Interview Scoring

IntelliView adalah **AI-Powered Interview Assessment System** yang dikembangkan sebagai proyek Capstone (A25-CS344) untuk mengotomatisasi penilaian wawancara kandidat secara objektif, konsisten, dan efisien.

## 📌 Fitur Utama
- **Speech-to-Text (Whisper)**: Mengonversi audio wawancara menjadi transkrip teks.
- **AI Interview Scoring (Groq LLM API)**: Menganalisis jawaban kandidat berdasarkan rubrik penilaian dan menghasilkan skor serta reasoning.
- **Confidence Score**: Menunjukkan tingkat kepercayaan hasil transkripsi.
- **Dashboard Interaktif (Streamlit)**: Visualisasi skor, transkrip, dan hasil evaluasi secara real-time.

## 🧠 Arsitektur Sistem
1. Audio interview diproses menggunakan Whisper (Speech-to-Text).
2. Hasil transkrip dianalisis oleh Groq LLM API untuk penilaian berbasis rubrik.
3. Output disimpan dalam format JSON.
4. Dashboard Streamlit menampilkan hasil analisis secara visual.

## 📂 Struktur File
```
├── dashboard.py                # Aplikasi Streamlit untuk visualisasi hasil interview
├── final_payload.json          # Output hasil STT dan scoring LLM
├── requirements.txt            # Daftar dependency Python
├── Final_Capstone_Project.ipynb# Notebook eksperimen & pipeline utama
```

## 📊 Dashboard Preview
Dashboard menampilkan:
- Total skor interview
- Skor per pertanyaan
- Confidence score STT
- Transkrip jawaban kandidat
- Reasoning penilaian dari LLM

## 🛠️ Teknologi yang Digunakan
- Python
- Whisper (Speech-to-Text)
- Groq LLM API
- Streamlit
- Pandas & Matplotlib

## 🎯 Tujuan Proyek
Meningkatkan efisiensi proses rekrutmen dengan penilaian wawancara yang lebih cepat, objektif, transparan, dan minim bias.

---
Proyek ini dikembangkan dalam program **Asah led by Dicoding in association with Accenture**.

