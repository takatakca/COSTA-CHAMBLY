# Inventaire et validation des médias — COSTA-CHAMBLY — 2026-11-17

## Résultat des contrôles techniques
- **59 photographies JPEG** : retrouvées et téléchargées depuis le dossier Google Drive privé, numérotation `PHOTO-COSTA-001.jpg` à `PHOTO-COSTA-059.jpg` sans lacune.
- **59/59 photographies identiques octet pour octet entre Drive et GitHub** : chaque copie locale Drive a été calculée sous forme d'objet Git SHA-1 (`blob <taille>\0<octets>`), et les 59 identifiants obtenus concordent avec les SHA des blobs GitHub dans `medias/photos/`.
- **59/59 JPEG** : ouverture et décodage validés avec Pillow, aucun fichier corrompu décelé.
- **8/8 archives vidéo ZIP** : fichiers complets téléchargés depuis Drive, test CRC ZIP réussi sur tous les membres.
- **17 vidéos MP4 distinctes** : 16 directement incluses dans les archives; la 17e (`1000130161.mp4`) a été reconstituée par concaténation, dans l'ordre, des trois pièces `.part01`, `.part02`, `.part03`.
- **17/17 MP4** : métadonnées de format et durée reconnues par `ffprobe`.
- Un essai de décodage intégral `ffmpeg` n'a pas abouti dans la limite d'exécution : aucun résultat de validation complète image par image n'est revendiqué.
- Des empreintes SHA-256 ont été calculées sur les **59 JPEG téléchargés, 17 MP4 reconstitués et 8 archives ZIP**. Le registre détaillé `REGISTRE_SHA256.csv` a été produit en copie locale dans l'espace de travail; il n'est pas publié ici.

## Origine et rangement
- Sources : dossier Drive privé « 04 — COSTA CHAMBLY — R2NETTE — DOSSIER SINISTRE ».
- Photos déjà présentes dans ce dépôt public : `medias/photos/`.
- Lots d'archives : `COSTA_VIDEOS_LOT_01_SUR_08.zip` à `COSTA_VIDEOS_LOT_08_SUR_08.zip`; tailles respectives 43884443, 43300851, 42681647, 43330326, 42900142, 42698816, 42360115 et 42405773 octets.
- Le contrôle actuel porte sur la présence, la cohérence binaire des copies et l'ouverture des fichiers; il **ne certifie pas** l'authenticité des scènes filmées, les dates de prise de vue, la provenance initiale des appareils ou une chaîne de possession historique.

## Préservation et divulgation
- Aucune transformation des originaux stockés sur Google Drive.
- Les médias téléchargés ne doivent pas être publiés dans ce dépôt public sans examen des renseignements personnels et des autorisations.
- Aucun nouveau média binaire transféré vers GitHub dans cette opération.
- **Aucun document envoyé à l'assureur.**

Validation technique réalisée le 17 novembre 2026.
