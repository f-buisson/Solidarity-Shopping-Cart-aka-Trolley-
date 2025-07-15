# 2️⃣ Schéma de principe — Solidarity Shopping Cart (aka Trolley) / Caddie Solidaire

Voici une description textuelle du **schéma de principe** du système :

```
+-----------------------------+
|         Structure           |
|                             |
|  [Roues]                    |
|     │                        |
|  [Module frein léger] <---- │ Résistance appliquée si poids ≤ 50 kg
|     │                        |
|  [Accumulateur mécanique]   │ Stocke énergie fournie par la poussée "facile"
|     │                        |
|  [Embrayage contrôlé] ----> │ Libère énergie lorsque poids > 50 kg
|                             |
+-----------------------------+
```

### 🔧 Fonctionnement illustré :
- La **résistance appliquée** dans les phases légères sert à alimenter l’accumulateur mécanique.
- Lors des phases lourdes, l’**embrayage** libère cette énergie pour réduire l’effort de poussée.

Ce schéma pourra être remplacé par un diagramme visuel (voir `/images/caddie-solidaire-schema.png`).
