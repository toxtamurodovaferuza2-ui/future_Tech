# QALB PCG Monitor by FutureTech

**QALB PCG Monitor** — bu yurak tovushlarini (fonokardiogramma - PCG) real vaqt rejimida tinglash, yozib olish va chuqur tahlil qilish uchun mo'ljallangan innovatsion raqamli stetoskop va apparat-dasturiy kompleks. Qurilma tibbiyot xodimlari va mutaxassislar uchun yurak urishi ritmini kuzatish, anomaliyalarni aniqlash va bemor ma'lumotlarini arxivlash imkonini beradi.

---

## 📸 Loyiha Ko'rinishi (Overview)

| Apparat Qismi (Hardware) | Veb-Interfeys (Dashboard) |

---

## 🛠 Apparat Qismi (Hardware Features)

Qurilma ixcham va ko'chma korpusga ega bo'lib, o'rnatilgan displey va maxsus raqamli stetoskop datchigi bilan jihozlangan.

* **O'rnatilgan LCD Ekran:** Veb-interfeysga ulanmasdan turib ham jonli signal, yurak urishi (BPM) va ritm holatini bevosita ekranda ko'rish imkoniyati.
* **Akustik Stetoskop Sensori:** Yurakning past chastotali va nozik tovushlarini aniq ushlab oluvchi maxsus datchik.

| Displey Interfeysi | Stetoskop Sensori |

---

## 💻 Veb-Interfeys va Dasturiy Imkoniyatlar

Qurilma Wi-Fi orqali lokal server tarqatadi va foydalanuvchiga qulay veb-panel taqdim etadi.

### 1. Spektrogramma va Chuqur Tahlil
Yurakning akustik to'lqinlarini chastota va vaqt bo'yicha tahlil qilish uchun spektrogramma vizualizatsiyasi mavjud.

### 2. Moslashuvchan Sozlamalar va Audio Yozib Olish
* **Ovoz va Filtrlar:** Quloqchin/karnay ovozini sozlash hamda 25–150 Hz chastota filtrlarini qo'llash.
* **Yozuvlarni Eksport qilish:** Audio yozuvlarni **MP3**, **WAV** va rasm ko'rinishida yuklab olish.

| Sozlamalar Paneli | Yozuvlar va Audio Eksport |

---

## 🤖 FKG Tahlil AI Platformasi

Qurilmaga hamroh veb-platforma: <https://fkg-tahlil-fonokardiogramma-ai.ai.studio>

Platforma uch bosqichli ish oqimidan iborat:

1. **Yozuv & Namuna** — jonli stetoskop yozuvi yoki tayyor audio faylni yuklash
2. **FKG To'lqin & RMSSD** — to'lqin shakli va ritm o'zgaruvchanligi (RMSSD) tahlili
3. **AI Xulosa** — sun'iy intellekt asosidagi skrining xulosasi

### Yurak Tovushlarini Yozib Olish / Yuklash
* **Jonli stetoskop yozuvi:** mikrofonni ko'krak qafasiga qo'yib 10 soniyalik klinik FKG stripini yozib olish.
* **Fayl yuklash:** WAV, MP3, M4A, OGG formatidagi raqamli fonokardiograf yoki elektron stetoskop yozuvlarini sudrab tashlash yoki tanlash.

### Auskultatsiya va FKG Nuqtalari (5 ta standart nuqta)

| № | Nuqta | Anatomik joylashuv | Nimani baholaydi |
|---|-------|--------------------|------------------|
| 1 | Mitral (Yurak cho'qqisi) | V qovurg'alararo, o'rta o'mrov chizig'idan 1–1.5 sm ichkarida | Mitral qopqoq faoliyati, S1 toni, S3/S4 galop ritmlari, mitral regurgitatsiya/stenoz shovqinlari |
| 2 | Aortal | II qovurg'alararo, to'sh suyagining o'ng qirrasida | Aortal qopqoq nuqsonlari |
| 3 | O'pka arteriyasi | II qovurg'alararo, to'sh suyagining chap qirrasida | O'pka arteriyasi ustidagi II ton, gipertenziya belgilari |
| 4 | Triko'spidal | To'sh suyagining pastki qismi (xanjarsimon o'simta asosida) | O'ng bo'lim qopqoq faoliyati |
| 5 | Botkin-Erb (qo'shimcha aortal) | III–IV qovurg'alararo, to'sh suyagining chap qirrasida | Aortal yetishmovchilikning diastolik shovqini |

### Klinik FKG Namunalar Bazasi (8 ta standart patologiya)

Shifokorlar va o'rganuvchilar uchun etalon fonokardiogrammalar:

| Namuna | Toifa | Asosiy belgisi | BPM |
|--------|-------|----------------|-----|
| Normal FKG (sog'lom yurak) | Normal | S1 va S2 aniq, shovqinsiz, muntazam sinusli ritm | 72 |
| Aortal stenoz | Qopqoq nuqsoni | Mezosistolik rombsimon ejeksion shovqin | 76 |
| Mitral yetishmovchilik | Qopqoq nuqsoni | Cho'qqida holosistolik (pansistolik) shovqin | 78 |
| Mitral stenoz | Qopqoq nuqsoni | Sharaqlovchi S1, ochilish shaqillashi, mezodiastolik shovqin | 82 |
| Protodiastolik galop (S3) | Miokard kasalligi | Yurak yetishmovchiligi va qorincha disfunktsiyasi | 94 |
| Aortal yetishmovchilik | Qopqoq nuqsoni | Botkin-Erb nuqtasida protodiastolik pasayuvchi shovqin | 74 |
| Bo'lmachalar fibrillyatsiyasi | Ritm buzilishi | To'liq tartibsiz R-R intervallar, o'zgaruvchan S1 | 112 |
| O'pka gipertenziyasi | Miokard kasalligi | II ton o'pka arteriyasi ustida aksentlangan va ajralgan | 86 |

---

## 🚀 Qanday Foydalaniladi? (Getting Started)

1. **Qurilmani ishga tushirish:** QALB PCG Monitor qurilmasini yoqing va stetoskop sensorini ulang.
2. **Wi-Fi tarmoqqa ulanish:** Qurilma tarqatgan Wi-Fi tarmog'iga kompyuter yoki smartfoningiz orqali ulaning.
3. **Veb-panelni ochish:** Brauzerda quyidagi IP manzilga kiring:
   ```text
   http://192.168.4.1
   ```
4. **Monitoring:** Stetoskop sensorini ko'krak qafasiga qo'yib, real vaqt rejimidagi fonokardiogrammani kuzating.
5. **Natijalarni saqlash:** Tahlil yakunida audio faylni MP3/WAV formatida kompyuteringizga yuklab oling.
6. **AI tahlil:** Yozuvni <https://fkg-tahlil-fonokardiogramma-ai.ai.studio> platformasiga yuklab, to'lqin, RMSSD va AI xulosasini oling.

---

## ⚙️ Texnik Parametrlar

* **Namuna olish chastotasi (Sampling Rate):** 2000 Hz
* **Filtratsiya:** Klassik yurak tovushi filtri (25–150 Hz)
* **Ulanish interfeysi:** Wi-Fi (Local Web Server - `192.168.4.1`)
* **Eksport formatlari:** `.mp3`, `.wav`, `.png` (rasm)
* **Qo'llab-quvvatlanadigan yuklash formatlari (AI platforma):** WAV, MP3, M4A, OGG
* **Yozuv uzunligi (klinik strip):** 10 soniya
* **Ritm ko'rsatkichi:** RMSSD (yurak ritmi o'zgaruvchanligi)

---

## ⚠️ Muhim Eslatma
*Ushbu tizim skrining vositasi bo'lib, yakuniy tibbiy tashxis hisoblanmaydi. Natijalarni har doim malakali shifokor baholashi shart.*

---

## 🔗 Foydali Havolalar

* **AI tahlil platformasi:** <https://fkg-tahlil-fonokardiogramma-ai.ai.studio>
* **Loyiha hujjati (Google Drive):** <https://drive.google.com/file/d/1n-5WbRb821rvGJBdHf75qUpYBlq3bM_3/view?usp=drivesdk>
* **GitHub repozitoriysi:** <https://github.com/toxtamurodovaferuza2-ui/futureTech1>

---
*Developed by FutureTech.*
