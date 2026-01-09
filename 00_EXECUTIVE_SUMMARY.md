# PERFORMANCE OS – EXECUTIVE SUMMARY

## 🎯 Vision en Une Phrase

**Performance OS est la plateforme EPM AI-Native qui combine la robustesse des modules natifs de Tagetik, la flexibilité du moteur multidimensionnel de Pigment, et l'IA déterministe au cœur du produit.**

---

## 💡 Le Problème du Marché

Le marché EPM (Enterprise Performance Management) est bloqué par un **faux dilemme** :

- **Pigment/Anaplan** : Flexibilité totale, mais tout à construire from scratch → 2-3 mois de déploiement, dépendance consultants
- **Vulki/Tagetik** : Modules natifs packagés, mais rigides et impossible à étendre → Projets 9-12 mois, architecture legacy

**Résultat** : Les entreprises doivent choisir entre agilité (Pigment) et time-to-value (Tagetik), puis acheter 3-4 outils séparés (Sales Perf + Finance + BI + Data Prep).

---

## 🧭 Calibration : Vision Plateforme vs Wedge Produit

**Positionnement** : Performance OS est une **plateforme multi-départements** (Sales, Finance, HR...) — mais se construit avec un **wedge initial** très focalisé.

- **Vision (long terme)** : Un moteur universel + modules natifs + IA déterministe + collaboration + marketplace, pour adresser plusieurs départements sans refonte.
- **Wedge (Phase 1)** : Sales Performance (commissions/incentives) = entrée de marché pour prouver vitesse, auditabilité et adoption.
- **Règle de discipline** : *on sur-conçoit l’architecture, on sous-conçoit le scope produit au départ*.

---

## ✅ La Solution : Architecture 3 Couches Plugin-Based

Performance OS résout ce dilemme avec une **architecture modulaire en 3 couches** :

### **Couche 1 : Core Platform (Moteur Universel)**
- Moteur de calcul multidimensionnel (formules no-code, dimensions à la volée)
- Universal Ledger scalable (DuckDB, schéma évolutif sans migration)
- IA intégrée (génération de règles, mapping, prévisions)
- Progressive Web App responsive (desktop + mobile)

### **Couche 2 : Modules Natifs Évolutifs (Plugin-Based)**
- **Sales Performance** (Phase 1) : Commissions, incentives, contests
- **Financial Planning** (Phase 2) : Budgets, forecasts, simulations
- **Consolidation IFRS** (Phase 3) : Éliminations intercos, périmètre, reporting statutaire

**Clé** : Modules = code versionné (plugins), pas copies de paramétrages → **Auto-upgrade en 30s sans perte de customisation** (vs 2-3h migration manuelle Tagetik/Pigment)

### **Couche 3 : UX Persona Adaptive**
- Même data, UX différente par rôle + device
- Sales Ops (desktop), Sales Rep (mobile), CFO (hybrid)

---

## 🚀 Différenciateurs Clés

### **1. Time-to-Value : 2 semaines (vs 3 mois Vulki, vs 9-12 mois Tagetik)**
- IA génère plans de commission en 30 min (vs 2 jours manuels)
- Modules natifs pré-packagés avec best practices intégrées
- Extensibilité totale via formules no-code + SDK marketplace

### **2. Architecture Plugin-Based Unique**
- **Modules natifs upgradables automatiquement** en 30s, config client préservée
- **Marketplace écosystème** : Intégrateurs créent packages sectoriels, ISV créent plugins/apps
- **5 garde-fous critiques** : Séparation code/config, tests non-régression, sandbox, versioning, rollback auto

### **3. IA Déterministe (Zero-Trust) + Collaboration Temps Réel**
- **L'IA propose, jamais n'exécute** : Validation humaine obligatoire
- **Build vs Run** : IA aide au paramétrage (1×), exécution sans IA (coûts maîtrisés, pas d'hallucination)
- **Souveraineté IA** : Choix provider (Mistral, OpenAI, Gemini, Claude) selon besoins conformité
- **Collaboration Google Sheets-like** : Édition temps réel multi-users, workflows de validation, notifications Teams/Slack/Email
- **Audit trail complet** : Qui a validé quoi, quand, pourquoi (exportable pour auditeurs)

### **4. Plateforme Universelle Progressive**
- **Même architecture** pour Sales Perf, Finance, Consolidation, HR Perf
- **Land & Expand** : Démarrer sur Sales Perf (Phase 1), étendre vers Finance (Phase 2), puis EPM complet (Phase 3)
- **Remplace 3 outils** : Vulki + Pigment + BI en une seule plateforme

---

## 📊 Stratégie Go-to-Market : Sales Perf → Finance → EPM

### **Phase 1 (M0-M12) : Sales Performance Management**
- **Cible** : PME/ETI tech/B2B, 10-100 sales, CA 10M€-200M€
- **Pain** : Litiges commissions, paramétrage lourd, manque de transparence
- **Modules** : Sales Commission, Sales Contests, Sales Forecasting
- **Pricing** : 1-3k€/mois, onboarding inclus
- **KPI** : 10 clients, ARR 200-400k€ (MRR moyen 2k€)

**Pourquoi Sales Perf d'abord ?**
- Pain fort et universel (litiges commissions = turnover sales)
- Time-to-value immédiat (2 semaines vs 3 mois Vulki)
- Pas de conflit Alteryx (marché différent)
- Architecture EPM universelle dès M0 (extensible vers Finance)

### **Phase 2 (M12-M24) : Extension Financial Planning & Analysis**
- **Modules** : Budget Planning, Rolling Forecast, Variance Analysis
- **Cross-sell** : Clients Sales Perf étendent vers Finance (land & expand)
- **Pricing** : 3-8k€/mois
- **KPI** : 30 clients (15 Sales only, 15 Sales+Finance), ARR 800k€-1,5M€, NRR 140%

### **Phase 3 (M24-M36) : EPM Complet (Consolidation + Marketplace)**
- **Modules** : Consolidation IFRS, Intercompany, Currency Translation
- **SDK Marketplace** : Partenaires créent plugins/apps (ESG, Retail, Manufacturing)
- **Pricing** : 8-25k€/mois
- **KPI** : 100 clients, ARR 5-10M€

---

## 🧩 Concurrence (SPM & EPM) – Pourquoi on gagne

**SPM (Sales Performance Management)** :
- **Xactly / Spiff / CaptivateIQ** : Orientés “commission”, mais peu de moteur universel + audit déterministe + extensibilité plateforme.
- **Excel + scripts + BI** : Flexible mais non gouverné (risques litiges, erreurs, dépendance personnes clés).

**EPM (Finance)** :
- **Pigment / Anaplan** : Flexibles, mais nécessitent de tout construire + starter kits difficilement évolutifs.
- **Tagetik / HFM** : Natif robuste, mais rigide, lourd à déployer, et faible extensibilité.

**Notre pari** : combiner **wedge SPM** (pain immédiat) + **architecture plateforme** (expansion multi-départements).

---

## 🎯 Avantages Concurrentiels Défensifs

| **Critère** | **Performance OS** | **Pigment/Anaplan** | **Vulki/Tagetik** |
|-------------|-------------------|---------------------|-------------------|
| **Time-to-Value** | 2 semaines | 2-3 mois | 9-12 mois |
| **Modules natifs** | ✅ Évolutifs (plugin) | ❌ À construire | ✅ Rigides |
| **Extensibilité** | ✅ Formules + SDK | ⭐⭐⭐⭐ Formules | ⭐ Workarounds |
| **Upgrade modules** | ✅ Auto 30s | ⚠️ Migration manuelle | ✅ Auto mais rigide |
| **IA intégrée** | ✅ Déterministe | ⚠️ Chatbot gadget | ❌ Absente |
| **Collaboration** | ✅ Temps réel + workflows | ⭐⭐⭐ Temps réel | ⭐ Séquentiel |
| **Marketplace** | ✅ SDK partenaires | ❌ Absent | ❌ Absent |
| **Coût annuel** | 36-60k€ | 40-80k€ | 150-250k€ |

**Barrières à l'entrée croissantes** :
- Marketplace écosystème (effet réseau, switching cost élevé)
- Modules natifs évolutifs (impossible à répliquer avec starter kits)
- Architecture plugin-based (IP technique brevetable)

---

## 💰 Modèle Économique

### **Pricing SaaS Transparent**
- **Socle** : 2-5k€/mois (plateforme + stockage 100 Go)
- **Usage Data** : €/Go/mois au-delà du socle
- **Usage IA** : €/règle générée (plafond mensuel pour éviter surprises)
- **Users** : Forfait par tranche (1-10, 11-50, 51-200, 200+)

**Exemple Phase 1 (Sales Perf, 50 sales)** : ~2-3k€/mois (24-36k€/an)

**Exemple Phase 3 (EPM Complet, 100 users)** : ~8-15k€/mois (96-180k€/an) vs 150-250k€/an Tagetik

### **Revenue Streams**
1. **SaaS récurrent** : Licences + usage (70-80% ARR)
2. **Marketplace** : Commission 20-40% sur packages/plugins/apps partenaires (10-20% ARR)
3. **Services** : Onboarding, formation, support premium (10% ARR)

### **Unit Economics Cibles**
- **CAC** : 10-15k€ (inbound + POC gratuits)
- **LTV** : 100-150k€ (NRR 140%, retention 3-5 ans)
- **LTV/CAC** : 8-10× (benchmark SaaS : >3×)
- **Payback** : 6-9 mois

---

## 📌 Traction & Plan de Preuve (à compléter)

**Objectif** : transformer la vision en preuves en 6-12 semaines.

- **Design partners** (cible) : 3-5 entreprises (Sales Ops + Finance) pour itérer le wedge et valider l’architecture.
- **Mesures Phase 1** :
  - Time-to-value (premier calcul validé) : < 2 semaines
  - % tickets litiges commissions : -50% à -80%
  - % règles documentées/auditées : 100%
  - Adoption : > 60% utilisateurs actifs hebdo (Sales Rep)
- **Preuves commerciales** : LOI / pilote / budget identifié / sponsor interne (CFO ou Sales Ops).

---

## ⚠️ Risques Principaux & Mitigations

- **Risque “trop large”** : Roadmap plateforme qui dilue l’exécution.
  - **Mitigation** : wedge Phase 1 non négociable + métriques + non-goals explicites.
- **Risque “moteur universel trop tôt”** : complexité technique avant PMF.
  - **Mitigation** : core minimal (ledger + rules + audit) et modules progressifs.
- **Risque confiance (finance)** : peur d’erreurs/hallucinations.
  - **Mitigation** : build vs run, validation humaine, shadow calc, rollback, audit trail.
- **Risque go-to-market** : cycle plus long que prévu si on vise trop “EPM”.
  - **Mitigation** : vendre d’abord le pain SPM (ROI immédiat), puis expansion.

---

## 👥 Équipe Fondatrice

**Benoit Conley** (Fondateur)
- **Ex-Tagetik** : Consultant consolidation IFRS, ETL, pilotage performance (5 ans)
- **Alteryx** : Sales Engineer Data Prep & Analytics (actuellement)
- **Expertise unique** : Finance × Data Prep × IA
- **Vision** : Construire la plateforme AI-Native universelle pour le Performance Management

**Co-fondateur potentiel (en discussion)**
- Expertise Sales Operations, Commissions, Incentives
- Validation marché Sales Performance Management

**Besoins immédiats** :
- CTO/Lead Dev (full-stack SaaS + IA)
- Premier commercial/Sales Ops (validation ICP, POC clients)

---

## 🎯 Roadmap Produit

### **M0-M6 (MVP Phase 1)**
- Core Platform : Moteur universel + Universal Ledger + IA intégrée
- Module natif Sales Commission + UX Sales Ops/Manager/Rep
- POC 3-5 clients pilotes (gratuits, validation product-market fit)

### **M6-M12 (Extension Phase 1)**
- Modules Sales Contests, Sales Forecasting
- 10 clients payants, ARR 200-400k€

### **M12-M18 (Phase 2)**
- Module Budget Planning + UX CFO/Contrôleur/DAF
- 30 clients, ARR 800k€-1,5M€

### **M18-M24 (SDK Beta)**
- Ouverture SDK (5-10 partenaires pilotes)
- 1er plugin certifié (ESG Reporting)

### **M24-M36 (Phase 3)**
- Module Consolidation IFRS
- Marketplace publique (10 plugins/apps, 20 packages)
- 100 clients, ARR 5-10M€

---

## 💵 Besoins de Financement

### **Seed Round (cible 500k€-1M€)**
**Allocation** :
- **Produit** (50%) : CTO + 2 devs (full-stack SaaS, IA, frontend)
- **Go-to-Market** (30%) : 1 commercial/Sales Ops + marketing inbound
- **Ops** (20%) : Infra cloud, outils, légal, admin

**Runway** : 18-24 mois jusqu'à Series A

**Milestones Seed** :
- M6 : MVP + 3 POC clients validés
- M12 : 10 clients payants, ARR 200-400k€
- M18 : 30 clients, ARR 800k€-1,5M€, product-market fit consolidé

### **Series A (cible 3-5M€, M18-M24)**
**Objectifs** :
- Scale commercial (5-10 commerciaux)
- Ouverture SDK + marketplace
- Extension géographique (UK, Benelux)
- 100 clients, ARR 5-10M€ (M36)

---

## 🏆 Pourquoi Maintenant ?

### **Convergence de 3 Tendances**

1. **IA Générative Mature (2023-2024)**
   - LLMs souverains (Mistral AI) performants et abordables
   - Prompts déterministes pour use cases métier (fini l'hallucination)

2. **Marché EPM en Transition (2024-2025)**
   - Tagetik/HFM legacy vieillissants (architecture 2000s)
   - Pigment/Anaplan montrent les limites du "tout flexible" (projets longs, dépendance consultants)
   - Vulki acquis par des fonds → risque produit

3. **Demande Forte de Souveraineté (EU)**
   - RGPD, Cloud Act, souveraineté données sensibles (finance, RH)
   - Hébergement UE + LLM européens = différenciateur commercial

**Fenêtre d'opportunité** : 18-24 mois avant que les incumbents rattrapent leur retard IA (cycles produit 2-3 ans chez Oracle/SAP/Wolters Kluwer).

---

## 📞 Next Steps

**Pour investisseurs** :
- Démo produit (prototype fonctionnel disponible)
- Deck complet + modèle financier détaillé
- Références clients potentiels (LOI en discussion)

**Pour partenaires stratégiques** :
- Discussion co-développement modules sectoriels
- Pilote SDK marketplace (M18-M24)

**Contact** : benoit.conley@alteryx.com

---

**Performance OS : L'EPM AI-Native qui combine la robustesse de Tagetik, la flexibilité de Pigment, et l'IA au cœur.** 🚀
