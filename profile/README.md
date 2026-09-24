# uhifadhi

**The open-source observatory for nature conservation and protected areas.**

An installation of uhifadhi is one organisation's own observatory over the
protected areas it manages: the gazetted boundaries and the zones inside them,
the people and the positions they hold, and the capabilities the organisation
actually runs. Those capabilities — patrols, incidents, rosters — arrive as
**modules** that an administrator installs and switches on for the areas that
want them. An area that runs no patrols never sees the patrol screens.

> **A module registers with the registry and renders in the shell.**

## Where to go

| Repository | What it is for |
|---|---|
| [`uhifadhi/skeleton`](https://github.com/utafitilabs/skeleton) | Install an observatory — `composer create-project uhifadhi/skeleton` |
| [`uhifadhi/uhifadhi`](https://github.com/utafitilabs/uhifadhi) | The core: the registry, the shell, the team, the areas and the atlas — for building modules and updating installations |
| `uhifadhi/<name>-module` | One capability each, installed with `composer require`: [patrol](https://github.com/utafitilabs/patrol-module), [incident](https://github.com/utafitilabs/incident-module), [storage](https://github.com/utafitilabs/storage-module), [roster](https://github.com/utafitilabs/roster-module) |

## Licence

**AGPL-3.0-or-later** for the core and the skeleton; **MIT** for the contracts,
because an interface anybody may implement should cost nobody anything.

Science is never paywalled.
