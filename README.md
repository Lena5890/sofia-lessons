# Sofia · English lessons

Интерактивные уроки Софии. Каждый урок — HTML-файл со встроенными шрифтами и без внешних запросов.
Картинки уроков (страницы учебника) лежат в папке `img/`, аудио — в `audio/`.

| Урок | Файл | Ссылка (после включения Pages) |
|------|------|------|
| Talking Nature: Read Smarter, Not Harder · B2 · 55 мин | `talking-nature-b2.html` | `https://lena5890.github.io/sofia-lessons/talking-nature-b2.html` |
| Food is Free · чтение, лексика, verb patterns · 55 мин | `food-is-free.html` | `https://lena5890.github.io/sofia-lessons/food-is-free.html` |
| Whose English Is It? · Upper-Intermediate, аудирование · 55 мин | `whose-english-is-it.html` | `https://lena5890.github.io/sofia-lessons/whose-english-is-it.html` |

## Как включить GitHub Pages

1. Репозиторий уже публичный (на бесплатном плане Pages работает только для публичных).
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, папка `/ (root)` → Save.**
3. Через 1–2 минуты ссылка появится вверху страницы Settings → Pages.

## Приватность

- Главная страница (`index.html`) не показывает список уроков: урок открывается только по прямой ссылке.
- Все страницы закрыты от поисковиков (`noindex` + `robots.txt`).
- При этом публичный репозиторий виден на GitHub всем, кто его найдёт. Не кладите сюда личные данные учеников.
- Ответы ученика хранятся только в его браузере. На сервер ничего не отправляется.

## Как добавить новый урок

Положить новый `.html` в корень репозитория, его картинки — в `img/`, и добавить строку в таблицу выше.
