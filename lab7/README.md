# ЛР7. Покращення доступності вебсторінок

Основа — навчальний проєкт [kipz_tov/a11y-practical-task](https://gitlab.com/kipz_tov/a11y-practical-task) (завдання з курсу «Introduction to Web Accessibility WCAG 2.1»). Перший коміт ЛР7 — оригінал, наступні — виправлення, тож зміни видно в `git log -p -- lab7`.

**main.html** (11 пунктів): заголовок сторінки, `lang="en-GB"`, посилання «Skip to main content», ієрархія h1–h3, орієнтири header / nav / main / footer, видалено позитивні `tabindex`, контраст кольорів, `alt` для зображень, `figure` / `blockquote` для відгуків, `aria-label` для посилань і кнопок, посилання футера в списках.

**form.html** (3 пункти): мітки `label for`, обов’язкові поля (`required`, `aria-required`, позначка *), група доставки у `fieldset` / `legend`.

| Перевірка axe-core (WCAG 2.1 A/AA) | до | після |
|---|---|---|
| main.html | 130 порушень | 0 |
| form.html | 23 порушення | 0 |

Звіт: `ЛР7_Дзядзін_ІПЗ-24-2.docx`.
