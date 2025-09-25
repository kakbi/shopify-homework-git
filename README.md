# [ДЗ] Shopify - Робота з Git

## 📋 Опис завдання

Створити Dev-store у Partner Dashboard.
Встановити тему Dawn.
Завантажити тему через CLI: shopify theme pull
Створити репозиторій shopify-<назва-стору> на GitHub.
Завантажити код у GitHub.
Створити гілку dev від main.
Прив’язати обидві теми до GitHub у Shopify Admin (main/dev).
Створити feature-гілку, змінити секцію, зробити commit.
Відкрити PR → merge у dev.

## ✅ Реалізований функціонал

-   [x] Створив тему Dawn
-   [x] Клонування теми до VSC
-   [x] Створив гілки main, dev
-   [x] З'єднав з темою git; oкремо main-гілку, окремо dev-гілку.
-   [x] Зміна кольору секції в Customize.
-   [x] Створення гілки `feature/update-color-section` для роботи з новими змінами.
-   [x] Завантаження змін в локальну гілку через команду `shopify theme pull`.
-   [x] Підготовка Pull Request для мерджу в гілку `dev`, потім в main.

## 🔧 Технології та підходи

-   Shopify CLI для роботи з темами.
-   Git для управління версіями.
-   GitHub для роботи з PR.

## 🔗 Пов'язані ресурси

-   [Нотатка в Asana](https://app.asana.com/1/442123638460530/project/1211341031819481/task/1211341031819502)
-   [Shopify CLI Documentation](https://shopify.dev/tools/theme-cli)
