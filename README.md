# Irman Efendi — SOC Analyst (Tier 1) Portfolio

## 📄 Ringkasan Profesional

Spesialis IT Infrastructure & Cybersecurity dengan pengalaman kerja lebih dari 1,5 tahun dan latar belakang pendidikan Diploma Teknik Telekomunikasi, sedang bertransisi ke operasional **SOC Analyst (Tier 1)**. Memiliki kemampuan dalam pemantauan ancaman aset IT, analisis log SIEM menggunakan **Splunk Enterprise (SPL)**, inspeksi paket jaringan dengan **Wireshark**, triase alert (True Positive vs False Positive), pemetaan **MITRE ATT&CK**, dan eskalasi insiden sesuai **NIST SP 800-61**. Bersertifikat dalam Standar Kompetensi Kerja Nasional Indonesia (**KEPNAKER No. 391/2020**) untuk operasional SOC.

📁 CV lengkap (format ATS): [`cv/CV_ATS_Irman_Efendi_SOC_Analyst_EN-v2.pdf`](cv/CV_ATS_Irman_Efendi_SOC_Analyst_EN-v2.pdf)

---

## 🛠️ Technical Skills & SOC Competencies

| Kategori | Kemampuan |
|---|---|
| **SOC Operations & SIEM** | Splunk Enterprise (SPL Queries, Threshold Alerting, Cross-Case Correlation), Alert Triage (TP/FP), Severity Scoring, Tier 2 Escalation, Incident Ticketing, NIST SP 800-61, MITRE ATT&CK Framework |
| **Network & Packet Analysis** | Wireshark (PCAP Inspection, TCP/HTTP Stream Analysis, Display Filters), TCP/IP, DNS, HTTP/HTTPS, Firewall & WAF Log Review |
| **Infrastructure & Endpoint** | IT Asset Monitoring, Vulnerability Detection, EDR Alert Triage (LSASS Access, PowerShell, Ransomware Containment), IT Hardware Support & Troubleshooting |
| **Enterprise Software** | Microsoft Office, SAP, Lotus Notes, PEB, G-Soft |
| **Case Study** | Website & Server Unreachable |

---

## 💼 Pengalaman Kerja

### IT Infrastructure & Cybersecurity Specialist — BMD Group Corp (PT Bisa Mandiri Strategi Investasi)
*Mei 2025 – Oktober 2026*
- Memantau infrastruktur IT korporat dan aset sistem terhadap aktivitas ancaman siber, serta melakukan asesmen deteksi kerentanan secara rutin.
- Menganalisis log keamanan, mengevaluasi dampak insiden, menentukan kontrol penanganan awal, dan mendokumentasikan tiket insiden keamanan siber.
- Menjaga keandalan jaringan, ketersediaan hardware, dan dukungan teknis infrastruktur IT di lingkungan kantor dan laboratorium.

### Senior Staff General Affair — PT. Sicepat Express Indonesia
*2021 – Mei 2025*
- Mengontrol dan memantau inventaris aset fisik serta atribut operasional di 26 kantor cabang melalui pelacakan terpusat.
- Menyelesaikan masalah operasional, mengelola infrastruktur fasilitas, dan mengoordinasikan vendor eksternal untuk pembukaan cabang baru.

### Staff General Affair — PT. Mitra Ayu Adipratama
*2019 – 2021*
- Mengelola catatan inventaris kantor masuk dan keluar serta mengoordinasikan logistik dengan supplier, vendor, dan forwarder internasional.

### Staff General Affair — PT. Pindo Deli Pulp and Paper Mills
*2015 – 2019*
- Berkoordinasi dengan teknisi internal dan vendor maintenance untuk peralatan elektronik kantor serta mendukung sistem regulasi ekspor-impor.

---

## 🔎 Cybersecurity Lab & SOC Investigation Portfolio

> Studi kasus hasil simulasi lab (Splunk Enterprise & Wireshark lokal), didokumentasikan dengan pendekatan analisis SOC Tier 1: identifikasi, triase, dan rekomendasi eskalasi.


### Case 1, 2 & 3 — Brute Force, SQL Injection & Active Reconnaissance Detection (Splunk Enterprise)
- Menginvestigasi percobaan login admin eksternal yang mencurigakan dari satu subnet yang sama (**T1110, T1078**) → diklasifikasikan **True Positive (High)**, direkomendasikan penerapan MFA dan reset password.
- Memvalidasi percobaan SQL Injection yang diblokir WAF (**T1190**, HTTP 403) dan burst TCP Port Scanning (**T1595**) menggunakan SPL queries, dengan usulan firewall blocklist dan hardening service.
  
### Case 4 & 5 — Malware, Ransomware, LSASS Dumping & Data Exfiltration Correlation (Splunk Enterprise)
Mengorelasikan alert endpoint kritikal pada host `192.0.2.100` yang melibatkan eksekusi PowerShell mencurigakan (**T1059.001**), perilaku ransomware (**T1486**), dan LSASS credential dumping (**T1003.001**), bersamaan dengan upaya transfer keluar sebesar 810.62 MB ke IP eksternal (**T1048**).
- **Klasifikasi:** True Positive (Critical)
- **Rekomendasi:** Isolasi host, blokir IP, reset kredensial, eskalasi ke Tier 2.

### Case 6 — HTTP Traffic Packet Inspection & False Positive Triage (Wireshark PCAP)
Memeriksa capture `.pcapng` berisi 149 paket menggunakan display filter dan Follow TCP Stream, mengidentifikasi permintaan update Microsoft Office yang gagal (HTTP 400), dan menutup alert sebagai **Benign / False Positive**.

---

## 🎓 Education & Certifications

| Sertifikasi / Pendidikan | Penyelenggara | Tahun |
|---|---|---|
| Associate Degree (D3) Telecommunication Engineering | Politeknik Negeri Padang | 2011 – 2014 |
| Cybersecurity Awareness Training — Integrated with KEPNAKER No. 391/2020 (Reg. No: 01/BMD/CBA/IX/26) | BMD Street Consulting | September 2025 |
| Security Blue Team — Certified Blue Team Level 1 (BTL1) *(Certification ID: 884544262)* | Security Blue Team | 2 Februari 2026 |

📁 Sertifikat: [`certificates/`](certificates/)
- [Security Blue Team — BTL1 Certificate](certificates/Security_Blue_Team_Certificate__1_.pdf)
- [Sertifikat Cybersecurity Awareness — BMD Street Consulting](certificates/Sertifikat_SOC_Irman_Efendi.pdf)

**6 unit kompetensi SKKNI SOC yang diselesaikan (KEPNAKER No. 391/2020):**
1. `J.62SOC00.008.1` — Melakukan Pemantauan Aset Teknologi Informasi (TI) terhadap Aktivitas Ancaman Siber
2. `J.62SOC00.006.1` — Melakukan Deteksi Kerentanan Aset Teknologi Informasi (TI)
3. `J.62SOC00.011.1` — Menganalisis Log pada Security Operations Center (SOC)
4. `J.62SOC00.005.1` — Melakukan Analisis Keamanan Siber terhadap Insiden untuk Menentukan Kendali
5. `J.62SOC00.018.1` — Menganalisis Dampak Insiden Keamanan Siber
6. `J.62SOC00.010.1` — Memberikan Tiket terhadap Insiden Keamanan Siber

---

## 📫 Contact

- Email: irmaneffendie93@gmail.com
- Phone/WhatsApp: +62 853-7512-1014
- Location: South Tangerang, Banten, Indonesia
