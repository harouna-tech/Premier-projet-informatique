## 🔹 Linux — Jour 5 : Sticky bit (README.md)

📄 **Linux/jour5/README.md**

```md
# Linux — Jour 5 : Sticky bit (t)

## Objectif
Sécuriser un dossier partagé afin d’empêcher la suppression abusive de fichiers.

## Notions abordées
- Sticky bit (`t`)
- Dossier /tmp
- Suppression contrôlée des fichiers

## Sticky bit
Dans un dossier avec le sticky bit :
- Tout le monde peut créer des fichiers
- Seul le propriétaire du fichier peut le supprimer

## Commandes utilisées
```bash
chmod +t dossier_partage
ls -ld dossier_partage
