## Fonctionnement

La commande `command -v` recherche l'exécutable dans le `PATH` système :

- Si l'outil est trouvé, elle retourne son chemin et le code de sortie `0` (succès)
- L'opérateur `&&` exécute alors le `echo` pour afficher le message de confirmation
- Si l'outil n'est pas trouvé, rien ne s'affiche pour cette ligne

## Utilisation

```bash
chmod +x verif.sh

./verif.sh
```

### Lien Github

[Lien vers le git](https://github.com/yacineKHA/prairie.git)