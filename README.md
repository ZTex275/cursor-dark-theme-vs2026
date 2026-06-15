# Dark Theme VS2026

![Visual Studio 2026 Dark](images/icon.png)

---

## English

Dark theme for [Cursor](https://cursor.com) and [Visual Studio Code](https://code.visualstudio.com) with **Visual Studio 2026** syntax highlighting and the native **Cursor Dark** UI.

### Features

- **VS2026 syntax highlighting** — keyword, type, function, string, and comment colors inspired by Visual Studio.
- **Cursor UI** — panels, tabs, sidebar, and terminal inherit the built-in Cursor Dark theme instead of default VS Code styling.
- **Semantic highlighting** — LSP-based semantics for C#, C/C++, and more.
- **Broad language support** — dedicated rules for C, C++, C#, Go, Java, Python, HTML, XML, JSON, Shell, CMake, and others.

### Color palette

| Element | Color |
| --- | --- |
| Text | `#DCDCDC` |
| Comments | `#57A64A` |
| Strings | `#D69D85` |
| Keywords | `#569CD6` |
| Control keywords (C#) | `#D8A0DF` |
| Types / classes | `#4EC9B0` |
| Interfaces / enums | `#B8D7A3` |
| Functions / methods | `#DCDCAA` |
| Variables | `#9CDCFE` |
| Numbers | `#B5CEA8` |

### Installation

#### From Marketplace

1. Open the Extensions panel (`Ctrl+Shift+X`).
2. Search for **Dark Theme VS2026**.
3. Click **Install**.

#### From source

```bash
git clone https://github.com/ZTex275/cursor-dark-theme-vs2026.git
cd cursor-dark-theme-vs2026
```

In Cursor / VS Code: **Extensions** → `...` → **Install from VSIX...** (after building, see below)  
or open the extension folder in development mode (**Run Extension**).

#### Build VSIX

```bash
npm install -g @vscode/vsce
vsce package
```

Install the resulting `.vsix` via **Install from VSIX...**.

### Activation

1. Press `Ctrl+K`, then `Ctrl+T` (or **File → Preferences → Theme → Color Theme**).
2. Select **Visual Studio 2026 Dark**.

After updating the theme, reload the window: **Developer: Reload Window**.

### How it works

The theme is split into two parts:

| File | Purpose |
| --- | --- |
| `themes/base/cursor-workbench.json` | Cursor UI colors (panels, menus, tabs, etc.) |
| `themes/dark-color-theme.json` | VS2026 syntax highlighting (`tokenColors`, `semanticTokenColors`) |

This gives you familiar Visual Studio code colors without replacing the Cursor editor chrome.

### Requirements

- Cursor or Visual Studio Code **1.85.0** or newer

### License

MIT

### Author

**ZTex275** — [airflow275@gmail.com](mailto:airflow275@gmail.com)

Based on [vscode-dark-theme-vs2022](https://github.com/SoVoKaN/vscode-dark-theme-vs2022) by SoVoKaN.

---

## Русский

Тёмная тема для [Cursor](https://cursor.com) и [Visual Studio Code](https://code.visualstudio.com) с подсветкой синтаксиса в стиле **Visual Studio 2026** и нативным интерфейсом **Cursor Dark**.

### Особенности

- **Подсветка синтаксиса VS2026** — цвета ключевых слов, типов, функций, строк и комментариев как в Visual Studio.
- **Интерфейс Cursor** — панели, вкладки, боковая панель и терминал наследуются от встроенной темы Cursor Dark, без «чужого» оформления VS Code.
- **Семантическая подсветка** — поддержка LSP-семантики для C#, C/C++ и других языков.
- **Широкая поддержка языков** — отдельные правила для C, C++, C#, Go, Java, Python, HTML, XML, JSON, Shell, CMake и др.

### Палитра

| Элемент | Цвет |
| --- | --- |
| Текст | `#DCDCDC` |
| Комментарии | `#57A64A` |
| Строки | `#D69D85` |
| Ключевые слова | `#569CD6` |
| Управляющие конструкции (C#) | `#D8A0DF` |
| Типы / классы | `#4EC9B0` |
| Интерфейсы / enum | `#B8D7A3` |
| Функции / методы | `#DCDCAA` |
| Переменные | `#9CDCFE` |
| Числа | `#B5CEA8` |

### Установка

#### Из Marketplace

1. Откройте панель расширений (`Ctrl+Shift+X`).
2. Найдите **Dark Theme VS2026**.
3. Нажмите **Install**.

#### Из исходников

```bash
git clone https://github.com/ZTex275/cursor-dark-theme-vs2026.git
cd cursor-dark-theme-vs2026
```

В Cursor / VS Code: **Extensions** → `...` → **Install from VSIX...** (после сборки, см. ниже)  
или откройте папку расширения в режиме разработки (**Run Extension**).

#### Сборка VSIX

```bash
npm install -g @vscode/vsce
vsce package
```

Установите полученный `.vsix` через **Install from VSIX...**.

### Активация

1. `Ctrl+K`, затем `Ctrl+T` (или **File → Preferences → Theme → Color Theme**).
2. Выберите **Visual Studio 2026 Dark**.

После обновления темы перезагрузите окно: **Developer: Reload Window**.

### Как устроена тема

Тема состоит из двух частей:

| Файл | Назначение |
| --- | --- |
| `themes/base/cursor-workbench.json` | Цвета интерфейса Cursor (панели, меню, вкладки и т.д.) |
| `themes/dark-color-theme.json` | Подсветка синтаксиса VS2026 (`tokenColors`, `semanticTokenColors`) |

Такой подход даёт привычные цвета кода из Visual Studio без замены оформления редактора Cursor.

### Требования

- Cursor или Visual Studio Code **1.85.0** и новее

### Лицензия

MIT

### Автор

**ZTex275** — [airflow275@gmail.com](mailto:airflow275@gmail.com)

Основано на теме [vscode-dark-theme-vs2022](https://github.com/SoVoKaN/vscode-dark-theme-vs2022) от SoVoKaN.
