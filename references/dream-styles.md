# Dream Styles

Dream styles make the reasoning process visible to humans. They are narrative wrappers over traceable reasoning, not replacements for evidence.

## Config File

Create `.cognitive-training/dream-style-config.md`:

```markdown
# Dream Style Config

Mode: random
Fixed style: research-lab
Enabled styles:
- joyful-festival
- elegy-rain
- school-classroom
- research-lab
- field-training
- battlefield-command
- courtroom-trial
- sea-voyage
- mountain-pilgrimage
- marketplace-negotiation
- workshop-forge
- hospital-rounds
- library-archive
- city-crisis-room
- theater-rehearsal

Weights:
- joyful-festival: 1
- elegy-rain: 1
- school-classroom: 1
- research-lab: 2
- field-training: 2
- battlefield-command: 1
- courtroom-trial: 1
- sea-voyage: 1
- mountain-pilgrimage: 1
- marketplace-negotiation: 1
- workshop-forge: 1
- hospital-rounds: 1
- library-archive: 1
- city-crisis-room: 1
- theater-rehearsal: 1

Safety fallback: research-lab
```

## Style Catalog

Use these abstracted historical-human scenes:

| Style | Human-historical root | Best for | Tone |
| --- | --- | --- | --- |
| `joyful-festival` | harvest rites, victory celebrations, communal renewal | positive learning, breakthroughs, motivation | bright, social, energetic |
| `elegy-rain` | mourning rituals, exile literature, post-war reflection | mistakes, loss, regret, humility | quiet, reflective, restrained |
| `school-classroom` | academies, apprenticeships, examinations | active recall, lessons, drills | clear, pedagogical, corrective |
| `research-lab` | scientific laboratories, seminars, peer review | hypotheses, experiments, evidence gaps | rigorous, calm, precise |
| `field-training` | military drills, craft practice, sports training | procedural practice, habit formation | practical, repetitive, embodied |
| `battlefield-command` | campaigns, sieges, strategic command rooms | tian-dao branches, conflict, resource constraints | tense, strategic, decisive |
| `courtroom-trial` | legal argument, testimony, cross-examination | evidence evaluation, contradiction, falsification | forensic, skeptical, orderly |
| `sea-voyage` | exploration, navigation, trade routes | uncertainty, long-term strategy, changing conditions | expansive, navigational |
| `mountain-pilgrimage` | pilgrimages, ascetic study, summit seeking | long-term mastery, discipline, worldview shifts | austere, upward, patient |
| `marketplace-negotiation` | bazaars, trade fairs, bargaining tables | incentives, stakeholders, value exchange | lively, transactional, pragmatic |
| `workshop-forge` | smithing, guild workshops, invention | building, debugging, iterative refinement | tactile, constructive, focused |
| `hospital-rounds` | clinical rounds, diagnosis, treatment planning | error diagnosis, root causes, intervention design | careful, diagnostic, humane |
| `library-archive` | libraries, monasteries, archives, scholarship | knowledge organization, citation, memory | quiet, archival, connective |
| `city-crisis-room` | councils, disaster response, public administration | complex systems, operations, coordination | urgent, systemic, coordinated |
| `theater-rehearsal` | drama, ritual performance, rehearsal | communication, role-play, scenario testing | expressive, iterative, human-centered |

## Writing Rules

- Keep the style vivid but disciplined.
- Prefer concrete imagery tied to source fragments.
- Avoid gore, cruelty, or manipulative emotional pressure.
- Do not use the style to exaggerate certainty.
- If the user's content is sensitive, use `research-lab`, `school-classroom`, or `library-archive`.
- If the user sets a fixed style, honor it unless safety fallback is needed.

## Reasoning Map Example

```markdown
Reasoning map:
- The cracked compass -> today's failed assumption about tool availability.
- The split road -> branch point between manual setup and scheduled automation.
- The sealed notebook -> memory entry that should not store secrets.
- The dawn experiment table -> tomorrow's falsifiable test.
```
