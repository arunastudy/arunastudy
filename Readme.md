<!--
  README для Aruna Tazabekova (Aruuke Tazabekovna)
  - Красивый баннер с градиентом и анимацией (SVG)
  - Разделы: О себе, Навыки, Проекты, Контакты, Мини-игра
  - Используй GitHub Pages для хостинга игры/демо
-->

<!-- Gradient animated header (SVG embedded) -->
<p align="center">
  <img alt="banner" src="data:image/svg+xml;utf8,
  <svg xmlns='http://www.w3.org/2000/svg' width='1000' height='220'>
    <defs>
      <linearGradient id='g' x1='0' x2='1'>
        <stop offset='0' stop-color='%237F00FF'/>
        <stop offset='1' stop-color='%23E100FF'/>
      </linearGradient>
      <filter id='f' x='-50%' y='-50%' width='200%' height='200%'>
        <feGaussianBlur stdDeviation='12' result='b'/>
        <feBlend in='SourceGraphic' in2='b'/>
      </filter>
      <style>
        <![CDATA[
          .title { font-family: Inter, system-ui, -apple-system; fill: white; font-size:34px; font-weight:700; }
          .subtitle { font-family: Inter, system-ui, -apple-system; fill: rgba(255,255,255,0.95); font-size:16px; }
          .pulse { animation: pulse 3s ease-in-out infinite; transform-origin: center; }
          @keyframes pulse {
            0% { transform: translateY(0px) scale(1);}
            50% { transform: translateY(-6px) scale(1.02);}
            100% { transform: translateY(0px) scale(1);}
          }
        ]]>
      </style>
    </defs>

    <rect width='100%' height='100%' fill='url(%23g)' rx='20' />
    <!-- floating circles -->
    <g fill='rgba(255,255,255,0.08)'>
      <circle class='pulse' cx='880' cy='40' r='28' />
      <circle cx='120' cy='40' r='16' opacity='0.8'/>
      <circle cx='240' cy='140' r='22' opacity='0.7'/>
      <circle cx='600' cy='60' r='10' opacity='0.6'/>
    </g>

    <text x='50' y='80' class='title'>Aruna (Aruuke) Tazabekova</text>
    <text x='50' y='110' class='subtitle'>Frontend Developer • HTML • CSS • JavaScript • React • Python • Java • Dart (basic)</text>
    <text x='50' y='150' class='subtitle'>Orion — персональный навигатор в мире образования и карьеры • Победитель множества олимпиад</text>

  </svg>" width="100%" style="max-width:1000px;border-radius:12px;box-shadow:0 6px 30px rgba(0,0,0,0.25)"/>
</p>

---

## 👩‍💻 Обо мне
Привет! Я **Aruna (Aruuke) Tazabekova** — фронтенд-разработчик, также знакома с Python, Java и Dart (базовые знания). Люблю создавать понятные интерфейсы, обучающие проекты и простые игры.  
📞 `+996 50 734 3454` • ✉️ Telegram: [@aruna_study](https://t.me/aruna_study) • 📸 Instagram: [@arunastudy](https://instagram.com/arunastudy)

Подробное резюме и достижения (книги, стипендии, победы на олимпиадах) — в моём резюме. :contentReference[oaicite:0]{index=0}

---

## 🚀 Навыки

**Frontend**
- HTML5, CSS3 (Flexbox, Grid, Media Queries)
- Адаптивный дизайн, BEM, Tailwind CSS
- JavaScript (ES6+), DOM, Fetch, Promises
- React.js, Redux, React Router, Material-UI, Bootstrap
- UI/UX: Figma, Adobe Photoshop, CorelDRAW

**Backend / Прочее**
- Основы Java, Spring Boot (базовый)
- Python (базовый/скрипты)
- Dart / Flutter (база)
- Git, GitHub, Postman, тестирование

**Технические и профессиональные достижения**
- Автор книг по математике и саморазвитию, победитель национальных и международных олимпиад. Подробнее — резюме. :contentReference[oaicite:1]{index=1}

---

## 🛠 Технологии (иконки)
<!-- Используем эмодзи + маленькие значки -->
<p>
  <img alt="JS" src="https://img.shields.io/badge/-JavaScript-FFD43B?logo=javascript&logoColor=black" />&nbsp;
  <img alt="React" src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black" />&nbsp;
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" />&nbsp;
  <img alt="Java" src="https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white" />&nbsp;
  <img alt="HTML" src="https://img.shields.io/badge/-HTML-E34F26?logo=html5&logoColor=white" />&nbsp;
  <img alt="CSS" src="https://img.shields.io/badge/-CSS-1572B6?logo=css3&logoColor=white" />&nbsp;
  <img alt="Tailwind" src="https://img.shields.io/badge/-Tailwind%20CSS-38B2AC?logo=tailwindcss&logoColor=white" />
</p>

---

## ✨ Главный проект — Orion
**Orion — твой персональный навигатор в мире образования и карьеры.**  
Ссылка: https://orion-hackaton.vercel.app/  

Описание: Orion помогает школьникам Кыргызстана найти призвание, выбрать профессию и получить качественное образование. (Короткое описание для карточки проекта в README.)  

---

## 🔗 Проекты (подборка)
- [Orion — персональный навигатор (demo)](https://orion-hackaton.vercel.app/) — помощь школьникам в выборе карьеры.
- (Добавь сюда другие проекты — ссылки и краткое описание; можно вставить карточки с изображениями).

---

## 🎮 Мини-игра (встраиваемая демо)
Я добавила простую мини-игру (файл `index.html`) — маленькая анимация/игра на Canvas. Игра статична в README показать нельзя, но её можно разместить в корне репозитория и открыть через GitHub Pages (`https://<твой-ник>.github.io/<репо>/index.html`). Код игры ниже.

---

## 📱 Контакты и соцсети

<p>
  <a href="tel:+996507343454">📞 +996 50 734 3454</a> &nbsp; • &nbsp;
  <a href="https://t.me/aruna_study">💬 Telegram</a> &nbsp; • &nbsp;
  <a href="https://instagram.com/arunastudy">📸 Instagram</a> &nbsp; • &nbsp;
  <a href="https://github.com/arunastudy">🐙 GitHub</a>
</p>

---

## ✨ Как оформить репозиторий красиво (рекомендации)
1. Положи `README.md` в корень репозитория.  
2. Создай папку `demo/` или `site/` и положи туда `index.html` (мини-игра) и другие демо.  
3. Включи GitHub Pages (Settings → Pages) и укажи источник — `main` branch / `root` (либо `gh-pages`).
4. Добавь скриншоты (`assets/`) и ссылку на них в README (карточки проектов).
5. Для анимаций используй SVG (они работают в README), GIF (анимированные превью) или встроенные data-URI SVG (как в баннере выше).

---

## 🧾 Источники данных резюме
Данные об образовании, наградах, книгах и опыте работы взяты из твоего резюме (PDF). :contentReference[oaicite:2]{index=2}

---

## Лицензия
Этот README — твоё резюме/портфолио. Используй, изменяй и распространяй.

---
