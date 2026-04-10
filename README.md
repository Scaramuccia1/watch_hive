# 🎬 WatchHive — Фильмы, Сериалы, Дорамы

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](https://watchhive.example.com)

**WatchHive** — современный веб-каталог фильмов, сериалов и дорам с возможностью просмотра трейлеров, добавления в избранное, поиском и авторизацией через соцсети. Данные о контенте предоставляются [The Movie Database (TMDB)](https://www.themoviedb.org/).


## ✨ Основные возможности

- 🔍 **Умный поиск** — мгновенные подсказки при вводе названия фильма или сериала.
- 🎞️ **Три раздела** — Популярное, Все контенты, Избранное.
- 🎭 **Фильтрация по жанрам и типу** — фильмы, сериалы, дорамы (корейские сериалы).
- ❤️ **Избранное** — сохраняйте понравившиеся фильмы в личный список (работает после авторизации).
- 🔐 **Авторизация** — вход через Google, ВКонтакте или демо-режим.
- 🎥 **Встроенный видеоплеер** — просмотр трейлеров/демо-роликов с элементами управления.
- 💬 **Комментарии Disqus** — обсуждение каждого фильма/сериала.
- 📱 **Адаптивный дизайн** — корректное отображение на компьютерах, планшетах и смартфонах.
- 📊 **Статистика в футере** — количество доступных фильмов/сериалов и «онлайн» пользователей.

---

## 🛠️ Технологии

- **HTML5**, **CSS3** (Flexbox, Grid, анимации)
- **JavaScript** (ES6+) – без фреймворков
- **API**:
  - [TMDB API](https://developers.themoviedb.org/3) – получение данных о контенте
  - [Google Identity Services](https://developers.google.com/identity) – авторизация через Google
  - [VK Open API](https://vk.com/dev/openapi) – авторизация через ВКонтакте
  - [Disqus](https://disqus.com/) – система комментариев
- **Шрифты**: Google Fonts (Poppins), Font Awesome (иконки)

---

## 🚀 Быстрый старт

1. **Склонируйте репозиторий**:
   ```bash
   git clone https://github.com/yourusername/watchhive.git
   cd watchhive
Откройте файл index.html в браузере – сайт заработает с демо-данными.

Настройте API-ключи (рекомендуется для полноценной работы):

Откройте index.html в редакторе.

Найдите константы в начале <script>:

javascript
const API_KEY = 'be7d23de539307aafd91e16bc4ce5c8f'; // ваш ключ TMDB
const GOOGLE_CLIENT_ID = 'YOUR_GOOGLE_CLIENT_ID.apps.googleusercontent.com';
const VK_APP_ID = 12345678;
const DISQUS_SHORTNAME = 'watchhive';
Замените значения на свои (инструкции по получению ключей ниже).

Перезагрузите страницу – авторизация и комментарии заработают.

Примечание: Если не указывать ключи Google/VK, авторизация будет работать в демо-режиме (любое имя).

🔑 Получение API-ключей
TMDB API Key (обязательно)
Зарегистрируйтесь на themoviedb.org.

Перейдите в настройки API.

Создайте новое приложение, получите API Key (v3 auth).

Скопируйте ключ в переменную API_KEY.

Google OAuth 2.0 (для входа через Google)
Создайте проект в Google Cloud Console.

Включите Google Identity Services.

Создайте OAuth 2.0 Client ID для веб-приложения.

В поле Authorized JavaScript origins укажите http://localhost (или ваш домен).

Скопируйте Client ID в GOOGLE_CLIENT_ID.

VK Open API (для входа через ВКонтакте)
Создайте приложение на vk.com/dev.

Выберите тип «Веб-сайт».

Укажите адрес сайта (например, http://localhost).

Скопируйте ID приложения в VK_APP_ID.

Disqus Shortname (для комментариев)
Зарегистрируйтесь на disqus.com.

Создайте новый сайт (forum).

В настройках найдите Shortname.

Замените DISQUS_SHORTNAME на ваш shortname.

📁 Структура проекта
text
watchhive/
├── index.html          # Основной файл (вся вёрстка, стили и логика)
└── README.md           # Документация
Весь код находится в одном HTML-файле для простоты развёртывания. При желании можно разделить на отдельные файлы CSS/JS.

🤝 Вклад в проект
Буду рад любым предложениям и улучшениям!

Форкните репозиторий

Создайте ветку (git checkout -b feature/amazing-feature)

Закоммитьте изменения (git commit -m 'Add some amazing feature')

Запушьте ветку (git push origin feature/amazing-feature)

Откройте Pull Request

📄 Лицензия
Распространяется под лицензией MIT. См. файл LICENSE.

📧 Контакты
Автор: Артем
Email: uchebaartem@gmail.com
GitHub: @Scaramucсia1
