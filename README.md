# Python Yopiq Test (75 savol)

---

## 1. List tushunchasi

**1.** Python'da list qanday xususiyatga ega?

**2.** Quyidagilardan qaysi biri to'g'ri list?

**3.** List elementlari qanday tartibda saqlanadi?

**4.** Bo'sh list qanday yaratiladi?

**5.** Listda bir xil qiymat necha marta bo'lishi mumkin?

---

## 2. List yaratish usullari

**6.** `list()` funksiyasi yordamida qaysi ifodadan list yaratiladi?

**7.** `[x*2 for x in range(3)]` natijasi nima?

**8.** `range(5)` dan list yaratishning to'g'ri usuli qaysi?

**9.** `[0]*4` ifodasi qanday natija beradi?

**10.** Mavjud listdan yangi list nusxa olishning to'g'ri usuli qaysi?

---

## 3. List elementlariga murojaat qilish

**11.** `a = [10, 20, 30]` bo'lsa, `a[1]` qiymati nima?

**12.** `a = [5, 6, 7, 8]` bo'lsa, `a[-1]` qiymati nima?

**13.** `a = [1, 2, 3, 4, 5]` bo'lsa, `a[1:3]` qiymati nima?

**14.** `a = ['x', 'y', 'z']` bo'lsa, `a[0] = 'w'` bajarilsa list qanday bo'ladi?

**15.** `a = [[1,2],[3,4]]` bo'lsa, `a[1][0]` qiymati nima?

---

## 4. List metodlari (append, insert, remove, pop)

**16.** `append()` metodi nima qiladi?

**17.** `a.insert(1, 'x')` — bu nima qiladi?

**18.** `remove()` va `pop()` farqi nima?

**19.** `a.pop()` qo'shimcha argument berilmasa nima qiladi?

**20.** `a = [3, 1, 2]; a.sort()` bajarilganda `a` qanday bo'ladi?

---

## 5. List bilan ishlash (len, in, for)

**21.** `len([1, 2, 3, 4])` qiymati nima?

**22.** `3 in [1, 2, 3]` ifodasi qanday natija beradi?

**23.** `for x in [10, 20, 30]: print(x)` nima chiqaradi?

**24.** `5 not in [1, 2, 3]` qiymati nima?

**25.** `sum([1, 2, 3])` qiymati nima?

---

## 6. Tuple (o'zgarmas ro'yxat)

**26.** Tuple listdan asosiy farqi nima?

**27.** Tuple qanday belgi bilan yaratiladi?

**28.** `t = (5,)` — bu nima?

**29.** Tuple elementiga murojaat qilish mumkinmi?

**30.** Tuple qachon ishlatiladi?

---

## 7. Tuple yaratish va ishlatish

**31.** `tuple([1, 2, 3])` natijasi nima?

**32.** `a, b = (10, 20)` — `b` qiymati nima?

**33.** `t = (1, 2, 3); t[1] = 9` bajarilsa nima bo'ladi?

**34.** `len((4, 5, 6, 7))` qiymati nima?

**35.** `2 in (1, 2, 3)` qiymati nima?

---

## 8. Tuple va List farqi

**36.** Qaysi tuzilma o'zgartirilishi mumkin?

**37.** Dictionary kaliti sifatida nima ishlatilishi mumkin?

**38.** Tuple listga nisbatan qaysi jihatdan afzal?

**39.** List va Tuple ikkalasidaligida mavjud bo'lgan metod qaysi?

**40.** Funksiya bir nechta qiymat qaytarganda odatda qaysi tuzilma ishlatiladi?

---

## 9. Dictionary (lug'at) tushunchasi

**41.** Dictionary qanday tuzilmada ma'lumot saqlaydi?

**42.** Dictionary kalitlari takrorlanishi mumkinmi?

**43.** Qaysi tuzilma `{}` bilan yaratiladi?

**44.** `d = {'a': 1}` bo'lsa, `d['a']` qiymati nima?

**45.** Dictionary qaysi versiyadan boshlab kiritilish tartibini saqlaydi?

---

## 10. Dictionary yaratish usullari

**46.** `dict(name='Ali', age=20)` qanday natija beradi?

**47.** Bo'sh dictionary qanday yaratiladi?

**48.** `d = {x: x**2 for x in range(3)}` — `d` qanday bo'ladi?

**49.** Mavjud dict ga yangi kalit-qiymat qo'shishning to'g'ri usuli qaysi?

**50.** `d.update({'b': 2})` nima qiladi?

---

## 11. Dictionary metodlari (keys, values, items)

**51.** `d.keys()` nima qaytaradi?

**52.** `d.values()` nima qaytaradi?

**53.** `d.items()` nima qaytaradi?

**54.** `d.get('y', 0)` — `'y'` kaliti yo'q bo'lsa nima qaytaradi?

**55.** `d.pop('a')` nima qiladi?

---

## 12. Funksiya nima

**56.** Funksiyaning asosiy maqsadi nima?

**57.** Python'da funksiya yaratish uchun qaysi kalit so'z ishlatiladi?

**58.** Funksiya chaqirish uchun nima yoziladi?

**59.** Funksiya parametri va argumenti farqi nima?

**60.** Funksiya ichida e'lon qilingan o'zgaruvchi qaysi doirada (scope) bo'ladi?

---

## 13. Funksiya yaratish (`def`)

**61.** To'g'ri funksiya ta'rifi qaysi?

**62.** Funksiya tanasi qanday ajratiladi?

**63.** Hech narsa qilmaydigan funksiya tanasiga nima yoziladi?

**64.** Lambda funksiya nima?

**65.** Funksiya nomi qanday yozilishi tavsiya etiladi?

---

## 14. Funksiyaga argument berish

**66.** Default argument nima?

**67.** `def f(a, b=5):` bo'lsa, `f(3)` chaqirilganda `b` qiymati nima?

**68.** `*args` nima uchun ishlatiladi?

**69.** `**kwargs` nima qaytaradi?

**70.** `f(b=2, a=1)` — bu qanday argument berish usuli?

---

## 15. Return bilan va returnsiz funksiyalar

**71.** `return` ko'rsatmasisiz funksiya nima qaytaradi?

**72.** `return` bir nechta qiymat qaytara oladimi?

**73.** `return` bajarilgandan so'ng funksiya nima qiladi?

**74.** Qaysi funksiya turi yon ta'sir (side effect) uchun ishlatiladi?

**75.** `def f(): return 1, 2, 3` — `f()` qiymati nima?
