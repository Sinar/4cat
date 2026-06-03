# 4cat
Pelayan awam Sinar Project untuk mencuba [4cat](https://github.com/digitalmethodsinitiative/4cat), alat penyelidikan untuk mengumpul serta menganalisa data media sosial, kini tersedia untuk digunakan secara terhad. Jika berminat, sila e-mel team@sinarproject.org untuk ditambah sebagai pengguna di pelayan ini.

Alat ini perlu digunakan bersama-sama dengan https://tools.digitalmethods.net/zeeschuimer, yang hanya tersedia sebagai pemalam (plugin) pelayar Firefox.

Versi ini menyokong pengumpulan data daripada sumber-sumber berikut:
- TikTok (hantaran/posts)
- TikTok (komen)
- Instagram (hantaran & reels)
- LinkedIn
- 9GAG
- Imgur
- X/Twitter
- Douyin
- Gab
- Truth Social
- Threads
- Pinterest
- RedNote/Xiaohongshu
- RedNote (komen)

## Penggunaan Asas Penggalian Data (Data Crawling) daripada Media Sosial

**Apa yang anda perlukan:**
- Pelayar Firefox https://www.firefox.com/en-US/
- Akaun media sosial daripada salah satu sumber di atas (log masuk di tempat di mana anda boleh melihat hantaran dalam pelayar)
- Pautan sambungan Firefox yang dimuat turun https://tools.digitalmethods.net/zeeschuimer (hanya klik pada pautan tersebut dan ia akan terus dimuat turun ke komputer anda)
- kelayakan log masuk ke https://try4cat.sinarproject.org/

**Langkah-langkah**
1. Pastikan anda telah menyediakan semua item di atas sebelum memulakan. Apabila anda mendapat pautan token log masuk, buka URL tersebut di pelayar Firefox anda dan tetapkan semula kata laluan. Kemudian, log masuk menggunakan kata laluan yang telah ditetapkan.
   
2. Seterusnya, dalam pelayar yang sama, pergi ke menu (butang 3 baris di bahagian atas sebelah kanan, di bawah butang X) dan pergi ke *Extensions and Themes* (Sambungan dan Tema).

<img width="426" height="1017" alt="Screenshot from 2026-05-26 13-31-07" src="https://github.com/user-attachments/assets/78923cec-5d98-4fb3-9bbc-f094a5e45832" />

3. Pergi ke menu *Extensions* (Sambungan) (pilih simbol Yap-yap/Puzzle daripada salah satu pilihan di sebelah kiri).

<img width="861" height="322" alt="image" src="https://github.com/user-attachments/assets/ae0e20e9-545d-43f1-b6b5-258cfc662995" />

Dalam beberapa kes (lihat imej di bawah), Firefox mungkin telah memasang sambungan tersebut secara automatik untuk anda selepas dimuat turun (pilih *Continue to Installation* / Teruskan Pemasangan), jadi jika anda melihat sambungan `zeeschuimer` di sini, anda boleh langkau ke Langkah 9.

<img width="584" height="296" alt="image" src="https://github.com/user-attachments/assets/8d17044d-ddbb-427a-a00d-f3601bc17dea" />

4. Daripada butang Tetapan (*Settings*), pilih "*Install Add-on from File*" (Pasang Pengaya daripada Fail).

<img width="861" height="322" alt="image" src="https://github.com/user-attachments/assets/6782af9f-b0e2-498e-9c54-8433ad9d3a65" />

5. Pada tetingkap yang muncul, pergi ke folder Muat Turun (*Downloads*) anda dan cari fail "zeeschuimer-1.13.6.xpi".

6. Satu tetingkap akan muncul pada pelayar Firefox anda seperti ini. Klik "*Add*" (Tambah).

<img width="595" height="378" alt="image" src="https://github.com/user-attachments/assets/3dbe468b-e173-413b-b5a0-8302bcc89e30" />

7. Tandakan "*Pin extension to toolbar*" (pinkan sambungan ke toolbar) dan klik OK.

<img width="603" height="204" alt="image" src="https://github.com/user-attachments/assets/2bb27dda-3092-4ccf-9cbd-222b0e0c811f" />

8. Di bahagian atas pelayar (header), buka tab baharu dan laman web media sosial anda. Di sini kita menggunakan TikTok (https://www.tiktok.com/), yang membolehkan data diambil tanpa perlu log masuk.

9. Di tab yang lain, klik butang "Z" baharu pada bar alat pelayar anda. Ini akan membuka sambungan Zeeschuimer. Jika anda tidak melihat butang "Z", klik pada butang Yap-yap (Puzzle) pada bar alat dan klik pada sambungan tersebut.
<img width="202" height="55" alt="image" src="https://github.com/user-attachments/assets/eebe1383-51c9-43a5-80ff-caf3f6ba66e2" />

10. Aktifkan (*Active*) untuk TikTok (posts) dan tampal URL pelayan 4CAT di bawah "*Connect to 4CAT - 4CAT server URL:* " https://try4cat.sinarproject.org/ (pastikan anda masih log masuk di laman web Try4CAT).

<img width="819" height="964" alt="image" src="https://github.com/user-attachments/assets/747625b0-6338-43b8-99ef-d9f1f6a4f488" />

11. Memandangkan sambungan telah diaktifkan, ia akan mula menggali data. Kembali ke tab TikTok dan mula skrol ke bawah. Sambil anda skrol, sambungan tersebut akan mengumpul data.

12. Selepas beberapa hantaran, perhatikan bahawa bilangan "*Items*" (Item) dalam tab Zeeschuimer telah meningkat daripada 0, menunjukkan bahawa data telah dikumpul. Di bawah bahagian *Actions* (Tindakan), klik "*to 4CAT*" untuk memuat naik data tersebut ke 4CAT.
<img width="819" height="964" alt="image" src="https://github.com/user-attachments/assets/aa0ed1f4-8e8e-49f2-bcbd-21598854b107" />

13. Kembali ke tab 4CAT dan pergi ke bahagian "*Datasets*" (Set Data). Anda kini akan mempunyai satu set data CSV daripada TikTok.

<img width="825" height="648" alt="image" src="https://github.com/user-attachments/assets/8e3fdf63-6e6f-412f-b15a-7fd34cea0f54" />

14. Setelah selesai, ingat untuk menyahaktifkan (*disable*) sambungan tersebut kerana ia akan terus berjalan setiap kali anda membuka laman web media sosial anda.

<img width="855" height="274" alt="image" src="https://github.com/user-attachments/assets/0ba391d4-64a1-4541-98e5-de7faa0bff61" />

## Contoh set data yang telah dikumpul
https://drive.google.com/drive/folders/1tFbL4aq7YG4ByzRSOjOBokbMYAXOcP_d?usp=drive_link

## Sumber lain
https://slides.degeling.com/tiktok-research-methods/
