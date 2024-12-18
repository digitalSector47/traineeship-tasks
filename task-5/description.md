# Задание 5

| Дата старта | Дедлайн        | Имя ветки      |
|-------------|----------------|----------------|
| 26.11.24    | 09.12.24 23:59 | ds-kanban-task |

Почти любой проект выполняется командой разработчиков. В команде есть Руководитель проектов, QA, Backend-разработчики, Frontend-разработчики.\
На этом этапе мы будем создавать проект Канбан на NextJS. Разделим всех на отдельные Frontend-команды по 3 человека, в каждой будет Лид команды и 2 разработчика.
В обязанности Лида входят подача PR команды, валидация оценок задач, распределение задач между разработчиками и коммуникация.

Ссылка на API: [ссылка](https://trainee-academy.devds.ru/swagger)  
Ссылка на макет: [ссылка](https://www.figma.com/design/GyuFtKu9z950ZkGPNVXqg2/DS%2F%D1%81%D1%82%D0%B0%D0%B6%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%2F5?node-id=0-1&node-type=canvas&t=4YdJHNRUCywFZDKn-0)    
Ссылка на шрифт: [ссылка](https://fonts.google.com/specimen/Inter)

**Перед тем как начать выполнение задания, необходимо выполнить его оценку. Оценивать нужно поблочно в часах.**
**Декомпозицию оценки оставить в комментарии к задаче.**

## Техническое задание: [ссылка](https://disk.yandex.ru/i/ph0R8MyeCr2QhQ)  

## Технические требования:
1. Работа каждой команды ведется в отдельном приватном репозитории.
2. Проект должен быть разработан с использованием `NextJS` и использовать `Pages Router`.
3. Используем `Next Middleware` для работы с закрытыми страницами, которые недоступны без прохождения авторизации.
4. Для работы со шрифтами используем `Next Fonts`.
5. Для работы с запросами используем `SWR`, `React-Query` или `RTK-Query`.
6. Для работы с формами используем `React-hook-form`. Для схем валидации используем `Yup` или `Zod`.
7. Не разрешается использовать `jQuery`.
8. Шрифт подключается локально.
9. Можно использовать `SCSS-препроцессор`, `CSS-модули`, `CSS-in-JS библиотеки`.
10. В проекте должен использоваться `ESLint` (airbnb-config), `Prettier`, `TypeScript`.
11. Версия `Node.js` => `20.18.1 LTS`.
12. Код приложения должен быть читаемым.
13. В «.gitignore» добавлена папка `node_modules`.
14. Писать коммиты по правилам «[Соглашения о коммитах](https://www.conventionalcommits.org/ru/v1.0.0/)».

## Оформление задачи:

1. Вся работа ведется в командном приватном `github-репозитории`.
2. От ветки `ds-kanban-task` Лид команды создает PR в `master`.
3. Оформить PR (по правилам самопроверки).
4. Опубликовать на `gh-pages`, `vercel`, `netlify` или любую другую площадку.
5. В Канбан приложить ссылку на PR и деплой.

## Система оценки

Максимальная оценка за задачу - **670**.

- [ ] Настроено рабочее окружения для старта проекта на NextJS (**+10**)
- [ ] Используется Pages Router (**+10**)
- [ ] Используются Middleware в NextJS (**+30**)
- [ ] Используется SSG/SSR/ISR (**+30**)
- [ ] Используется локальный шрифт (**+10**)
- [ ] Для работы с формами используем `React-hook-form` (**+30**)
- [ ] Используется `SWR`, `React-Query` или `RTK-Query` (**+30**)
- [ ] Используются мутации в `SWR`, `React-Query` или `RTK-Query` (**+20**)
- [ ] Главная страница - верстка (**+10**)
- [ ] Главная страница - смена набор кнопок в хедере в зависимости от состояния Аутентификации (**+10**)
- [ ] Авторизация - верстка и интеграция с **API** (**+10**)
- [ ] Авторизация - валидация (**+20**)
- [ ] Сайдбар - сайдбар и скрытие по кнопке (**+10**)
- [ ] Страница проектов - верстка и интеграция с **API** (**+10**)
- [ ] Страница проектов - ролевая модель (**+30**)
- [ ] Страница проектов - блок фильтров (**+30**)
- [ ] Страница проектов - архивные проекты (**+10**)
- [ ] Страница проектов - избранные проекты (**+10**)
- [ ] Канбан доска - верстка и интеграция с **API** (**+10**)
- [ ] Канбан доска - ролевая модель (**+30**)
- [ ] Канбан доска - скролл гор. и верт. (**+20**)
- [ ] Канбан доска - блок фильтров (**+50**)
- [ ] Канбан доска - блок задач (**+20**)
- [ ] Канбан доска - карточка задачи (приоритет, статус, типа, текста) (**+10**)
- [ ] Задача - верстка и интеграция с **API** (**+10**)
- [ ] Задача - ролевая модель (**+10**)
- [ ] Задача - вывод превью файлов (**+20**)
- [ ] Задача - редактор в блоке с комментариями (**+30**)
- [ ] Задача - блок комментариев (**+20**)
- [ ] Редактирование/создание задачи - форма (**+20**)
- [ ] Редактирование/создание задачи - редактор (**+30**)
- [ ] Редактирование/создание задачи - загрузка файлов (**+30**)
- [ ] Редактирование/создание задачи - валидация обязательных полей (**+10**)
- [ ] Редактирование Задачи - заполнение полей данными от API (**+20**)
- [ ] Клик вне модалки вызывает модалку с текстом «Закрыть окно» (**+10**)

## Задачи повышенной сложности
- [ ] Канбан доска - Drag'n'Drop задач (**+50**)
- [ ] Редактирование/создание задачи - в поле оценки время вводится в минутах, например, "90" парсится и переводится в "1ч 30м" (**+30**)

## Штрафы

- [ ] Используется jQuery (**-500**)
- [ ] Не используется `NextJS` (**-500**)
- [ ] Не используется `Next fonts` для работы со шрифтами (**-50**)
- [ ] Не используется `SWR`, `React-Query` или `RTK-Query` (**-200**)
- [ ] Не используется `React-hook-form`, `Yup` или `Zod` (**-200**)
- [ ] Версия `Node.js` не `LTS` (**-50**)
- [ ] Реализация решения без использования TypeScript (**-300**).
- [ ] Если исходный код проекта нечитаем, не структурирован по файлам/папкам (**-50**)
- [ ] Сохранение в github-репозитории лишних файлов (node_modules, dist, build, env-файлы и пр.) (**-50**)
- [ ] Коммиты не по правилам «[Соглашения о коммитах](https://www.conventionalcommits.org/ru/v1.0.0/)» (**-50**)

## Материалы
https://nextjs.org/  
https://swr.vercel.app/docs/getting-started   
https://tanstack.com/query/latest/docs/framework/react/quick-start  
https://react-hook-form.com/get-started  
https://habr.com/ru/articles/726354/ – Архитектура React приложений
