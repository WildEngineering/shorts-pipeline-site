# Site public — pages légales pour l'audit TikTok / la vérification Google

Trois pages statiques autonomes (aucune dépendance, style inline) :

| Fichier | Sert de… |
|---------|----------|
| `index.html` | **Web/Desktop URL** de l'app (page d'accueil qui décrit l'outil) |
| `privacy.html` | **Privacy Policy URL** |
| `terms.html` | **Terms of Service URL** |

## Publier sur GitHub Pages (gratuit, ~3 min)

1. Crée un dépôt **public**, ex. `shorts-pipeline-site`.
2. Dépose les trois fichiers `.html` **à la racine** du dépôt.
3. Dépôt → **Settings → Pages** → *Build and deployment* → *Source : Deploy from a branch* →
   branche `main`, dossier `/ (root)` → **Save**.
4. Au bout d'une minute, le site est en ligne à :
   `https://<ton-user-github>.github.io/shorts-pipeline-site/`

## Les 3 URLs à coller dans le formulaire TikTok

En remplaçant `<user>` par ton pseudo GitHub :

- **Web/Desktop URL** : `https://<user>.github.io/shorts-pipeline-site/`
- **Privacy Policy URL** : `https://<user>.github.io/shorts-pipeline-site/privacy.html`
- **Terms of Service URL** : `https://<user>.github.io/shorts-pipeline-site/terms.html`

## Alternatives sans GitHub
- **Notion** : colle le contenu dans 3 pages, publie-les sur le web, récupère les URLs.
- **Netlify / Cloudflare Pages** : glisse-dépose le dossier `site/`.

## À personnaliser avant publication
- L'e-mail de contact est `aivideostom@gmail.com` (modifiable dans les 3 fichiers).
- La date d'effet est le **13 juillet 2026**.
- Ces pages servent **aussi** à la vérification OAuth Google (YouTube) — mutualise-les.
