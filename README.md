# Genealogy

Семейный генеалогический поиск с Claude Code.

В `.claude/skills/ex-ussr-kinship-research/` лежит скилл
[ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)
(лицензия — в папке скилла). Он подгружается автоматически в каждой сессии Claude Code,
открытой в этом репозитории, в том числе с телефона.

Обновить скилл до свежей версии:

```bash
rm -rf .claude/skills/ex-ussr-kinship-research
git clone --depth 1 https://github.com/DenisSergeevitch/ex-ussr-kinship-research .claude/skills/ex-ussr-kinship-research
rm -rf .claude/skills/ex-ussr-kinship-research/.git
```
