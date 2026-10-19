# Jovia 1.0.9

Cette version ajoute les sessions séparées par onglet et améliore les couleurs dynamiques et la stabilité du navigateur.

## Nouveautés

- **Plusieurs connexions au même site** : choisissez une session dans la barre latérale. Chaque session conserve ses cookies, données de site et mots de passe ; vos connexions existantes restent dans « Par défaut ».
- **Création et renommage des sessions** : créez une session depuis le sélecteur et renommez-la dans les paramètres de navigation.
- **Écran partagé et aperçus** : la session s’applique au volet focalisé et accompagne les aperçus mobile et tablette, les onglets dupliqués, rouverts et restaurés.
- **Couleurs dynamiques par zone** : réglez séparément la barre d’outils, la barre latérale, les menus internes et le fond dans les paramètres d’apparence.

## Améliorations et corrections

- Protection des brouillons lors des changements de session, y compris dans les pages intégrées et les aperçus.
- Changement de session bloqué pendant un téléchargement actif ou tant qu’une fenêtre liée est ouverte.
- Meilleure gestion des onglets, de l’écran partagé et du cycle de vie des vues WebKit.
- Gestion plus robuste des téléchargements et affichage d’une erreur récupérable lorsqu’un processus de page s’arrête.
- Correction de la lecture des couleurs hexadécimales et de la transparence.
- Couleurs plus stables pendant le défilement ; résultats d’anciennes pages ignorés.
- Conservation du suivi des couleurs après l’ouverture et la fermeture de fenêtres liées.
- Suggestions et stockage des mots de passe séparés par session.

## Vérification

85 tests automatisés réussis et compilation Release validée avant la préparation de cette version.

## À savoir

- Changer de session recharge la page. Une confirmation peut être demandée pour protéger un contenu potentiellement modifié.
- Historique et favoris restent communs aux sessions. Les imports CSV de mots de passe vont dans « Par défaut ».
- La suppression des sessions et l’intégration ChatGPT ne font pas partie de cette version.
- Les connexions aux fournisseurs réels et le contrôle visuel complet restent à valider en usage réel.
