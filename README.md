# 📋 EduKanban École

> **Tableau Kanban collaboratif pour les équipes pédagogiques des écoles primaires**  
> Gratuit · Sans installation · Sans compte · 100% RGPD · Données stockées localement

![EduKanban Badge](https://img.shields.io/badge/Éducation%20Nationale-ERUN%2077-2D6A4F?style=flat-square)
![RGPD Badge](https://img.shields.io/badge/RGPD-100%25%20local-1F5C3A?style=flat-square)
![Licence Badge](https://img.shields.io/badge/Licence-Libre%20usage%20pédagogique-blue?style=flat-square)
![HTML Badge](https://img.shields.io/badge/Tech-HTML%20%2F%20CSS%20%2F%20JS-F59E0B?style=flat-square)

---

## 🚀 Utiliser l'application

### ▶️ [→ Ouvrir EduKanban École](https://isabellebareyre.github.io/edukanban/)

> *(Remplacez le lien ci-dessus par votre URL GitHub Pages une fois déployée)*

Ou téléchargez le fichier [`index.html`](./index.html) et ouvrez-le directement dans votre navigateur — aucune installation requise.

---

## 🎯 À quoi ça sert ?

EduKanban École est une application de **gestion de projet visuelle** (méthode Kanban) conçue spécifiquement pour les **directeurs d'école, équipes pédagogiques et personnels de l'Éducation Nationale**.

### Usages typiques
- 📊 **Suivi des évaluations nationales**  — de l'analyse à la remédiation
- 🏫 **Pilotage du projet d'école)** — actions, responsables, échéances
- 💻 **Plan numérique** — déploiement ENT, formations, équipements
- 🗣 **Préparation des conseils** d'école et de cycle
- ♿ **Dispositifs élèves** — suivi PPRE, PAP, PAI, PPS
- 📌 **Tout projet d'équipe** nécessitant un suivi collaboratif

---

## ✨ Fonctionnalités

### 5 vues complémentaires

| Vue | Description |
|-----|-------------|
| 📋 **Tableau Kanban** | 4 colonnes (À faire / En cours / En révision / Terminé), glisser-déposer |
| 📅 **Calendrier** | Toutes les échéances sur un calendrier mensuel navigable |
| 📊 **Tableau de bord** | Avancement, charge par membre, répartition par priorité et étiquette |
| 📄 **Ordre du jour** | Génération automatique pour les réunions, impression A4 |
| 👥 **Vue par membre** | Charge de travail de chaque enseignant, filtre par projet |

### Gestion complète
- 🗂 **Projets multiples** — créer, renommer, supprimer à volonté
- 🏷 **Étiquettes personnalisables** — avec emoji et couleur au choix
- 👥 **Multi-responsables** — une tâche peut être assignée à plusieurs personnes
- 🔴🟡🟢 **Niveaux de priorité** — Haute / Moyenne / Basse
- ⚠️ **Alertes de retard** — les tâches échues apparaissent en rouge dans toutes les vues
- 🖨 **Impression A4 paysage** — export propre de chaque projet

### Sauvegarde & partage
- 💾 **Export JSON** — sauvegarde horodatée d'un clic (ou `Ctrl+S`)
- 📂 **Import JSON** — restauration ou partage entre collègues
- 🔄 **Sauvegarde automatique** dans le navigateur entre les sessions

---

## 🔒 Conformité RGPD

> **Aucune donnée ne quitte votre ordinateur.**

- ❌ Pas de serveur distant
- ❌ Pas de compte utilisateur
- ❌ Pas de cookies de tracking
- ❌ Pas de collecte d'analytics
- ✅ Stockage 100% local (`localStorage` du navigateur)
- ✅ Fichier JSON exportable et lisible par un humain
- ✅ Utilisable hors connexion après le premier chargement

Conforme aux exigences de la **CNIL** et aux recommandations numériques de l'**Éducation Nationale** pour le traitement des données en contexte scolaire.

---

## ⌨️ Raccourcis clavier

| Raccourci | Action |
|-----------|--------|
| `Ctrl + S` | Sauvegarder le tableau en JSON |
| `Ctrl + N` | Créer une nouvelle tâche |
| `Ctrl + P` | Imprimer le projet actif (A4 paysage) |
| `Échap` | Fermer la fenêtre active |

> Sur Mac : remplacer `Ctrl` par `Cmd ⌘`

---

## 🛠 Technologies

Un seul fichier HTML autonome — aucune dépendance externe, aucun framework, aucun build requis.

```
index.html        ← L'application complète (~95 Ko)
README.md         ← Ce fichier
```

- **HTML5** — structure et contenu
- **CSS3** — mise en page, animations, responsive, styles d'impression
- **JavaScript Vanilla** — logique, drag & drop, rendu dynamique
- **localStorage** — persistance des données côté navigateur
- **Google Fonts** — Bricolage Grotesque + DM Sans (chargées en ligne)

---

## 📦 Installation & déploiement

### Option 1 — Utilisation locale (0 configuration)
```
1. Télécharger index.html
2. Double-cliquer pour ouvrir dans Chrome ou Firefox
3. C'est tout.
```

### Option 2 — GitHub Pages (accès URL publique)
```
1. Forker ce dépôt (bouton Fork en haut à droite)
2. Aller dans Settings → Pages
3. Source : Deploy from branch → main → / (root)
4. Sauvegarder → URL disponible en 2 minutes
```

### Option 3 — Partage en réseau local scolaire
```
1. Placer index.html dans un dossier partagé (Teams, ENT, serveur école)
2. Partager le chemin réseau aux collègues
3. Chacun ouvre le fichier dans son navigateur
4. Partage des données via export/import JSON
```

---

## 🤝 Contribuer

Les retours et suggestions sont les bienvenus, notamment de la part des **directeurs d'école, enseignants et personnels de l'EN** qui utilisent l'outil au quotidien.

- 🐛 **Signaler un bug** → [Ouvrir une issue](../../issues)
- 💡 **Suggérer une fonctionnalité** → [Ouvrir une issue](../../issues) avec le label `enhancement`
- 🔀 **Proposer une modification** → Pull request bienvenue

---

## 📄 Licence

**Usage pédagogique libre.**  
Cet outil est mis à disposition gratuitement pour un usage dans le cadre de l'Éducation Nationale et des établissements scolaires. Toute utilisation commerciale est soumise à accord préalable.

---

## 👩‍💻 Auteure

**Isabelle BAREYRE**  
ERUN — Enseignante Référente aux Usages du Numérique  
Seine-et-Marne (77) · Académie de Créteil




📧 *Contact via GitHub Issues ou LinkedIn*

---

*EduKanban École — Parce que les équipes enseignantes méritent les mêmes outils de pilotage que les équipes agiles, adaptés à leur contexte.*
