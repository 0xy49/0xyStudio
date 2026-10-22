---
publish: true
created: 2026-10-22T13:08:10.594Z
modified: 2026-10-22T13:08:10.595Z
---

|                              | Base | Skiltree                                                             | Autre | Total  | Total Points |
| ---------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Blood Spell Power==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Blood Magic Resistance== | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==       | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Fire Magic Resistance==  | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Holy Magic Resistance==  | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Ender Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 🩸 Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Fire["Fire School"] -->|bat| Blood(("Blood School"))
    Holy["Holy School"] -->|bat| Blood(("Blood School"))
    Ender["Ender School"] -->|bat| Blood(("Blood School"))
    Blood -->|bat| Ice["Ice School"]
    Blood -->|bat| Lightning["Lightning School"]
    Blood -->|bat| Evocation["Evocation School"]
    class Fire,Holy,Ender,Ice,Lightning,Evocation internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Fire,Holy,Ender weak;
    class Ice,Lightning,Evocation strong;
    class Blood self;
```

> [!success] 🟢 Fort contre
>
> - [[Ice School|❄️ Ice]]
> - [[Lightning School|⚡ Lightning]]
> - [[Evocation School|🔮 Evocation]]

> [!failure] 🔴 Faible contre
>
> - [[Fire School|🔥 Fire]]
> - [[Holy School|✨ Holy]]
> - [[Ender School|🌌 Ender]]

> [!note] ⚪ Neutre
>
> - [[Nature School|🌿 Nature]]
> - [[Eldritch School|👁️ Eldritch]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Ender School|🌌 Ender]] → **🩸 Blood** → [[Ice School|❄️ Ice]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Fire School|🔥 Fire]] → **🩸 Blood** → [[Lightning School|⚡ Lightning]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Holy School|✨ Holy]] → **🩸 Blood** → [[Evocation School|🔮 Evocation]]
