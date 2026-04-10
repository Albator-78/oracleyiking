# 🔮 Oracle Yi Ching Interactif — Construction Progressive

## 📖 Vue d'ensemble

L'**Oracle Yi Ching Interactif** vous permet de **construire un hexagramme complètement du Yi Ching** en tirant les traits un par un, étape par étape, avec interaction à chaque niveau.

Contrairement à la version précédente, ici vous **participez activement à la création** de votre consultation en construisant l'hexagramme trait par trait.

---

## 🎯 Processus de Tirage

### **Phase 0 : Préparation**
```
🔮 Oracle Yi Ching Interactif
Cliquer : ✦ Commencer le Tirage ✦
```

### **Phase 1 : Construction du Trigramme Inférieur**

#### Étape 1 : Tirer le Trait 1
```
Cliquer : 🎲 Tirer le Trait 1
         ↓
Résultat : Yang (━━━) ou Yin (━ ━)
```

#### Étape 2 : Choisir le Type du Trait 1
Une fois le trait tiré, **4 options** apparaissent :

```
┌──────────────────────────────────────┐
│   Choisir le Type du Trait 1         │
│                                      │
│  ━━━       ━ ━      ━━━⟳    ━ ━⟳   │
│ Yang      Yin      Y.Chang   Yi.Chang
│                                      │
│ (solide)  (solide) (changeant)(changeant)
└──────────────────────────────────────┘
```

**Symboles :**
- **⚏ (━━━)** : Yang immobile = Force continue
- **⚌ (━ ━)** : Yin immobile = Réceptivité stable
- **⚍ (━━━⟳)** : Yang changeant = Transformation active
- **⚎ (━ ━⟳)** : Yin changeant = Transformation réceptive

#### Étape 3 : Tirer les Traits 2 et 3
```
Cliquer : 🎲 Tirer le Trait 2
         ↓
Sélectionner le Type parmi 4 options
         ↓
Cliquer : 🎲 Tirer le Trait 3
         ↓
Trigramme 1 Révélé !
         ↓
Affichage du symbole : ☰ ☱ ☲ ☳ ☴ ☵ ☶ ☷
         Avec nom pinyin et français
```

**Résultat Phase 1 :**
```
☷ Kūn — Terre (Réceptif, stable)
☶ Gèn — Montagne (Immobilité, repos)
☵ Kǎn — Eau (Profondeur, danger)
☴ Xùn — Vent (Pénétration, douceur)
☳ Zhèn — Tonnerre (Mouvement, choc)
☲ Lí — Feu (Clarté, adhérence)
☱ Duì — Lac (Joie, échange)
☰ Qiàn — Ciel (Créatif, actif)
```

### **Phase 2 : Construction du Trigramme Supérieur**
Recommencez exactement le même processus :
1. Tirer le Trait 1
2. Choisir parmi 4 types
3. Tirer et choisir le Trait 2
4. Tirer et choisir le Trait 3

### **Phase 3 : L'Hexagramme Révélé**
```
Les 2 trigrammes se croisent dans la Table Périodique
         ↓
L'intersection = Hexagramme du Yi Ching (1-64)
         ↓
Affichage complet avec :
  • Symbole hexagramme
  • Nom français
  • Numéro Yi Ching
  • Trigrammes inférieur/supérieur
  • Arcane Tarot correspondante
```

---

## 🎲 Mathématique du Yi Ching

### **Comment les Traits Forment un Trigramme**

Chaque trigramme est composé de **3 traits** (de bas en haut) :

```
Trait 3 (haut)   ─────  ou  ─ ─
Trait 2 (milieu) ─────  ou  ─ ─
Trait 1 (bas)    ─────  ou  ─ ─
```

**Système Binaire :**
```
Yang (─────) = 1
Yin (─ ─)   = 0
```

**Calcul du Trigramme :**
```
Nombre = (Trait3 × 4) + (Trait2 × 2) + Trait1

Exemple :
  Trait 1 : Yin = 0
  Trait 2 : Yang = 1
  Trait 3 : Yang = 1
  
  Nombre = (1 × 4) + (1 × 2) + 0 = 6
  Trigramme 6 = ☲ Lí (Feu)
```

### **Les 8 Trigrammes (Index 0-7)**

| Index | Binaire | Symbole | Pinyin | Français | Qualité |
|-------|---------|---------|--------|----------|---------|
| 0 | 000 | ☷ | Kūn | Terre | Réceptif |
| 1 | 001 | ☶ | Gèn | Montagne | Immobile |
| 2 | 010 | ☵ | Kǎn | Eau | Profond |
| 3 | 011 | ☴ | Xùn | Vent | Pénétrant |
| 4 | 100 | ☳ | Zhèn | Tonnerre | Mouvant |
| 5 | 101 | ☲ | Lí | Feu | Clair |
| 6 | 110 | ☱ | Duì | Lac | Joyeux |
| 7 | 111 | ☰ | Qiàn | Ciel | Créatif |

### **Comment l'Hexagramme se Forme**

```
Trigramme Inférieur (TI)  = rangée dans la table
Trigramme Supérieur (TS)  = colonne dans la table

GRID[TI][TS] = Hexagramme du Yi Ching (1-64)
```

**Exemple :**
```
TI = 0 (Kūn — Terre)
TS = 7 (Qiàn — Ciel)

GRID[0][7] = 12

Hexagramme 12 = "Adversité" (天地否)
```

---

## 📊 Les 4 Types de Traits

### **Les 2 Bases**
```
Yang (─────) = Force complète, immuable
Yin (─ ─)   = Réceptif séparé, immuable
```

### **Les 2 Changeants**
```
Yang Changeant (─────⟳) = Force qui se transforme en Yin
Yin Changeant (─ ─⟳)   = Yin qui se transforme en Yang
```

### **Signification Divinatoire**

| Trait | Symbole | Sens | Transformation |
|-------|---------|------|-----------------|
| **Yang** | ⚏ | Force, action, lumière | Aucune |
| **Yin** | ⚌ | Réceptif, repos, obscurité | Aucune |
| **Yang Changeant** | ⚍ | Force active en mutation | Devient Yin |
| **Yin Changeant** | ⚎ | Réceptif en évolution | Devient Yang |

---

## 🎯 Exemple Complet de Consultation

### **Phase 1 : Trigramme 1**
```
Clic 1 : 🎲 Tirer le Trait 1
Résultat : Yang (━━━)

Choix : Sélectionner ⚍ (Yang Changeant)

Clic 2 : 🎲 Tirer le Trait 2
Résultat : Yin (━ ━)

Choix : Sélectionner ⚌ (Yin Immobile)

Clic 3 : 🎲 Tirer le Trait 3
Résultat : Yang (━━━)

Choix : Sélectionner ⚏ (Yang Immobile)

━━━⟳ (Yang Chang)
━ ━  (Yin)
━━━  (Yang)

Calcul : (1×4) + (0×2) + 1 = 5

Trigramme 1 = Index 5 = ☲ Lí (Feu)
```

### **Phase 2 : Trigramme 2** 
```
Clic 4 : 🎲 Tirer le Trait 1
Résultat : Yang

Choix : ⚏ (Yang Immobile)

Clic 5 : 🎲 Tirer le Trait 2
Résultat : Yin

Choix : ⚌ (Yin Immobile)

Clic 6 : 🎲 Tirer le Trait 3
Résultat : Yin

Choix : ⚌ (Yin Immobile)

━ ━  (Yin)
━ ━  (Yin)
━━━  (Yang)

Calcul : (0×4) + (0×2) + 1 = 1

Trigramme 2 = Index 1 = ☶ Gèn (Montagne)
```

### **Phase 3 : Hexagramme Final**
```
TI = 5 (Lí — Feu)
TS = 1 (Gèn — Montagne)

GRID[5][1] = 22

Hexagramme 22 = "Embellir" (山火賁)

Affichage :
  ䷕
  Embellir
  Hexagramme n°22
  
  Trigramme Inférieur : ☲ Lí — Feu
  Trigramme Supérieur : ☶ Gèn — Montagne
  Arcane Tarot : 10 de Deniers
```

---

## 🎮 Mode d'Emploi Détaillé

### **Installation Android**
```
1. Télécharger index_interactive.html
2. Ouvrir avec Chrome
3. Attendre le prompt "Installer"
4. Installer comme PWA
5. L'app s'ajoute à l'écran d'accueil
```

### **Utilisation**
```
1. Lancer l'app depuis l'écran d'accueil
2. Lire les instructions
3. Cliquer : ✦ Commencer le Tirage ✦
4. À chaque étape :
   - Cliquer pour tirer un trait
   - Choisir le type parmi 4 options
   - Répéter 3 fois pour un trigramme
5. Recommencer pour le 2e trigramme
6. Voir l'hexagramme final
7. Cliquer pour une nouvelle consultation
```

---

## 💡 Interprétation

### **Les Traits Changeants**
Les traits changeants (⚍ et ⚎) indiquent une **transformation en cours** :
- **Yang Changeant** → Force qui devient réceptive
- **Yin Changeant** → Réceptif qui devient actif

Cela suggère une **période de transition** ou un **changement énergétique**.

### **Combinaisons Significatives**

**6 Yangs (⚏⚏⚏)** = Trigramme ☰ Qiàn (Ciel)
- Maximum de force créative
- Action pure, expansion maximale

**6 Yins (⚌⚌⚌)** = Trigramme ☷ Kūn (Terre)
- Maximum de réceptivité
- Accueil complet, stabilité absolue

**3 Yins + 3 Yangs** = Équilibre
- Harmonie des forces
- Momento d'équité

---

## 🔮 Maîtriser la Méthode

### **Conseil 1 : Respecter le Ordre**
Les traits se tirent **de bas en haut** mais s'affichent **de haut en bas** :
```
Trait 3 (dernier tiré, en haut)
Trait 2 (deuxième tiré, au milieu)
Trait 1 (premier tiré, en bas)
```

### **Conseil 2 : Les Traits Changeants**
Notez mentalement les traits changeants (⚍ et ⚎) :
- Ils indiquent les **zones de transition** de votre tirage
- Ils peuvent révéler les **actions à prendre**

### **Conseil 3 : Les Trigrammes Opposés**
```
Qiàn ☰ (Ciel) est opposé à Kūn ☷ (Terre)
Zhèn ☳ (Tonnerre) est opposé à Xùn ☴ (Vent)
Kǎn ☵ (Eau) est opposé à Lí ☲ (Feu)
Gèn ☶ (Montagne) est opposé à Duì ☱ (Lac)
```

Les hexagrammes opposés révèlent souvent des **tensions ou complémentarités**.

---

## 🌟 Fichiers

**Fichier Principal :**
✅ `index_interactive.html` — Oracle Yi Ching Interactif

**Fonctionnalités :**
- ✨ Interface interactive à chaque étape
- ✨ 4 choix pour chaque trait
- ✨ Calcul automatique des trigrammes
- ✨ Consultation de la Table Périodique
- ✨ Résumé complet de l'hexagramme
- ✨ Arcane Tarot correspondante

---

**🔮 Bonne consultation ! Que chaque trait révèle votre destinée. ✦**

*— Arnauld de Beaugency*
