# AI usage log

| Date | Work | Purpose | Tool/model | Human contribution and verification | Disclosure needed? |
| --- | --- | --- | --- | --- | --- |
| YYYY-MM-DD | _link_ | _e.g., critique, explanation_ | _tool/version_ | _what I checked/rewrote_ | _yes/no/course policy_ |
| 2026-10-02 | [[git-vs-github]], [[2026-vvit-lecture-01-git]], `wiki/index.md`, `wiki/glossary.md`, `templates/concept.md` | ревью базы знаний; перенос заметки из шаблона в `wiki/concepts/`, исправление frontmatter и опечаток, составление source-карточки по слайдам, восстановление шаблона | Claude Code / claude-opus-5-5 | формулировки заметки мои, LLM их не переписывала; замечания ревью и extract карточки не сверены — статус `needs-review` | course policy |
| 2026-11-24 | [[2026-ml-notebooks-rus-v18]], [[machine-learning-course-roadmap]], `wiki/index.md`, `wiki/glossary.md`, `wiki/open-questions.md`, `log/ingest.md` | каталогизация локального архива notebook и составление учебной карты знаний | Copilot SDK / AI assistant | структура архива, количество файлов и библиотеки просмотрены автоматически; права, авторство, воспроизводимость и отдельные определения датасетов не проверены — статус `needs-review` | course policy / unknown rights |
| 2026-11-24 | `.github/agents/uchitel.agent.md` | создание кастомного агента-преподавателя по спецификации пользователя | Codex / GPT-6 | пользователь предоставил требования; адаптированы правила постоянной памяти с учётом append-only журналов и границ папок репозитория; профиль ученика оставлен предварительным | course policy |
| 2026-11-24 | `study/` | сохранение результатов вводного занятия по SQL и следующего шага по просьбе пользователя | Codex / GPT-6 | запись отражает ответы в диалоге; освоение SQL помечено предварительным, выполнение запросов в БД не проверялось | no |
| 2026-11-24 | `.github/agents/uchitel.agent.md` | улучшение преподавателя: иерархия источников, проверка фактов, provenance, ограничения веб-доступа и учёт ссылок в `study/SOURCES.md` | Copilot SDK / GPT-6 Luna | правила адаптированы к `AGENTS.md`: материалы курса и первоисточники в приоритете, неподтверждённое маркируется, `raw/` защищён, журналы append-only | course policy |

- 2026-11-26 — Vacancy Coach / ChatGPT: summarized learning dialogue, checked answers and prepared a progress note at `learning/reflections/ml-engineer-progress.md`; user reviewed before publishing.
