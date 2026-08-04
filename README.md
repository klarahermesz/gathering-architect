# Gathering Architect

A coaching-first Claude skill for designing gatherings that actually connect people: workshops, meetups, hackathons, team sessions, and learning communities. It draws on facilitation science, community design frameworks, and social-learning research to go well beyond "make an agenda."

Distributed as a Claude Code / Cowork **plugin marketplace** containing one plugin (`gathering-architect`), which provides the skill.

## What the skill does

Instead of immediately spitting out a schedule, it works like a good facilitator would:

- **Diagnoses purpose first.** It asks two or three sharp questions before recommending anything, because every other decision flows from why you're gathering. Even under time pressure, it promises the deliverable and still asks the questions that change the shape of the event.
- **Recommends the non-obvious.** Specific methods with reasoning (World Café, Three Things on a Card, Think Pair Room, Fishbowl, Open Space) rather than generic "do an icebreaker."
- **Designs for introverts by default.** Processing time, small-group options, write-before-speak patterns.
- **Thinks in energy, not just time.** Sequences activities along the Kaospilot Learning Arch (SET / HOLD / LAND), developed by the [Kaospilot](https://www.kaospilot.dk) school.
- **Names what can go wrong**, and offers an honest gut-check, including whether a gathering should happen at all.
- **Backs claims with defensible evidence** (named, peer-reviewed sources), not blog statistics.

It bundles five reference libraries (facilitation methods, community frameworks, hackathon/build formats, social-learning evidence, facilitator pain points) and five ready-to-use templates (community quick-read, opening contract, run-of-show, community evidence audit, agenda-builder prompt).

## Install

In Claude Code (or Cowork), add this marketplace and install the plugin:

```
/plugin marketplace add klarahermesz/gathering-architect
/plugin install gathering-architect@gathering-architect
```

Then just describe a gathering you're planning, or run the skill directly:

```
/gathering-architect:gathering-architect
```

## What's inside

```
.claude-plugin/
  marketplace.json                       the marketplace catalog (one plugin, this repo's root)
  plugin.json                            the plugin manifest
skills/gathering-architect/
  SKILL.md                               the skill itself
  references/                            five on-demand reference libraries
  assets/                                five workshop templates
  CHANGELOG.md                           version history
```

The repo root is both the marketplace catalog and the plugin itself — the same layout used by other single-plugin marketplace repos (e.g. Vercel's). That's what makes both install paths above work: `/plugin marketplace add` reads `marketplace.json`, and a direct plugin reference to this repo reads `plugin.json`.

## License

Licensed under the [Apache License, Version 2.0](LICENSE). See [NOTICE](NOTICE) for attribution.

The skill references third-party frameworks and methods: [Community Canvas](https://community-canvas.org) and [Community Weaving](https://www.community-weaving.org/) (both CC BY-NC-SA 4.0), Etienne Wenger's Communities of Practice (copyrighted book content, not Creative Commons licensed), [Liberating Structures](https://www.liberatingstructures.com) (CC BY-NC 4.0), [Open Space Technology](https://openspaceworld.org/wp2/what-is/) (Harrison Owen), the [Hyper Island Toolbox](https://toolbox.hyperisland.com), [SessionLab](https://www.sessionlab.com), Gary Klein's premortem, and Tom Wujec's Marshmallow Challenge. Every one of them is named, attributed and linked only. None of their framework structures, principle wording, worksheets or facilitation sequences are restated here. Separately, the skill describes a handful of established general-practice formats in its own words (World Café, fishbowl, mastermind groups, show and tell, check-ins, and the Kaospilot Learning Arch), each with its originator and the write-up we consulted credited in [NOTICE](NOTICE) and in the method's own Source line. This skill carries its own original tools instead (`skills/gathering-architect/assets/community-quick-read.md`, `.../assets/community-audit-workshop.md`, `.../assets/opening-contract-template.md`, and the thirteen originally-designed methods in `.../references/facilitation-methods.md`) that don't require any of them. All referenced frameworks are owned by their respective authors, carry their own licenses, and are **not** relicensed by this repo's Apache-2.0 grant. This license covers only the original writing, synthesis, and structure of the skill itself.

## Credits

Created by **[Klara Hermesz](https://github.com/klarahermesz)**, Co-founder & Chief Learning Architect at [AI Enablement Academy](https://aienablement.academy).
