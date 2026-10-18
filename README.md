# [Ba4ana.github.io](https://ba4ana.github.io/)
Страница приветствия

## Версионирование Git

Для коммитов ветки `main` действует схема `v.MAJOR.MINOR.PATCH`. Новый `PATCH` не превышает `99`; после `v.X.Y.99` следующий коммит получает `v.X.(Y+1).1`. Старые номера не переписываются. Правило проверяется через [GitHub Actions](.github/workflows/version-policy.yml), общий источник — [инструкции ai-passport](https://github.com/Ba4ana/ai-passport/blob/main/AGENTS.md).
