# Рекомендації по курсу **Harvard CS50**

- **Тиждень 0:** *Scratch*
  - **Опис:** Опанування мови візуального програмування Scratch. Мова підтримує складні конструкції, багатопотоковість, та інші можливості розвинутих мов.
  - **Завдання:**
    - *Программа на мові Scratch*: Зазвичай це гра, тому що на цій мові більше нічого путнього не виходить. Це відбірковий етап і ускладнень для відібраних людей становити не має. Людей, у яких, на цьому етапі, виникають ускладнення - краще не відбирати.

- **Тиждень 1:** Вступ в *С*
  - **Опис:** Базовий синтаксис С, цикли, умови.
  - **Завдання:**
    - *hello*: Завдання складається в тому щоб запустити цю программу;
    - *water*: Елементарне завдання, яке до того ж може бути спрощене до одного рядка;
    - *mario*: Не складне завдання. Треба бути обережним з пробілами та переносами строк;
    - *greedy*: Підступне завдання. Тести адресують проблеми округлення. Щоб їх оминути треба винятково працювати з копійками, як цілими числами.

- **Тиждень 2:** ASCII
  - **Опис:** Людей знайомлять з *мономорфністю* мов низького рівня, зокрема в С. Все є число. Логічні значення це число. Символ це число. До нього можно додавати щось або віднімати. Строка це набір чисел. Введення в масиви.
  - **Завдання:**
    - *initials*: Базові навички роботи зі строками;
    - *caesar*: Знайомство з математикою. Все що треба робити добре розписано у завданні;
    - *vigenere*: Усладнена версія попереднього завдання. Ніяких значних особливостей.

- **Тиждень 3:** Алгоритми
  - **Опис:** Дуже стисло пояснюються базові алгоритми сортування та пошуку. Базові навички користування утилітою `make`.
  - **Завдання:**
    - *helpers*: Завдання цікаве але не дуже добре організоване. Хоча перші результати студент отрімує майже одразу, треба звернути увагу на те як протестувати сортування та бінарний пошук;
    - *feefteen*: Треба реалізувати деякі методи. Досить механічне завдання. Не нехтуйте можливістю передати файл на стандартний поток вводу.
  - **Рекомендовано додати тиждень:** На поглиблене пояснення алгоритмів сортування та пошуку. `O` велике - дуже популярне запитання на співбесідах.

- **Тиждень 4:** Вказівники
  - **Опис:** Введення до вказівників, найскладнішого для розуміння розділу, цього курсу.
  - **Завдання:** Завдання розраховане на два тижні. Та на опанування матеріалу двох тижнів.
    - *whodunit*: Досить просте завдання. Підготовка до слідуючого.
    - *resize*: Дуже складне завдання. Не дівлячись на наочну простоту, `bmp` всередині не дуже простий формат. Не нехтуйте можливістю звірити заголовки за допомогою допоміжної програми `~cs50/pset4/peek`.
    - *recover*: Студентів лякає що треба все писати з нуля, без "фреймворку". Але завдання досить просте, а можливість відновити фотки з бінарного файлу дуже мотивуюча.

- **Тиждень 5:** Структури даних
  - **Опис:** Введення до структур даних.

- **Тиждень 6:** Словник
  - **Опис:** "Начитка" *С* закінчилася. Починається поступова підготовка до Web-у.
  - **Завдання:**
    - *dictionary*: Лектор каже що це найскладніше завдання курсу, спойлер: це не так. Не дивлячись на це студенту доведеться використати всі свої навички в повнії мірі: вказівники, алгоритми, структури данних. Рекомендується робити завдання за допомогою структури `Trie` (вона на диво легше засвоюється ніж `HashMap`, та найоптимальніша для цієї конкретної задачі). Але якнайменше використовувати рекурсію (хіба що під час очищення пам'яті). Не забувайте про апостроф та перевірити программу на великих файлах.
  - **Рекомендовано додати тиждень:** Та розглянути декілька можливих рішень задачі. Зазвичай студенти застрягають на цьому завданні, тому повторити ще раз буде корисно.

- **Тиждень 7:** HTTP Сервер
  - **Опис:** Активна начитка *HTML/CSS* та *PHP*. Не дивлячись на це, завдання все ще на С.
  - **Завдання:**
    - *server*: Наскладніше завдання курсу. Великий об'єм "фреймворку", який доведеться розібрати для відладки помилок. Завдання треба виконувати в строгому порядку, що відрізняється від порядку в завданні: parse, load, lookup, indexes. Порядок такий бо в іншому випадку дуже важко перевірити корректність реалізації.
  - **Рекомендовано додати тиждень:** Щоб грунтовно попрощатися з С. Також бо завдання дісно складне.

- **Тиждень 8:** Web
  - **Опис:** До *PHP* додається *SQL*.
  - **Завдання:**
    - **finance** Завдання не складне але дуже об'ємне. Більша частина питань, які можуть виникнути, розглянута в специфікації завдання.
  - **Рекомендовано додати тиждень:** Слідуюче завдяння буде зі значним акцентом на *JavaScript*, тому рекомендується додати тиждень щоб студенти призвичаїлися до купи новіх технологій: *HTML/CSS/Bootstrap/PHP/SQL/PHPMyadmin*.

- **Тиждень 9:** Mashup
  - **Опис:** Ще більше нових технологій *JavaScript/jQuery/Ajax*.
  - **Завдання:**
    - **machup** Калейдоскоп технологій викликає в студентів головокружіння але завдання не складне. Є багато підсказок у коді, його можно виконати використовуючи в основному copy/paste. Це останнє завдання.


- **Тиждень 10, 11, 12:** Фінал
  - **Опис:** Підготовка до фінального проекту та здача "хвостів".
  - **Завдання:**
    - *фінальний проект*: розписаний в [окремому документі](../final).

