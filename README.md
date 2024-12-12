## ORALIQ TEST (20 TA - HAR BIRIGA 2.5 BALLDAN BERILADI)

1. Python dasturlash tilining quyidagi xususiyatlaridan qaysi biri noto'g'ri?
- a) Python yuqori darajadagi ma'lumotlar strukturasiga ega
- b) Python dasturlash tilida xotirani boshqarish shart emas
- c) Python ko'p platformalarda hech qanday o'zgartirishlarsiz ishlaydi
- d) Python interpretatsiyalanmaydigan til hisoblanadi

2. Pythonda o'zgaruvchilar bilan ishlashda qaysi holat noto'g'ri?
- a) O'zgaruvchi nomi harf yoki tag chiziq bilan boshlanishi kerak
- b) O'zgaruvchi nomi faqat harflar va raqamlardan iborat bo'lishi mumkin
- c) O'zgaruvchi nomi probel bilan ajratilgan bo'lishi mumkin 
- d) O'zgaruvchi nomlari katta-kichik harflarni farqlaydi

3. random() modulidagi qaysi funksiya berilgan ketma-ketlikni tasodifiy tartibda joylashtiradi?
- a) randrange()
- b) shuffle()
- c) choice()
- d) random()

4. Pythonda quyidagilardan qaysi biri mantiqiy operator hisoblanmaydi?
- a) and
- b) or  
- c) not
- d) set

5. Tuple va List o'rtasidagi asosiy farq nimada?
- a) Tuple elementlari o'zgartirilishi mumkin, List elementlari o'zgartirilmaydi
- b) List elementlari o'zgartirilishi mumkin, Tuple elementlari o'zgartirilmaydi 
- c) Tuple elementlari ko'p xotira egallaydi, List elementlari kam
- d) List va Tuple elementlari bir xil o'zgartirilishi mumkin

6. datetime modulida qaysi format kodi yilning qisqa ko'rinishini beradi?
- a) %Y
- b) %y
- c) %d
- d) %m

7. OOP da inkapsulyatsiya nima uchun ishlatiladi?
- a) Kodning qayta ishlatilishini ta'minlash uchun
- b) Kodning strukturasini yaxshilash uchun
- c) Metodlar va o'zgaruvchilarga kirishni cheklash uchun
- d) Obyektlar orasidagi munosabatlarni aniqlash uchun

8. Python dasturlash tilida qaysi operator shartlarni birlashtirib ishlatish uchun kerak?
- a) break
- b) continue
- c) pass
- d) and

9. math modulidagi qaysi funksiya sonning absolyut qiymatini qaytaradi?
- a) pow()
- b) fabs() 
- c) ceil()
- d) floor()

10. Quyidagi try-except blokida nima yuz beradi?
```python
try:
    print(x)
except:
    print("x o'zgaruvchi mavjud emas")
```
- a) x o'zgaruvchi mavjud bo'lsa, uni ekranga chiqaradi
- b) x o'zgaruvchi mavjud bo'lmasa, xatolik haqida xabar beradi
- c) x o'zgaruvchining qiymatini o'zgartiradi
- d) x o'zgaruvchini o'chiradi

11. Pythonda os.path.exists() funksiyasi nima vazifani bajaradi?
- a) Fayl hajmini tekshiradi
- b) Fayl mavjudligini tekshiradi
- c) Faylni o'chiradi
- d) Faylni ochadi

12. Quyidagi metodlardan qaysi biri Set(to'plam)ga tegishli emas?
- a) add()
- b) remove()
- c) append()
- d) discard()

13. __init__() funksiyasi qanday vazifani bajaradi?
- a) Obyektni o'chiradi
- b) Obyekt xususiyatlarini o'zgartiradi  
- c) Obyekt uchun xotira ajratadi
- d) Obyekt yaratilayotganda uning xususiyatlariga qiymatlarni biriktiradi

14. lambda funksiyasi nima uchun ishlatiladi?
- a) Katta hajmdagi funksiyalarni yozish uchun
- b) Kichik anonim funksiyalar yaratish uchun
- c) Rekursiv funksiyalar yaratish uchun
- d) Global o'zgaruvchilarni e'lon qilish uchun

15. Quyidagi operator va ifodalardan qaysi biri eng yuqori prioritetga ega?
- a) +, -
- b) *, /
- c) **
- d) ()

16. pickle moduli nima vazifani bajaradi?
- a) Dastur tezligini oshiradi
- b) Ma'lumotlarni arxivlaydi
- c) Obyektlarni faylga saqlash va undan o'qib olish
- d) Fayllarni shifrlash

17. Pythonda vorislik(inheritance) qanday amalga oshiriladi?
- a) super() funksiyasi orqali
- b) Sinf nomidan keyin qavsda ota-sinf nomini ko'rsatish orqali
- c) __init__() funksiyasi orqali
- d) pass operatori orqali

18. datetime.strftime() metodida %A format kodi nimani bildiradi?
- a) Oyning to'liq nomi
- b) Hafta kunining to'liq nomi
- c) Soat (00-23)
- d) Yilning to'liq ko'rinishi

19. Quyidagi funksiyalardan qaysi biri ro'yxatni tartiblaydi?
- a) append()
- b) extend()  
- c) sort()
- d) reverse()

20. Pythonda quyidagilardan qaysi biri ma'lumot turi hisoblanmaydi?
- a) list
- b) dict
- c) function
- d) elif

## MASALALAR (10 TA - HAR BIRIGA 5 BALLDAN BERILADI)

1. List va for sikli bilan ishlash masalasi:
- Foydalanuvchidan nechta son kiritmoqchi ekanligini so'rang
- Kiritilgan sonlarni ro'yxatga saqlang
- Ro'yxatning juft indeksli (0,2,4...) elementlarini ekranga chiqaring
Masalan: [10,20,30,40,50] → 10,30,50 ekranga chiqadi

2. Dictionary bilan ishlash masalasi:
- Talabalar haqida ma'lumot saqlovchi lug'at yarating:
  - Har bir talaba uchun: 
    - Ismi
    - Yoshi  
    - Kursi
- Foydalanuvchi talaba ismini kiritganda:
  - Shu talabaning barcha ma'lumotlari ekranga chiqsin
  - Agar bunday talaba bo'lmasa, xabar berilsin

3. OOP asoslari masalasi:
- "Kitob" klassini yarating quyidagi xususiyatlar bilan:
  - Kitob nomi
  - Muallifi
  - Nashr yili
- Klassda kitob haqida ma'lumot beruvchi metod yarating
- Shu klassdan foydalanib 3 ta turli kitob yarating
- Har bir kitob haqidagi ma'lumotni ekranga chiqaring

4. While sikli masalasi:
- Foydalanuvchidan istalgan son kiriting
- While sikli yordamida:
  - Sonni raqamlarga ajrating
  - Raqamlarni yig'indisini hisoblang
Masalan: 123 → 1+2+3=6

5. Fayllar bilan ishlash masalasi:
- Mavjud matn faylini o'qing
- Matndagi so'zlarni ajrating
- Har bir so'z uzunligini tekshiring
- Eng uzun so'zni toping va ekranga chiqaring
- Necha harfdan iborat ekanligini ko'rsating

6. String metodlari masalasi:
- Foydalanuvchidan gap kiriting
- Unli harflar ro'yxatini tuzing (a,e,i,o,u)
- Kiritilgan gapdagi har bir harfni tekshiring
- Unli harflar sonini hisoblang
- Natijani ekranga chiqaring

7. Vorislik masalasi:
- "Transport" klassini yarating:
  - Umumiy xususiyatlar: tezlik, rang, ishlab chiqarilgan yil
- "Avtomobil" klassini yarating (Transport klassidan voris olsin):
  - Qo'shimcha xususiyatlar: markasi, eshiklar soni
- Har ikkala klassda ma'lumot beruvchi metodlar yarating
- Klasslardan obyektlar yarating va metodlarni ishlating

8. Funksiyalar masalasi:
- Mukammal son funksiyasini yarating
- Funksiya parametr sifatida son qabul qilsin
- Son bo'luvchilarini toping (1 dan songacha bo'lgan)
- Bo'luvchilar yig'indisini hisoblang
- Yig'indi songa teng bo'lsa True, aks holda False qaytarsin
Masalan: 6 soni mukammal son (1+2+3=6)

9. Set to'plami masalasi:
- Ikkita to'plam yarating
- Ularning kesishmasini toping
- Ya'ni ikkala to'plamda ham mavjud elementlarni aniqlang
Masalan: {1,2,3} va {3,4,5} → {3}

10. Math moduli masalasi:
- Foydalanuvchidan son kiriting
- Math moduli yordamida:
  - Sonning faktorialini hisoblang
  - Sonning kvadrat ildizini toping
  - Natijalarni ekranga chiqaring
Masalan: 5 → Faktorial=120, Ildiz=2.236...
