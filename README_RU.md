# APM — Пакетный менеджер и реестр языка Alca

[English](README.md) | [Русский](README_RU.md)

**APM** — это официальный пакетный менеджер, сервер реестра и веб-индекс библиотек для [языка программирования Alca](https://github.com/alca-lang/alca).

## Возможности
- **Воспроизводимые сборки**: Строгое SemVer-разрешение графа зависимостей и фиксирование версий в `alca.lock`.
- **Мультиплатформенность**: Атомарная сборка байткода и нативных артефактов под Windows, Linux и macOS.
- **Встроенный веб-портал**: Индекс пакетов в стиле PyPI с поиском, управлением токенами и библиотекой.
- **Интерактивная документация**: Подробная документация в стиле Arch Linux Wiki и Python Docs.
- **Безопасность**: Проверка контрольных сумм SHA-256, токены доступа и защита от Zip-Slip.

## Установка
```powershell
# Windows PowerShell
irm https://raw.githubusercontent.com/alca-lang/apm/master/scripts/install.ps1 | iex
```

```bash
# Linux / macOS
curl -fsSL https://raw.githubusercontent.com/alca-lang/apm/master/scripts/install.sh | bash
```

## Быстрый старт
```bash
# Создание нового пакета
apm init my-lib

# Установка зависимостей
apm add mathutils

# Публикация в реестр
apm publish
```

## Лицензия
Apache-2.0
