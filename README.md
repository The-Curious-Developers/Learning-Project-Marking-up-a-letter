# Learning-Project-Marking-up-a-letter

IT Brains Fullstack Web Development Course
Level 1 
GitHub Learning Project: Marking Up a Letter 
Introducing to: Git, HTML & CSS

## Вступ 

Щирі привітання з вашими першими кроками на шляху до професії розробника! Протягом навчання ви матимете справу з Git, HTML та CSS. Цей навчальний проект відкритий безкоштовно для всіх, хто бажає тренувати свої вміння та навички практичним досвідом.

Головним завданням для вас буде перетворити звичайний файл з текстом листа (letter.txt) на такий інтернет файл, котрий можна переглянути в браузері (letter.html), та який використовує технології HTML та CSS. 

Бажаємо приємної практики та успіхів в навчанні!

Команда "Допитливі розробники"

## Git 

Ви вже мали урок з Git та знаєте основні команди. Чудова нагода вперше застосувати їх в своєму першому проекті - як справжні розробники!

### Готуемся до практики 

Перед виконанням практики вам знадобиться свій акаунт в GitHub та завантажений на комп'ютер термінал. Зауважимо, що ваш акаунт в GitHub має в налаштуваннях дозволяти комунікацію з терміналом на компютри. Зараз ми припустимо, що ви вже це зробили після уроку про Git.

**Увага!** Якщо ви переглянули уважно відео урок, але не змогли налаштувати все як треба, зверніться до свого товариша зі студентів курсу. Звичайно,  служба підтримки курсу теж допоможе.

Якщо ви вперше встановили в себе на комп'ютер термінал, його треба налаштувати вказавши своє ім'я та адресу командами:
* git config --global user.name "<your_name>" 
* git config --global user.email "<your_mail@example.com>"

Ще один крок, це налаштування терміналу в консолі Visual Studio Code. Ми радимо саме так виконувати цей проект, бо це дуже зручно.

З уроку про Visual Studio Code ви знаєте де знаходиться консоль терміналу. Якщо треба його налаштувати:
* Відкрийте Visual Studio Code 
* Натисніть CTRL + SHIFT + P щоб відкрити Command Palette
* В пошук наберіть “Terminal: Select Default Profile” 
* Виберіть потрібний вам термінал. Ми в нашому випадку обрали “Git Bash”

## Починаємо практику

Мета практики з Git - отримати досвід застосування Git команд. Для цього ви будете користуватися цим навчальним проектом Допитливих розробників на своєму комп'ютери та в вашому GitHub аккаунті.

Наш навчальний проект, це фактично відкритий для всіх (Public) репозиторій в GitHub. Щоб почати практику, зробіть свою копію (Fork) цього репозиторію і він з'явиться в акаунті GitHub вже як ваш власний. Всі подальші дії ви будете робити саме з ним.

### Робочий день 1 

Для зручності, ми поділили практику на умовні робочі дні. Але ви можете не дотримуватись до цього графіка.

На своєму комп'ютері, за допомогою термінала в Visual Studio Code, створіть папку в якої будете працювати, наприклад на диску С, папка work
* cd C:/ 
* mkdir work

Тепер, коли ви маєте порожню папку, увійдіть до неї та створіть початкову Git папку:
* cd work
* git init

Чудово! Зараз ви маєте початкову Git папку: 
* ls -a

Команда ls -a показує список усіх файлів та папок, включаючи приховані, у поточній папці.Зараз Git порожній, тобто можете завантажити до неї репозиторій файлів цього навчального проекту:
* git clone <repository_url>

Зверніть увагу, що вказуючи repository_url вам потрібно вказати всі деталі, наприклад:
* https://github.com/<login_name>/<repository_name>.git 

Якщо все вказано як треба, ви отримаєте всі файли репозиторію на свій комп'ютер та зможете їх переглядати, змінювати тощо, за допомогою Visual Studio Code. 

Чудова робота! 

Для того, щоб завершити перший етап практики, вам потрібно зробити зміни в файлі letter.html, зробити свій перший commit та оновити код репозиторію в GitHub.

Для цього треба створити нову гілку, наприклад structuring та увійти до неї:
* git branch <branch_name>
* git checkout <branch_name>
або так:
* git checkout -b <branch_name>

Що можна змінити вже зараз? Ось, наприклад, подивіться в редакторі коду Visual Studio Code на початку файла letter.html ім'я автора, та напишіть своє ім'я:
 * … author=”<your_name>”

Відредагуйте те, що в лапках та запишіть зміни за допомогою Ctrl+S

Перевірте статус своїх файлів за допомогою: 
* git status

Git вам звітує, що нових commit ще немає, але є зміни в файлі letter.html 

Тепер додайте зміни за допомогою команди:
* git add letter.html 

Зафіксуйте ваші зміни за допомогою:
* git commit -m "commit message"

В лапках додайте коротенько що саме ви змінили, наприклад: “author name changed“ 

Тепер треба відправити зміни (тобто зробити Push) до репозиторію в GitHub (ваш приватний remote repository) за допомогою: 
* git push <remote_url> structuring

Якщо все правильно зроблено, термінал звітуе про успішне відправлені до репозиторію зміни. 

Чудово! Ваш перший навчальний робочий день завершено!
