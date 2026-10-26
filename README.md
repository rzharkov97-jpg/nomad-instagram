# Nomad Instagram

Готовые слайды для Instagram гостиницы Nomad (Есик). Папки по дате публикации; Metricool забирает картинки по прямым ссылкам.

## ИИ-агенты

В `.claude/agents/` — команда агентов Claude Code. Вызов: «попроси агента nomad-designer сделать карусель на 15.11».

| Агент | Что делает |
|---|---|
| `nomad-strategist` | контент-план, темы, офферы, тренды Reels |
| `nomad-copywriter` | подписи, тексты слайдов, хэштеги, KZ/EN |
| `nomad-designer` | слайды JPG для постов и сторис в фирменном стиле |
| `nomad-reels` | сценарий и монтаж Reels (ffmpeg) |
| `nomad-publisher` | постановка в Metricool (по умолчанию — на проверку) |
| `nomad-analyst` | еженедельный разбор статистики Metricool |

Типичная цепочка: strategist → copywriter → designer / reels → publisher, раз в неделю — analyst.
