# Мини-аппы Telegram

Статичные мини-аппы на GitHub Pages. API — функция Supabase `leto` (проект Ustoy-M).

- `site/leto/` — LETO Real Estate (@LETO_RealEstate_Agent_bot)
- `site/demo/` — демо для агентств (@realestate_nwe_agent_bot)
- `site/bikes/` — прокат байков «Ветер» (@DEMO_RENTALBOT), админка в `site/bikes/admin/`. API — RPC `bike_*` и функции `bike-bot`, `bike-upload` в Supabase (проект la-ban-vietnam-compass)

Восстановлено 3–4 ноября 2026 после сбоя хостинга Beget (раньше отдавались из n8n).

## Сайты на своих доменах
`domains/<домен>/` → `https://<домен>/` (сервер Reg.ru забирает каждые 10 минут, `rsync --delete`: держите в папке все файлы сайта, включая index.html).
Подключены: foodbotmenu.ru, scanbusiness.info. Подготовлен: xn--90aihqiaaun.xn--p1ai (ооотимбер.рф, ООО «ТИМБЕР»). Новый домен сначала нужно прописать в Caddy (репозиторий server).
