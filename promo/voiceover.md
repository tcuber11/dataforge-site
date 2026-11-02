# Voice-over — video promosi DataForge (45 detik)

Untuk ElevenLabs: suara multilingual v2 (Indonesia untuk `voice-id.mp3`, Inggris untuk `voice-en.mp3`), kecepatan normal, stability ~50, similarity ~75. Hasilkan **satu file per bahasa** dari teks siap tempel di bawah. Simpan sebagai `site/promo/voice-id.mp3` / `site/promo/voice-en.mp3`, lalu jalankan `node scripts/render-promo.mjs`: musik latar (`site/promo/bgm.mp3`, dibuat `scripts/make-bgm.py`) otomatis mengecil di bawah suara. Kalau durasinya meleset lebih dari 1–2 detik, atur kecepatan di ElevenLabs atau ubah `<break time="…" />`.

| Detik | Adegan | Naskah (ID) |
|---|---|---|
| 0–5 | Judul | Query cepat. Ubah dengan aman. Ini DataForge. |
| 5–13 | 50 engine | Semua database kamu dalam satu navigator: lima puluh engine, dari PostgreSQL sampai Kafka. Dua puluh delapan sudah diuji dengan server sungguhan. |
| 13–22 | Query | Query jalan dengan akun read-only, dan setiap statement diparse dengan grammar engine-nya sendiri sebelum dijalankan. |
| 22–32 | Review & deploy | Perubahan ke prod butuh dua reviewer. Yang di-deploy persis byte yang disetujui, dan setiap langkahnya tercatat di audit log. |
| 32–39 | AI | AI menulis draf, kamu yang memutuskan. Atau sambungkan Claude Code lewat MCP. |
| 39–45 | Penutup | Satu workspace untuk setiap database. Unduh DataForge untuk macOS. |

## Teks siap tempel (ID)

Query cepat. Ubah dengan aman. Ini DataForge. <break time="1.2s" />
Semua database kamu dalam satu navigator: lima puluh engine, dari PostgreSQL sampai Kafka. Dua puluh delapan sudah diuji dengan server sungguhan. <break time="1.0s" />
Query jalan dengan akun read-only, dan setiap statement diparse dengan grammar engine-nya sendiri sebelum dijalankan. <break time="1.5s" />
Perubahan ke prod butuh dua reviewer. Yang di-deploy persis byte yang disetujui, dan setiap langkahnya tercatat di audit log. <break time="1.5s" />
AI menulis draf, kamu yang memutuskan. Atau sambungkan Claude Code lewat MCP. <break time="1.2s" />
Satu workspace untuk setiap database. Unduh DataForge untuk macOS.

## English version (same timing)

Query fast. Change safely. This is DataForge. <break time="1.2s" />
All your databases in one navigator: fifty engines, from PostgreSQL to Kafka. Twenty-eight of them tested against real servers. <break time="1.0s" />
Queries run on a read-only account, and every statement is parsed by the engine's own grammar before it runs. <break time="1.5s" />
Changes to prod need two reviewers. What gets deployed is exactly the bytes that were approved, and every step lands in the audit log. <break time="1.5s" />
The AI writes a draft; you decide. Or connect Claude Code over MCP. <break time="1.2s" />
One workspace for every database. Download DataForge for macOS.
