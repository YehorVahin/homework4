# Порівняння HTML, CSS і JavaScript

Навчальна сторінка з невеликою таблицею порівняння трьох базових технологій веброзробки.

**Опублікована сторінка:** https://yehorvahin.github.io/homework4/

## Мета

Потренуватися з контентним контейнером, локальним шрифтом, семантичною таблицею та базовою нормалізацією стилів.

## Використані технології

- HTML5: семантична таблиця (`caption`, `thead`, `tbody`, `th` зі `scope="col"` і `scope="row"`, `td`)
- CSS3: контентний контейнер (`max-width` + `margin-inline: auto`), `border-collapse`, внутрішні відступи комірок, чергування кольорів рядків (`:nth-child`), нормалізація стилів
- Локальний шрифт у форматі WOFF2 через `@font-face` із системним fallback: `"Inter Local", system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif`
- GitHub Pages для публікації

## Структура репозиторію

```
index.html
style.css
fonts/
  Inter-Regular-subset.woff2
  Inter-Bold-subset.woff2
  LICENSE.txt
README.md
```

## Шрифт

Inter (Regular і Bold), підмножина Basic Latin + Cyrillic, конвертована у WOFF2.
Ліцензія SIL Open Font License 1.1, див. `fonts/LICENSE.txt`.

## Перевірка

Сторінку фактично перевірено у Google Chrome. Друге середовище Firefox. Локальний шрифт завантажується коректно, таблиця та контентний контейнер відображаються стабільно.

