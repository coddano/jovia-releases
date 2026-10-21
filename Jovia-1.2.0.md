# Jovia 1.2.0 — Extensions Chrome sur WebKit

## Installer depuis le Chrome Web Store

Ouvrez la fiche d’une extension, puis le bouton puzzle de Jovia et « Installer cette extension… ». Le gestionnaire permet aussi de coller le lien officiel d’une fiche. Jovia télécharge le paquet, vérifie sa signature et son identité, puis affiche ses autorisations avant toute activation.

Le gestionnaire est accessible depuis le bouton puzzle, le menu Extensions (⌥⌘E) et les réglages.

## Gérer ses extensions

- Activation et données séparées pour chaque session ; aucun accès aux onglets privés.
- Boutons d’action, popups et pages d’options pour les extensions compatibles.
- Consultation et révocation des autorisations ; une page déjà modifiée peut nécessiter un rechargement.
- Recherche manuelle des mises à jour, vérification du nouveau paquet et confirmation des accès.
- Conservation de la version précédente si une installation ou mise à jour échoue avant validation.
- Désactivation et suppression, avec nettoyage du stockage persistant de l’extension.

## Compatibilité vérifiée

Recette réelle avec Dark Reader 4.9.133, JSON Formatter 0.10.2 et JSONVue 0.2.3 : modification d’une page synthétique, popup ou options, lecture/écriture du stockage, désactivation et suppression. La séparation entre sessions et la persistance après recréation du contrôleur ont une recette dédiée.

Les extensions nécessitent macOS 15.4 ou ultérieur. Jovia conserve WebKit : toutes les API de Chrome ne sont pas disponibles. La communication avec des applications externes (`nativeMessaging`) est refusée. Ces trois recettes ne constituent pas une garantie pour toutes les extensions du Store.

Cette version conserve le nouveau design Mac, les sessions et les corrections précédentes. Elle n’ajoute pas l’intégration de ChatGPT.
