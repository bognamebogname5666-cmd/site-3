# AWE - Alpha Wash Equipment Website

Сайт для компании Alpha Wash Equipment - профессиональное оборудование для моек самообслуживания.

## Развертывание на Vercel

### Способ 1: Через Git (Рекомендуется)

1. **Создайте репозиторий на GitHub:**
   - Зайдите на https://github.com
   - Нажмите "New repository"
   - Назовите репозиторий (например, `awe-website`)
   - Сделайте его публичным или приватным
   - Нажмите "Create repository"

2. **Загрузите файлы в репозиторий:**
   - Нажмите "uploading an existing file"
   - Перетащите файлы `index.html` и `vercel.json`
   - Нажмите "Commit changes"

3. **Подключите к Vercel:**
   - Зайдите на https://vercel.com
   - Нажмите "Add New Project"
   - Выберите "Import Git Repository"
   - Найдите ваш репозиторий и нажмите "Import"
   - Нажмите "Deploy"

### Способ 2: Через Vercel CLI

1. **Установите Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Войдите в аккаунт:**
   ```bash
   vercel login
   ```

3. **Разверните проект:**
   ```bash
   cd путь/к/папке/с/файлами
   vercel
   ```

### Способ 3: Drag & Drop (Самый простой)

1. Зайдите на https://vercel.com/new
2. Выберите вкладку "Deploy from template" или просто перетащите папку с файлами
3. Перетащите папку с `index.html` и `vercel.json` в окно браузера
4. Дождитесь завершения деплоя

## Структура проекта

```
├── index.html      # Главная страница сайта
├── vercel.json     # Конфигурация для Vercel
└── README.md       # Этот файл
```

## Важные замечания

- Файл **ДОЛЖЕН** называться `index.html` (не `index_html.html`)
- Файл должен находиться в корне проекта
- После развертывания Vercel автоматически предоставит домен вида `your-project.vercel.app`

## Настройка собственного домена

После успешного развертывания:

1. Зайдите в настройки проекта на Vercel
2. Перейдите в раздел "Domains"
3. Добавьте ваш домен
4. Следуйте инструкциям по настройке DNS

## Контакты

Сайт создан для Alpha Wash Equipment
- Телефон: +373 68 42 50 26
- Email: alphawash.ro@gmail.com
