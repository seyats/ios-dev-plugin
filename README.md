# iOS Dev Plugin

Профессиональный набор инструментов для разработки iOS приложений на SwiftUI с фокусом на производительность, отладку и оптимизацию.

## Возможности

**Разработка**
- Паттерны и лучшие практики SwiftUI
- Интеграция App Intents и App Shortcuts
- Поддержка Liquid Glass API (iOS 26+)

**Производительность**
- Аудит производительности SwiftUI
- Обнаружение утечек памяти
- ETTrace профилирование для фокусных потоков приложения

**Отладка**
- Отладка iOS приложений на симуляторе
- Зеркалирование симулятора в браузер
- Горячая перезагрузка SwiftUI превью

**Рефакторинг**
- Разложение больших view компонентов
- Рекомендации по оптимизации кода
- Паттерны с приоритетом производительности

## Быстрый старт

```bash
# Распакуй плагин
tar -xzf ios-dev-plugin.tar.gz

# Используй в своём проекте
cp -r ios-dev-plugin/skills ./your-project/
```

## Включённые Skills

| Skill | Назначение |
|-------|-----------|
| `ios-debugger-agent` | Отладка iOS приложений на симуляторе |
| `ios-simulator-browser` | Зеркалирование симулятора в браузер |
| `ios-ettrace-performance` | Профилирование производительности приложения |
| `ios-memgraph-leaks` | Обнаружение утечек памяти |
| `ios-app-intents` | Создание App Intents и App Shortcuts |
| `swiftui-liquid-glass` | Реализация Liquid Glass UI |
| `swiftui-performance-audit` | Аудит производительности SwiftUI |
| `swiftui-ui-patterns` | Применение лучших практик UI |
| `swiftui-view-refactor` | Оптимизация структуры view |

## Требования

- Xcode 15+
- iOS 15+
- Swift 5.9+

## Документация

Каждый skill включает подробную документацию в файле `SKILL.md` с:
- Инструкциями по настройке
- Примерами использования
- Лучшими практиками
- Шаблонами кода

## Структура проекта

```
ios-dev-plugin/
├── .codex-plugin/       # Манифест плагина
├── .mcp.json            # Конфиг MCP
├── skills/              # 9 профессиональных skills
│   ├── ios-debugger-agent/
│   ├── ios-simulator-browser/
│   ├── ios-ettrace-performance/
│   ├── ios-memgraph-leaks/
│   ├── ios-app-intents/
│   ├── swiftui-liquid-glass/
│   ├── swiftui-performance-audit/
│   ├── swiftui-ui-patterns/
│   └── swiftui-view-refactor/
├── agents/              # Метаданные агентов
└── assets/              # Ресурсы плагина
```

## Использование

1. **Клонируй репозиторий**
   ```bash
   git clone https://github.com/seyats/ios-dev-plugin.git
   ```

2. **Интегрируй skills в свой проект**
   ```bash
   cp -r ios-dev-plugin/skills ./your-ios-project/
   ```

3. **Следуй документации каждого skill**
   - Открой `skills/[skill-name]/SKILL.md`
   - Примени рекомендации в своём коде

## Лицензия

MIT

---

**Создано на основе OpenAI Codex Plugin Framework**
