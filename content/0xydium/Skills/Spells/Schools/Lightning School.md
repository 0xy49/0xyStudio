---
publish: true
created: 2026-10-22T13:09:30.020Z
modified: 2026-10-22T13:09:30.021Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Lightning Spell Power==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Lightning Magic Resistance== | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Nature Magic Resistance==    | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Eldritch Magic Resistance==  | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Blood Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## ⚡ Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Nature["Nature School"] -->|bat| Lightning(("Lightning School"))
    Blood["Blood School"] -->|bat| Lightning(("Lightning School"))
    Eldritch["Eldritch School"] -->|bat| Lightning(("Lightning School"))
    Lightning -->|bat| Evocation["Evocation School"]
    Lightning -->|bat| Ender["Ender School"]
    Lightning -->|bat| Ice["Ice School"]
    class Nature,Blood,Eldritch,Evocation,Ender,Ice internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Nature,Blood,Eldritch weak;
    class Evocation,Ender,Ice strong;
    class Lightning self;
```

> [!success] 🟢 Fort contre
>
> - [[Evocation School|🔮 Evocation]]
> - [[Ender School|🌌 Ender]]
> - [[Ice School|❄️ Ice]]

> [!failure] 🔴 Faible contre
>
> - [[Nature School|🌿 Nature]]
> - [[Blood School|🩸 Blood]]
> - [[Eldritch School|👁️ Eldritch]]

> [!note] ⚪ Neutre
>
> - [[Fire School|🔥 Fire]]
> - [[Holy School|✨ Holy]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Nature School|🌿 Nature]] → **⚡ Lightning** → [[Evocation School|🔮 Evocation]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Blood School|🩸 Blood]] → **⚡ Lightning** → [[Ender School|🌌 Ender]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Eldritch School|👁️ Eldritch]] → **⚡ Lightning** → [[Ice School|❄️ Ice]]
