# viber

Перекидка `https://dnk-natsii.github.io/viber/#380XXXXXXXXX` → `viber://chat?number=+380XXXXXXXXX`.
Потрібна, бо Telegram не робить посилання viber:// клікабельним. Використовує ERP (`modules/site/tg_notify.py`).
Номер лише після `#` — на сервер не надсилається. Без аналітики.
