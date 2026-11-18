# Supermarket Telegram Mini App & Bot (Click & Collect)

Ushbu loyiha universal supermarketlar uchun **Navbatsiz olib ketish (Click & Collect)** tizimiga asoslangan Telegram Mini App va Boshqaruv Botini o'z ichiga oladi.

## Imkoniyatlari
1. **3 pog'onali Boshqaruv Tizimi:**
   - **Super Admin:** Barcha vakolatlar, admin va ishchilarni Telegram ID orqali tayinlash (`/addadmin`, `/addworker`), yetkazib berish rejimini yoqish/o'chirish (yoki 500 000 so'mdan yuqori xaridda avtomatik ochish).
   - **Admin:** Buyurtmalarni qabul qilish, holatini o'zgartirish ("Tayyor"), bo'lim ishchilari yuborgan tovar o'zgarishlarini tasdiqlash/rad etish, mijozlar savol va rasmlariga javob berish.
   - **Bo'lim ishchisi (Nonchi, Kolbasachi va b.):** Faqat o'z bo'limiga tovar qo'shish/o'chirish so'rovini yuboradi (Admin tasdiqlagach ilovada ko'rinadi).
2. **Mijoz oqimi:**
   - Botga `/start` bosganda telefon raqamni ulashish.
   - Chegirmasiz asl narxlarda savatchani shakllantirish.
   - Buyurtma ID raqami orqali kassadan navbatsiz olib ketish.
   - Botga to'g'ridan-to'g'ri yozilgan savol yoki yuborilgan rasm avtomatik adminga yo'naltiriladi.

## Ishga tushirish (GitHub va Hosting)

### 1. GitHub'ga yuklash
```bash
git init
git add .
git commit -m "Supermarket Telegram Mini App"
git branch -M main
git remote add origin [https://github.com/SIZNING_PROFIL/supermarket-tma.git](https://github.com/SIZNING_PROFIL/supermarket-tma.git)
git push -u origin main
