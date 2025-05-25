# nil-ui

UI-библиотека на базе [Next.js](https://nextjs.org) с использованием SCSS и кастомных переменных. Проект поддерживает современные шрифты (Manrope, JetBrains Mono) и легко расширяется новыми компонентами.

## Особенности

- Next.js 15, React 19
- Стилизация через SCSS с переменными и миксинами
- Кастомные кнопки и типографика
- Импорт и настройка шрифтов Manrope и JetBrains Mono
- Готовая структура для расширения UI-компонентами

## Структура проекта

- `app/` — основной каталог приложения
  - `layout.jsx` — глобальное подключение шрифтов и стилей
  - `page.jsx` — пример использования кнопок
  - `styles/` — SCSS-переменные и элементы
- `public/` — статические файлы и иконки
- `package.json` — зависимости и скрипты

## Установка и запуск

```bash
npm install
npm run dev
```

Откройте [http://localhost:3000](http://localhost:3000) в браузере.

### Сборка и запуск продакшн-версии

```bash
npm run build
npm start
```

## Используемые технологии

- [Next.js](https://nextjs.org)
- [React](https://react.dev)
- [Sass (SCSS)](https://sass-lang.com)
- [Google Fonts](https://fonts.google.com)

## Пример использования

```jsx
<div className="button-accent button">Button</div>
<div className="button-white button">Button</div>
<div className="button-black button">Button</div>
```

## Документация

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/learn)
- [Sass Documentation](https://sass-lang.com/documentation)

## Деплой

Самый простой способ деплоя — [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Подробнее: [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying)
