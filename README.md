# Spring-course
## Функціональні вимоги

### Ролі користувачів і дії
1. **Адміністратор:**
   - Управління маршрутами, зупинками, транспортними засобами та розкладами.
   - Призначення транспортних засобів на маршрути.
   - Управління асоціаціями маршрут-зупинка.

2. **Водій:**
   - Перегляд призначених маршрутів і розкладів.
   - Оновлення статусу транспортного засобу.

3. **Пасажир:**
   - Перегляд доступних маршрутів і розкладів.
   - Пошук зупинок за місцезнаходженням.
   - Відстеження транспортних засобів у реальному часі.

### Основні функції
1. **Управління маршрутами:**
   - Створення, оновлення та видалення маршрутів.
   - Перегляд деталей маршрутів, включаючи асоційовані зупинки та розклади.

2. **Управління зупинками:**
   - Створення, оновлення та видалення зупинок.
   - Перегляд деталей зупинок, включаючи асоційовані маршрути.

3. **Управління транспортними засобами:**
   - Створення, оновлення та видалення транспортних засобів.
   - Перегляд деталей транспортних засобів, включаючи призначені маршрути та розклади.

4. **Управління розкладами:**
   - Створення, оновлення та видалення розкладів.
   - Перегляд деталей розкладів, включаючи асоційовані маршрути та транспортні засоби.

5. **Асоціація маршрут-зупинка:**
   - Додавання або видалення зупинок з маршрутів.
   - Перегляд зупинок, асоційованих з маршрутом.

6. **Взаємодія з користувачами:**
   - Пасажири можуть шукати маршрути та зупинки.
   - Водії можуть оновлювати статус свого транспортного засобу.

## Макети

### Панель приладів
- **Панель адміністратора:**
  - Огляд маршрутів, зупинок, транспортних засобів та розкладів.
  - Швидкі посилання для управління об'єктами.

- **Панель водія:**
  - Перегляд призначених маршрутів.
  - Оновлення статусу транспортного засобу.

- **Панель пасажира:**
  - Пошук маршрутів і зупинок.
  - Перегляд розкладів і відстеження транспортних засобів.

### Управління маршрутами
- **Перегляд списку маршрутів:**
  - Відображення всіх маршрутів з можливістю додати, редагувати або видалити маршрути.
  - Параметри пошуку та фільтрації.

- **Перегляд деталей маршруту:**
  - Відображення детальної інформації про обраний маршрут.
  - Список асоційованих зупинок і розкладів.
  - Можливості додавання або видалення зупинок з маршруту.

### Управління зупинками
- **Перегляд списку зупинок:**
  - Відображення всіх зупинок з можливістю додати, редагувати або видалити зупинки.
  - Параметри пошуку та фільтрації.

- **Перегляд деталей зупинки:**
  - Відображення детальної інформації про обрану зупинку.
  - Список асоційованих маршрутів.

### Управління транспортними засобами
- **Перегляд списку транспортних засобів:**
  - Відображення всіх транспортних засобів з можливістю додати, редагувати або видалити транспортні засоби.
  - Параметри пошуку та фільтрації.

- **Перегляд деталей транспортного засобу:**
  - Відображення детальної інформації про обраний транспортний засіб.
  - Список призначених маршрутів і розкладів.

### Управління розкладами
- **Перегляд списку розкладів:**
  - Відображення всіх розкладів з можливістю додати, редагувати або видалити розклади.
  - Параметри пошуку та фільтрації.

- **Перегляд деталей розкладу:**
  - Відображення детальної інформації про обраний розклад.
  - Список асоційованих маршрутів і транспортних засобів.

## Поведінка системи

### Управління маршрутами
- **Створення маршруту:**
  - Система перевіряє та зберігає інформацію про маршрут.
  - Адміністратор може додавати зупинки до маршруту.

- **Оновлення маршруту:**
  - Система перевіряє та оновлює інформацію про маршрут.
  - Адміністратор може змінювати список зупинок, асоційованих з маршрутом.

- **Видалення маршруту:**
  - Система перевіряє наявність залежностей (наприклад, розкладів) перед видаленням.
  - Адміністратор може видалити маршрут.

### Управління зупинками
- **Створення зупинки:**
  - Система перевіряє та зберігає інформацію про зупинку.
  - Адміністратор може асоціювати зупинку з декількома маршрутами.

- **Оновлення зупинки:**
  - Система перевіряє та оновлює інформацію про зупинку.
  - Адміністратор може змінювати список маршрутів, асоційованих з зупинкою.

- **Видалення зупинки:**
  - Система перевіряє наявність залежностей (наприклад, маршрутів) перед видаленням.
  - Адміністратор може видалити зупинку.

### Управління транспортними засобами
- **Створення транспортного засобу:**
  - Система перевіряє та зберігає інформацію про транспортний засіб.
  - Адміністратор може призначити транспортний засіб на маршрути.

- **Оновлення транспортного засобу:**
  - Система перевіряє та оновлює інформацію про транспортний засіб.
  - Адміністратор може змінювати маршрути, призначені транспортному засобу.

- **Видалення транспортного засобу:**
  - Система перевіряє наявність залежностей (наприклад, розкладів) перед видаленням.
  - Адміністратор може видалити транспортний засіб.

### Управління розкладами
- **Створення розкладу:**
  - Система перевіряє та зберігає інформацію про розклад.
  - Адміністратор може призначити розклад на маршрути та транспортні засоби.

- **Оновлення розкладу:**
  - Система перевіряє та оновлює інформацію про розклад.
  - Адміністратор може змінювати маршрути та транспортні засоби, призначені на розклад.

- **Видалення розкладу:**
  - Система перевіряє наявність залежностей (наприклад, маршрутів, транспортних засобів) перед видаленням.
  - Адміністратор може видалити розклад.

## REST API кінцеві точки

### Кінцеві точки маршруту
- **GET /routes:** Отримати список всіх маршрутів.
- **POST /routes:** Створити новий маршрут.
- **GET /routes/{id}:** Отримати деталі конкретного маршруту.
- **PUT /routes/{id}:** Оновити конкретний маршрут.
- **DELETE /routes/{id}:** Видалити конкретний маршрут.

### Кінцеві точки зупинки
- **GET /stops:** Отримати список всіх зупинок.
- **POST /stops:** Створити нову зупинку.
- **GET /stops/{id}:** Отримати деталі конкретної зупинки.
- **PUT /stops/{id}:** Оновити конкретну зупинку.
- **DELETE /stops/{id}:** Видалити конкретну зупинку.

### Кінцеві точки транспортного засобу
- **GET /vehicles:** Отримати список всіх транспортних засобів.
- **POST /vehicles:** Створити новий транспортний засіб.
- **GET /vehicles/{id}:** Отримати деталі конкретного транспортного засобу.
- **PUT /vehicles/{id}:** Оновити конкретний транспортний засіб.
- **DELETE /

vehicles/{id}:** Видалити конкретний транспортний засіб.

### Кінцеві точки розкладу
- **GET /schedules:** Отримати список всіх розкладів.
- **POST /schedules:** Створити новий розклад.
- **GET /schedules/{id}:** Отримати деталі конкретного розкладу.
- **PUT /schedules/{id}:** Оновити конкретний розклад.
- **DELETE /schedules/{id}:** Видалити конкретний розклад.

### Кінцеві точки асоціації маршрут-зупинка
- **POST /routes/{routeId}/stops/{stopId}:** Додати зупинку до маршруту.
- **DELETE /routes/{routeId}/stops/{stopId}:** Видалити зупинку з маршруту.

### Кінцеві точки взаємодії з користувачами
- **GET /routes/search:** Пошук маршрутів за критеріями (наприклад, ім'я, номер).
- **GET /stops/search:** Пошук зупинок за критеріями (наприклад, ім'я, місцезнаходження).
- **GET /vehicles/{vehicleId}/status:** Отримати статус конкретного транспортного засобу.
- **PUT /vehicles/{vehicleId}/status:** Оновити статус конкретного транспортного засобу.
