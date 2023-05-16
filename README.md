# FinanceAPI
___
## Ідея:

### Розробити систему розрахунку бюджету учасника або групи учасників з метою аналізу витрат зароблених коштів.

## Мета:

### Допомогти користувачу або групі користувачів завдяки системі вести облік зароблених грошей та правильно розпоряджатися коштами.

___
![](https://github.com/stupns/FinanceAPI/blob/main/Documentation/drawio.png)

## Основні розділи системи:

- Індивідуальна сторінка
- Групова сторінка

Індивідуальна сторінка:

- Баланс
- Дата останньої транзакції
- Витрати на послуги
- Залишок коштів після оплати послуг
- Заощадження (20% від залишку коштів)
- Порівняння профіту за певний період
- Планові покупки
- Транзакція

Групова сторінка:

- Назва групи
- Список учасників
- Заробіток за період
(сумується з заробітком учасника за певний період)
- Спільні групові витрати на послуги
- Баланс 
(Активний баланс групи, можна зробити галочку щоб не враховувати кошти що є індивідуальним заощадженням)
- Заощадження (20% від залишку коштів групи)
- Порівняння профіту за певний період
- Планові покупки групи
- Групова транзакція

## Додаткові розділи:


Користувач:

- Ім'я користувача
- Прізвище
- Рік народження
- Email
- Група ("індивідуальна" або "групова")
- Баланс

Послуга:

- Ім'я послуги
- Пріоритет ("обов'язкове" або "необов'язкове")
- Група ("індивідуальна" або "групова")
- Вартість послуги
- Щомісячне списання
- Транзакція

Планова покупка:

- Назва покупки
- Опис покупки
- Дата створення заявки
- Спільність (індивідуальна або групова)
- Вартість покупки
- Статус
- Транзакція

Транзакція:
- Додавання коштів
- Зняття коштів
- Здійснення оплати

Витрати(додатково):
- Інформація про щомісячні витрати окремого користувача (вибір)
- Інформація про місячні витрати групи



