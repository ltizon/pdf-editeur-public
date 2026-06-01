# PDF Editeur — canal public de mise à jour

Ce dépôt **public** héberge uniquement :

- **`version.json`** — le manifeste de version lu par l'application pour détecter
  les nouvelles versions (vérification « check + notification » au démarrage) ;
- les **installateurs** Windows, publiés dans les **[Releases](../../releases)**.

Le **code source** de PDF Editeur reste **privé**. Ce dépôt sert de canal de
distribution / mise à jour, sur le modèle de l'app sœur *Renommeur*.

PDF Editeur fait partie de la **suite Abeille Technologie**.

## Installation

Téléchargez le dernier `PDF_Editeur_Setup_<version>.exe` depuis la page
[Releases](../../releases) et exécutez-le.

## Manifeste

```json
{
  "latest": "0.5.0",
  "type": "minor",
  "download_url": "https://github.com/ltizon/pdf-editeur-public/releases/tag/v0.5.0"
}
```
