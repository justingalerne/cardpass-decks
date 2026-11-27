# CardPass — Politique de confidentialité / Privacy Policy

*Dernière mise à jour : 27 novembre 2026 (version 3.0.0)*

## Français

CardPass ne collecte, ne vend et ne partage **aucune donnée personnelle**. Tant
que vous ne connectez pas d'assistant IA (option ci-dessous), rien ne quitte
votre appareil. Pas de compte, pas d'analytique, pas de publicité.

- **Connecteur d'assistant IA (facultatif, désactivé par défaut).** Si vous
  connectez un assistant ou agent IA compatible MCP (en scannant le code qu'il
  affiche), CardPass utilise Internet pour échanger vos cartes avec le relais
  CardPass (`cardpass-justin.duckdns.org`, code source public :
  https://github.com/justingalerne/cardpass-relay) :
  - les cartes que l'assistant ajoute ou modifie, et une copie des cartes que
    vous avez créées dans CardPass (pour qu'il puisse les retrouver), sont
    **chiffrées** (AES-256-GCM) avec une clé générée sur votre téléphone ;
  - le relais ne conserve que ces données chiffrées et des empreintes ; il ne
    stocke ni la clé ni le texte des cartes. Le texte n'existe en clair, en
    mémoire, que pendant le traitement d'une demande de l'assistant ;
  - le relais voit des métadonnées techniques (identifiant aléatoire de
    l'appareil, tailles, horaires) ;
  - l'assistant que vous connectez, et son fournisseur, voient les cartes qu'il
    écrit ou lit, selon ses propres conditions ;
  - les decks importés d'Anki ne sont jamais envoyés ;
  - vous pouvez déconnecter un assistant à tout moment dans Réglages.
  Si une carte reçue contient un lien d'image (https), le téléphone télécharge
  cette image.
- **Sans connecteur**, l'application ne se connecte à rien. Le bouton
  « Parcourir les decks AnkiWeb » ouvre simplement votre navigateur.
- **Statistiques d'usage** (`PACKAGE_USAGE_STATS`) : utilisées uniquement pour
  savoir quelle application est au premier plan, en mémoire, à l'instant T.
  L'historique d'utilisation des autres applications n'est ni enregistré ni
  transmis.
- **Données stockées localement** :
  - vos réglages (apps surveillées, deck choisi, nombre de cartes, durée
    d'accès) ;
  - les decks que vous importez (fichiers `.apkg` ou tableaux CSV) et les
    cartes que vous créez, y compris leurs images et sons ;
  - votre progression : historique de vos réponses et date de chaque
    déblocage (application débloquée, nombre de cartes), pour le tableau de
    bord.

  Ces données restent sur l'appareil, sont exclues des sauvegardes système et
  sont supprimées avec l'application.
- **Fichiers que vous ouvrez** : CardPass lit uniquement les fichiers que vous
  choisissez d'importer (decks, tableaux, images).
- **Aucun tiers** : pas d'analytique, pas de publicité, pas de SDK de suivi.

### Supprimer vos données (CardPass)

- **Données sur le relais** (si vous avez connecté un assistant) : dans
  CardPass → Réglages → Assistant IA, touchez **« Supprimer mes données du
  relais »**. Le relais efface immédiatement et définitivement tout ce qu'il
  garde pour votre téléphone : assistants connectés, cartes en attente et copie
  chiffrée de vos cartes. Rien n'est conservé ensuite. « Déconnecter » un
  assistant lui retire seulement l'accès.
- **Données sur le téléphone** : supprimez des cartes ou des decks dans
  l'application, ou désinstallez-la pour tout effacer.
- Pour toute question : justin.galerne@hotmail.fr.

CardPass n'est pas affiliée à Anki ni à AnkiDroid. « Anki » est une marque de
son ayant droit ; CardPass sait seulement lire le format de fichier `.apkg`.

Contact : justin.galerne@hotmail.fr

## English

CardPass does not collect, sell, or share **any personal data**. Unless you
connect an AI assistant (optional, below), nothing leaves your device. No
account, no analytics, no ads.

- **AI assistant connector (optional, off by default).** If you connect an
  MCP-compatible AI assistant or agent (by scanning the code it shows),
  CardPass uses the Internet to exchange your cards with the CardPass relay
  (`cardpass-justin.duckdns.org`, public source code:
  https://github.com/justingalerne/cardpass-relay):
  - cards the assistant adds or edits, and a copy of the cards you created in
    CardPass (so it can find them), are **encrypted** (AES-256-GCM) with a key
    generated on your phone;
  - the relay keeps only this encrypted data and fingerprints; it stores
    neither the key nor the card text. Text exists in plain form only in
    memory, while an assistant request is being handled;
  - the relay sees technical metadata (random device id, sizes, timestamps);
  - the assistant you connect, and its provider, see the cards it writes or
    reads, under their own terms;
  - decks imported from Anki are never sent;
  - you can disconnect an assistant at any time in Settings.
  If a received card contains an image link (https), the phone downloads that
  image.
- **Without the connector**, the app connects to nothing. The "Browse AnkiWeb
  decks" button simply opens your browser.
- **Usage access** (`PACKAGE_USAGE_STATS`): used solely to determine which app
  is currently in the foreground, in memory, at that moment. Your usage history
  of other apps is neither recorded nor transmitted.
- **Locally stored data**:
  - your settings (watched apps, chosen deck, card count, unlock duration);
  - the decks you import (`.apkg` files or CSV spreadsheets) and the cards you
    create, including their images and sounds;
  - your progress: history of your answers and the time of each unlock
    (unlocked app, number of cards), for the dashboard.

  This data stays on the device, is excluded from system backups, and is
  deleted with the app.
- **Files you open**: CardPass only reads the files you choose to import
  (decks, spreadsheets, images).
- **No third parties**: no analytics, no ads, no tracking SDKs.

### Delete your data (CardPass)

- **Data on the relay** (if you connected an assistant): in CardPass →
  Settings → AI assistant, tap **"Delete my data from the relay"**. The relay
  immediately and permanently erases everything it keeps for your phone:
  connected assistants, pending cards and the encrypted copy of your cards.
  Nothing is kept afterwards. "Disconnect" only removes an assistant's access.
- **Data on the phone**: delete cards or decks in the app, or uninstall it to
  erase everything.
- Any question: justin.galerne@hotmail.fr.

CardPass is not affiliated with Anki or AnkiDroid. "Anki" is a trademark of its
respective owner; CardPass only reads the `.apkg` file format.

Contact: justin.galerne@hotmail.fr
