# Sentinella cron — repo PUBBLICO `accumunation-social`

WQ-294 criterio 1. Stessi cron di `pubblica.yml` (repo PRIVATO `accumunation-media`),
stesso account, stesso runner: unica variabile la visibilita' del repo.
Ritardo = ora vera del run meno ora del cron, in minuti, UTC.

| previsto UTC | run UTC | ritardo min | cron |
|---|---|---|---|
| n/d | 2026-09-04 14:11 | n/d | `manuale` |
| 2026-09-04 16:36 | 2026-09-04 19:06 | 150 | `36 16 * * *` |
| 2026-09-04 16:55 | 2026-09-04 19:10 | 135 | `55 16 * * *` |
| 2026-09-04 18:06 | 2026-09-04 20:38 | 152 | `6 18 * * *` |
