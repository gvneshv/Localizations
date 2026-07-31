# Localizations

A collection of localization projects, including movie subtitle translations and, potentially, game translations in the future.

---

## 🌐 Language

- 🇺🇦 [Українська](#-українська)
- 🇬🇧 [English](#-english)

---

# 🇺🇦 Українська

## Про репозиторій

Цей репозиторій містить проєкти з локалізації, зокрема переклади субтитрів до фільмів. У майбутньому тут також можуть з'явитися локалізації ігор або інших матеріалів.

Усі переклади виконуються мною у вільний час як некомерційні проєкти. Фільм публікується лише після завершення перекладу на 100% — часткові версії не викладаються.

---

## Структура репозиторію

```
Localizations/
├── README.md
├── LICENSE
└── movies/
      └── <назва-фільму>/
            ├── README.md              # інформація про фільм, доступні мови
            └── <код-мови>/            # напр. uk
                  ├── README.md        # статистика перекладу, інструкція із завантаження
                  ├── subtitles.srt
                  └── screenshots/
```

Кожен проєкт перекладу зберігається у власній папці всередині `movies/`. Усередині — окрема підпапка для кожної мови перекладу (наприклад, `uk/`), що дозволяє додавати переклади іншими мовами в майбутньому, у тому числі від інших контриб'юторів.

### Правило іменування

Назви папок і файлів пишуться англійською, малими літерами, слова розділені дефісом (kebab-case). Приклад: `dear-zachary-a-letter-to-a-son-about-his-father/`.

Причина: такі назви однаково коректно працюють у Windows/Linux/macOS, не містять пробілів, добре виглядають в URL і легко шукаються.

---

## Доступні переклади

| Назва | Тип | Мова перекладу | Статус | Посилання |
|---|---|---|---|---|
| Dear Zachary: A Letter to a Son About His Father | Фільм (документальний) | 🇺🇦 Українська | ✅ Завершено | [Перейти](movies/dear-zachary-a-letter-to-a-son-about-his-father/) |

Наразі триває робота над наступним перекладом. Він з'явиться в цій таблиці після завершення — часткові версії не публікуються.

---

## Ліцензія

Переклади субтитрів, розміщені в цьому репозиторії, поширюються за ліцензією **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0)**.

Коротко це означає:

- ✅ можна вільно завантажувати й використовувати переклад для особистих некомерційних цілей;
- ✅ обов'язково вказувати автора перекладу з посиланням на цей репозиторій;
- ❌ не можна використовувати в комерційних цілях;
- ❌ не можна публікувати змінену або похідну версію перекладу під іншим авторством.

Повний текст ліцензії — у файлі [LICENSE](LICENSE).

Це стосується лише текстів перекладу. Права на самі фільми, ігри та інші оригінальні матеріали належать їхнім правовласникам.

> Локалізації ігор (якщо з'являться в майбутньому) можуть публікуватися на інших умовах, які будуть зазначені окремо для кожного такого проєкту — оскільки розповсюдження змінених файлів гри регулюється умовами використання самої гри, а не лише авторським правом на переклад.

---

## Контакти

Якщо ви знайшли помилку, маєте пропозицію або хочете зв'язатися зі мною:

- GitHub Issues
- Email: <gvneshv.localizes@gmail.com>

---

# 🇬🇧 English

## About

This repository contains localization projects, including movie subtitle translations. In the future, it may also include game localizations and other translation-related projects.

All translations are created in my free time as non-commercial projects. A translation is only published once it's 100% complete — partial versions are not released.

---

## Repository Structure

```
Localizations/
├── README.md
├── LICENSE
└── movies/
      └── <movie-name>/
            ├── README.md              # movie info, available languages
            └── <lang-code>/           # e.g. uk
                  ├── README.md        # translation stats, download instructions
                  ├── subtitles.srt
                  └── screenshots/
```

Each translation project lives in its own folder under `movies/`. Inside, there's a separate subfolder per translated language (e.g. `uk/`), which leaves room for other languages to be added later, including by other contributors.

### Naming Convention

Folder and file names are written in English, in lowercase, with words separated by hyphens (kebab-case). Example: `dear-zachary-a-letter-to-a-son-about-his-father/`.

Reason: this format works identically across Windows/Linux/macOS, contains no spaces, reads cleanly in a URL, and is easy to search for.

---

## Available Translations

| Title | Type | Target Language | Status | Link |
|---|---|---|---|---|
| Dear Zachary: A Letter to a Son About His Father | Movie (documentary) | 🇺🇦 Ukrainian | ✅ Complete | [Open](movies/dear-zachary-a-letter-to-a-son-about-his-father/) |

Another translation is currently in progress. It will be added to this table once finished — partial versions aren't published.

---

## License

Subtitle translations in this repository are released under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0)** license.

In short:

- ✅ free to download and use for personal, non-commercial purposes;
- ✅ attribution to the translator with a link back to this repository is required;
- ❌ no commercial use;
- ❌ no publishing a modified or derivative version of the translation under different authorship.

Full license text: [LICENSE](LICENSE).

This applies only to the translation text itself. Rights to the original movies, games, and other source material belong to their respective owners.

> Game localizations (if added in the future) may be released under different terms, specified per project — since redistributing modified game files is governed by the game's own terms of use, not just copyright on the translation.

---

## Contact

If you found an issue, have a suggestion, or would like to get in touch:

- GitHub Issues
- Email: <gvneshv.localizes@gmail.com>