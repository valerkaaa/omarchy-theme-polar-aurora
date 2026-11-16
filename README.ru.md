<div align="center">

<img src="preview.png" alt="Polar Aurora — тема для Omarchy" width="100%">

# Polar Aurora

[English](README.md) · **Русский**

**Тёмная тема для Omarchy: полярная ночь, северное сияние и мятно-бирюзовый акцент, который не мешает.**

[![License](https://img.shields.io/badge/license-MIT-ffcead)](LICENSE)
[![Omarchy 4](https://img.shields.io/badge/Omarchy-4-0a1130)](#установка)

</div>

---

## Установка

```bash
omarchy theme install https://github.com/valerkaaa/omarchy-theme-polar-aurora
omarchy theme set "Polar Aurora"
```

Или руками:

```bash
git clone https://github.com/valerkaaa/omarchy-theme-polar-aurora \
  ~/.config/omarchy/themes/polar-aurora
omarchy theme set "Polar Aurora"
```

В теме нет ни одного `*.lua` и нет конфигов терминалов, поэтому при установке
ничего не отбрасывается — Omarchy генерирует их из `colors.toml`.

## Что внутри

- **Пять обоев** в `backgrounds/` — переключаются через `omarchy theme bg next`:
  сияние над соснами, фиолетовый дрейф, бирюзовый горизонт, замёрзшее озеро,
  заснеженная хижина.
- **Градиентная рамка окон** — от мятного к фиолетовому под 45°, приглушённый
  сланец в неактивном окне.
- **Тема для всего, что Omarchy умеет темизировать**: Hyprland, бар и его панели,
  лаунчер, Alacritty, Foot, Kitty, Ghostty, btop, Helix, Neovim, VS Code,
  Chromium, fcitx5, Claude, Hermes.
- **Экран блокировки и превью** (`unlock.png`, `preview.png`,
  `preview-unlock.png`), чтобы тема правильно выглядела в выборе тем.

## Палитра

| Роль | Цвет | |
|---|---|---|
| акцент | `#63e6c4` | мятно-бирюзовый, сияние |
| второй акцент | `#bd8cff` | фиолетовый, вторая полоса |
| фон | `#0b1220` | полярная ночь |
| фон темнее | `#04070e` | |
| текст | `#d6e6f7` | подсвеченный снегом |
| выделение | `#1e3350` | |
| приглушённый | `#3d5273` | |
| красный / жёлтый / зелёный / циан / синий / маджента | `#f4778f` `#f0d27d` `#7ce3a2` `#5ed9e8` `#7fa8f5` `#bd8cff` | |

Полный набор, включая яркие варианты, — в [`colors.toml`](colors.toml).

## Заметки

- Тема иконок — `Yaru-prussiangreen-dark`, идёт вместе с Omarchy.
- Подсветка клавиатуры — `#63e6c4`, для клавиатур, которые это умеют.
- Всё генерируется из `colors.toml`: правь его и переприменяй тему, чтобы
  поменять весь рабочий стол разом.

## Лицензия

MIT — см. [LICENSE](LICENSE). Тема для Omarchy, с Omarchy не связана.
