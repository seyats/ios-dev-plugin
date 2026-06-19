---
name: ios-dev-plugin
description: Профессиональный набор инструментов для разработки iOS приложений на SwiftUI с фокусом на производительность, отладку и оптимизацию.
---

# iOS Dev Plugin

Комплексный плагин для разработки, отладки и оптимизации iOS приложений на SwiftUI.

## Включённые Skills

### 1. ios-app-intents
Создание App Intents, App Entities и App Shortcuts для системных поверхностей iOS.

### 2. ios-debugger-agent
Отладка iOS приложений на симуляторе с поддержкой XcodeBuildMCP для сборки, запуска и отладки.

### 3. ios-ettrace-performance
Захват и анализ ETTrace профилей для выявления узких мест производительности.

### 4. ios-memgraph-leaks
Обнаружение и анализ утечек памяти через memgraph захват и анализ.

### 5. ios-simulator-browser
Зеркалирование iOS симулятора в браузер с поддержкой горячей перезагрузки SwiftUI превью.

### 6. swiftui-liquid-glass
Реализация и проверка Liquid Glass UI для iOS 26+ с использованием нативных API.

### 7. swiftui-performance-audit
Аудит производительности SwiftUI кода с выявлением проблем и рекомендациями.

### 8. swiftui-ui-patterns
Построение и рефакторинг SwiftUI UI с использованием проверенных паттернов и примеров.

### 9. swiftui-view-refactor
Рефакторинг больших SwiftUI view в стабильные, тестируемые компоненты.

## Быстрый старт

1. Выбери нужный skill из папки `skills/`
2. Прочитай `SKILL.md` в папке skill
3. Следуй инструкциям и примерам кода
4. Используй `references/` для справочной информации

## Требования

- Xcode 15+
- iOS 15+
- Swift 5.9+

## Структура

```
ios-dev-plugin/
├── SKILL.md                 ← Этот файл
├── README.md                ← Документация
├── skills/                  ← 9 профессиональных skills
│   ├── ios-app-intents/
│   ├── ios-debugger-agent/
│   ├── ios-ettrace-performance/
│   ├── ios-memgraph-leaks/
│   ├── ios-simulator-browser/
│   ├── swiftui-liquid-glass/
│   ├── swiftui-performance-audit/
│   ├── swiftui-ui-patterns/
│   └── swiftui-view-refactor/
├── agents/                  ← Конфиг OpenAI
└── assets/                  ← Иконки и логотипы
```

## Использование в проекте

```bash
# Клонируй репозиторий
git clone https://github.com/seyats/ios-dev-plugin.git

# Скопируй нужные skills в свой проект
cp -r ios-dev-plugin/skills/swiftui-ui-patterns ./your-project/

# Используй документацию и примеры
cat ios-dev-plugin/skills/swiftui-ui-patterns/SKILL.md
```

## Лучшие практики

1. **Начни с документации** — каждый skill имеет подробный SKILL.md
2. **Используй примеры** — в `references/` есть готовые паттерны
3. **Профилируй код** — используй performance audit перед релизом
4. **Отлаживай на симуляторе** — используй debugger-agent для быстрой итерации

## Поддержка

Каждый skill содержит:
- Пошаговые инструкции
- Примеры кода
- Справочные материалы
- Лучшие практики iOS разработки

---

Создано на основе OpenAI Codex Plugin Framework
