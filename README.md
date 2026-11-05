# J.2.0 — Mon conseiller IA

Mini-application web statique en français, avec l'identité visuelle J.2.0, habillée avec l'identité colorée et ludique J.2.0 : 10 questions, recommandations personnalisées et liens vers les outils d'IA.

## Lancer l'application
Ouvrez simplement `index.html` dans un navigateur. Aucun serveur, compte, base de données ou clé API n'est nécessaire.

## Publier gratuitement avec GitHub Pages
1. Créez un dépôt GitHub public, par exemple `mon-conseiller-ia`.
2. Ajoutez `index.html` à la racine du dépôt (vous pouvez aussi ajouter ce README).
3. Dans le dépôt, ouvrez **Settings > Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**.
5. Sélectionnez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**.
6. Après quelques minutes, le site sera disponible à l'adresse `https://VOTRE-PSEUDO.github.io/mon-conseiller-ia/`.

## Personnalisation
Les questions se trouvent dans le tableau `questions` du fichier `index.html`. Les outils et leurs liens sont définis dans le tableau `tools`. Le système de recommandation est local au navigateur : il compare les thèmes choisis aux compétences associées à chaque outil.

## À propos des offres gratuites
Une formule gratuite est disponible pour les outils listés, mais les quotas, fonctions accessibles, pays disponibles et conditions peuvent changer. L'application ne promet pas un accès gratuit illimité : elle invite à vérifier les conditions sur les sites officiels.

## Confidentialité
Les réponses ne quittent pas le navigateur et aucun suivi analytique n'est installé.
