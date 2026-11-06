# Politique de confidentialité

_Dernière mise à jour : 6 novembre 2026. [English version below.](#privacy-policy-english)_

LaTeX Studio Ultimate est un éditeur LaTeX pour Android, édité par un particulier (compte développeur
SIMONOCORP). Il fonctionne sans compte. L'application ne contient ni publicité, ni mesure d'audience, ni outil
de suivi, et l'éditeur n'exploite aucun serveur qui recevrait vos documents.

## Ce qui reste sur l'appareil

Vos projets (fichiers .tex, .bib, images, PDF produits), l'historique des versions, les dépôts Git, vos signatures
et vos réglages. Les pages scannées et la reconnaissance de texte sont traitées sur l'appareil. Les jetons et mots de
passe que vous saisissez (service de compilation, WebDAV, S3, Git) sont chiffrés avec une clé du Keystore Android
qui ne quitte pas l'appareil, et sont exclus des sauvegardes.

## Ce qui quitte l'appareil, et seulement quand vous utilisez la fonction

| Fonction | Données envoyées | Destinataire |
|---|---|---|
| Compiler sur l'appareil | rien de votre projet : les fichiers de la distribution TeX sont téléchargés, ce qui révèle à ce serveur votre adresse IP et les noms des fichiers TeX demandés | serveurs de Tectonic (`*.fullyjustified.net`) |
| Compiler ou convertir avec un service | les fichiers du projet ou le document | le service dont **vous** avez saisi l'adresse |
| Synchronisation WebDAV, S3 ou dossier | les projets synchronisés | le serveur ou le dossier que **vous** avez choisi |
| Git, dépôt distant | le contenu du dépôt | l'hôte HTTPS que **vous** avez saisi |
| Compte, co-édition et assistant, si vous reliez l'appli à un serveur | adresse e-mail, projets, commentaires, modifications, curseur ; texte choisi et consigne pour l'assistant, après votre consentement | le serveur dont **vous** avez saisi l'adresse |
| Import par DOI ou ISBN | l'identifiant saisi | Crossref ou Open Library |
| Partager, imprimer | le document choisi | l'application que vous choisissez |

Ces services sont choisis par vous : leur propre politique s'applique aux données qu'ils reçoivent. Les connexions
utilisent HTTPS ; la version publiée refuse les adresses `http://`.

## Permissions

Appareil photo, seulement pour le scanner et seulement si vous l'autorisez. Internet, pour les fonctions ci-dessus.
Les fichiers passent par le sélecteur d'Android : l'appli n'accède qu'à ceux que vous choisissez.

## Vos droits

Désinstaller l'application efface ses données locales. Vous pouvez aussi supprimer un projet depuis l'appli, puis vider
la corbeille. Si vous l'avez reliée à un serveur de compte, l'écran Compte permet d'exporter et de supprimer ces
données ; l'éditeur n'y a pas accès.

L'application ne s'adresse pas spécialement aux enfants de moins de 13 ans.

## Supprimer votre compte et vos données {#suppression}

**LaTeX Studio Ultimate** n'a pas de compte chez son éditeur : vous n'en avez un que si vous reliez l'appli à un serveur de
votre choix. Pour le supprimer :

1. Ouvrez LaTeX Studio Ultimate, puis l'onglet **Compte**.
2. Touchez **Supprimer le compte**, puis confirmez.

Le serveur efface alors votre compte, votre adresse e-mail, vos projets et vos commentaires. Ce serveur appartenant à vous ou
à la personne qui vous l'a fourni, c'est sa propre politique qui fixe les éventuelles durées de conservation ; l'éditeur
de l'appli n'y a pas accès et ne conserve rien.

Les données restées sur l'appareil s'effacent en supprimant un projet puis en vidant la corbeille, ou en désinstallant
l'appli. Une question : voir **Contact** ci-dessous.

## Contact

<serge.simono27@gmail.com>

---

# Privacy policy (English)

_Last updated: 6 November 2026._

LaTeX Studio Ultimate is a LaTeX editor for Android, published by an individual (developer account SIMONOCORP). It
works with no account. It has no ads, no analytics and no trackers, and the publisher runs no server that would
receive your documents.

**Stays on the device:** your projects, version history, Git repositories, signatures and settings. Scanned pages and
text recognition are processed on the device. Tokens and passwords you enter are encrypted with an Android Keystore key
that never leaves the device, and are excluded from backups.

**Leaves the device only when you use the feature:** on-device compiling downloads TeX distribution files from Tectonic's
servers (`*.fullyjustified.net`), which see your IP address and the names of the TeX files requested, and nothing from your
project; compiling or converting with a service sends the project files or document to the service whose address **you**
entered; WebDAV, S3 or folder sync sends synced projects to the server or folder **you** chose; Git sends the repository to
the HTTPS host **you** entered; if you connect the app to an account server of your choice, it receives your e-mail, projects,
comments, edits and caret, and for the assistant, after your consent, the selected text and your instruction; DOI or ISBN
import sends the identifier to Crossref or Open Library; sharing or printing sends the chosen document to the app you choose.

**Permissions:** camera, only for the scanner and only if you allow it; internet, for the features above. Files go through
Android's picker: the app only reaches those you choose.

**Your rights:** uninstalling removes local data. You can also delete a project in the app, then empty the trash. If you
connected an account server, the Account screen exports and deletes that data; the publisher has no access to it.

**Delete your account and data:** the publisher holds no account for you; you only have one if you connect the app to a server
of your choice. Open LaTeX Studio Ultimate, go to the **Account** tab, tap **Delete account** and confirm. That server then erases your
account, e-mail, projects and comments; its own policy sets any retention period, and the publisher has no access to it and keeps
nothing. Data on the device goes when you delete a project and empty the trash, or uninstall the app.

**Contact:** <serge.simono27@gmail.com>
