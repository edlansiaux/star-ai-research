# STaR-AI - Systems for Triage and Response with AI

🏥 Site web du groupe de recherche STaR-AI dédié à l'amélioration du triage aux urgences par l'Intelligence Artificielle.

🌐 **Site bilingue** : Français / English

## 🚀 Déploiement GitHub Pages

### Option 1 : Déploiement automatique (recommandé)

1. **Fork** ce repository ou **push** vers votre compte GitHub
2. Allez dans **Settings** > **Pages**
3. Sous "Source", sélectionnez **Deploy from a branch**
4. Choisissez la branche `main` et le dossier `/ (root)`
5. Cliquez sur **Save**

Votre site sera accessible à : `https://[votre-username].github.io/[nom-du-repo]/`

### Option 2 : Avec un domaine personnalisé

1. Suivez l'Option 1
2. Dans **Settings** > **Pages** > **Custom domain**, entrez votre domaine
3. Créez un fichier `CNAME` à la racine contenant votre domaine :
   ```
   www.star-ai.fr
   ```
4. Configurez les DNS de votre domaine (voir [documentation GitHub](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site))

## 📁 Structure du projet

```
star-ai-github/
├── index.html              # Page d'accueil (FR)
├── README.md               # Ce fichier
├── .nojekyll               # Désactive Jekyll
├── assets/
│   └── css/
│       └── style.css       # Styles partagés
├── projets/                # Pages projets (FR)
│   ├── projet-tiaeu.html
│   ├── projet-tiaeu-2.html
│   ├── projet-triade.html
│   ├── projet-eimlia.html
│   └── projet-redirect.html
└── en/                     # Version anglaise
    ├── index.html          # Homepage (EN)
    └── projets/
        ├── projet-tiaeu.html
        ├── projet-tiaeu-2.html
        ├── projet-triade.html
        ├── projet-eimlia.html
        └── projet-redirect.html
```

## 🔬 Projets de Recherche

| Projet | Status | Description |
|--------|--------|-------------|
| **TIAEU** | ✅ Publié | Étude pilote monocentrique (n=657) - 90% concordance IA |
| **TIAEU-2** | 🔄 En cours | Validation multicentrique prospective (5 centres) |
| **TRIADE** | 💰 Financement | Essai randomisé bicentrique |
| **EIMLIA-3M-TEU** | 🔄 En cours | Évaluation par simulation hybride |
| **REDIRECT-IA** | 🌍 International | Collaboration France-Canada |

## 📚 Publications

- [JMIR Medical Informatics](https://doi.org/10.2196/83318) - Article principal TIAEU
- [IEEE/ACM BDCAT 2025](https://dl.acm.org/doi/10.1145/3773276.3774289) - Conférence Nantes

## 👥 Équipe

- **Dr Edouard Lansiaux** - Investigateur Principal, CHU de Lille
- **Dr Ramy Azzouz** - Co-directeur, CHU de Lille
- **Pr Emmanuel Chazard** - Méthodologie, METRICS ULR 2694
- **Pr Eric Wiel** - Direction Scientifique, CHU de Lille

## 📧 Contact

- Email : edouard.lansiaux@chu-lille.fr
- Institution : CHU de Lille, Pôle de l'Urgence

## 📄 Licence

© 2024-2026 STaR-AI Research Group. Tous droits réservés.

---

*Développé avec ❤️ pour améliorer le triage aux urgences*
