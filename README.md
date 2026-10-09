# INFOTELCOM — Protocole d’accord de partenariat et de collaboration

Site web statique pour permettre aux structures candidates de renseigner le protocole d’accord INFOTELCOM et de télécharger ensemble :
- le protocole prérempli au format PDF ;
- une version PDF de présentation institutionnelle d’INFOTELCOM.

## Fonctionnement
1. Le partenaire complète les champs obligatoires et choisit au moins une forme de collaboration.
2. Il confirme l’exactitude des informations.
3. Le bouton de téléchargement s’active uniquement lorsque le formulaire est valide.
4. Un fichier ZIP est généré localement dans le navigateur avec les deux PDF.

## Confidentialité
Cette version ne transmet pas les réponses à un serveur : la génération se fait dans le navigateur. Le site ne sauvegarde pas les demandes. Pour une collecte centralisée ou un envoi automatique à INFOTELCOM, il faudra ajouter un backend sécurisé, une politique de confidentialité et des règles de conservation des données.

## Publication GitHub Pages
Le workflow `.github/workflows/pages.yml` déploie le contenu du dépôt sur GitHub Pages à chaque push sur `main`.

Après activation de GitHub Pages avec la source **GitHub Actions**, le site sera disponible à :
https://infotelcom.github.io/INFOTELCOM-Protocole-d-accord-de-partenariat-et-de-collaboration/

## Important
Le téléchargement ne constitue ni une acceptation de partenariat ni une signature électronique. Le protocole doit être vérifié et signé par les représentants habilités.
