==============================
Білий Віталій Олегович
==============================


#. Локальні та віддалені репозиторії Git. Наведіть команду для відправки локальних комітів з гілки dev до віддаленого репозиторію.
#. Для чого слугує файл .gitignore? Наведіть його синтаксис для виключення всіх файлів з розширенням .o в усіх директоріях та
   директорії build в корені репозиторію

#. Який інструмент використовується в курсі для автоматичного форматування вихідних файлів C відповідно до Coding Style?
   Де взяти основний шаблон з описом формату для коду ядра? Наведіть команду для форматування файлу module.c відповідно
   до Coding Style ядра.
#. Є невелика програма (на стадії розробки), що збирається для GNU/Linux оточення та складається з вихідних файлів
   main.c dep.c та заголовку dep.h. Наведіть команду для збірки у бінарний файл prog. При збірці використовується компілятор
   GCC з другим рівнем оптимізації, код написано за стандартом C18 з розширеннями GNU. При компіляції необхідно побачити всі
   можливі попередження (warning). Який флаг необхідно додати, аби трактувати warning як error

#. Що таке макромодифікатори __init та __exit в коді модуля ядра? Як працюють та для чого використовуються?
#. В якому порядку виконуються алокації та деалокації в модулях ядра. Наведіть приклад коду з обробкою виключень, якщо
   невдалось виділити певний ресурс. (з використанням goto)

#. Фізична та віртуальна пам'ять ядра, в чому різниця та як це реалізовано?
   Які функції ядро надає (основні) для виділення та вивільнення пам'яті кожного з цих типів?
#. Як працює та для чого використовується макрос container_of. Наведіть приклад доступу до поля data контейнеру типу struct outer, 
   всередині структури якого визначено поле innerobj типу struct inner.
