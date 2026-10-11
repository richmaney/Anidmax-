# 🎌 Anime Bot (aiogram 3)

Telegramda ishlaydigan zamonaviy anime bot: shifrli kodlar, premium obuna, majburiy obuna, kanalga post yuborish.

## Imkoniyatlar

**Foydalanuvchi tomoni:**
- 🎌 Zamonaviy anime uslubidagi bosh menyu
- ❗ Majburiy obuna (kanallarga obuna bo'lmasa bot ishlamaydi)
- 🔑 Shifrli kod kiritib anime qismlarini ochish
- 💎 Premium sotib olish (narxlardan tanlaydi → chek yuboradi → admin tasdiqlaydi)
- 🎬 Animelar ro'yxati (premium 🔒 / bepul 🆓 belgisi bilan)
- 👤 Profil (premium muddati, ishlatilgan kodlar)

**Admin tomoni (`/admin`) — rasmadagi kabi:**
- ⚙️ Birlamchi sozlamalar (post kanali, narxlar, admin qo'shish)
- 📊 Statistika
- 📢 Xabar yuborish (hamma foydalanuvchilarga)
- 📬 Post tayyorlash (tugmali post kanalga)
- 📌 Konkurs (tasodifiy g'oliblar tanlash)
- 📩 TEXT POST
- 🎬 Animelar sozlash (anime/qism qo'shish, shifrli kod yaratish, o'chirish)
- 💳 Hamyonlar (to'lov kartalari)
- 🔍 Foydalanuvchini boshqarish (premium berish, ban)
- 📣 Kanallar (majburiy obuna kanallari)
- 🔘 Tugmalar va 📄 Matnlar (bot matn/tugmalarini o'zgartirish)

## O'rnatish

```bash
pip install -r requirements.txt
```

1. `config.py` da `BOT_TOKEN` va `ADMIN_IDS` ni to'ldiring
2. `python bot.py` buyrug'i bilan botni ishga tushiring
3. Botda `/admin` yozing — panel ochiladi

## Muhim eslatmalar

- **Majburiy obuna:** bot `@BotFather` orqali yaratilgan bo'lishi kerak va u majburiy kanallarda **admin** bo'lishi shart.
- **Post kanali:** ⚙️ Birlamchi sozlamalar → 📢 Post kanalini o'rnatish (bot shu kanalda admin bo'lishi shart).
- **Qism qo'shish:** 🎬 Animelar sozlash → ➕ Qism qo'shish → video/fayl yuboriladi → bot shifrli kod beradi (yoki o'zingiz kiritasiz).
- Katta fayllar (50MB dan ortiq) uchun foydalanuvchi kanalga yuborilgan video file_id sini ishlatish tavsiya etiladi.
- 
