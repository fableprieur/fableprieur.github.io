# Site web de Fabien Leprieur

Site statique (HTML/CSS, aucune dépendance) prêt pour GitHub Pages.

## Mettre en ligne
1. Créer un compte sur https://github.com (si besoin).
2. New repository → nom : `VOTRE-PSEUDO.github.io` → Public → Create.
3. « uploading an existing file » → glisser TOUT le contenu de ce dossier (fichiers + dossier `img`) → Commit changes.
4. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)` → Save.
5. Après 1–2 minutes, le site est en ligne sur https://VOTRE-PSEUDO.github.io

## Modifier
Cliquer sur un fichier .html dans GitHub → icône crayon → modifier → Commit changes. Le site se met à jour en ~1 minute.
Pour ajouter une publication : dans `publications.html`, copier une ligne `<li value="117">…</li>` et changer le numéro et le texte.

## Nom de domaine (optionnel)
Settings → Pages → Custom domain → saisir le domaine (ex. fabienleprieur.fr), puis chez le registrar (OVH, Gandi…) ajouter les enregistrements DNS indiqués par GitHub. Cocher « Enforce HTTPS ».
