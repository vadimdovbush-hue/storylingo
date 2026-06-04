# StoryLingo — Deploy Instructions

## Структура файлів

```
storylingo/
├── index.html                    ← головна сторінка
├── netlify.toml                  ← конфіг Netlify
├── netlify/
│   └── functions/
│       └── generate.js           ← проксі до Anthropic API
└── README.md
```

## Деплой на Netlify (покроково)

### 1. Завантаж файли на GitHub

```bash
git init
git add .
git commit -m "StoryLingo MVP"
git remote add origin https://github.com/YOUR_USERNAME/storylingo.git
git push -u origin main
```

### 2. Підключи репозиторій до Netlify

- Зайди на netlify.com → Add new site → Import from Git
- Вибери репозиторій storylingo
- Build command: (залиш порожнім)
- Publish directory: . (крапка)
- Натисни Deploy

### 3. Додай API ключ як змінну середовища

- Site settings → Environment variables → Add variable
- Key:   `ANTHROPIC_API_KEY`
- Value: `sk-ant-api03-...` (твій ключ з console.anthropic.com)

### 4. Перероби деплой (якщо вже задеплоєно)

- Deploys → Trigger deploy → Deploy site

## Отримати Anthropic API ключ

1. console.anthropic.com
2. Sign up або Log in
3. API Keys → Create Key
4. Скопіюй ключ (починається з sk-ant-api03-)

## Ціна API

- ~$0.003 за генерацію 500 слів
- 1000 генерацій = ~$3
- Маржа при $7.99/місяць: ~95%
