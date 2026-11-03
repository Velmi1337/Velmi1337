# Expressive Profile

Renderer: https://github.com/metawka/expressive-profile (MIT), pinned to a reviewed commit.
Configuration: `profile.json`. Daily update: `.github/workflows/expressive-profile.yml`.
The workflow uses the profile repository's built-in `github.token`, not a personal token or private-repository secret.
The generator writes README and light/dark SVG cards; real public GitHub data supplies the statistics.
The previous bilingual README is preserved in `.profile/README-before-expressive.md`.

Google Sans Flex / Roboto Flex fonts: SIL OFL 1.1. Material Symbols: Apache-2.0.
Icons in `.profile/icons.json` are copied from Google's Material Symbols rounded set.
Animated SVGs respect `prefers-reduced-motion`. Set `motion: false` for fully static cards.

## Русский

Профиль создан с Expressive Profile, обновляется ежедневно и использует только встроенный токен репозитория.
Личного токена и доступа к закрытым репозиториям не добавлено. Статистика берётся из настоящих публичных данных GitHub.
Исходный текст README сохранён рядом. Оформление меняется через `profile.json`.
