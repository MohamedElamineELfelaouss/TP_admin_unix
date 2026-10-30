# TP — Administration Unix

Corrections, captures d'écran et comptes rendus des travaux pratiques d'administration Unix.

## Organisation

```text
TP_admin_unix/
├── TPN2/
│   ├── screenshots/
│   └── compte_rendu/
├── TPN3/
│   ├── screenshots/
│   └── compte_rendu/
└── TPN4/
    ├── screenshots/
    └── compte_rendu/
```

Pour chaque TP, déposer les captures d'écran dans `screenshots/`, le compte rendu (PDF, DOCX ou Markdown) dans `compte_rendu/` et les scripts ou corrections directement dans le dossier du TP.

## Publier les modifications

Ouvrir PowerShell et exécuter :

```powershell
cd "$HOME\Desktop\TP_admin_unix"
git add .
git commit -m "Ajout de la correction du TPN2"
git push
```

Adapter le message du commit au TP concerné. Pour ajouter un nouveau TP, créer son dossier ici, puis utiliser les mêmes commandes.
