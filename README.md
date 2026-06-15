# CSS Border Practice 🎨

Ushbu kichik loyiha HTML elementlariga CSS orqali turli xil chegaralar (**border**) berish, ularning qalinligi, uslubi va ranglarini boshqarishni o'rganish hamda amaliyotda qo'llash uchun yaratilgan.

## ✨ O'rganilgan asosiy xossalar (Features)

Loyiha davomida CSS-ning quyidagi border xossalari mukammal o'rganildi va qo'llanildi:

* **`border-width`** — Chegaraning qalinligini belgilash (`px`, `em` yoki `rem` o'lchov birliklarida).
* **`border-style`** — Chegara chizig'ining ko'rinishi:
    * `solid` (tekis chiziq)
    * `dashed` (shtrixli chiziq)
    * `dotted` (nuqtalardan iborat chiziq)
    * `double` (qo'sh chiziq)
* **`border-color`** — Chegaraning rangi (nomi, HEX, RGB yoki HSL formatida).
* **`border-radius`** — Element burchaklarini yumaloq qilish (aylana yoki silliq burchaklar yaratish uchun).
* **Shorthand (Qisqa yozuv):** Uchala xossani bir qatorda yozish (`border: 2px solid red;`).

## 💻 CSS Kodidan namuna (Code Snippet)

Loyihada ishlatilgan asosiy CSS qoidalari:

```css
/* Oddiy tekis chegara va burchaklarni yumaloq qilish */
.box-solid {
    border: 3px solid #3498db;
    border-radius: 10px;
    padding: 20px;
}

/* Shtrixli (chiziqli) chegara */
.box-dashed {
    border-width: 2px;
    border-style: dashed;
    border-color: #e74c3c;
}

/* Faqat bitta tomonga (masalan, pastga) chegara berish */
.text-underline {
    border-bottom: 4px solid #2ecc71;
    padding-bottom: 5px;
}
