# 📈 Suivi d'Investissements Personnels

Application web interactive de suivi d'investissements personnels sous forme de timeline mensuelle.

## Fonctionnalités

- **3 statuts** : Réalisé ✅ / Planifié 🗓 / Prévisionnel 💡
- **Métriques globales** : totaux par statut, valeur future estimée, gain net
- **Graphique mensuel** : barres groupées avec effet lumineux
- **Projection ROI** : courbes sur 10 ans par investissement et portefeuille total
- **Timeline chronologique** : cartes avec bordure lumineuse colorée, filtre et recherche
- **Module ROI** : calcul par intérêts composés, sparkline individuel
- **Formulaire modal** : ajout / modification / suppression
- **Persistance** : localStorage
- **Mode sombre** automatique via `prefers-color-scheme`
- **Compatible iOS** : safe areas, touch targets 44px, bottom sheet

## Stack

- HTML + CSS + JavaScript Vanilla — **un seul fichier `index.html`**
- [Chart.js 4.4.1](https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js) via CDN
- Aucun build tool, aucune dépendance npm

## Déploiement

Application statique déployée sur **Vercel** : aucune configuration serveur requise.

## Lancer en local

Ouvrir `index.html` directement dans le navigateur, ou utiliser un serveur local :

```bash
npx serve .
```
