<!--
Автоматически подставляется в описание PR. Заполните все секции.
-->

## Связанное issue

Closes #<N>

## Что изменено

<кратко по пунктам>

## Чем проверено

- [ ] `uv run ty check <каталог>` и `uv run ruff check <каталог>` (+ `ruff format --check <каталог>`) — по каждому затронутому каталогу
- [ ] pytest: <набор и результат, например `sh scripts/back-test.sh test` — 24 passed>
- [ ] Для UI-изменений: Selenium `front/tests` **и** Playwright `front/tests/playwright`

## Секреты

- [ ] Я не читал(а) и не коммитил(а) `vk_auth.json`, `miminet_secret.conf`, `client_yandex.json`, `front/.env`, `back/.env`

## Handoff

- [ ] Заполнен шаблон `.team/templates/handoff.md`, текст приложен к этому PR
- [ ] Строка добавлена в `.team/session-log.md`
