# Vigía externo

Chequea cada 10 minutos, **desde GitHub (fuera del VPS)**, que las webs públicas
de Gringo Labs respondan. Si alguna se cae dos chequeos seguidos (60s de
diferencia), avisa por Telegram.

Existe por la trabada del 18-ago-2026: el VPS quedó congelado (load 800+, SSH
afuera) y no había NADA fuera de la máquina que pudiera avisar — Franco se
enteró intentando usarlo.

- Fuente de verdad y documentación: `~/vigia-externo/` en el VPS +
  `~/HANDOFF-ROBUSTEZ-VPS.md`.
- Secrets del repo: `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.
- Prueba manual: pestaña Actions → vigia → Run workflow → prueba: `si`.
- El repo es público a propósito (Actions gratis sin límite de minutos). Acá no
  va ningún dato interno: solo URLs que ya son públicas.
