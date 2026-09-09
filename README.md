# wibt-communicatie

Claude Code-skills en communicatiewerk voor [Wetenschap in begrijpelijke taal](https://github.com/ubvu/wibt) (WiBT), het project van de KB Nationale Bibliotheek, de VU Universiteitsbibliotheek en de VU-vakgroep AI & Behaviour.

Deze repository bevat twee dingen: een set schrijf- en compliance-skills, en de conceptteksten die daarmee gemaakt zijn voor de communicatieronde van het project.

## Skills

Zeven skills onder `.agents/skills/` (gespiegeld naar `.claude/skills/` voor gebruik in Claude Code):

| Skill | Waarvoor |
|---|---|
| [`academic-writing`](.agents/skills/academic-writing/SKILL.md) | Wetenschappelijk schrijven en compliance: CRediT, preregistratie, Plan S, Nelson Memo, preprints, ORCID, LLM-disclosure. |
| [`ai-writing-detox`](.agents/skills/ai-writing-detox/SKILL.md) | Haalt AI-schrijfpatronen uit tekst die het vertrouwen van lezers ondermijnen, waaronder een harde regel tegen lange streepjes. |
| [`brainstorming`](.agents/skills/brainstorming/SKILL.md) | Verkent doel en ontwerp voordat er iets wordt gebouwd of geschreven. |
| [`fact-check-workflow`](.agents/skills/fact-check-workflow/SKILL.md) | Gestructureerd factchecken van claims vóór publicatie. |
| [`labeling-ai-generated-content`](.agents/skills/labeling-ai-generated-content/SKILL.md) | Bepaalt of en hoe AI-gegenereerde tekst, beeld, audio of video gelabeld moet worden onder artikel 50 van de EU AI Act. |
| [`newsletter-publishing`](.agents/skills/newsletter-publishing/SKILL.md) | Workflows voor e-mailnieuwsbrieven. |
| [`newsroom-style`](.agents/skills/newsroom-style/SKILL.md) | Stijlregels voor nieuwsteksten en koppen, gebaseerd op AP Style. |

Zes van deze skills komen uit [jamditis/claude-skills-journalism](https://github.com/jamditis/claude-skills-journalism), vastgelegd (inclusief hash) in [`skills-lock.json`](skills-lock.json). `labeling-ai-generated-content` is specifiek voor dit project geschreven, met een EU-brede insteek: het legt uit wanneer AI-gegenereerde content een label nodig heeft en welke van de twee AI Act-verplichtingen (provider-markering of deployer-labeling) van toepassing is.

Skills bijwerken of opnieuw laden: `/reload-skills`.

## Conceptteksten

[`concepten/wibt-conceptteksten.md`](concepten/wibt-conceptteksten.md) bevat de conceptteksten voor het communicatieplan van WiBT: LinkedIn, Mastodon, drie interne nieuwsbrieven, een SURF-nieuwsitem, het Informatieprofessional-artikel, en startdrafts voor de kanalen van andere teamleden. Alle cijfers daarin zijn herbruikt uit de al goedgekeurde resultaten op de [projectpagina](https://ubvu.github.io/wibt/), dus zonder nieuwe claims.

## Licentie

CC0 1.0 Universal. Zie [LICENSE](LICENSE).
