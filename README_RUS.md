# Code Complete - 2nd Edition
## Помощь русскоязычным читателям


## Table of Contents



## Закладка фундамента ##

__Глава 1: Добро пожаловать в разработку программного обеспечения__

_Что такое построение программного обеспечения?_

Разработка программного обеспечения включает в себя:

   1. Определение проблемы
   2. Разработка требований, детальное проектирование, корректирующее техническое обслуживание
   3. Конструктивное планирование, кодирование и отладка, интеграция, интеграционное тестирование
   4. Архитектура программного обеспечения, модульное тестирование, системное тестирование
   5. Хотя разработка программного обеспечения в основном связана с кодированием и отладкой, она также включает детальное проектирование, планирование строительства, модульное тестирование, интеграцию, интеграционное тестирование и другие виды деятельности.

Конкретные задачи, связанные со строительством:

   1. Проверка того, что фундамент был заложен, чтобы строительство могло успешно продолжаться
   2. Проектирование и написание классов и процедур
   3. Создание и именование переменных и именованных констант
   4. Выбор структур управления и организация блоков операторов
   5. Модульное тестирование, интеграционное тестирование и отладка собственного кода
   6. Обзор низкоуровневых дизайнов и кодирования других членов команды и их обзор ваших
   7. Полировка кода путем тщательного форматирования и комментирования
   8. Интеграция программных компонентов, созданных отдельно
   9. Настройка кода, чтобы сделать его быстрее и использовать меньше ресурсов

    _Какое значение имеет разработка программного обеспечения?_

    * Строительство - это большая часть разработки программного обеспечения.
    * Строительство является центральным направлением в разработке программного обеспечения.
    * Требования и архитектура выполняются до начала строительства, чтобы вы могли эффективно выполнять строительство. Тестирование системы (в строгом смысле независимого тестирования) проводится после завершения строительства, чтобы убедиться, что строительство было сделано правильно. Строительство находится в центре процесса разработки программного обеспечения.
    * Если сосредоточиться на построении, производительность отдельного программиста может значительно повыситься.
    * Продукт строительства, исходный код, часто является единственным точным описанием программного обеспечения.
    *__Строительство - это единственная деятельность, которая гарантированно будет выполнена__


__Глава 3: Измерьте Дважды, Отрежьте Один Раз: Предварительные условия Восходящего Потока__

Как и в случае со строительством зданий, большая часть успеха или неудачи проекта была определена еще до начала строительства. Если фундамент был заложен плохо или плохо спланирован, лучшее, что вы можете сделать во время строительства, - это свести ущерб к минимуму.

Если вы делаете упор на качество в конце проекта, вы делаете упор на системное тестирование.

Если вы делаете упор на качество в середине проекта, вы делаете упор на практику строительства.

Если вы подчеркиваете качество в начале проекта, вы планируете, требуете и проектируете качественный продукт.

Главная цель предварительной подготовки-снижение рисков: хороший планировщик проекта как можно раньше устраняет основные риски, чтобы основная часть проекта могла пройти как можно более гладко.

_3.2 Определите тип программного обеспечения, над которым Вы работаете_


Различные виды программных проектов требуют различного баланса между подготовкой и строительством. Каждый проект уникален, но проекты, как правило, подпадают под общие стили разработки.

Итеративный проект, который сокращает или устраняет предварительные условия, будет отличаться двумя способами от последовательного проекта, который делает то же самое. Во-первых, средние затраты на исправление дефектов будут ниже, поскольку дефекты, как правило, обнаруживаются ближе к тому времени, когда они были вставлены в программное обеспечение. Однако дефекты все равно будут обнаруживаться на поздних стадиях каждой итерации, и для их исправления потребуется перепроектировать, перекодировать и повторно протестировать части программного обеспечения, что делает затраты на исправление дефектов выше, чем это необходимо.