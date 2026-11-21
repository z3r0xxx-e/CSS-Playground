
  /EN/
---

# 🎨 CSS Playground

[![Live demo](https://img.shields.io/badge/demo-live-brightgreen)](https://z3r0xxx-e.github.io/CSS-Playground/)
[![Single file](https://img.shields.io/badge/single%20file-index.html-7c5cff)](https://github.com/z3r0xxx-e/CSS-Playground/blob/main/index.html)

A visual CSS style generator for shapes, gradients, shadows and glassmorphism — with live preview and ready-to-copy code you can drop straight into your project.

**🔗 Site: [z3r0xxx-e.github.io/CSS-Playground](https://z3r0xxx-e.github.io/CSS-Playground/)**

---

## ✨ Features

- **Six shapes** — square, rectangle, circle, oval, diamond and parallelogram.
- **Corner rounding** — a single radius or per-corner customization.
- **Fill** — a solid color or a two/three-color gradient at any angle.
- **Multi-layer shadows** — up to six `box-shadow` layers with individual offset, blur, spread, color and opacity.
- **Glass effect** — `backdrop-filter: blur()`, a translucent fill and a customizable border.
- **Live code** — the ready-made `.my-element { ... }` updates on every action and copies in one click.
- **Ready-made presets** — neumorphism, Apple style, hard shadow, frosted glass, neon, gradient wave.
- **Three UI languages** — `RU + EN`, `RU` only, `EN` only.
- **Auto-adaptive text** — the label color is picked by contrast against the fill.
- **One file, zero dependencies** — no bundlers, no npm packages, no frameworks.

## 🖼 Screenshot

> <img width="1280" height="625" alt="{EC6FCCF9-E85C-4B59-B42F-4186EEA6B809}" src="https://github.com/user-attachments/assets/76e79cc6-433e-46d7-892b-34be42708a82" />


## 🚀 How to use

1. Open the [site](https://z3r0xxx-e.github.io/CSS-Playground/) or download `index.html` and open it in your browser — everything works locally, without a server.
2. Adjust the shape, fill, shadows and glass in the tabs on the left.
3. Click **"Copy CSS"**.
4. Paste the `.my-element` class into your project and rename it to suit your needs.

No sign-up, no data sent to a server, no internet required — everything is computed in the browser.

## 🧩 What it generates

Example for the "Rectangle" shape with a shadow and the glass effect:

```css
.my-element {
  box-sizing: border-box;
  width: 420px;
  height: 260px;
  background: linear-gradient(140deg, rgba(139, 92, 255, 0.24), rgba(255, 92, 138, 0.24));
  border-radius: 28px;
  box-shadow: 0 24px 60px -10px rgba(0, 0, 0, 0.55);
  border: 2px solid rgba(255, 255, 255, 0.45);
  backdrop-filter: blur(18px);
  -webkit-backdrop-filter: blur(18px);
}
```

## 🛠 Tech stack

- **HTML + CSS + JavaScript** — no frameworks, no dependencies.
- No bundlers, no transpilers, no `npm install`.
- Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## 📁 Structure

```
.
├── index.html      # the whole app: markup, styles and script
└── README.md
```

## 🌐 Local run

Just open `index.html` by double-clicking — that's enough (or "Open with" → "your browser"). If you prefer a local server:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## 🤝 Contributing

Ideas, bugs and pull requests are welcome. If you found a problem — [open an issue](https://github.com/z3r0xxx-e/CSS-Playground/issues).

---

Made with ♥♥♥


##
##
##
##

   /RU/
---
# 🎨 CSS Playground

[![Live demo](https://img.shields.io/badge/demo-live-brightgreen)](https://z3r0xxx-e.github.io/CSS-Playground/)
[![Single file](https://img.shields.io/badge/single%20file-index.html-7c5cff)](https://github.com/z3r0xxx-e/CSS-Playground/blob/main/index.html)

Визуальный генератор CSS-стилей для фигур, градиентов, теней и эффекта стекла — с живым предпросмотром и готовым кодом, который можно сразу скопировать в свой проект.

**🔗 Сайт: [z3r0xxx-e.github.io/CSS-Playground](https://z3r0xxx-e.github.io/CSS-Playground/)**

---

## ✨ Возможности

- **Шесть форм** — квадрат, прямоугольник, круг, овал, ромб и параллелограмм.
- **Скругление углов** — общий радиус или отдельная настройка каждого угла.
- **Заливка** — однотонный цвет или градиент из двух/трёх цветов под любым углом.
- **Многослойные тени** — до шести слоёв `box-shadow` с индивидуальными смещением, размытием, spread, цветом и прозрачностью.
- **Эффект стекла** — `backdrop-filter: blur()`, полупрозрачная заливка и настраиваемая рамка.
- **Живой код** — готовый `.my-element { ... }` обновляется на каждое действие и копируется в один клик.
- **Готовые пресеты** — неоморфизм, Apple-стиль, жёсткая тень, матовое стекло, неон, градиентная волна.
- **Три языка интерфейса** — `RU + EN`, только `RU`, только `EN`.
- **Автоадаптация текста** — цвет подписи подбирается по контрасту к заливке.
- **Один файл, ноль зависимостей** — никаких сборщиков, npm-пакетов и фреймворков.

## 🖼 Скриншот

> <img width="1280" height="625" alt="{EC6FCCF9-E85C-4B59-B42F-4186EEA6B809}" src="https://github.com/user-attachments/assets/76e79cc6-433e-46d7-892b-34be42708a82" />


## 🚀 Как пользоваться

1. Откройте [сайт](https://z3r0xxx-e.github.io/CSS-Playground/) или скачайте `index.html` и откройте его в браузере — всё работает локально, без сервера.
2. Настройте форму, заливку, тени и стекло во вкладках слева.
3. Нажмите **«Скопировать CSS»**.
4. Вставьте класс `.my-element` в свой проект и переименуйте под свои нужды.

Никакой регистрации, отправки данных на сервер или интернета — всё считается в браузере.

## 🧩 Что генерируется

Пример для формы «Прямоугольник» с тенью и эффектом стекла:

```css
.my-element {
  box-sizing: border-box;
  width: 420px;
  height: 260px;
  background: linear-gradient(140deg, rgba(139, 92, 255, 0.24), rgba(255, 92, 138, 0.24));
  border-radius: 28px;
  box-shadow: 0 24px 60px -10px rgba(0, 0, 0, 0.55);
  border: 2px solid rgba(255, 255, 255, 0.45);
  backdrop-filter: blur(18px);
  -webkit-backdrop-filter: blur(18px);
}
```

## 🛠 Технологии

- **HTML + CSS + JavaScript** — без фреймворков и зависимостей.
- Никаких сборщиков, транспайлеров и `npm install`.
- Работает во всех современных браузерах (Chrome, Firefox, Safari, Edge).

## 📁 Структура

```
.
├── index.html      # всё приложение: разметка, стили и скрипт
└── README.md
```

## 🌐 Локальный запуск

Просто откройте `index.html` двойным щелчком — этого достаточно (или "открыть с помощью" → 'ваш браузер'). Если хотите через локальный сервер:

```bash
# Python 3
python -m http.server 8000
# затем откройте http://localhost:8000
```

## 🤝 Участие

Идеи, баги и пул-реквесты приветствуются. Если нашли проблему — [создайте issue](https://github.com/z3r0xxx-e/CSS-Playground/issues).

---

Сделано с ♥♥♥
