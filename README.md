📚 Student Performance EDA

📌 Loyiha tavsifi

Ushbu loyiha **talabalar akademik ko‘rsatkichlari** bo‘yicha **Exploratory Data Analysis (EDA)** ga bag‘ishlangan. Ma’lumotlar orqali talabalar natijalariga ta’sir qiluvchi ijtimoiy va ta’limiy omillar tahlil qilinadi.

Dataset **1000 nafar talaba** haqidagi ma’lumotlarni o‘z ichiga oladi.

---

🎯 Tadqiqot maqsadi

Talabalarning **math, reading va writing** fanlari bo‘yicha natijalariga ta’sir qiluvchi asosiy omillarni aniqlash.

---

📊 Ma’lumotlar tavsifi

Kuzatuvlar soni: **1000**
Belgilar soni: **9**

| Ustun                       | Tavsif                           | Tip    |
| --------------------------- | -------------------------------- | ------ |
| gender                      | Talabaning jinsi                 | object |
| race/ethnicity              | Millati / etnik guruhi           | object |
| parental level of education | Ota-onaning ta’lim darajasi      | object |
| lunch                       | Tushlik turi                     | object |
| test preparation course     | Tayyorlov kursida qatnashganligi | object |
| math score                  | Matematika bali                  | int    |
| reading score               | O‘qish bali                      | int    |
| writing score               | Yozish bali                      | int    |
| Total Score                 | Umumiy ball                      | int    |

---

🧠 Tekshirilgan gipotezalar

1. **Ota-onasining ta’lim darajasi**
   Ota-onasi oliy yoki yuqori ma’lumotli bo‘lgan talabalar yaxshiroq natija ko‘rsatadi. ✅

2. **Millat (ethnicity) omili**
   Ayrim etnik guruhlarga mansub talabalar yuqori natija ko‘rsatadi degan gipoteza tasdiqlanmadi. ❌

3. **Tushlik turi (lunch)**
   Standard lunch iste’mol qilgan talabalar yuqoriroq ball oladi degan gipoteza tasdiqlanmadi. ❌

4. **Jins omili**
   Qizlar umumiy hisobda yuqoriroq natija ko‘rsatadi. ✅

5. **Test preparation course**
   Tayyorlov kurslarida qatnashgan talabalar sezilarli darajada yaxshiroq natija ko‘rsatadi. ✅

---

🛠 Foydalanilgan texnologiyalar

* Python
* pandas
* Jupyter Notebook

---

📈 Analiz bosqichlari

* Ma’lumotlarni dastlabki ko‘rib chiqish (`info`, `describe`)
* Kategoriyali va sonli ustunlarni tahlil qilish
* Gipotezalarni tekshirish
* Yakuniy xulosalar chiqarish

---

✅ Xulosalar

Tahlil natijalariga ko‘ra, talabalar natijalariga eng kuchli ta’sir qiluvchi omillar **ota-onaning ta’lim darajasi**, **jins** va **test preparation course** ekanligi aniqlandi.

👤 Muallif

Loyiha Data Science yo‘nalishida bilim va portfelni mustahkamlash maqsadida bajarilgan.
