# <img src="https://nomlings.cc/badge/_egg?scale=4" alt="a wobbling pixel egg" height="34"> Nomlings Badge

**A tiny pixel pet for your GitHub README that eats your commits.**

Add one line of markdown and an animated Nomling moves into your profile.
It shows your real contribution stats: it munches when you commit, keeps
your streak, celebrates your big days, and falls asleep if you go quiet.

```md
[![my nomling](https://nomlings.cc/badge/YOUR-USERNAME)](https://nomlings.cc/badge)
```

That's it. No signup, no token, no config. Clicking the pet leads back to
the Nomlings, so every adopted badge is also a door here.

## Pets in the wild

These are live, rendered from each account's real activity right now:

| | |
| --- | --- |
| [![torvalds' nomling](https://nomlings.cc/badge/torvalds?scale=5&color=%2358a6ff)](https://nomlings.cc/badge) | **Linus Torvalds** built Linux and git. His Wispling has been eating kernel commits since 1991. |
| [![pewdiepie's nomling](https://nomlings.cc/badge/pewdiepie-archdaemon?scale=5&color=%23ff8833)](https://nomlings.cc/badge) | **PewDiePie** hatched a Sproutling. It eats dotfiles and self-hosted AI. |
| [![sindresorhus' nomling](https://nomlings.cc/badge/sindresorhus?scale=5&color=%23ffd700)](https://nomlings.cc/badge) | **Sindre Sorhus** maintains a thousand npm packages. His Twinkling never goes hungry. |
| [![karpathy's nomling](https://nomlings.cc/badge/karpathy?scale=5&color=%23ff6ec7)](https://nomlings.cc/badge) | **Andrej Karpathy**'s Peckling naps between training runs. It wakes up hungry. |

Yours is already waiting at `https://nomlings.cc/badge/YOUR-USERNAME`. Go say hi.

## What the pet is telling you

The badge reads your contribution calendar (the same numbers as your
profile graph, private contributions included when your profile shows
them) and turns it into a mood:

| Mood | Meaning |
| --- | --- |
| 🎉 celebrating | 15+ contributions today. On fire. |
| 😋 eating | you contributed today (with your current streak) |
| 🙂 idle | active this week, nothing yet today |
| 💤 sleeping | zero contributions in 7 days |
| 🥚 egg | no contributions in the last year. Hatch it. |

Your pet's **level** grows with your yearly total, and the badge always
shows the real numbers: contributions today, your streak, and your
last-year total.

## Choose your species

Your species is hatched from your username, but there are ten Nomlings
and you can pick any of them with `?pet=`:

`nomling` (Munchling) · `enderling` · `peckling` · `wispling` ·
`byteling` · `sproutling` · `hopling` · `twinkling` · `sporeling` ·
`buzzling`

```md
[![my nomling](https://nomlings.cc/badge/YOUR-USERNAME?pet=byteling)](https://nomlings.cc/badge)
```

## Options

| Param | Example | Effect |
| --- | --- | --- |
| `pet` | `?pet=wispling` | pick your species |
| `scale` | `?scale=6` | pixel size, 2 to 8 (default 4) |
| `color` | `?color=%23ff8833` | sprite color (default GitHub green) |
| `label` | `?label=off` | sprite only, no text |

### Sizes

`?scale=2` for a footnote, default 4, `?scale=6` for a hero:

![scale 2](https://nomlings.cc/badge/torvalds?scale=2)

![scale 4](https://nomlings.cc/badge/torvalds)

![scale 6](https://nomlings.cc/badge/torvalds?scale=6)

### Colors

Any hex via `?color=` (URL-encode the `#` as `%23`):

![orange hopling](https://nomlings.cc/badge/FrancescoCoding?pet=hopling&color=%23ff8833)

![purple wispling](https://nomlings.cc/badge/FrancescoCoding?pet=wispling&color=%23b085f5)

![gold twinkling](https://nomlings.cc/badge/FrancescoCoding?pet=twinkling&color=%23ffd700)

### Sprite only

`?label=off` drops the text. Perfect next to your name or in a table:

![sprite only](https://nomlings.cc/badge/FrancescoCoding?label=off&scale=5) ![sprite only gold](https://nomlings.cc/badge/FrancescoCoding?pet=twinkling&label=off&scale=5&color=%23ffd700) ![sprite only purple](https://nomlings.cc/badge/FrancescoCoding?pet=wispling&label=off&scale=5&color=%23b085f5)

Combine anything: `https://nomlings.cc/badge/YOU?pet=hopling&scale=6&color=%23ff8833`

## FAQ

**Is it free?** Yes.

**Why does my badge lag my latest commit?** Renders are cached for a few
hours to keep things fast and gentle. Your pet notices, just not
instantly.

**Do private contributions count?** They count whenever your GitHub
profile is set to show private contribution activity, because the badge
reads the same calendar your profile displays.

**Is the code open source?** The service is closed source: the Nomling
characters and pixel art are original work and this keeps them home.
Bugs, ideas, and species requests are very welcome in this repo's issues.

**Where do Nomlings come from?** They are the desktop pets that live next
to your terminal and eat your Claude Code tokens. Meet the full 3D
version at [Nomlings/app](https://github.com/Nomlings/app).

---

*Nomling species designs and artwork © Nomlings. All rights reserved.*
