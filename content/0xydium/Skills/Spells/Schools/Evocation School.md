---
publish: true
created: 2026-10-22T13:08:44.090Z
modified: 2026-10-22T13:08:44.090Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Evocation Spell Power==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Evocation Magic Resistance== | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Lightning Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Ender Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Blood Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 🔮 Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Lightning["Lightning School"] -->|bat| Evocation(("Evocation School"))
    Blood["Blood School"] -->|bat| Evocation(("Evocation School"))
    Ender["Ender School"] -->|bat| Evocation(("Evocation School"))
    Evocation -->|bat| Holy["Holy School"]
    Evocation -->|bat| Nature["Nature School"]
    Evocation -->|bat| Fire["Fire School"]
    class Lightning,Blood,Ender,Holy,Nature,Fire internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Lightning,Blood,Ender weak;
    class Holy,Nature,Fire strong;
    class Evocation self;
```

> [!success] 🟢 Fort contre
>
> - [[Holy School|✨ Holy]]
> - [[Nature School|🌿 Nature]]
> - [[Fire School|🔥 Fire]]

> [!failure] 🔴 Faible contre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Blood School|🩸 Blood]]
> - [[Ender School|🌌 Ender]]

> [!note] ⚪ Neutre
>
> - [[Ice School|❄️ Ice]]
> - [[Eldritch School|👁️ Eldritch]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Lightning School|⚡ Lightning]] → **🔮 Evocation** → [[Holy School|✨ Holy]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Ender School|🌌 Ender]] → **🔮 Evocation** → [[Nature School|🌿 Nature]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Blood School|🩸 Blood]] → **🔮 Evocation** → [[Fire School|🔥 Fire]]
