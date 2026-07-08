# Calendar Event Scheduler
![Image](https://github.com/user-attachments/assets/44443874-b415-4b24-97b5-51a2b351dc53)


A modern, responsive web app that merges a **monthly calendar** with a **timed event / to-do list**. Pick future (or today’s) dates, set hours and minutes, write a short note, then **add**, **edit**, or **delete** events. The UI uses a dark **glassmorphism** style, subtle **Framer Motion** transitions, and **Sonner** toasts for feedback. All event data lives in the browser via **`localStorage`**—there is **no server database** and **no REST API** in this repo.


## 🛠️ Стек
* **Фреймворк:** Next.js 15 (App Router) + React 19 + TypeScript
* **Стили и анимация:** Tailwind CSS v4 + Framer Motion
* **Хранение данных:** `localStorage` (данные сохраняются в браузере)




## 🛫 Инструкция по локальному запуску (Пошаговое руководство)

Выполните эти команды по очереди в вашем терминале (Bash, Zsh или Git Bash):

```bash
# =========================================================================
# ШАГ 1: Клонирование репозитория
# Скачиваем все исходные файлы проекта с удаленного сервера GitHub на ваш ПК.
# Замените 'YOUR_REPO_NAME' на фактическое имя вашей папки репозитория.
# =========================================================================
git clone [https://github.com/b4631119-oss/YOUR_REPO_NAME.git](https://github.com/b4631119-oss/YOUR_REPO_NAME.git)


# =========================================================================
# ШАГ 2: Переход в директорию проекта
# Перемещаем указатель терминала внутрь скачанной папки. 
# Все последующие команды должны выполняться строго внутри корня проекта!
# =========================================================================
cd YOUR_REPO_NAME


# =========================================================================
# ШАГ 3: Установка зависимостей
# Скачиваем и устанавливаем локально все библиотеки, указанные в package.json 
# (Next.js, React, Tailwind, Lucide-иконки). Создается папка node_modules.
# =========================================================================
npm install


# =========================================================================
# ШАГ 4: Запуск локального сервера для разработки
# Компилируем проект и запускаем локальный веб-сервер.
# Поддерживается Fast Refresh — изменения в коде сразу видны в браузере.
# =========================================================================
npm run dev
```