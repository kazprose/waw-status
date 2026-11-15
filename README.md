# waw.kz status

Тәуелсіз мониторинг: GitHub Actions әр 5 минут сайын https://waw.kz және https://waw.kz/api/health адрестерін тексеріп, нәтижесін осы репоға жазады (`history/*.json`). Тарих ашық, оны waw.kz өзгерте алмайды.

- Сайт күйі: https://waw.kz/status
- Деректер: `history/YYYY-MM.json` — әр жазба: `{ "t": ISO-уақыт, "site": HTTP коды, "api": HTTP коды, "ms": жауап уақыты }`

Independent uptime monitor for waw.kz: a GitHub Actions job checks the site and API every 5 minutes and commits the results here. History is public and cannot be altered by the service itself.


Ескерту (Telegram): репо secrets ішінде  және  болса, сайт құлағанда және қайта көтерілгенде хабар келеді; резервтік көшірме 30 сағаттан ескірсе күніне бір рет ескертеді. Әр жазбада  (API дерекқорды тексерді ме) өрісі бар.
