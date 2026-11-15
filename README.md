# Ручные задания для курса «Алгоритмы и структуры данных» 📝

Задачи решаются **вручную и оформляются в формате Markdown**, без программного кода. Среда — [Visual Studio Code](https://code.visualstudio.com/). Виртуальное окружение Python здесь **не нужно**.

Инструкции курса (репозиторий [docs](https://github.com/hse-algo-ris-25-4/docs)):

- [Установка необходимого ПО](https://github.com/hse-algo-ris-25-4/docs/blob/main/installing-software.md) — GitHub, Git, VS Code, клонирование этого репозитория
- [Структура ветвления](https://github.com/hse-algo-ris-25-4/docs/blob/main/branching-model.md) — чем ручные задания отличаются от программных

Программные задания — в отдельном репозитории [code-tasks](https://github.com/hse-algo-ris-25-4/code-tasks). Правила веток и pull request там **другие**.

## С чего начать

1. Настроить VS Code по инструкции по установке ПО и **клонировать этот репозиторий** (`manual-tasks`).
2. Для превью Markdown и диаграмм Ганта / сетей поставьте расширения [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) и [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid).

Оформить решение: [руководство по Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637), формулы — [LaTeX](https://grammarware.net/text/syutkin/MathInLaTeX.pdf).

## Задания

Условия лежат в каталогах ветки `main`: `Задание 1`, `Задание 2`, … Каталог появляется, когда
преподаватель выдаёт задание; в нём — `README.md` с постановкой и правилами оформления.

Решение команды — файл `<название_команды>.md` **в том же каталоге** (не в корне репозитория).
Что именно должно быть в файле (вариант, ход решения, диаграммы) — в README задания.

Для работы создайте ветку **от `main`**, например `first-team-task-1`. В `main` напрямую
не коммитьте.

Список заданий в этом семестре ведётся на доске Projects организации — ссылка появится здесь, когда будет выдано первое задание.

## Результат выполнения задания: pull request

Это не `code-tasks`: здесь pull request открывают **в `main`**, и после ревью его **вливают**.

- **base** — `main`, **compare** — ваша ветка (`first-team-task-3`).
- Замечания правят новым коммитом в ту же ветку, новый pull request создавать не нужно.
- После одобрения изменения попадают в `main`: там остаются и условия, и решения команд. Эти материалы можно использовать для подготовки к контрольным работам и экзаменам по дисциплине.
