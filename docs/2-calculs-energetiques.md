# 2️⃣ Calculs énergétiques — Solidarity Shopping Cart (aka Trolley) / Caddie Solidaire

## 📏 Hypothèses de base :
- Poids caddie vide : 30 kg
- Charge moyenne : 50 kg
- Charge max : 100 kg
- Coefficient de roulement : 0,01
- Distance moyenne : 500 m / parcours

## 🔋 Énergie récupérable (phase légère) :
- Force roulage vide : 30 kg × 9,81 × 0,01 = 2,94 N
- Résistance additionnelle appliquée : ~2 N (simulation de +20 kg)
- Effort total phase ≤ 50 kg : ~5 N
- Distance : 100 m (avant dépassement seuil 50 kg)

👉 Énergie stockée ≈ 5 N × 100 m = **500 J = 0,14 Wh**

## 🔧 Énergie requise (phase lourde) :
- Force roulage pleine charge : 100 kg × 9,81 × 0,01 = 9,81 N ≈ 10 N
- Distance lourde : 400 m
- Énergie nécessaire : 10 N × 400 m = **4000 J = 1,1 Wh**

## 🎯 Conclusion :
- Assistance partielle possible (~0,14 Wh stocké vs 1,1 Wh requis)
- Effet perceptible sur ~50–100 m lors de la phase lourde
- Optimisation possible par augmentation progressive de la résistance calibrée sans dégrader l’expérience utilisateur.

---

# 2️⃣ Energy Calculations — Solidarity Shopping Cart (aka Trolley)

## 📏 Basic assumptions:
- Empty cart weight: 30 kg
- Average load: 50 kg
- Max load: 100 kg
- Rolling resistance coefficient: 0.01
- Average distance: 500 m / trip

## 🔋 Recoverable energy (light phase):
- Rolling force empty: 30 kg × 9.81 × 0.01 = 2.94 N
- Additional resistance applied: ~2 N (simulating +20 kg)
- Total effort phase ≤ 50 kg: ~5 N
- Distance: 100 m (before exceeding 50 kg threshold)

👉 Energy stored ≈ 5 N × 100 m = **500 J = 0.14 Wh**

## 🔧 Required energy (heavy phase):
- Rolling force fully loaded: 100 kg × 9.81 × 0.01 = 9.81 N ≈ 10 N
- Heavy distance: 400 m
- Energy needed: 10 N × 400 m = **4000 J = 1.1 Wh**

## 🎯 Conclusion:
- Partial assistance possible (~0.14 Wh stored vs 1.1 Wh required)
- Noticeable effect over ~50–100 m during heavy phase
- Possible optimization by progressively increasing calibrated resistance without degrading user experience
