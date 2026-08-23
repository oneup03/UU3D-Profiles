# UU3D-Profiles

Per-Game Profiles for UU3D

A profile is named after the game's **executable**, not its store name, because
that is what UU3D uses for its per-game folder (`%APPDATA%\UU3D\<profile>\`).


## Game to profile

| Game | Profile |
| --- | --- |
| Black Myth: Wukong | `b1-Win64-Shipping` |
| Clair Obscur: Expedition 33 | `SandFall-Win64-Shipping`, `SandFall-WinGDK-Shipping` |
| Denshattack! | `Denshattack_Proto-Win64-Shipping` |
| Fantasy Life i: The Girl Who Steals Time | `NFL1-Win64-Shipping` |
| FINAL FANTASY VII REBIRTH | `ff7rebirth_` |
| Gotham Knights | `GothamKnights` |
| Hogwarts Legacy | `HogwartsLegacy` (also `AFW/HogwartsLegacy`) |
| Palworld | `Palworld-Win64-Shipping`, `Palworld-WinGDK-Shipping` |
| Persona 3 Reload | `P3R` |
| Returnal | `Returnal-Win64-Shipping` |
| Senua's Saga: Hellblade II | `Hellblade2-Win64-Shipping`, `Hellblade2-WinGDK-Shipping` |
| Shin Megami Tensei V: Vengeance | `SMT5V-Win64-Shipping` |
| STAR WARS Jedi: Survivor | `JediSurvivor` |
| Stellar Blade | `SB-Win64-Shipping` |
| The Adventures of Elliot | `Elliot-Win64-Shipping` |
| The Plucky Squire | `Storybook-Win64-Shipping` |

## Notes

- **`-Win64-Shipping` vs `-WinGDK-Shipping`** — the same game built for different
  stores. `Win64` is the Steam / EGS build; `WinGDK` is the Microsoft Store and
  Game Pass build. Pick the one matching where you own the game; both profiles
  hold the same settings.
- **`AFW/`** — an alternate profile tuned for the Alternate Frame Warping
  rendering method. Use it instead of the top-level one when running AFW.
