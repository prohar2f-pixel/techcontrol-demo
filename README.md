# TECHCONTROL demo — GitHub Pages

Папка содержит готовую статическую демо-страницу и workflow GitHub Pages.

Чтобы опубликовать её из PowerShell:

1. Авторизуйте GitHub CLI командой `gh auth login -h github.com -p https -w` и завершите вход в браузере.
2. Перейдите в эту папку и выполните `powershell -ExecutionPolicy Bypass -File .\deploy.ps1`.

Скрипт создаст отдельный публичный репозиторий `prohar2f-pixel/techcontrol-demo` (если его ещё нет), отправит только страницу демо и включит GitHub Pages через Actions. Ожидаемый адрес: <https://prohar2f-pixel.github.io/techcontrol-demo/>. Он начнёт открываться после успешного завершения workflow GitHub Pages.

В репозиторий не включены черновик коммерческого отклика или оценка стоимости.
