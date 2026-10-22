---
publish: true
created: 2026-10-22T13:09:01.830Z
modified: 2026-10-22T13:09:01.830Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Holy Spell Power==           | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Holy Magic Resistance==      | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Ice Magic Resistance==       | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Evocation Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Ender Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## ✨ Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Ice["Ice School"] -->|bat| Holy(("Holy School"))
    Evocation["Evocation School"] -->|bat| Holy(("Holy School"))
    Ender["Ender School"] -->|bat| Holy(("Holy School"))
    Holy -->|bat| Eldritch["Eldritch School"]
    Holy -->|bat| Fire["Fire School"]
    Holy -->|bat| Blood["Blood School"]
    class Ice,Evocation,Ender,Eldritch,Fire,Blood internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Ice,Evocation,Ender weak;
    class Eldritch,Fire,Blood strong;
    class Holy self;
```

> [!success] 🟢 Fort contre
>
> - [[Eldritch School|👁️ Eldritch]]
> - [[Fire School|🔥 Fire]]
> - [[Blood School|🩸 Blood]]

> [!failure] 🔴 Faible contre
>
> - [[Ice School|❄️ Ice]]
> - [[Evocation School|🔮 Evocation]]
> - [[Ender School|🌌 Ender]]

> [!note] ⚪ Neutre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Nature School|🌿 Nature]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Evocation School|🔮 Evocation]] → **✨ Holy** → [[Eldritch School|👁️ Eldritch]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Ice School|❄️ Ice]] → **✨ Holy** → [[Fire School|🔥 Fire]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Ender School|🌌 Ender]] → **✨ Holy** → [[Blood School|🩸 Blood]]
