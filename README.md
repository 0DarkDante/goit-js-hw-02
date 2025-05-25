# 📘 Домашнє завдання №2 — _Основи JavaScript_

## ✅ Опис

Це домашнє завдання включає **4 задачі**, які допомагають закріпити:

- _арифметичні операції_
- _умовні конструкції_ `if...else` та `switch`
- _логічні оператори_
- _роботу з рядками_
- _написання функцій_

---

## 📁 Структура проєкту

/js-hw-2
├── index.html
└── js
├── task-1.js // Транзакція
├── task-2.js // Форматування повідомлення
├── task-3.js // Перевірка на спам
└── task-4.js // Вартість доставки

---

## 🧠 Задачі

### 🔹 **Задача 1 — `makeTransaction()`**

Розрахунок вартості замовлення і перевірка, чи вистачає кредитів користувачу.

_Вивід:_  
`You ordered <n> droids worth <total> credits!`  
або  
`Insufficient funds!`

---

### 🔹 **Задача 2 — `formatMessage()`**

Якщо повідомлення довше за `maxLength`, обрізається і додається `...`.

_Приклад:_  
`formatMessage("Hello JavaScript", 10)` → `"Hello Java..."`

---

### 🔹 **Задача 3 — `checkForSpam()`**

Перевірка повідомлення на вміст `spam` або `sale`.  
Порівняння без врахування регістру (`toLowerCase()`).

_Приклад:_  
`checkForSpam("Get SALE now!")` → `true`

---

### 🔹 **Задача 4 — `getShippingCost()`**

Використовує `switch` для визначення вартості доставки.

**Доступні країни:**

| Country   | Price |
| --------- | ----- |
| China     | 100   |
| Chile     | 250   |
| Australia | 170   |
| Jamaica   | 120   |

_Результат:_

- `Shipping to <country> will cost <price> credits`
- або `Sorry, there is no delivery to your country`

---

## 🚀 Запуск

Відкрий `index.html` у браузері (рекомендується через Live Server).  
Усі скрипти підключено:

```html
<script src="js/task-1.js"></script>
<script src="js/task-2.js"></script>
<script src="js/task-3.js"></script>
<script src="js/task-4.js"></script>
```
