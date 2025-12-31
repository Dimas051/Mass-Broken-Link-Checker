![alt text](https://d.top4top.io/p_3652lx9rx1.png?raw=true)

Mass Broken Link Checker yang dirancang untuk memeriksa status ketersediaan URL dalam jumlah besar secara paralel menggunakan multi-threading! 🎯

1. Filter URL aktif vs mati -> Memisahkan website yang masih online (200 OK) dari yang sudah mati (404/error)
2. Pembersihan daftar URL -> Membersihkan list URL dari broken links
3. Reconnaissance awal -> Dalam bug bounty/pentesting, untuk mengidentifikasi target yang masih aktif
4. Validasi massal -> Mengecek ribuan URL sekaligus dengan efisien

🚀 Contoh penggunaan:
python script.py -i urls.txt -o active.txt -t 50 -d 0.2

Parameter:

- -i/--input: File input (default: list.txt)
- -o/--output: File output (default: result.txt)
- -t/--threads: Jumlah thread (default: 100)
- -d/--delay: Delay antar request (detik)

Kelebihan:

✅ Cepat dengan threading paralel
✅ Output informatif dengan warna
✅ Configurable (threads, delay, retry)
✅ Error handling robust
✅ Mendukung URL tanpa skema

🎯 Kesimpulan: Program ini adalah alat yang powerful untuk memeriksa ribuan URL dengan cepat! Dengan multi-threading dan optimisasi yang baik, sangat cocok untuk pentester, SEO specialist, atau administrator sistem! 🚀✨
