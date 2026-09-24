<p align="center"><img src="icon.png" width="96" alt="Icône de Gonia"></p>

<h1 align="center">Gonia</h1>

<p align="center">Un îlot dynamique pour Windows : une pilule en haut de l'écran qui affiche la musique en cours, un minuteur, l'état du micro et vos notifications.</p>

## Télécharger

**[⬇ Télécharger la dernière version](https://github.com/ferdinandcharly/gonia-releases/releases/latest)**. Dans la section **Assets**, prenez `Gonia-Setup-x.y.z.exe` : un seul installeur pour les PC Intel/AMD (x64) et ARM64.

Windows 10 ou 11. L'installation se fait pour votre compte, sans droits administrateur.

### « Windows a protégé votre ordinateur »

Gonia n'est pas signé numériquement (un certificat de signature est payant), donc Windows SmartScreen affiche un avertissement à l'installation. Cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

## Ce que fait Gonia

- **Musique** : titre, artiste et pochette de ce qui joue, avec lecture/pause, suivant et précédent. Fonctionne avec toutes les applis qui s'affichent dans le panneau média de Windows : Spotify, Deezer, Apple Music, YouTube ou n'importe quel site dans le navigateur. Aucun compte à connecter.
- **Minuteur** avec anneau de progression, directement dans la pilule.
- **Micro** : couper ou rétablir le micro en réunion, avec un rappel visible quand il est coupé, où que la coupure ait été faite.
- **Notifications Windows** des applis de votre choix, affichées brièvement dans la pilule.
- **Clipboard IA** (facultatif) : historique du presse-papiers avec `Ctrl+Shift+V`, et actions IA (corriger, traduire, expliquer…).
- Se cache tout seul en plein écran, peut se ranger en onglet sur le bord droit, thèmes et couleurs personnalisables.

## Mises à jour

Gonia se met à jour tout seul : il télécharge les nouvelles versions en arrière-plan et les installe à la fermeture. Le menu de l'icône Gonia, dans la zone de notification, indique quand une mise à jour est prête.

## Vos données

- La musique, le micro et les notifications sont lus localement par Windows : rien n'est envoyé sur Internet.
- La météo de l'accueil utilise Open-Meteo, avec une position approximative déduite de votre adresse IP (ip-api.com) si vous n'indiquez pas de ville.
- L'historique de Clipboard IA reste sur votre PC. Seules les actions IA que vous lancez envoient le texte choisi au service Groq, avec votre propre clé API.

## Désinstaller

**Paramètres Windows → Applications → Applications installées → Gonia → Désinstaller.**
