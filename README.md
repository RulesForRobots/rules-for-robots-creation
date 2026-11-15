<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/RulesForRobots/.github/raw/main/brand/lockups/creation-dark.svg">
  <img src="https://github.com/RulesForRobots/.github/raw/main/brand/lockups/creation-light.svg" alt="Rules for Robots Creation" height="64">
</picture>

# Rules for Robots Creation

Making pictures, video, and games with agents.

Rules for Robots lets one person direct agents through a whole project by approving decisions, never commands. Start at the front door, [RulesForRobots/rules-for-robots](https://github.com/RulesForRobots/rules-for-robots), for the charter, which plugins to install, and the `rfr` marketplace. This repository is where the Creation plugins are made; you install them from the marketplace, not from here.

## Scope

Creation is for work whose result is a picture, a film, a game, or a VR scene rather than software: a logo, a brand, an intro film, illustrations, a game's art. Its first plugin, `rfr-creation`, comes at step 7 of the [rebuild plan](https://github.com/lifelike-and-believable/rules-for-robots/blob/main/docs/rebuild-plan.md), built from the logo and intro-film trials of 2026-11-14:

- **Each approval locks an artifact before a costlier one is made.** A brief before style frames, style frames before a proxy, a proxy before the finished film. Generating is where the money goes, so nothing expensive is made from something unapproved.
- **Checks are technical conformance only:** sizes, formats, colour values, duration, file names. Whether it is good is the person's call, made on a review page of options at real sizes.
- **Outside services are expected.** Image and video generation run in services the project declares, within the limits the person approved.

It is the first domain that is not software, so it is also the test that Core's process engine (`rfr-process`) is truly domain-neutral: Creation declares its stages and artifacts, and the engine runs them.

Software that happens to draw (a renderer, a game engine plugin) belongs in [rules-for-robots-engineering](https://github.com/RulesForRobots/rules-for-robots-engineering).

## Plugins

| Plugin | For | Status |
|---|---|---|
| `rfr-creation` | Stages that lock each artifact (a brief, a style frame, a proxy, an illustration) before a costlier one is made, checks that are technical conformance only (sizes, formats, colour, duration), and taste left to the person. Built from the logo and intro-film trials of 2026-11-14. | Step 7 |

Open work is in [ROADMAP.md](ROADMAP.md).

## Working on this repository

Node 22 or later; there is nothing to install.

```
npm run verify
```

[AGENTS.md](AGENTS.md) has the layout and conventions, for people and agents alike. Contributing and security reports follow the organization's defaults in [RulesForRobots/.github](https://github.com/RulesForRobots/.github).

## Licence

[MIT](LICENSE).
