# HoroCMS — Guide d’installation

*Bêta 0.2.2*

Comment installer HoroCMS sur un Mac ou un PC Windows et l’application compagnon sur un téléphone, le configurer, le mettre à jour, le transférer vers un autre ordinateur et le désinstaller.

## Configuration requise

- macOS 13 Ventura ou plus récent (Apple silicon ou Intel), ou Windows 10 ou 11 (64 bits).
- Application compagnon (facultative) : Android 8 ou plus récent (64 bits), sur le même réseau Wi-Fi que l’ordinateur. L’application pour iPhone (iOS 15 ou plus récent) n’est pas encore offerte au public.
- Environ 100 Mo d’espace disque pour l’application, plus la place pour vos photos et documents.
- Aucune connexion Internet n’est nécessaire. HoroCMS ne va en ligne que pour la vérification des mises à jour (www.leger.ca et GitHub, désactivable), les taux de change officiels (Banque du Canada, si vous les activez) et l’assistant en ligne (Anthropic, si vous l’activez).

## Obtenir l’installateur

HoroCMS est gratuit. Téléchargez-le depuis la page publique de téléchargement :

https://github.com/ITriskMgr/HoroCMS-updates/releases/latest

Sous Assets, choisissez le fichier de votre système : HoroCMS-Mac.dmg pour un Mac (Apple silicon ou Intel), HoroCMS-Windows-Setup.exe pour Windows (ou le .msi) et HoroCMS-Android.apk pour un téléphone Android. Aucun compte n’est nécessaire. La même page offre ces guides en PDF.

## Installer sur un Mac

1. Téléchargez HoroCMS-Mac.dmg depuis la page de téléchargement (voir Obtenir l’installateur) et ouvrez-le.
2. Glissez HoroCMS dans Applications, puis ouvrez-le depuis Applications.
3. La bêta n’est pas encore signée par Apple; macOS la bloque donc la première fois. Sur macOS 15 Sequoia ou plus récent : choisissez Terminé, ouvrez Réglages Système › Confidentialité et sécurité, descendez jusqu’à « HoroCMS a été bloqué », choisissez Ouvrir quand même, confirmez avec votre mot de passe, puis Ouvrir. Sur macOS 13 ou 14 : cliquez avec le bouton droit sur HoroCMS dans Applications, choisissez Ouvrir, puis Ouvrir de nouveau.

Si macOS indique que HoroCMS est endommagé, ouvrez Terminal et exécutez xattr -dr com.apple.quarantine /Applications/HoroCMS.app, puis ouvrez-le de nouveau. macOS ne le demande qu’une fois.

Pour mettre à jour, installez la nouvelle version de la même façon; votre coffre et vos réglages sont conservés. HoroCMS fonctionne sur macOS 13 Ventura ou plus récent (Apple silicon et Intel).

## Installer sur Windows

1. Téléchargez HoroCMS-Windows-Setup.exe depuis la page de téléchargement (voir Obtenir l’installateur) et lancez-le. Le .msi fait de même pour les ordinateurs gérés.
2. Si Windows SmartScreen indique avoir protégé votre PC, choisissez Informations complémentaires, puis Exécuter quand même. La bêta n’est pas encore signée; Windows avertit donc une fois.
3. Suivez l’installateur; HoroCMS apparaît dans le menu Démarrer.

HoroCMS exige Windows 10 ou 11 avec Microsoft Edge WebView2 (déjà présent sur les versions actuelles; l’installateur l’ajoute au besoin). Le coffre est conservé dans vos données d’application locales, qui ne sont pas synchronisées par OneDrive.

## Créer votre coffre

HoroCMS conserve votre collection dans un coffre chiffré sur cet ordinateur. Rien n’est envoyé ailleurs.

1. Choisissez la langue et le format des nombres et des dates.
2. Choisissez une phrase de passe d’au moins 12 caractères. Quatre ou cinq mots inhabituels sont faciles à retenir et difficiles à deviner.
3. Imprimez ou recopiez votre clé de récupération, puis retapez son troisième groupe pour confirmer que vous l’avez.

Rangez la clé de récupération loin de l’ordinateur : avec les papiers de vos montres, dans un coffre-fort ou chez votre notaire. C’est le seul moyen d’ouvrir le coffre si vous oubliez la phrase de passe.

## Installer l’application compagnon sur Android

1. Sur le téléphone, ouvrez la page de téléchargement dans le navigateur (voir Obtenir l’installateur) et téléchargez HoroCMS-Android.apk. Ou téléchargez-le sur l’ordinateur et copiez-le sur le téléphone (câble, Google Drive ou courriel à vous-même).
2. Ouvrez le .apk téléchargé depuis la notification ou l’application Fichiers.
3. Android demande une fois d’autoriser l’installation d’applications de cette source : autorisez-la, puis choisissez Installer. Vous pouvez retirer cette autorisation ensuite.
4. Ouvrez HoroCMS sur le téléphone, choisissez une phrase de passe pour le téléphone, puis jumelez-le (voir Votre collection sur votre téléphone).

Il faut Android 8 ou plus récent sur un téléphone 64 bits. Si la nouvelle version refuse de s’installer par-dessus l’ancienne (bêta signée avec une autre clé), désinstallez d’abord l’ancienne et jumelez de nouveau; rien n’est perdu, la collection revient de votre ordinateur.

## Installer l’application compagnon sur iPhone

L’application compagnon pour iPhone n’est pas encore offerte au public : elle viendra par TestFlight d’Apple. Utilisez Soutien dans HoroCMS pour demander à être avisé lorsqu’elle sera prête.

Apple n’accepte une application sur un iPhone que si elle est signée par un compte de développeur Apple. D’ici là, les testeurs l’installent de l’une de deux façons :

- TestFlight (recommandé) : avec l’Apple Developer Program (99 $ US par an). L’auteur compile l’application avec votre identifiant d’équipe (Team ID) et l’envoie à TestFlight; vous installez l’application gratuite TestFlight depuis l’App Store, acceptez l’invitation, puis installez HoroCMS. Les mises à jour arrivent de la même façon.
- Xcode, sans compte payant : sur un Mac avec Xcode et un identifiant Apple gratuit, l’application s’installe par câble. Elle cesse de s’ouvrir après 7 jours et doit être réinstallée.

1. Une fois installée, ouvrez HoroCMS sur l’iPhone et autorisez l’appareil photo (pour lire le code QR de jumelage) et le réseau local (pour joindre votre ordinateur) quand ils sont demandés.
2. Choisissez une phrase de passe pour le téléphone, puis jumelez-le (voir Votre collection sur votre téléphone).

Il faut iOS 15 ou plus récent. Les étapes techniques pour l’auteur se trouvent dans docs/MOBILE.md.

## Votre collection sur votre téléphone

L’application compagnon HoroCMS pour iPhone et Android affiche votre collection et ses photos, vous permet de mettre une montre au poignet et de la retirer, et tient votre liste de souhaits. Ce que vous changez sur le téléphone revient sur votre ordinateur.

Sur l’ordinateur, ouvrez Paramètres › Application compagnon pour téléphone, choisissez Activer l’application compagnon, puis Jumeler un téléphone (votre phrase de passe est demandée). Sur le téléphone, choisissez une phrase de passe pour le téléphone, puis Scanner le code, ou saisissez l’adresse et le code affichés sur l’ordinateur. Les deux doivent être sur le même réseau Wi-Fi.

Le téléphone garde sa propre copie chiffrée de la collection et se verrouille quand vous quittez l’application. Il ne parle qu’à votre ordinateur, sur votre réseau domestique, et seulement quand HoroCMS y est déverrouillé; rien ne passe par Internet. Si vos ordinateurs se synchronisent par un dossier infonuagique, le téléphone reçoit aussi ce que les autres ordinateurs envoient.

La première fois, macOS ou Windows peut demander si HoroCMS peut accepter des connexions entrantes : autorisez-le sur les réseaux privés seulement. Désactivez l’application compagnon au même endroit quand vous n’en avez pas besoin. Si vous oubliez la phrase de passe du téléphone, effacez ses données depuis son écran de déverrouillage et jumelez-le de nouveau.

## Mettre HoroCMS à jour

Au démarrage, HoroCMS demande à www.leger.ca et à GitHub si une version plus récente existe (seul le numéro de version de l’application est transmis). Si c’est le cas, un bandeau vous la propose; Paramètres › Mises à jour › Vérifier maintenant fait la même chose en tout temps. Désactivez-y la vérification au démarrage pour garder HoroCMS entièrement hors ligne.

1. Faites une sauvegarde (Paramètres › Sauvegardes). HoroCMS vous le rappelle si la dernière date de plus d’une journée.
2. Cliquez sur Installer et redémarrer. HoroCMS se verrouille, télécharge la mise à jour, vérifie qu’elle est signée par son auteur (tout le reste est refusé), l’installe et redémarre.
3. Déverrouillez comme d’habitude. Votre collection est reprise automatiquement : HoroCMS en garde une copie, la met à jour, vérifie chaque fiche et remet la copie en place en cas de problème.

Votre coffre, vos préférences et vos sauvegardes automatiques restent où ils sont; une mise à jour ne les supprime jamais. Les photos et documents ne sont pas touchés.

Vous pouvez aussi installer une nouvelle version à la main, comme la première fois (voir Installer sur un Mac, ou Installer sur Windows) : la même mise à jour sécuritaire se fait au déverrouillage suivant.

Si HoroCMS indique qu’il n’a pas pu mettre le coffre à jour, rien n’a été modifié : réinstallez la version précédente pour continuer et communiquez avec l’auteur. Un coffre utilisé par une version plus récente ne peut pas être ouvert par une version plus ancienne; mettez plutôt l’application à jour.

## Restaurer une sauvegarde ou changer d’ordinateur

Sur un nouvel ordinateur, choisissez Restaurer une sauvegarde… au premier écran; sur celui-ci, passez par l’écran de déverrouillage ou les Paramètres.

1. Choisissez le fichier de sauvegarde (.horobak).
2. Tapez sa phrase de passe.
3. Choisissez la phrase de passe du coffre restauré.

Tout est vérifié avant de toucher au coffre actuel, qui est mis de côté. Vous recevez une nouvelle clé de récupération à imprimer.

## Sauvegardes

HoroCMS fait automatiquement une sauvegarde chiffrée après le déverrouillage, au plus une fois par jour, dans le dossier de données de HoroCMS (ou un dossier de votre choix; Paramètres › Sauvegardes › Afficher dans le Finder ou l’Explorateur l’ouvre). Il garde les 10 plus récentes. Chaque sauvegarde automatique s’ouvre avec la phrase de passe utilisée ce jour-là.

Pour en faire une vous-même, allez dans Paramètres › Sauvegardes, choisissez une phrase de passe pour elle et Enregistrer une sauvegarde…, puis un endroit comme une clé USB. Gardez au moins une copie loin de l’ordinateur.

## En cas de problème

HoroCMS vérifie tout ce qu’il lit : un dommage est donc détecté plutôt qu’affiché comme une donnée erronée. Deux genres de problèmes peuvent survenir après une défaillance de disque ou un plantage.

La collection ne s’ouvre pas, même si la phrase de passe est la bonne. HoroCMS propose alors deux façons de s’en sortir :

- Revenir à une copie automatique : HoroCMS en garde une avant chaque mise à jour. Les changements faits depuis sont perdus; les photos et documents ne sont pas touchés. Le fichier endommagé est mis de côté.
- Restaurer une sauvegarde : choisissez la plus récente (voir Restaurer une sauvegarde).

Des photos ou des documents sont manquants ou endommagés. Paramètres › Santé du coffre › Vérifier le coffre les repère. Choisissez une sauvegarde faite quand ils étaient intacts et tapez sa phrase de passe : HoroCMS recopie seulement ces fichiers, après avoir vérifié chacun. Les fichiers absents de toute sauvegarde peuvent ensuite être retirés de la fiche; la montre elle-même n’est pas touchée.

Gardez des sauvegardes sur une clé USB ou un autre disque, pas seulement sur cet ordinateur : ce sont elles qui permettent de se remettre de tout problème.

## Où sont vos données

- Mac : ~/Library/Application Support/ca.leger.horocms/vault (chiffré).
- Windows : %LOCALAPPDATA%\ca.leger.horocms\vault (chiffré; non synchronisé par OneDrive).
- Sauvegardes automatiques : le dossier Backups à côté du coffre (avant la version 0.2.1 : Documents/HoroCMS Backups), sauf si vous avez choisi un autre dossier.
- Préférences (langue, thème, devise d’affichage) : un petit fichier dans le dossier des réglages du système; il ne contient rien sur votre collection.

## Désinstaller HoroCMS

Faites d’abord une sauvegarde (Paramètres › Sauvegardes). Sur Mac, glissez HoroCMS des Applications vers la Corbeille; sur Windows, passez par Paramètres › Applications › HoroCMS › Désinstaller. Le coffre chiffré reste en place pour qu’une réinstallation retrouve votre collection; supprimez le dossier indiqué ci-dessus si vous voulez l’effacer.

---

© 2026 Marc-André Léger. Tous droits réservés. Conçu avec Claude (Anthropic).
