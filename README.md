# Курс "Современные технологии программирования"

**Дорогой студент ИТиУТС БГУИР,**
*ведущие к диплому приветствуют тебя! =)*

Ты заглянул в репозиторий по курсу «Современные технологии программирования» для студентов специальности “Информационные технологии и управление в технических системах”.

Здесь, в лаконичной форме и надеемся доступной форме, ты сможешь найти необходимую информацию о нашем плане на пути к победе над избыточной энтропией, компьютерной неграмотностью и недостаточной мотивацией в рискованном деле изучения современнх технологий программирования.
Более подробная информация содержится в папочках по отдельным лабораторным работам.

## Концепция курса

Общей целью лабораторных работ является разработка собственного приложения, сходного по своим функциональным возможностям и интерфейсной части с проектом [“Conduit”](https://github.com/gothinkster/realworld)

«Conduit» представляет собой веб-приложение - платформу для публикации социальных блогов (наподобие «medium.com»). Он использует собственный API для всех запросов, включая аутентификацию. Вот [здесь](https://demo.realworld.io) можно просмотреть живую демонстрацию проекта.

А вот здесь можно и нужно заглянуть в официальный репозиторий с [исходным кодом проекта](https://github.com/gothinkster/realworld)

Главная особенность данного проекта заключается в том, что он позвояляет изучить особенности современного процесса разработки на общем едином *"эталонном"* примере приложения ( таком как "Сonduit"), и в деталях реализации которого отражено большое количество современных подходов, встречающихся в реальных проектах, на основе различных технологических стеков и платформ. 
По задумке авторов проекта, это даёт возможность Вам освоить и легко перейти от одной, уже знакомой Вам парадигмы, архитектуры, платформы, языка, фреймворка (нужное подчеркгуть), к другому, с наименьшим количеством затрат на “трение” при изучении. 

 И даже если Вы находитесь вначале своего пути в увлекательном мире современных технологий программирования, такая концепция позволяет быстрее погрузиться в тонкости современных технологий разработки.

Общий функционал приложения включает в себя:
- Возможность получения и отображения списка статей, разделённого на страницы (pagination).
- Выполнение CRUD (Create Read Update Delete – Создание Чтение Обновление Удаление) операций на ссущностями «Статьи»
- Выполнение CRU* операций над сущностями “Пользователи” (страница регистрации и настроек - удаление не требуется)
- Выполнение CR * D операций над сущностями «Комментарии к статьям» (обновление не требуется)
- Возможность отметки «любимых статей» (like)
- Возможность наблюдений за активностью других пользователей (following)
- Аутентификация пользователей через JWT (страницы входа / регистрации + кнопка выхода на странице настроек)
- Применение принципов REST-архитектуры для обеспечения взаимодействия клиентской и серверной части 

Для начала работы над собственным проектом необходимо сформировать небольшое техническое задание (ТЗ), в виде странички описания проекта на GitHub. Хороший пример оформления краткого ТЗ можно посмотреть, например, [здесь](https://github.com/Call-for-Code/Project-Sample#short-description).

Также вы можете проявить инициативу и предложить собсвтенную идею проекта, архитектурыне решения или свой технологический стек.
Можете обращаться к самому передовому опыту и использовать любые интересующие Вас технологии и инструментальные средства!

## Лабораторные работы

Если вы не чувствуете пока в себе силы взяться за такую задачу не расстраивайтесь. Дорогу, как говориться, осилит идущий. Главное не бояться и пробывать! 
Будем вместе двигаться к достижению поставленной цели! 
Главным “мечом Джедая” (читай инструментальным средством разработки) который мы будем использовать на этом пути будет язык Python, а также его сравнительно новый и свежий фреймворк FastAPI. Не забываем что технологии то у нас “современные”  ; )

А для этого Вы можете пройти курс подготовки молодого бойца ИТ-фронта в виде серии лабораторных, которые будут включать в себя следующие основные темы:
- **Лаба 1.** [Введение в Git & Python Crash Course](https://github.com/bsuir-cs/stp2020/blob/master/lab01/lab01_task.md)
- Лаба 2. Объектно-ориентированное программирование на Python & введение в FastAPI
- Лаба 3. Создание веб-приложения для выполнения операций CRUD.
- Лаба 4. Создание веб-приложения с авторизацией на основе токенов
- Лаба 5. Cоздание веб-приложения “TODO List”
- Лаба 6. Создание собственного “малого” проекта

Важное замечание! Вы можете предложить любой альтернативный язык (например: Java, C#, NodeJS, Kotlin, Go, Rust, Closure, Nim, или Swift – *да-да, на нём тоже иногда пишут бэкенды 0_o*) или фреймворк (классику жанра как Django или Flask) 
про который в знаете и с которым Вам было бы интересно познакомиться. 

Каждая лабораторная работа включается в себя три фазы:
- Подготовка
- Выполнение
- Защита.
Если вы чувствуете, что информация на фазе «Подготовки» и Вы все условия, Вы можете сразу переходить к фазам «Выполнение» и «Защита».
Для «Защиты» Вам необходимо иметь с собой ЭЛЕКТРОННУЮ ВЕРСИЮ отчёта, представляющую собой электронный документ размещающийся в Вашем личном репозитории.  Для каждой лабораторной делайте в вашем репозитории отдельную папочку.
В разделе «Зашита», вы также можете найти список контрольных вопросов, необходимых для защиты по данной лабораторной работе.

Если кто-либо желает двигаться быстрее в удобном для него темпе, может выполнять работы над проект самостоятельно, не дожидаясь остальных, ведь конечная точка маршрута известна!

## Средства разработки

Рекомендуемые для использования инструментальные средства разработки:
- Visual Studio Code
- Sublime Text
- GitHub Atom
- СonEmu (удобный эмулятор консоли для Windows)
- Сhocolatey («человеческий» менеджер пакетов для Windows)
- Babun (эмулятор СygWin с Unix совместитмым комнадным интерфейсом для Windows. Проще говоря если хотите испольщовать Как альтернативу можно прибегнуть к GitBash)
- Docker (средство виртуализации и контейнерезации)

Если что-то из этого Вам не известно, можете потихоньку осваивать самостоятельно, опираясь на наши советы, помощь и поддержу!

Всем доброй охоты за знаниями! :sunglasses:
