---
publish: true
created: 2026-10-22T13:08:25.335Z
modified: 2026-10-22T13:08:25.336Z
---

|                                 | Base | Skiltree                                                             | Autre | Total  | Total Points |
| ------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Eldritch Spell Power==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Eldritch Magic Resistance== | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==          | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Fire Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Nature Magic Resistance==   | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Holy Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 👁️ Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Fire["Fire School"] -->|bat| Eldritch(("Eldritch School"))
    Nature["Nature School"] -->|bat| Eldritch(("Eldritch School"))
    Holy["Holy School"] -->|bat| Eldritch(("Eldritch School"))
    Eldritch -->|bat| Ender["Ender School"]
    Eldritch -->|bat| Ice["Ice School"]
    Eldritch -->|bat| Lightning["Lightning School"]
    class Fire,Nature,Holy,Ender,Ice,Lightning internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Fire,Nature,Holy weak;
    class Ender,Ice,Lightning strong;
    class Eldritch self;
```

> [!success] 🟢 Fort contre
>
> - [[Ender School|🌌 Ender]]
> - [[Ice School|❄️ Ice]]
> - [[Lightning School|⚡ Lightning]]

> [!failure] 🔴 Faible contre
>
> - [[Fire School|🔥 Fire]]
> - [[Nature School|🌿 Nature]]
> - [[Holy School|✨ Holy]]

> [!note] ⚪ Neutre
>
> - [[Blood School|🩸 Blood]]
> - [[Evocation School|🔮 Evocation]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Holy School|✨ Holy]] → **👁️ Eldritch** → [[Ender School|🌌 Ender]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Nature School|🌿 Nature]] → **👁️ Eldritch** → [[Ice School|❄️ Ice]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Fire School|🔥 Fire]] → **👁️ Eldritch** → [[Lightning School|⚡ Lightning]]
