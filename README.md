```shell
git clone https://github.com/angganix/appwrite-self-hosted.git
cd appwrite-self-hosted
docker-compose up -d
```
- Pastikan sesuaikan file .env nya
- Pastikan tidak ada Image appwrite sebelumnya
- Pastikan tidak ada Volume appwrite sebelumnya
- Pastikan step di atas di lakukan di clean docker (khusus appwrite)

Setelah selesai melakukan compose docker, tunggu beberapa saat. karena jika langsung melakukan akses http://localhost akan terjadi
Bad Gateway. tunggu 10 - 30 detik sembari melakukan akses ke http://localhost (disini saya menggunakan port 80 sebagai default port).