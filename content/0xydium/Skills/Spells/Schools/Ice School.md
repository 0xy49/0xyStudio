---
publish: true
created: 2026-10-22T13:09:25.922Z
modified: 2026-10-22T13:09:25.923Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Ice Spell Power==            | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Ice Magic Resistance==       | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Lightning Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Eldritch Magic Resistance==  | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Blood Magic Resistance==     | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## ❄️ Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Lightning["Lightning School"] -->|bat| Ice(("Ice School"))
    Blood["Blood School"] -->|bat| Ice(("Ice School"))
    Eldritch["Eldritch School"] -->|bat| Ice(("Ice School"))
    Ice -->|bat| Fire["Fire School"]
    Ice -->|bat| Holy["Holy School"]
    Ice -->|bat| Nature["Nature School"]
    class Lightning,Blood,Eldritch,Fire,Holy,Nature internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Lightning,Blood,Eldritch weak;
    class Fire,Holy,Nature strong;
    class Ice self;
```

> [!success] 🟢 Fort contre
>
> - [[Fire School|🔥 Fire]]
> - [[Holy School|✨ Holy]]
> - [[Nature School|🌿 Nature]]

> [!failure] 🔴 Faible contre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Blood School|🩸 Blood]]
> - [[Eldritch School|👁️ Eldritch]]

> [!note] ⚪ Neutre
>
> - [[Evocation School|🔮 Evocation]]
> - [[Ender School|🌌 Ender]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Blood School|🩸 Blood]] → **❄️ Ice** → [[Fire School|🔥 Fire]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Eldritch School|👁️ Eldritch]] → **❄️ Ice** → [[Holy School|✨ Holy]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Lightning School|⚡ Lightning]] → **❄️ Ice** → [[Nature School|🌿 Nature]]
