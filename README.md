# Дмитрий Борисюк

### Внешний финансовый директор. Смотрю на бизнес глазами банкира.

Двадцать лет в корпоративном кредитовании — кредитный анализ и реструктуризация в банках
(последнее место — Совкомбанк, CIB). Сейчас работаю финансовым директором на аутсорсе
для малого и среднего бизнеса и сам строю инструменты под эту работу: управленческий учёт,
финансовые модели, подготовка к банковскому финансированию.

Здесь лежит код. Финансовые кейсы — на сайте-портфолио, разбор задач — в канале.

[![Портфолио](https://img.shields.io/badge/Портфолио-кейсы_и_подход-1f6b4d?style=flat-square)](https://dabman1980.github.io/portfolio)
[![Telegram-канал](https://img.shields.io/badge/@FindirMoscow-канал-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/FindirMoscow)
[![Связь](https://img.shields.io/badge/@DmitryBorisyuk-связь-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/DmitryBorisyuk)

---

## Чем занимаюсь

**Финансы.** Управленческий учёт и отчётность, финансовые модели, экспресс-диагностика
подготовки компании к банковскому финансированию: что увидит в отчётности кредитный
аналитик и что стоит поправить заранее. Решение по кредиту принимает банк, моя часть —
подготовка и расчёты.

**Инструменты под эти задачи.** Ассистенты по документации на базе поиска по документам
(RAG), Telegram-боты, разбор отчётности и первичных документов, дашборды, обезличивание
документов перед отправкой в языковые модели.

**Принцип.** Модель готовит черновик, решение принимает человек. Каждое число в отчёте
прослеживается до первичного документа. Персональные данные и коммерческая тайна за пределы
российского контура не уходят — это заложено в код, а не в инструкцию.

---

## Проекты

### 🧾 [Портфолио: кредитный анализ и реструктуризация](https://github.com/Dabman1980/portfolio)
Сайт с обезличенными кейсами: перевод проблемного инвестиционного кредита в здоровое
обслуживание, лизинг вместо кредита с расчётом налогового эффекта. Исходники страниц.
`HTML` · `CSS` · `GitHub Pages` → [открыть сайт](https://dabman1980.github.io/portfolio)

### 🔒 [Anonymizer — обезличивание документов перед отправкой в LLM](https://github.com/Dabman1980/anonymizer)
Договоры, отчётность и меморандумы обезличиваются локально: имена, компании, счета и адреса
заменяются метками, ключ соответствия остаётся на компьютере. После работы модели текст
восстанавливается обратно. Данные не покидают машину.
`Python` · `docx/xlsx/pdf` · `regex` · `Natasha (NER)`

### 🛡 [Безопасный RAG-ассистент: роли, маскировка, границы данных](https://github.com/Dabman1980/per09-secure-rag-assistant)
Ролевой доступ к базе знаний: гость, аналитик и администратор видят разные документы,
персональные данные маскируются, часть документов не векторизуется вообще. Тест на утечку —
30 проверок из 30. Право на персональные данные даёт не роль, а пара «роль + куда уходят данные».
`Python` · `ChromaDB` · `bge-m3` · `Ollama / GigaChat / GPT`

### 🔁 [RAG-ассистент со сменным слоем языковых моделей](https://github.com/Dabman1980/per08-findir-rag-assistant)
Один поиск — три модели на выбор: локальная, российская и зарубежная через шлюз. Замер RAGAS
показал, что точность поиска у всех трёх одинакова (0,93), а достоверность ответа расходится
от 0,81 до 0,98 — то есть отвечает за выдумки модель, а не поиск.
`Python` · `ChromaDB` · `RAGAS` · `кэш на SQLite`

### 🔍 [Анализатор конкурентов ниши](https://github.com/Dabman1980/pem08-findir-competitor-monitor)
Разбор сайтов конкурентов по сегменту клиентов, ценообразованию и сигналам доверия: текст,
скриншот страницы целиком и пакетный прогон по нише. Веб-интерфейс и настольная версия.
`FastAPI` · `Selenium` · `Vision-модель` · `PyQt6`

**В приватных репозиториях** (там личные данные, публиковать нечего): секретарь-бот «Ася» —
входящие из текста, голоса, писем и скриншотов превращаются в события и задачи календаря,
работает круглосуточно на российском сервере; дневник силовых тренировок с разбором динамики
за четыре года.

---

## Стек

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-2CA5E0?style=flat-square&logo=telegram&logoColor=white)

Языковые модели — Claude, GPT, GigaChat, локальные через Ollama. Поиск по документам —
ChromaDB, Weaviate, Pinecone, эмбеддинги bge-m3, оценка качества через RAGAS.
Финансовая часть — 1С, Excel, ПланФакт, Финтабло.

---

## Статистика

![Основной язык](https://img.shields.io/github/languages/top/Dabman1980/per09-secure-rag-assistant?style=flat-square&color=3776AB)
![Последний коммит](https://img.shields.io/github/last-commit/Dabman1980/per09-secure-rag-assistant?style=flat-square&label=%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BD%D0%B8%D0%B9%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82&color=417068)
![Размер репозитория](https://img.shields.io/github/repo-size/Dabman1980/per09-secure-rag-assistant?style=flat-square&label=%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%80&color=417068)

График вкладов ниже GitHub рисует сам.

---

## Связь

- Telegram для связи — [@DmitryBorisyuk](https://t.me/DmitryBorisyuk)
- Канал о финансах для собственников — [@FindirMoscow](https://t.me/FindirMoscow)
- Кейсы — [dabman1980.github.io/portfolio](https://dabman1980.github.io/portfolio)

Услуги оказывает Борисюк Дмитрий Владимирович.
