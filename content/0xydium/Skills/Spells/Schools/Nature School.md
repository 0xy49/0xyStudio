---
publish: true
created: 2026-10-22T13:09:38.295Z
modified: 2026-10-22T13:09:38.295Z
---

|                                  | Base | Skiltree                                                             | Autre | Total  | Total Points |
| -------------------------------- | ---- | -------------------------------------------------------------------- | ----- | ------ | ------------ |
| ==🟢Nature Spell Power==         | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Nature Magic Resistance==    | 100% | 5% skilltree CLASS<br>==(1 x 5%)==<br>20% skilltree<br>==(20 x 1%)== |       | 125%   | 20           |
| ==🟢Spell resistance==           | 100% | 12.5% skilltree<br>==(10 x 1.25%)==                                  |       | 112.5% | 10           |
| ==🔴Ice Magic Resistance==       | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Fire Magic Resistance==      | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |
| ==🔴Evocation Magic Resistance== | 100% | -25% skilltree<br>==(50 x -0.5%)==                                   |       | 75%    | 50           |

---

## 🌿 Affinités

> [!abstract] Résumé
> Voir la [[Table des affinités]] pour la vue d'ensemble.

```mermaid
flowchart LR
    Fire["Fire School"] -->|bat| Nature(("Nature School"))
    Ice["Ice School"] -->|bat| Nature(("Nature School"))
    Evocation["Evocation School"] -->|bat| Nature(("Nature School"))
    Nature -->|bat| Lightning["Lightning School"]
    Nature -->|bat| Eldritch["Eldritch School"]
    Nature -->|bat| Ender["Ender School"]
    class Fire,Ice,Evocation,Lightning,Eldritch,Ender internal-link;
    classDef weak fill:transparent,stroke:#e05252,stroke-width:2px;
    classDef strong fill:transparent,stroke:#4fc36b,stroke-width:2px;
    classDef self fill:transparent,stroke:#9d9dff,stroke-width:3px;
    class Fire,Ice,Evocation weak;
    class Lightning,Eldritch,Ender strong;
    class Nature self;
```

> [!success] 🟢 Fort contre
>
> - [[Lightning School|⚡ Lightning]]
> - [[Eldritch School|👁️ Eldritch]]
> - [[Ender School|🌌 Ender]]

> [!failure] 🔴 Faible contre
>
> - [[Fire School|🔥 Fire]]
> - [[Ice School|❄️ Ice]]
> - [[Evocation School|🔮 Evocation]]

> [!note] ⚪ Neutre
>
> - [[Blood School|🩸 Blood]]
> - [[Holy School|✨ Holy]]

> [!tip]- Position dans les branches
>
> - **[[Table des affinités#Branche 1|Branche 1]]** : [[Fire School|🔥 Fire]] → **🌿 Nature** → [[Lightning School|⚡ Lightning]]
> - **[[Table des affinités#Branche 2|Branche 2]]** : [[Evocation School|🔮 Evocation]] → **🌿 Nature** → [[Eldritch School|👁️ Eldritch]]
> - **[[Table des affinités#Branche 3|Branche 3]]** : [[Ice School|❄️ Ice]] → **🌿 Nature** → [[Ender School|🌌 Ender]]
