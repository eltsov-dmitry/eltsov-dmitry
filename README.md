## Дмитрий Ельцов

Фронтенд-разработчик, шесть лет коммерческой разработки. Сейчас - ведущий фронтенд-разработчик
в AI-платформе конверсии трафика: админка на Next.js и MobX, библиотека встраиваемых виджетов
на Preact и браузерный SDK, который решает, какой виджет показать на чужом сайте.

До этого - крупное PWA в экосистеме Сбера, три продукта в VK и общая UI-библиотека поверх VKUI.

### Почему здесь только пет-проекты

Продукты, над которыми я работаю, закрытые - выложить их код нельзя. Поэтому в профиле то,
что написано с нуля и для себя. Пишу их не ради галочки: в коммерческой работе у меня MobX,
Vite и Vitest, а рынок чаще спрашивает Redux и Webpack. Пет-проекты - способ закрыть этот разрыв
руками, а не по статьям.

| Чего не было в проде | Где закрыл | Что именно сделано |
|---|---|---|
| Redux Toolkit, RTK Query | [pet-catalog](https://github.com/eltsov-dmitry/pet-catalog) | один api-слайс и `injectEndpoints`, бесконечная подгрузка на `infiniteQuery`, теги с точечными правками кэша через `updateQueryData` вместо перезапроса всех страниц |
| Webpack, собранный руками | [pet-catalog](https://github.com/eltsov-dmitry/pet-catalog) | конфиг с нуля, ленивые роуты и ленивые куски интерфейса, `splitChunks` по сроку жизни, бюджет размеров, замеры в gzip и brotli |
| Node и Express на TypeScript | [express-ts-mock-api](https://github.com/eltsov-dmitry/express-ts-mock-api) | слои routes-service-store, валидация на zod, access и refresh с ротацией и отзывом семьи токенов, пагинация |

### Проекты

**[pet-catalog](https://github.com/eltsov-dmitry/pet-catalog)** - каталог товаров: React 19,
Redux Toolkit с RTK Query, Feature-Sliced Design, сборка на Webpack.
[Живое демо](https://eltsov-dmitry.github.io/pet-catalog/). В README - разбор решений
со ссылками на файлы и замеры бандла: почему `Tooltip` затащил 10 КБ в критический путь
и чем ленивая загрузка отличается от правильной группировки чанков.

**[express-ts-mock-api](https://github.com/eltsov-dmitry/express-ts-mock-api)** - мок-бэкенд
для фронтовой разработки на Express 5 и TypeScript. Повторное использование отозванного
refresh-токена гасит всю семью выданных токенов. Тесты на встроенном `node --test`,
без единой тестовой зависимости.

### Стек

В работе: React, TypeScript, Next.js, MobX, Preact, Vite, Vitest, Playwright, Material UI.
Вторым стеком - Vue и Nuxt. На бэке - Node с Express и Nest, но это не основная моя зона.

### Связаться

[eltsob.dmitry@gmail.com](mailto:eltsob.dmitry@gmail.com) · [@eltsov_dmitry](https://t.me/eltsov_dmitry)

<!-- profile -->
