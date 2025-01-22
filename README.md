<div align="center">
# Muslim Api V2 - by Kang Muhtar
<p align="center">
<img height="100" src="images/masjid1.png">
</p>
<p align="center">
<a href="#"><img title="Public API" src="https://img.shields.io/badge/Public Api-blue?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/kiramizuky"><img title="Author" src="https://img.shields.io/badge/Author-kiramizuky-orange.svg?style=for-the-badge&logo=github"></a>
</p>
<!-- <p align="center">
<a href="https://github.com/kiramizuky/followers"><img title="Followers" src="https://img.shields.io/github/followers/kiramizuky?color=red&style=flat-square"></a>
<a href="https://github.com/kiramizuky/islamic-rest-api-indonesian-v2/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/kiramizuky/islamic-rest-api-indonesian-v2?color=blue&style=flat-square"></a>
<a href="https://github.com/kiramizuky/islamic-rest-api-indonesian-v2/network/members"><img title="Forks" src="https://img.shields.io/github/forks/kiramizuky/islamic-rest-api-indonesian-v2?color=red&style=flat-square"></a>
<a href="https://github.com/kiramizuky/islamic-rest-api-indonesian-v2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/kiramizuky/islamic-rest-api-indonesian-v2?label=Watchers&color=blue&style=flat-square"></a> -->
</p>
<p align='center'>
   <!-- <a href="https://instagram.com/zhirr_ajalah"><img height="30" src="https://raw.githubusercontent.com/TobyG74/TobyG74/main/instagram.jpg"></a> -->
</P>
<p align ='center'>
Muslim Api V2 adalah Api yang berisi data2 islami yang lebih lengkap daripada versi sebelumnya, yaitu Api Islamic yang pernah saya buat sebelumnya.
</p>


## ☪️ Islamic API
| Menu | Fitur | 
|------------ | ---------|
| Data Islami | ✔️ |
| Hadith | ✔️ |
| Qur'an | ✔️ |
| Kisah Nabi | ✔️ |
| DLL | ✔️ |


## ☪️ Web Featured
| Menu | Web | 
|------------ | ---------|
| Landing Page | ✔️ |
| Docs Page | ✔️ |


## ☪️ Data JSON
| Menu | Penjelasan | Endpoint |
|------------ | ---------| ---------|
| Data AsmaulHusna JSON | Menampilkan Data AsmaulHusna | /asmaulhusna |
| Data Tahlil JSON | Menampilkan Data Doa Tahlil | /tahlil |
| Data KisahNabi JSON | Menampilkan Data Kisah Para Nabi | /kisahnabi |

## ☪️ Data Al Qur'an JSON
| Menu | Penjelasan | Endpoint |
|------------ | ---------| ---------|
| Data Daftar Surah JSON| Menampilkan Data Semua Surah di Al Qur'an | /quran |
| Data Surah JSON | Menampilkan Surah tertentu di Al Qur'an | /quran/1 |
| Data Ayah JSON | Menampilkan Ayah tertentu dalam suatu Surah di Al Qur'an | /quran/2/257 |

## ☪️ Data Hadith JSON
| Menu | Penjelasan | Endpoint | Parametr |
| ------------ | --------- | --------- | --------- |
| Daftar Imam | Menampilkan Daftar kitab-kita Hadits | /hadits |  |
| Abu Daud | Menampilkan Data Hadith Abu Daud | /hadits/abu-daud | page=1?limit=20 |
| Ahmad | Menampilkan Data Hadith Ahmad | /hadits/ahmad | page=1?limit=20 |
| Bukhari | Menampilkan Data Hadith Bukhari | /hadits/bukhari | page=1?limit=20 |
| Darimi | Menampilkan Data Hadith Darimi | /hadits/darimi | page=1?limit=20 |
| Ibnu Majah | Menampilkan Data Hadith Ibnu Majah | /hadits/ibnu-majah | page=1?limit=20 |
| Nasai | Menampilkan Data Hadith Nasai | /hadits/nasai | page=1?limit=20 |
| Malik | Menampilkan Data Hadith Malik | /hadits/malik | page=1?limit=20 |
| Muslim | Menampilkan Data Hadith Muslim | /hadits/muslim | page=1?limit=20 |
| Arbain Nawawi | Menampilkan Data Hadith Arbain An Nawawiah | /hadits/arbain |

## ☪️ Data Shalat JSON
| Menu | Penjelasan | Endpoint |
|------------ | ---------| ---------|
| Bacaan Niat seluruh shalat Wajib | Menampilkan semua Bacaan Niat seluruh shalat Wajib | /shalat/niat|
| Shubuh | Menampilkan Data Niat Shalat Shubuh | /shalat/niat/niatshubuh |
| Dzuhur | Menampilkan Data Niat Shalat Dzuhur | /shalat/niat/niatdzuhur |
| Ashar | Menampilkan Data Niat Shalat Ashar | /shalat/niat/niatashar |
| Maghrib | Menampilkan Data Niat Shalat Maghrib | /shalat/niat/niatmaghrib |
| Isya | Menampilkan Data Niat Shalat Isya | /shalat/niat/niatisya |
| Bacaan Shalat | Menampilkan Bacaan-bacaan tiap gerakan dalam Shalat | /shalat/bacaan |
| Daftar Kota | Menampilkan daftar kota untuk melihat jadwal Shalat se-Indonesia | /shalat/kota |
| Jadwal Shalat per Tanggal | Menampilkan melihat jadwal waktu shalat untuk waktu dan kota terntentu di Indonesia | /shalat/jadwal/:kota/:tahun/:bulan/:tanggal |
| Jadwal Shalat per Bulan | Menampilkan melihat jadwal waktu shalat untuk 1 Bulan pada kota terntentu di Indonesia | /shalat/jadwal/:kota/:tahun/:bulan |

## ☪️ Data Do'a JSON
| Menu | Penjelasan | Endpoint |
|------------ | ---------| ---------|
| Daftar Sumber Do'a | Menampilkan Data Semua Sumber Do'a | /doa/listsumber |
| Daftar Sumber Do'a dari Sumber tertentu | Menampilkan Data Semua Do'a dari Sumber tertentu| /doa/sumber/:sumber |
| Do'a acak | Menampilkan Do'a acak | /doa/acak |

## ☪️ Data Kalender Hijriah JSON
| Menu | Penjelasan | Endpoint |
|------------ | ---------| ---------|
| Daftar Hari | Menampilkan Daftar Hari | /kalender/listhari |
| Daftar Bulan | Menampilkan Daftar Bulan Hijriah | /kalender/listbulan |
| Data Hari ini | Menampilkan Data Kalender Hijriah untuk Hari ini | /kalender/hariini |
| Data Tangal Tertentu | Menampilkan Data Kalender Hijriah untuk Tanggal Tertentu | /kalender/tanggal/:tanggal |


```
Untuk Melihat

# Live API
- https://islamic-api.vwxyz.id
- Gunakan Parameter Yg Sama Yaa :)
- 100 % Open Source
- Like This Repository Okeee 🎉
- Special Note : Ini Adalah Public API Yang Digunakan Bersama-Sama, Jadi Kita Harus Memakai Nya Dengan Bijak Okey 👍
