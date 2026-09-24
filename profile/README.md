# Utafiti Labs

Software for the people who look after wild places: research, conservation and
the field work behind both. *Utafiti* is Swahili for research.

## What we build

| Project | What it is |
|---|---|
| [**uhifadhi**](https://github.com/utafitilabs/skeleton) | The open-source observatory for nature conservation and protected areas — one installation per organisation, capabilities as modules. Start with `composer create-project uhifadhi/skeleton`; the core is [`uhifadhi/uhifadhi`](https://github.com/utafitilabs/uhifadhi), the modules are `uhifadhi/<name>-module`. |
| **Doria** | The uhifadhi field app for rangers' handsets — patrols, observations, check-ins — free to use, built to keep working without signal. Downloads at [downloads](https://github.com/utafitilabs/downloads). |
| [`utafitilabs/postgis-bundle`](https://github.com/utafitilabs/postgis-bundle) | Typed PostGIS geometry for Doctrine and Symfony, with the DQL functions to query it. Generic: any Symfony application. |
| [`utafitilabs/postgis`](https://github.com/utafitilabs/postgis) | The PostGIS container image the platform and its test suites run on. |

Everything generic — a bundle any Symfony application could install unchanged —
ships as `utafitilabs/<name>`. Everything that is a piece of uhifadhi ships as
`uhifadhi/<name>`.

## Licences

**AGPL-3.0-or-later** for uhifadhi's core, starter and modules, so that a
modified observatory offered over a network stays open to the people using it.
**MIT** for the contracts a module implements, because an interface anybody may
implement should cost nobody anything. Generic bundles carry their own licence
in their repository.

Science is never paywalled.
