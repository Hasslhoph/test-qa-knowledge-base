# QA База знаний — iThive

> База знаний для QA-тестирования модулей платформы **iThive**.
> Работает через **Obsidian** + **opencode** с AI-субагентами.

---

## Что внутри

| Раздел | Описание |
|--------|----------|
| 📖 [Инструкции](Instructions/) | Пошаговые руководства по каждому модулю |
| 🧩 [Модули](Modules/) | Описания модулей и их связи |
| ✅ [Тест-кейсы](Test%20Cases/) | Чек-листы проверок для QA |
| 🗂 [Шаблоны](Templates/) | Шаблоны для новых документов |

## Быстрый старт

### Для QA-инженеров

1. Установи [Obsidian](https://obsidian.md)
2. Открой эту папку как vault
3. Начни с [[00 - Index]] — главная точка входа

### Для настройки AI-субагентов

Полная инструкция по настройке opencode, подключению субагентов и работе с AI:

👉 **[obsidian-team-setup/README.md](obsidian-team-setup/README.md)**

Включает:
- Установка Obsidian (Mac + Windows)
- Установка opencode (Mac + Windows)
- Подключение субагентов: `@obsidian-indexer`, `@qa-teacher`, `@qaithive`
- Подключение нейросетей (Qwen, OpenAI, Anthropic)
- Сценарии работы с примерами

## Модули

| Модуль | Пакет |
|--------|-------|
| HelpDesk | `ithive.helpdesk` |
| База знаний | `ithive.knowledgebase` |
| Библиотека | `ithive.library` |
| Брендирование Битрикс24 | `ithive.changeportaldefaultheme` |
| Геймификация | `ithive.gamification` |
| Главная страница | `ithive.homepage` |
| Интерактивные подсказки | `ithive.hints` |
| Карта офиса + Бронирование | `ithive.workplaces` |
| Корпоративный университет | `ithive.ipr` |
| Мультиязычность | `ithive.b24multilanguage` |
| Настройка уведомлений | `ithive.imsettingsforall` |
| Опросы | `ithive.polls` |
| Оценка 360 | `ithive.assessment360` |
| Управление целями. Дерево | `ithive.goalsmanagement2` |
| Управление целями. Каскад | `ithive.goalsmanagement` |
| Фото и видео галерея | `ithive.mediagallery` |

## AI-субагенты

| Субагент | Задача |
|----------|--------|
| `@obsidian-indexer` | Индексирует инструкции в базу знаний |
| `@qa-teacher` | Отвечает на вопросы по модулям |
| `@qaithive` | Создаёт чек-листы проверок для QA |

## Технологии

- **[Obsidian](https://obsidian.md)** — база знаний с wikilinks
- **[opencode](https://opencode.ai)** — AI-ассистент в терминале
- **Qwen 3.6 Plus Free** — бесплатная AI-модель
