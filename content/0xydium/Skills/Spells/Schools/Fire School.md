---
publish: true
created: 2026-10-22T13:08:53.854Z
modified: 2026-10-22T13:08:53.854Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Fire Spell Power==           | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Fire Magic Resistance==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Ice Magic Resistance==       | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Evocation Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Holy Magic Resistance==      | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 🔥 Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Ice["Ice School"] -->|bat| Fire(("Fire School"))
    Evocation["Evocation School"] -->|bat| Fire(("Fire School"))
    Holy["Holy School"] -->|bat| Fire(("Fire School"))
    Fire -->|bat| Nature["Nature School"]
    Fire -->|bat| Blood["Blood School"]
    Fire -->|bat| Eldritch["Eldritch School"]
    class Ice,Evocation,Holy,Nature,Blood,Eldritch internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Ice,Evocation,Holy weak;
    class Nature,Blood,Eldritch strong;
    class Fire self;
```

> [!success] 🟢 Fort contre
>
> - [[Nature School|🌿 Nature]]
> - [[Blood School|🩸 Blood]]
> - [[Eldritch School|👁️ Eldritch]]

> [!failure] 🔴 Faible contre
>
> - [[Ice School|❄️ Ice]]
> - [[Evocation School|🔮 Evocation]]
> - [[Holy School|✨ Holy]]

> [!note] ⚪ Neutre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Ender School|🌌 Ender]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Ice School|❄️ Ice]] → **🔥 Fire** → [[Nature School|🌿 Nature]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Holy School|✨ Holy]] → **🔥 Fire** → [[Blood School|🩸 Blood]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Evocation School|🔮 Evocation]] → **🔥 Fire** → [[Eldritch School|👁️ Eldritch]]
