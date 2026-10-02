<div align="center">
  
  # 📐 DUMA (Diagram untuk Mahasiswa)
  **Revolusi Diagram Mahasiswa: Dari Konsep ke Kode.**

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Made with Markdown](https://img.shields.io/badge/Made_with-Markdown-1f425f.svg)](https://daringfireball.net/projects/markdown/)
  [![Status: Beta](https://img.shields.io/badge/Status-Active_Beta-00c4be.svg)]()

  *Proses Cepat. Diagram Tepat. Skripsi Selamat.*

</div>

---

## 🚀 Apa itu DUMA?
**DUMA** adalah *IDE (Integrated Development Environment)* ringan yang dirancang khusus untuk membantu mahasiswa menyusun diagram akademik dengan presisi absolut. Menggunakan pendekatan *Markdown-first* (Diagram-as-Code), DUMA mengubah sintaks teks sederhana menjadi visual diagram yang kompleks secara *real-time*. 

DUMA dibangun dengan pemahaman bahwa alat penunjang akademik harus sangat fungsional namun tetap terjangkau, terutama bagi mahasiswa yang harus pintar-pintar mengatur uang saku bulanan yang terbatas. Kami menghadirkan fitur sekelas *enterprise* dengan harga yang masuk akal.

## ✨ Fitur Unggulan

- **📝 Pendekatan Markdown-First (Code-to-Diagram):** Ketik sintaks Markdown/Mermaid Anda, dan DUMA akan merendernya menjadi diagram instan tanpa perlu repot melakukan *drag-and-drop*.
- **🤖 AI Diagram Generator (Zero-Cost Architecture):** Cukup deskripsikan alur sistem Anda menggunakan bahasa manusia, dan DUMA akan mengonversinya menjadi sintaks diagram yang valid. Didukung oleh integrasi LLM *client-side* yang dioptimalkan untuk meminimalkan beban server.
- **🛡️ Academic Rule Checker:** *Linter* bawaan yang memvalidasi diagram Anda layaknya kode pemrograman. DUMA akan memunculkan peringatan jika ada relasi *database* yang salah, alur yang terputus, atau entitas yang tidak standar (PERIKSA: Diagram Alur Bebas Kesalahan).
- **🔄 Sinkronisasi Real-time:** Antarmuka *split-pane* yang mulus. Perubahan pada kode di panel kiri langsung tecermin pada kanvas visual di panel kanan.
- **💾 Format Portabel:** Ekspor diagram ke format `.png`, `.svg`, atau cukup *copy-paste* blok `.md` langsung ke Readme GitHub atau laporan skripsi Anda.

## 📊 Dukungan Diagram
DUMA mendukung standar diagram yang paling sering digunakan dalam tugas akhir, skripsi, dan proyek IT:
- [x] Flowchart
- [x] Entity Relationship Diagram (ERD)
- [x] Use Case Diagram
- [x] Activity Diagram
- [x] Data Flow Diagram (DFD)
- [ ] *BPMN 2.0 (Segera Hadir)*
- [ ] *Text-based Wireframing (Segera Hadir)*

## 💻 Cara Kerja

DUMA berjalan murni dari *browser* atau aplikasi lokal Anda, memastikan performa maksimal dengan jejak memori yang sangat kecil.

```mermaid
graph LR
    A[Teks / Prompt User] --> B(AI / Manual Markdown)
    B --> C{Rule Checker}
    C -->|Error| B
    C -->|Valid| D[Live Visual Render]
    D --> E(Ekspor ke Skripsi)
