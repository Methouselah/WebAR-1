## Проста обробка текстових даних засобами оболонки Unix-подібних ОС інтерпретора команд ОС
### 2.1 Документування рішень завдань лабораторної роботи
2.1.1 Особливості підготовки до процесу документування рішень
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/1.JPG)

2.1.2 Особливості проведення процесу документування рішень
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/2.JPG)
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/3.JPG)

### 2.2 Навігація по файловій системі через засоби оболонки Git Bash інтерпретатору командного рядку Bash
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/4.JPG)
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/5.JPG)

### 2.3 Налаштування псевдонімів команд оболонки Bash
2.3.1 Виконати команду зі створення псевдоніму виклику команди, пов’язаною з Bash
командою у відповідності з таблицею 4. Перевірити роботу псевдоніму команди.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/6.JPG)

2.3.2 Виконати команду зі створення псевдоніму виклику команди, яка буде надавати
поточну дату лише із поточним днем, місяцем та роком. Назва псевдоніму визначається за шаблоном: «дата_» + «дія», де «дія» - значення синоніму команди з таблиці 4, наприклад, «дата_зібрати». При описі псевдоніму рекомендується використовувати подвійні лапки.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/7.JPG)

2.3.3 Перейти до домашнього каталогу вашого користувача. Використовуючи
текстовий редактор, наприклад, nano, розпочати редагування файлу .bash_profile та додати у файл два рядки зі створеними раніше псевдонімами виклику команд.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/8.JPG)

2.3.5 Повторно запустити GitBash-оболонку та перевірити роботу одного зі створених псевдонімів команд, щоб підтвердити їх автоматичну реєстрацію через файл .bash_profile
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/9.JPG)

2.3.6 Скопіювати файл .bash_profile до каталогу «Laboratory-work-3» Git-репозиторію
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/10.JPG)

### 2.4 Робота з файлами через перенаправлення вхідних/вихідних потоків
2.4.1 Створити файл з назвою як транслітерація вашого прізвища з прикінцевою
цифрою 1, наприклад blazhko_1, використовуючи команду cat з перенаправленням stdin-потоку на stdout-потік так, що файл містив один рядок з вашими прізвищем та ім’ям.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/11.JPG)
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/12.JPG)

2.4.2 Додати до створеного файлу через перенаправлення stdout-потоку ще один
рядок з назвою вашої групи.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/13.JPG)

2.4.3 Створити файл з назвою як транслітерація вашого імені з прикінцевою цифрою 2, наприклад blazhko_2, який містить два рядки, створені через перенаправлення stdout-потоку двох наступних команд:
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/14.JPG)
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/15.JPG)

2.4.4 Об`єднати два раніше створені файли в один файл командою cat зі створенням нового файлу, назва якого – транслітерація вашого прізвища та імені із суфіксом-розширенням .cat.txt;
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/16.JPG)
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/17.JPG)

2.4.5 Повторити об`єднання файлів, але вже командою paste зі створенням нового файлу, де назва файлу – транслітерація вашого прізвища та імені із суфіксом-розширенням .paste.txt
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/18.JPG)

### 2.5 Проста обробка результатів виконання команд
2.5.1 Отримати перелік каталогів для швидкого пошуку файлів, які можуть
виконуватися в командному рядку без вказування повного шляху до файлу, враховуючи, що кожну назву каталогу необхідно вивести в окремому рядку, наприклад, рядок з каталогами /c/user1/:/c/user2/ необхідно перетворити на два окремі рядки /c/user1/ та /c/user1/;
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/19.JPG)

2.5.2 Змінити рішення попереднього завдання так, щоб всі назви каталогів були в окремих рядках, наприклад, рядок з каталогами /c/user1/:/c/user2/ необхідно перетворити на чотири окремі рядки c, user1, c, user2
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/20.JPG)

2.5.3 Змінити рішення попереднього завдання, впорядкувавши значення назв
каталогів за зростанням та видаливши всі дублікати цих назв;
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/21.JPG)

2.5.4 Змінити рішення попереднього завдання, визначивши лише перші 5 назв
каталогів;
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/22.JPG)

2.5.5 Провести статистичний аналіз результату завдання 2.5.3, отримавши кількість каталогів та розмір найбільшої назви каталогу.
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/23.JPG)


### 2.6 Двонаправлене узгодження Git-репозиторія та GitHub-репозиторія
![Иллюстрация к проекту](https://github.com/Methouselah/WebAR-1/blob/Laboratory-work-3/Laboratory-work-3/foto/24.JPG)
