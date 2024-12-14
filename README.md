# 1-BOBDAN SAVOLLAR!

1. Python dasturlash tilining qaysi xususiyati uni sun'iy intellekt sohasida yuqori talabga ega qiladi?
a) Kutubxonalarining ko'pligi va matematik hisoblashlarga moslanganlik
b) Interpretatsiya qilinadigan til ekanligi
c) Sodda sintaksisga egaligi 
d) Kengayishga moyilligi

2. Pythonda kodni C/C++ tilida yozib, Python orqali chaqirish imkoniyati qanday xususiyat deb ataladi?
a) Interpretatsiyalanish
b) Krossplatformalilik
c) Kengayishga moyillik
d) Obyektga yo'naltirilganlik

3. Quyidagi kod nima uchun xato beradi?
```python
#print ("Salom dunyo")
print ("Dasturlashni o'rganamiz")
x = "Python"
# y = 'Dastur'
print(x+y)
```
a) Izohga olingan qatorlar tufayli
b) y o'zgaruvchisi izohda bo'lgani uchun
c) print funksiyasi noto'g'ri ishlatilgani uchun
d) x va y turli qo'shtirnoqlarda yozilgani uchun

4. Python lokal va global o'zgaruvchilar bilan ishlashda qanday tamoyilga amal qiladi?
a) Global o'zgaruvchilar faqat funksiya tashqarisida ishlaydi
b) Lokal o'zgaruvchilar global o'zgaruvchilarni bekor qiladi
c) Bir xil nomdagi o'zgaruvchilar funksiya ichida lokal, tashqarida global bo'ladi
d) Global kalit so'zi faqat yangi global o'zgaruvchilar yaratish uchun ishlatiladi

5. Quyidagi kod nima uchun xato beradi?
```python
2myvar = "Python"
my-var = "Python"
my var = "Python"
```
a) O'zgaruvchi nomi raqam bilan boshlanishi va maxsus belgilar ishlatilgani uchun
b) "Python" qiymati noto'g'ri berilgani uchun 
c) O'zgaruvchilar katta-kichik harflarga sezgir bo'lgani uchun
d) Qo'shtirnoqlar noto'g'ri ishlatilgani uchun

6. Python dasturlash tilida quyidagi operatorlar ketma-ketligi qanday natija beradi?
```python
x = 15
y = 4
print(x//y)
print(x%y)
print(x/y)
```
a) 3, 3, 3.75
b) 3, 3, 3
c) 3.75, 3, 3.75
d) 3.0, 3, 3.75

7. Mantiqiy operatorlar bilan ishlashda qaysi holat noto'g'ri?
```python
x = 5
print(x > 3 and x < 10)
print(x > 3 or x < 4)
print(not(x > 3 and x < 10))
y = 0
```
a) Barcha natijalar mantiqiy qiymat qaytaradi
b) or operatori ikkala shart ham rost bo'lganda True qaytaradi
c) and operatori bitta shart rost bo'lganda True qaytaradi
d) not operatori mantiqiy qiymatni teskarisiga o'zgartiradi

8. Python dasturlash tilida quyidagi kod nima uchun True qaytaradi?
```python
x = ["olma", "banan"]
z = x
print(x is z)
```
a) x va z bir xil qiymatga ega bo'lgani uchun
b) x va z xotiraning bir xil joyiga yo'naltirilgani uchun
c) x va z bir xil uzunlikdagi ro'yxat bo'lgani uchun
d) x va z bir xil elementlarga ega bo'lgani uchun

9. A'zolik operatorlarining ishlash tamoyili to'g'ri ko'rsatilgan javobni toping:
```python
x = ["audi", "bmw", "tesla"]
print("audi" in x)
print("ford" not in x)
y = "tesla"
```
a) in elementi mavjudligini, not in mavjud emasligini tekshiradi
b) in indeksni, not in elementni qidiradi
c) in va not in faqat ro'yxatlar uchun ishlaydi
d) in va not in elementlarni solishtiradi

10. Bitli operatorlar bilan ishlashda qaysi operator bitlarni chapga siljitadi?
a) >>
b) 
c) &
d) |

11. Quyidagi funksiya global o'zgaruvchi bilan qanday ishlaydi?
```python
x = "python"
def test():
    x = "java"
    print("Dasturlash: " + x)
test()
print("Dasturlash: " + x)
```
a) Ikki marta "java" chiqaradi
b) Ikki marta "python" chiqaradi
c) Birinchi "java", keyin "python" chiqaradi
d) Xatolik beradi

12. Pythonda quyidagi kod nima uchun xato beradi?
```python
x = 5
y = "10"
print(x + y)
```
a) O'zgaruvchilar turli tipdagi bo'lgani uchun
b) Qo'shish operatori noto'g'ri ishlatilgani uchun
c) y o'zgaruvchisi qo'shtirnoqda bo'lgani uchun
d) print funksiyasi noto'g'ri ishlatilgani uchun

13. Pythonda bir qatorda bir nechta o'zgaruvchiga qiymat berish qaysi javobda to'g'ri ko'rsatilgan?
a) x = y = z = "Python"
b) x; y; z = "Python"
c) x + y + z = "Python"
d) (x, y, z) = "Python"

14. Quyidagi kodning natijasi nima bo'ladi?
```python
def func():
    global x
    x = "yangi"
    print(x)
x = "eski"
func()
print(x)
```
a) eski, eski
b) yangi, eski
c) yangi, yangi
d) xatolik beradi

15. Python dasturlash tilida qaysi operator eng yuqori prioritetga ega?
a) //
b) **
c) %
d) *

16. Quyidagi kodning natijasi nima?
```python
x = True
y = False
print(not x or y and x)
```
a) True
b) False
c) None
d) Xatolik

17. Bitli operatorlar bilan ishlashda quyidagi ifoda natijasi nima bo'ladi?
```python
x = 5 # (101)
y = 3 # (011)
print(x & y)
```
a) 7
b) 1
c) 2
d) 0

18. Python dasturlash tilida quyidagi kodni bajarishda nima sodir bo'ladi?
```python
x = [1, 2, 3]
y = x
y.append(4)
print(x)
```
a) [1, 2, 3]
b) [1, 2, 3, 4]
c) Xatolik
d) None

19. Quyidagi kodda nechta sintaktik xato bor?
```python
if 5 > 2
print("Besh katta")
    print("Test")
else
    print("Ikki katta")
```
a) 1
b) 2
c) 3
d) 4

20. Quyidagi kodning natijasi nima bo'ladi?
```python
def func():
    x = 1
    def inner():
        nonlocal x
        x = 2
        print(x)
    inner()
    print(x)
x = 0
func()
print(x)
```
a) 2, 2, 0
b) 2, 1, 0
c) 1, 1, 0
d) Xatolik

# 2-BOBDAN SAVOLLAR!

1. Pythonda quyidagi kod natijasi nima bo'ladi?
```python
x = 3+5j
y = 5j
z = -5j
print(type(x))
print(type(y))
print(type(z))
```
A) str, str, str
B) float, float, float  
C) complex, complex, complex
D) int, int, int

2. Quyidagi kodning natijasi nima?
```python
txt = "Olmaxon yerdagi olmani olib ketdi"
x = "ol" in txt
print(x)
y = "ol" not in txt
print(y) 
```
A) True, True
B) False, False
C) True, False 
D) False, True

3. Dictionary metodlaridan qaysi biri lug'atdagi qiymatlarni qaytaradi?
A) dict.keys()
B) dict.items()
C) dict.values()
D) dict.get()

4. Set to'plamida qaysi metod ikkala to'plamda ham mavjud bo'lgan bir xil elementlardan tashqari barcha elementlarni olib yangi to'plam hosil qiladi?
A) issubset()
B) symmetric_difference()
C) intersection()
D) difference()

5. Quyidagi kod natijasi nima bo'ladi?
```python
a = "Python"
print(type(a))
a = 20  
print(type(a))
```
A) <class 'str'>, <class 'str'>
B) <class 'int'>, <class 'int'> 
C) <class 'str'>, <class 'int'>
D) <class 'int'>, <class 'str'>

6. Kortejda (tuple) qanday metodlar mavjud?
A) append(), insert(), remove()
B) add(), update(), remove() 
C) count(), index()
D) sort(), reverse(), clear()

7. Set to'plamida quyidagi kod nima vazifani bajaradi?
```python
x = {"a", "b", "c"}
y = {"l", "c", "a", "o"}
z = x.intersection(y)
```
A) x to'plamdagi barcha elementlarni y to'plamga qo'shadi
B) x va y to'plamlardagi umumiy elementlarni z ga yig'adi
C) x to'plamdagi y to'plamda yo'q elementlarni z ga yig'adi
D) x va y to'plamlardagi farqli elementlarni z ga yig'adi

8. Dictionary da quyidagi kod nima vazifani bajaradi?
```python
avto = {
  "brend": "Chevrolet",
  "model": "Malibu",
  "yil": 2016
}
avto.popitem()
```
A) "brend" kalitli elementni o'chiradi
B) "yil" kalitli elementni o'chiradi
C) Oxirgi kiritilgan elementni o'chiradi
D) Tasodifiy elementni o'chiradi

9. Pythonda quyidagi kod natijasi nima bo'ladi?
```python
x = float(1)     
y = float(2.8)   
z = float("3")   
w = float("4.2")
print(x, y, z, w)
```
A) 1 2.8 3 4.2
B) 1.0 2.8 3.0 4.2
C) Error beradi
D) 1 2 3 4

10. List metodlaridan qaysi biri ro'yxatni teskari tartibda joylashtiradi?
A) sort()
B) reverse()
C) clear()
D) copy()

11. Set to'plamida quyidagi kod natijasi nima bo'ladi?
```python
x = {"a", "b", "c"}
y = {"l", "m", "n"}
z = x.isdisjoint(y)
print(z)
```
A) False
B) True
C) None
D) Error beradi

12. Dictionary da quyidagi kod natijasi nima bo'ladi?
```python
avto = {
  "brend": "Chevrolet",
  "model": "Malibu",
  "yil": 2016
}
x = avto.setdefault("rang", "qora")
print(avto)
```
A) Xatolik beradi
B) {"brend": "Chevrolet", "model": "Malibu", "yil": 2016}
C) {"brend": "Chevrolet", "model": "Malibu", "yil": 2016, "rang": "qora"}
D) None

13. List metodlaridan qaysi biri ro'yxatni saralaydi?
A) reverse()
B) sort()
C) clear()
D) count()

14. Complex sonlar ustida quyidagi amallardan qaysi birini bajarib bo'lmaydi?
A) Qo'shish
B) Ko'paytirish
C) Modda olish
D) Bo'lish

15. Set to'plamida quyidagi kod natijasi nima bo'ladi?
```python
x = {"a", "b", "c"}
y = {"c", "d", "e"}
z = x.difference(y)
print(z)
```
A) {'a', 'b', 'c', 'd', 'e'}
B) {'c'}
C) {'a', 'b'}
D) {'d', 'e'}

16. Dictionary da quyidagi kod natijasi nima bo'ladi?
```python
avto = {
  "brend": "Chevrolet",
  "model": "Malibu",
  "yil": 2016
}
for x, y in avto.items():
    if y == "Malibu":
        print(x)
```
A) Malibu
B) model
C) brend
D) yil

17. Tuple da quyidagi kod natijasi nima bo'ladi?
```python
x = ("kitob",)
y = ("kitob")
print(type(x))
print(type(y))
```
A) tuple, tuple
B) str, str
C) tuple, str
D) list, str

18. Set to'plamida quyidagi kod natijasi nima bo'ladi?
```python
x = {"a", "b", "c"}
y = {"c", "d", "e"}
x.intersection_update(y)
print(x)
```
A) {'a', 'b', 'c', 'd', 'e'}
B) {'c'}
C) {'a', 'b'}
D) {'d', 'e'}

19. Dictionary da quyidagi kod natijasi nima bo'ladi?
```python
avto = {
  "brend": "Chevrolet",
  "model": "Malibu",
  "yil": 2016
}
x = avto.get("rang", "mavjud emas")
print(x)
```
A) None
B) Error beradi
C) "mavjud emas"
D) KeyError

20. List metodlaridan qaysi biri ro'yxatning nusxasini yaratadi?
A) append()
B) extend()
C) copy()
D) clear()

# 3-BOBDAN SAVOLLAR!

1. Quyidagi kodni bajarish natijasida nima hosil bo'ladi?
```python
a = 50
b = 90
if a>b:
    print("HA")
else:
    print("YO'Q")
```
A) HA
B) False
C) YO'Q 
D) True

2. Quyidagi kod nima uchun xato beradi?
```python
a = 50
b = 30
if a>b:
print("HA")
```
A) print() funksiyasi noto'g'ri yozilgan
B) if sharti noto'g'ri
C) o'zgaruvchilar noto'g'ri e'lon qilingan
D) abzatsdan yozilmagan (indentation xatosi)

3. Mantiq operatorlarining qaysi biri "Agar ikkala shart ham rost bo'lsa, rost qiymat qaytaradi" degan vazifani bajaradi?
A) or
B) not
C) and
D) elif

4. Ushbu kodni bajarish natijasi nima bo'ladi?
```python
for x in "dastur":
    if x == "s":
        break
    print(x)
```
A) dastur
B) da
C) dast
D) das

5. Quyidagi kodni bajarish natijasida nima chiqadi?
```python
i = 1
while i < 11:
    i+=1
    if i == 6:
        continue
    print(i)
```
A) 1,2,3,4,5,7,8,9,10
B) 2,3,4,5,7,8,9,10,11
C) 1,2,3,4,5,6,7,8,9,10
D) 2,3,4,5,6,7,8,9,10

6. range() funksiyasining quyidagi ko'rinishi natijasi nima bo'ladi?
```python
for x in range(2, 11, 2):
    print(x)
```
A) 1,3,5,7,9
B) 2,4,6,8
C) 2,4,6,8,10
D) 1,2,3,4,5,6,7,8,9,10

7. bool() funksiyasi qachon False qaytaradi?
A) x="Salom" bo'lganda
B) y=15 bo'lganda
C) z=0 bo'lganda
D) w=["olma"] bo'lganda

8. Quyidagi kodni bajarish natijasi nima bo'ladi?
```python
print(not(5>3 and 5<10))
```
A) True
B) False
C) Error
D) None

9. isinstance() funksiyasi nima vazifani bajaradi?
A) O'zgaruvchini int tipga o'zgartiradi
B) O'zgaruvchi qiymatini tekshiradi
C) O'zgaruvchining ma'lum turga tegishli ekanligini tekshiradi
D) O'zgaruvchini float tipga o'zgartiradi

10. Qanday holatda while sikli tanasi umuman bajarilmaydi?
A) break ishlatilganda
B) continue ishlatilganda
C) else bloki bo'lmaganda
D) shart false bo'lganda

11. For sikli ichida range(5) ishlatilsa, qaysi sonlar ketma-ketligi hosil bo'ladi?
A) 1,2,3,4,5
B) 0,1,2,3,4
C) 1,2,3,4
D) 0,1,2,3,4,5

12. Quyidagi kodni bajarish natijasi nima bo'ladi?
```python
for x in range(1,6):
    if x == 3:
        continue
    print(x)
```
A) 1,2,4,5
B) 1,2,3,4,5
C) 1,2,3
D) 1,2,4

13. range() funksiyasida uchinchi parametr nima vazifani bajaradi?
A) Boshlanғich qiymatni belgilaydi
B) Oxirgi qiymatni belgilaydi
C) Qadam qiymatini belgilaydi
D) Takrorlanishlar sonini belgilaydi

14. Quyidagi kodni bajarish natijasi nima bo'ladi?
```python
meva = ["olma", "anor", "banan"]
for x in meva:
    if x == "anor":
        break
    print(x)
```
A) olma,anor,banan
B) olma
C) anor
D) banan

15. Python mantiq operatorlarida qaysi kombinatsiya True qiymat qaytaradi?
A) False and True
B) False or False
C) True and False
D) True or False

16. Quyidagi kodni bajarish natijasi nima bo'ladi?
```python
def myfunc():
    return False
if myfunc():
    print("rost")
else:
    print("yolg'on")
```
A) rost
B) False
C) yolg'on
D) True

17. For va while sikllari orasidagi asosiy farq nimada?
A) while sikli tezroq ishlaydi
B) for sikli faqat sonlar bilan ishlaydi
C) while siklida shart tekshiriladi, for siklida esa ketma-ketlik bo'ylab yuriladi
D) for sikli cheksiz sikl yarata olmaydi

18. pass operatori qaysi holatda ishlatiladi?
A) Siklni to'xtatish uchun
B) Siklni davom ettirish uchun
C) Bo'sh blokni belgilash uchun
D) Siklni qayta boshlash uchun

19. Quyidagi kodni bajarish natijasi nima bo'ladi?
```python
rang = ["qora", "oq"]
mashina = ["Spark"]
for x in rang:
    for y in mashina:
        print(x,y)
```
A) qora,oq,Spark
B) qora Spark,oq Spark
C) Spark qora,Spark oq
D) qora,Spark

20. Mantiq operatorlari bilan ishlashda quyidagi ifodaning natijasi nima bo'ladi?
```python
a = 5
print(a>3 or a<4)
```
A) True and False
B) False
C) True
D) Error

# 4-BOBDAN SAVOLLAR!

1. Quyidagi funksiya chaqiruvlaridan qaysi biri noto'g'ri yozilgan?
a) my_func = lambda a,b,c: a+b+c
b) def my_func(x): return x*2
c) from math import pi as p
d) import salom from module

2. Math modulidagi qaysi funksiya mantissa va tartibni (m,i) juftligi ko'rinishida qaytaradi, bunda m - o'zgaruvchan nuqtali son, i esa x=m*2**i tenglikdagi butun son bo'ladi?
a) modf() 
b) frexp()
c) ldexp()
d) hypot()

3. Pickle modulida obyektni faylga yozish uchun qaysi funksiya ishlatiladi va bu jarayon qanday nomlanadi?
a) load() - "unpickling"
b) dump() - "pickling" 
c) write() - "saving"
d) save() - "storing"

4. Os modulida kataloglar bo'luvchi qaysi ifoda joriy katalogni bildiradi?
a) os.pardir
b) os.pathsep
c) os.curdir
d) os.altsep

5. Datetime modulida "%W" format kodi nimani bildiradi?
a) Hafta kunini raqam shaklida
b) Yildagi hafta raqami (Yakshanba birinchi kun)
c) Yildagi hafta raqami (Dushanba birinchi kun)
d) Oyning hafta raqami

6. Quyidagi Python operatorlaridan qaysi biri eng yuqori prioritetga ega?
a) **
b) ~x
c) x.attribute
d) lambda

7. Sys modulining qaysi obyekti interpretator ishlaydigan platformani bildiradi?
a) sys.version
b) sys.platform
c) sys.argv
d) sys.path

8. Copy modulida qaysi funksiya obyektlarning butun imkoniyati bilan rekursiv nusxalanishini ta'minlaydi?
a) copy()
b) clone()
c) deepcopy()
d) recursivecopy()

9. Random modulining qaysi funksiyasi normal holatda taqsimlangan ketma-ketlikdan raqamni chiqaradi?
a) randrange()
b) normalvariate()
c) choice()
d) shuffle()

10. Os.access() funksiyasining flags parametrida qaysi bayroq fayldan o'qish mumkinligini tekshiradi?
a) os.F_OK
b) os.W_OK
c) os.R_OK
d) os.X_OK

11. Math modulidagi qaysi funksiya haqiqiy sonning butun qismini qaytaradi?
a) floor()
b) ceil()
c) trunc()
d) int()

12. Datetime obyektining strftime() metodida "%c" format kodi nimani bildiradi?
a) Mahalliy sana
b) Mahalliy vaqt
c) Mahalliy sana va vaqt
d) Universal vaqt

13. Platform modulining system() funksiyasi Windows operatsion tizimida qanday natija qaytaradi?
a) "Win32"
b) "Windows"
c) "Microsoft"
d) "PC"

14. Os modulida qaysi funksiya src fayli yoki katalogini dst deb qayta nomlaydi va dst yo'li uchun kerakli kataloglarni yaratadi?
a) rename()
b) renames()
c) move()
d) replace()

15. Lambda funksiyasi bilan ishlashda qaysi yozuv xato hisoblanadi?
a) x = lambda a,b: a if a>b else b
b) x = lambda a: [i for i in range(a)]
c) x = lambda a,b: {a:b}
d) x = lambda a: print(a) return a

16. Math modulidagi qaysi funksiya berilgan sonning natural logarifmini qaytaradi?
a) log2()
b) log10()
c) log()
d) ln()

17. Os.environ obyekti qanday ma'lumotlarni o'z ichiga oladi?
a) Operatsion tizim sozlamalari
b) Tizim o'zgaruvchilari
c) Joriy katalog yo'li
d) Fayl ruxsatlari

18. Random modulining seed() funksiyasi qanday vazifani bajaradi?
a) Tasodifiy sonlar generatorini boshlang'ich holatga keltiradi
b) Tasodifiy sonlar ketma-ketligini saqlaydi
c) Tasodifiy sonlar diapazonini belgilaydi
d) Tasodifiy sonlar generatorini to'xtatadi

19. Pythonda modullarni import qilishning qaysi usuli noto'g'ri?
a) import math as m
b) from math import *
c) from math import sqrt, pi
d) import math.sqrt

20. Datetime modulida sanani belgilashda qaysi format xato hisoblanadi?
a) datetime(2024, 12, 31)
b) datetime(2024, 12, 31, 23, 59, 59)
c) datetime(24, 12, 31)
d) datetime(2024/12/31)

# 5-BOBDAN SAVOLLAR!

1. Pythonda "E:\projects\data.txt" faylini o'chirish uchun qaysi kod to'g'ri yozilgan?
a) os.delete("E:\projects\data.txt")
b) remove.file("E:\projects\data.txt") 
c) import os
   os.remove("E:\projects\data.txt")
d) delete.file("E:\projects\data.txt")

2. Qaysi kod ketma-ketligi faylni to'g'ri o'qib, yopadi?
a) f = read("test.txt")
   f.close()
b) f = open("test.txt", "r")
   f.read()
   close()
c) f = open("test.txt", "r")
   print(f.read())
   f.close()
d) f = open("test.txt")
   f.readline()
   close(f)

3. try-except bloklari bilan ishlashda finally bloki qachon ishga tushadi?
a) Faqat xatolik yuzaga kelganda
b) Faqat else bloki ishlagandan so'ng
c) Xatolik bo'lsa ham, bo'lmasa ham
d) except bloki ishlamagan holda

4. Fayl mavjudligini tekshirib, mavjud bo'lmasa yangi fayl yaratish uchun qaysi rejim to'g'ri?
a) "r+"
b) "w"
c) "rb"
d) "x"

5. Quyidagi kodda nima xatolik yuz beradi?
```python
f = open("test.txt", "r")
f.write("Yangi matn")
```
a) SyntaxError
b) FileNotFoundError
c) IOError
d) UnsupportedOperation

6. os.path.exists() funksiyasi noto'g'ri natija qaytarishi mumkin bo'lgan holat qaysi?
a) Fayl mavjud bo'lmaganda
b) Fayl ochiq bo'lganda
c) Faylga yozish huquqi bo'lmaganda
d) Race condition holatida tekshirilganda

7. Quyidagi kod nima uchun ishlatiladi?
```python
with open("file.txt", "r") as f:
    data = f.read()
```
a) Faylni avtomatik yopish uchun
b) Faylni faqat o'qish uchun
c) Faylni xavfsiz o'chirish uchun
d) Fayl mavjudligini tekshirish uchun

8. ValueError istisnosi qachon yuzaga keladi?
a) Fayl topilmaganda
b) Raqamni nolga bo'lganda
c) String tipidagi qiymatni integerga o'tkazishda xatolik bo'lganda
d) Fayl yopilmaganda

9. Faylga ma'lumot qo'shish uchun qaysi rejim to'g'ri?
a) "w"
b) "r+"
c) "a"
d) "x"

10. Quyidagi kodni bajarishda nima yuz beradi?
```python
try:
    print(1/0)
except ZeroDivisionError:
    print("Xato")
else:
    print("OK")
finally:
    print("Tugadi")
```
a) Xato
   OK
   Tugadi
b) Xato
   Tugadi
c) OK
   Tugadi
d) Tugadi

11. Binary fayllar bilan ishlash uchun qaysi rejim to'g'ri?
a) "rb"
b) "b"
c) "wb+"
d) "binary"

12. raise Exception() operatori nima uchun ishlatiladi?
a) Xatolikni to'g'rilash uchun
b) Dasturni to'xtatish uchun
c) O'z xatoligimizni yaratish uchun
d) Xatolikni e'tiborsiz qoldirish uchun

13. Faylni o'qish rejimida ochganda qaysi metod mavjud emas?
a) read()
b) readline()
c) write()
d) readlines()

14. TypeError istisnosi qachon yuzaga keladi?
a) Fayl topilmaganda
b) Nolga bo'lganda
c) O'zgaruvchi e'lon qilinmaganda
d) String va integer ustida arifmetik amal bajarganda

15. Papkani o'chirish uchun qaysi funksiya ishlatiladi?
a) os.removedir()
b) os.deletedir()
c) os.rmdir()
d) os.delete()

16. input() funksiyasi qanday tip qiymat qaytaradi?
a) int
b) str
c) float
d) bool

17. Faylni "w" rejimida ochish natijasida nima bo'ladi?
a) Fayl o'chiriladi va qayta yaratiladi
b) Fayl oxiridan yozish boshlanadi
c) Fayl boshi dan yozish boshlanadi, avvalgi matn saqlanadi
d) Fayl faqat o'qish uchun ochiladi

18. finally blokida return operatori ishlatilsa nima bo'ladi?
a) Funksiya to'xtaydi
b) Xatolik yuz beradi
c) except bloki ishga tushadi
d) else bloki ishga tushadi

19. Quyidagi kodni bajarish natijasi nima?
```python
x = "abc"
if type(x) is not int:
    raise TypeError("Butun son emas")
```
a) SyntaxError
b) TypeError: Butun son emas
c) ValueError
d) Kod xatosiz ishlaydi

20. os.path.exists() funksiyasi nima qaytaradi?
a) String
b) Integer
c) Boolean
d) None

# 6-BOBDAN SAVOLLAR!

1. Qaysi kod to'g'ri natija beradi?
A) 
```python
class Son:
   def __init__(x, y):
      x.y = y
   def tanish():
      print(x.y)
```
B) 
```python
class Son:
   def __init__(self, y):
      y.self = y 
   def tanish(self):
      print(self.y)
```
C) 
```python
class Son:
   def __init__(self, y):
      self.y = y
   def tanish(self):
      print(self.y)  
```
D) 
```python
class Son:
   def __init__(self, y):
      self = y
   def tanish():
      print(y)
```

2. Vorislik bo'yicha qaysi kod xato?
A)
```python
class Odam:
    def __init__(self, ism):
        self.ism = ism
        
class Talaba(Odam):
    def __init__(self, ism):
        super().__init__(ism)
```
B)
```python 
class Odam:
    def __init__(self, ism):
        self.ism = ism
        
class Talaba(Odam):
    def __init__(self, ism):
        Odam.__init__(ism)
```
C)
```python
class Odam:
    def __init__(self, ism):
        self.ism = ism
        
class Talaba(Odam):
    def __init__(self, ism):
        Odam.__init__(self, ism)
```
D)
```python
class Odam:
    def __init__(self, ism):
        self.ism = ism
        
class Talaba(Odam):
    pass
```

3. Konstruktor yaratishda qaysi qator xato?
A) Konstruktorlar ikki xil bo'ladi: parametrlangan va parametrlanmagan
B) __init__ metodi konstruktorni simulyatsiya qiladi
C) Har bir sinf konstruktorga ega bo'lishi shart
D) Python-da __init__ funksiyasi har doim parametrsiz bo'lishi kerak

4. Python OOP ning asosiy tamoyillarini ko'rsating
A) Abstraksiya, Inkapsulyatsiya, Polimorfizm, Vorislik
B) Abstraksiya, Modullik, Vorislik, Polimorfizm 
C) Inkapsulyatsiya, Modullik, Abstraksiya, Interfeys
D) Vorislik, Interfeys, Abstraksiya, Inkapsulyatsiya

5. Pythonda obyektni o'chirish to'g'ri ko'rsatilgan qatorni belgilang
A) remove p1
B) p1.delete()
C) del p1
D) delete p1

6. Quyidagi kodning natijasi nima bo'ladi?
```python
class Student:
    count = 0
    def __init__(self):
        Student.count = Student.count + 1
        
s1=Student()
s2=Student() 
print(Student.count)
```
A) 0
B) 1  
C) 2
D) Error

7. Qaysi metod obyekt atributini o'zgartirish uchun ishlatiladi?
A) getattr()
B) setattr()
C) hasattr()
D) delattr()

8. Quyidagi kodda xatolik mavjud qatorni toping:
```python
class Employee:
    def __init__(self,name,id):
        self.id = id
        self.name = name
    
    def display(self):
        print("ID: %d \nName: %s"%(self.id,self.name))

emp1 = Employee()
emp1.display()
```
A) display() metodida 
B) print() funksiyasida
C) konstruktorda parametrlar berilgan
D) obyekt yaratishda parametrlar berilmagan

9. O'rnatilgan sinf atributlari bo'yicha qaysi javob noto'g'ri?
A) __dict__ - sinf nomlari maydoni haqidagi ma'lumotli lug'at
B) __doc__ - sinf hujjatiga ega qator
C) __init__ - sinfning asosiy metodlarini saqlaydi
D) __name__ - sinf nomiga kirish uchun ishlatiladi

10. Vorislikda super() funksiyasi vazifasi nima?
A) Yangi xususiyatlar qo'shish
B) Ota-sinf metodlarini o'chirish
C) Ota-sinf xususiyat va metodlarini voris-sinfga o'tkazish
D) Voris-sinf metodlarini ota-sinfga o'tkazish

11. Abstraksiya va inkapsulyatsiya o'rtasidagi farq nima?
A) Abstraksiya kodlarni yashiradi, inkapsulyatsiya ma'lumotlarni
B) Inkapsulyatsiya kodlarni yashiradi, abstraksiya ma'lumotlarni
C) Ikkalasi ham bir xil vazifani bajaradi
D) Ikkalasi bir-biriga bog'liq emas

12. Obyektga yo'naltirilgan dasturlashning protsedurali dasturlashdan asosiy farqi nimada?
A) OOP murakkab, protsedurali oddiy
B) OOP xavfsiz, protsedurali xavfli
C) OOP real dunyoni modellashtiradi, protsedurali bosqichma-bosqich bajaradi
D) OOP tez ishlaydi, protsedurali sekin

13. self parametri haqida qaysi fikr to'g'ri?
A) self o'rniga faqat abc yozish mumkin
B) self parametri ixtiyoriy
C) self birinchi parametr bo'lishi shart
D) self faqat __init__ da ishlatiladi

14. Quyidagi kodni bajarilish natijasini toping:
```python
class Test:
    x = 0
    def __init__(self):
        Test.x += 1
    
    def __del__(self):
        Test.x -= 1
        
t1 = Test()
t2 = Test()
del t1
print(Test.x)
```
A) 0
B) 1
C) 2
D) Error

15. Polimorfizm qaysi holatda to'g'ri qo'llanilgan?
A) 
```python
class Animal:
    def speak(self):
        pass
        
class Dog(Animal):
    def speak(self):
        return "Woof!"
```
B)
```python
class Animal:
    def speak(self):
        return "Sound"
        
class Dog(Animal):
    speak = "Woof!"
```
C)
```python
class Animal:
    speak = "Sound"
        
class Dog(Animal):
    def speak(self):
        return "Woof!"
```
D)
```python
class Animal:
    def speak(self):
        return "Sound"
        
class Dog:
    def speak(self):
        return "Woof!"
```

16. Pythonda private o'zgaruvchilar qanday e'lon qilinadi?
A) _variable
B) __variable
C) __variable__
D) private variable

17. Qaysi holat multiple inheritance (ko'p vorislik) ni to'g'ri ko'rsatadi?
A) class C(A, B)
B) class C(A + B)
C) class C(A): class C(B)
D) class C(A && B)

18. Quyidagi kodning natijasi nima?
```python
class A:
    def __init__(self):
        self.x = 1
    def method(self):
        self.x = 10
        
class B(A):
    def __init__(self):
        super().__init__()
        self.x = 2
    
obj = B()
print(obj.x)
```
A) 1
B) 2
C) 10
D) Error

19. Pythonda property decoratorning vazifasi nima?
A) Metodni xususiyatga aylantiradi
B) Xususiyatni metodga aylantiradi
C) Xususiyatni yashiradi
D) Metodni yashiradi

20. Quyidagi kodni bajarish natijasi qanday bo'ladi?
```python
class Counter:
    def __init__(self):
        self.__count = 0
    def increment(self):
        self.__count += 1
    def value(self):
        return self.__count
        
c = Counter()
c.__count = 5
print(c.value())
```
A) 5
B) 1
C) 0
D) Error
