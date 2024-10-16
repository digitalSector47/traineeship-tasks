# Задание 1

| Дата старта | Дедлайн        | Имя ветки |
| ----------- | -------------- | --------- |
| 15.10.24    | 28.10.24 23:59 | ds-markup |

**Перед началом работы [ознакомится](https://github.com/digitalSector47/traineeship-tasks/blob/master/base-rules.md)**

Важное и&nbsp;базовое умение для любого фронтенд-разработчика&nbsp;&mdash; это верстка. На&nbsp;этом этапе мы&nbsp;будем заниматься версткой страницы. Страница местами непростая, вы&nbsp;поработаете с&nbsp;анимациями, с&nbsp;css-масками, реализуете адаптивную верстку под планшеты, мобилки, а&nbsp;также поработаем с&nbsp;оценкой задач.

Необходимо сверстать [макет](https://www.figma.com/design/mu3xyHH7jl5xGsAB6C0eDa/DS%2F%D1%81%D1%82%D0%B0%D0%B6%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%2F1?node-id=0-1&t=pO8T3EvVcBMVUoT6-1])<br />
Шрифты по [ссылке](https://github.com/digitalSector47/traineeship-tasks/tree/master/task-1/fonts).

**В фигме есть uikit, не забываем про него, в нем отображены состояния ховеров для кнопок, инпутов, ссылок, цветовая палитра, текстовые элементы и т.п..**

### Адаптивы:

Десктоп отображается от&nbsp;`1280px` и&nbsp;выше. Контейнер имеет фиксированную ширину и&nbsp;центрируется. Планшет отображается в&nbsp;промежутке `768px`&nbsp;&mdash; `1279px`, все что ниже `768px`&nbsp;&mdash; отображаем мобилку.

### Элементы интерфейса:

Для этих блоков необходимо реализовать бегущую строку:

![Running line](https://github.com/digitalSector47/traineeship-tasks/blob/master/task-1/images/running-lines.jpg)

При наведении на эту карточку новости, необходимо добавить `css-анимацию` `rotate` для этого элемента:

![Hover decor](https://github.com/digitalSector47/traineeship-tasks/blob/master/task-1/images/hover-decor.jpg)

Как вы&nbsp;могли уже заметить картинки на&nbsp;странице имеют нестандартную форму, поэтому необходимо использовать `css маски`. Нужно сохранить для каждой картинки свою маску и&nbsp;применить ее&nbsp;в&nbsp;верстке.

![Image mask](https://github.com/digitalSector47/traineeship-tasks/blob/master/task-1/images/image-mask.jpg)

На&nbsp;странице есть форма подписки, необходимо реализовать валидацию `email`, если поле не&nbsp;корректно заполнили подсвечиваем инпут красным, в макетах есть пример текстового поля с ошибкой в секции `ui-kit`. После успешного заполнения формы и отправки мы&nbsp;должны показать блок успеха, в&nbsp;макетах он&nbsp;также отображен в&nbsp;секции `ui-kit`.

![Form](https://github.com/digitalSector47/traineeship-tasks/blob/master/task-1/images/forms.jpg)

**Перед тем как начать выполнение задания, необходимо выполнить его оценку, оценивать нужно поблочно в&nbsp;часах. Декомпозицию оценки оставить в комментарии в задаче.**

## Технические требования:

1. Работа ведется в своем приватном репозитории.
2. Не&nbsp;разрешается использовать `Bootstrap`, `Material Design` и&nbsp;т.п. `CSS-фреймворки`.
3. Не&nbsp;разрешается использовать `jQuery`, другие `JS-библиотеки` и&nbsp;`фреймворки`.
4. Можно использовать `SCSS-препроцессор`.
5. Исходный код приложения должен быть читаемым, без минимизации или обфускации, не&nbsp;забываем структурировать стили/скрипты.
6. Верстка должна отображаться корректно во&nbsp;всех современных браузерах и&nbsp;устройствах.
7. Используем подход `Pixel Perfect`. Допуски по `Pixel Perfect`, для отступов между секциями или большими блоками до `10px`, в маленьких блоках не более `5px`, важно, чтобы расхождения не бросались в глаза, чтобы не было ситуации, что даже без накладывания макета видно, что где-то блок поехал.
8. Для именования классов используем методологию `БЭМ`.
9. В «.gitignore» добавлена папка «node_modules».
10. Писать коммиты по правилам «[Соглашения о коммитах](https://www.conventionalcommits.org/ru/v1.0.0/)».

## Оформление задачи:

1. От&nbsp;ветки `ds-markup` создать&nbsp;PR в&nbsp;`master`.
2. Оформить `PR`&nbsp;&mdash; https://github.com/digitalSector47/traineeship-tasks/blob/master/pull-request-rules.md.
3. Опубликовать на&nbsp;`GitHub-pages`.
4. В&nbsp;Канбан приложить ссылку на&nbsp;`PR` и&nbsp;деплой.

## Система оценки:

Максимальная оценка за задачу - **100**.

- [ ] Верстка корректно отображения во&nbsp;всех современных браузерах и&nbsp;устройствах **(+20)**.
- [ ] Используется подход `Pixel Perfect` **(+20)**.
- [ ] Для именования классов используется БЭМ **(+10)**.
- [ ] Реализована анимация ховера для ссылок которая есть в&nbsp;макетах **(+10)**.
- [ ] Реализованы ховер состояния **(+10)**.
- [ ] Изображения нестандартной формы реализованы с&nbsp;помощью `css масок` **(+10)**.
- [ ] Реализована анимация бегущей строки декоративного блока **(+10)**.
- [ ] Реализована валидация и&nbsp;состояние ошибки для формы подписки **(+10)**.

## Штрафы:

- [ ] Не разрешается использовать `Bootstrap`, `Material Design` и т.п. `CSS-фреймворки` (**-50**).
- [ ] Не разрешается использовать `jQuery`, другие JS-библиотеки (**-30**).
- [ ] Сохранение в github-репозитории лишних файлов (node_modules, dist, build, env-файлы и пр.) (**-10**).
- [ ] Коммиты не по правилам «Соглашения о коммитах» (**-10**).
- [ ] Если исходный код проекта нечитаем, не структурирован по файлам/папкам (**-20**).

## Материалы:

- [https://doka.guide/tools/how-the-browser-creates-pages/](https://doka.guide/tools/how-the-browser-creates-pages/)
- [https://doka.guide/css/pixel-perfect/](https://doka.guide/css/pixel-perfect/)
- [https://habr.com/ru/companies/ruvds/articles/729974/](https://habr.com/ru/companies/ruvds/articles/729974/)
- [https://doka.guide/css/animation/](https://doka.guide/css/animation/)
- [https://ru.bem.info/methodology/quick-start/](https://ru.bem.info/methodology/quick-start/)
- [https://doka.guide/html/form/](https://doka.guide/html/form/)
- [https://doka.guide/js/deal-with-forms/](https://doka.guide/js/deal-with-forms/)
- [https://doka.guide/tools/preprocessors/](https://doka.guide/tools/preprocessors/)
- [https://doka.guide/tools/pixel-density/](https://doka.guide/tools/pixel-density/)
- [https://doka.guide/html/picture/](https://doka.guide/html/picture/)
- [https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web/Dealing_with_files](https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web/Dealing_with_files)
- [https://developer.mozilla.org/ru/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure](https://developer.mozilla.org/ru/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [https://sky.pro/wiki/html/organizatsiya-papok-js-i-css-v-proekte-luchshie-praktiki/](https://sky.pro/wiki/html/organizatsiya-papok-js-i-css-v-proekte-luchshie-praktiki/)
