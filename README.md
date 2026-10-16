# road-to-devfest-2026-jkt

Materi praktik **Token Efficiency** untuk Road to DevFest Jakarta 2026: cara hemat token di AI-native apps dan agentic coding workflow.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/algonacci/road-to-devfest-2026-jkt/blob/main/token_efficiency.ipynb)

## Isi

[`token_efficiency.ipynb`](token_efficiency.ipynb) mengikuti urutan slide:

1. **Dasar token**: tokenizer, token bukan kata, English vs Indonesia, JSON vs CSV
2. **Habisnya di input**: perbandingan token input dan output
3. **Prompt caching**: cache miss vs cache hit, prefix harus identik, snippet TTL Claude/Gemini/DeepSeek
4. **Biaya ganti model** di tengah sesi
5. **Level aplikasi**: urutan prompt, pembunuh cache, kirim lebih sedikit (log, file, gambar)
6. **Agent loop**: agent mini yang membenerin bug login, dengan grafik token per giliran
7. **Kuota sadar cache**: estimasi naif vs sadar cache

Bagian 1, 4, dan 7 bisa dijalankan tanpa API key.

## API key

Klaim kuota di **platform.orvix.id/e/ROAD-TO-DEVFEST-JKT-2026**, buat API key dengan scope `ai:invoke`, lalu masukkan saat cell setup meminta.
