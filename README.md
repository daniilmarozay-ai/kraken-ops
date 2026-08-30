# kraken-ops

Минимальный репозиторий для Cursor Cloud Agent (Kraken CRM ops).

Сюда **не** кладём CRM, клиентские сайты, `.env` и пароли.
Агент получает бриф задачи из CRM/Telegram; этот репо — рабочая песочница для правок/скриптов.

## Связка
- Telegram Ops bot → задача в CRM → `ops_jobs`
- VDS worker → brief → Cloud Agent на этот репо
