---
publish: true
created: 2026-10-22T13:08:34.332Z
modified: 2026-10-22T13:08:34.332Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Ender Spell Power==          | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Ender Magic Resistance==     | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Nature Magic Resistance==    | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Lightning Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Eldritch Magic Resistance==  | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 🌌 Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Lightning["Lightning School"] -->|bat| Ender(("Ender School"))
    Nature["Nature School"] -->|bat| Ender(("Ender School"))
    Eldritch["Eldritch School"] -->|bat| Ender(("Ender School"))
    Ender -->|bat| Blood["Blood School"]
    Ender -->|bat| Evocation["Evocation School"]
    Ender -->|bat| Holy["Holy School"]
    class Lightning,Nature,Eldritch,Blood,Evocation,Holy internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Lightning,Nature,Eldritch weak;
    class Blood,Evocation,Holy strong;
    class Ender self;
```

> [!success] 🟢 Fort contre
>
> - [[Blood School|🩸 Blood]]
> - [[Evocation School|🔮 Evocation]]
> - [[Holy School|✨ Holy]]

> [!failure] 🔴 Faible contre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Nature School|🌿 Nature]]
> - [[Eldritch School|👁️ Eldritch]]

> [!note] ⚪ Neutre
>
> - [[Fire School|🔥 Fire]]
> - [[Ice School|❄️ Ice]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Eldritch School|👁️ Eldritch]] → **🌌 Ender** → [[Blood School|🩸 Blood]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Lightning School|⚡ Lightning]] → **🌌 Ender** → [[Evocation School|🔮 Evocation]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Nature School|🌿 Nature]] → **🌌 Ender** → [[Holy School|✨ Holy]]
