# COSTA-CHAMBLY — HISTORIQUE INTÉGRAL ACCESSIBLE DU CHAT ET INVENTAIRE MÉDIAS
**Mise à jour : 17 novembre 2026.** Documentation des échanges accessibles dans ce fil et des extraits de conversations antérieures visibles dans le projet. Ni transcription des conversations non accessibles, ni certification judiciaire.

> **Confidentialité : ce dépôt GitHub est PUBLIC.** Les originaux des vidéos et les fichiers privés restent sur Google Drive. Aucune pièce transmise à l'assureur dans cette opération.

## 1. Dossier, sources et accès
- Dossier : COSTA-CHAMBLY, sinistre R2NETTE / Rapide 2 Nette. La société « 9394-2621 QC INC » a été désignée par l'utilisateur dans une conversation précédente.
- GitHub : https://github.com/takatakca/COSTA-CHAMBLY ; branche main ; dépôt public.
- Photos GitHub : https://github.com/takatakca/COSTA-CHAMBLY/tree/main/medias/photos
- Dossier Google Drive : https://drive.google.com/drive/folders/1mQv057tYIylKi0YtY4dQ4wQHH8W77Mdc (04 — COSTA CHAMBLY — R2NETTE — DOSSIER SINISTRE).
- Documents GitHub liés : README.md, WORKLOG.md, dossier/INDEX.md, dossier/CHRONOLOGIE.md, dossier/OCR_ET_ARCHIVAGE.md, dossier/RAPPROCHEMENT_FINANCIER.md, dossier/DEPOT_DRIVE_2026-11-10.md.

## 2. Demandes successives de l'utilisateur dans le chat accessible
1. « telecharger tous les video et photo ajouter aussi a github Je vais récupérer les **59 photos et 17 vidéos** du dossier Costa, vérifier les fichiers et leurs empreintes, puis les ajouter au dépôt GitHub **COSTA-CHAMBLY**. Je vais conserver les originaux et mettre à jour le registre des preuves. Aucun document ne sera envoyé à l’assureur. »
2. « valide le tous »
3. Citation du bilan initial : « les 59 photos sont déjà sur GitHub, les huit archives vidéo sont retrouvées dans Drive, et le nouveau registre documente leur emplacement ainsi que les vérifications restant à effectuer. Le téléchargement des fichiers vidéo originaux, la confirmation des 17 vidéos et le calcul des empreintes SHA-256 restent à réaliser. Aucun nouveau fichier média binaire n'a été transféré pendant cette opération. Aucun document n'a été envoyé à l'assureur. »
4. « ou sont les video et photo je veut telechGREWR LE TOUS< »
5. « METTRE TOUS LINF0MARTION AU COMPLET DU CHAT COMPLET SANS OUBLIER RIEN » et lien explicite vers ce registre GitHub.

## 3. Historique des résultats communiqués dans le chat
### Première recherche et archivage
- Google Drive : dossier et documents retrouvés, 59 fichiers photo numérotés de 001 à 059, huit lots ZIP vidéo et fichiers annexes.
- GitHub : 59/59 photos déjà présentes dans medias/photos. Aucun nouveau fichier binaire nécessaire à ce stade.
- Les photos n'étaient d'abord validées que par présence; vidéos et empreintes restaient à vérifier.
- Création du présent registre : commit 6006fdfc333752245592af254f8706797538d45a.
### Validation approfondie
- Deuxième comparaison des listings : mêmes 59 noms, mêmes 59 tailles en octets entre Drive et GitHub, aucun nom manquant.
- Téléchargement annoncé comme réussi pour les 59 JPEG et les huit ZIP vidéo; contrôle de l'ouverture des 59 JPEG avec Pillow.
- Correspondance des 59 blobs Git SHA-1 calculés sur les fichiers Drive avec les 59 blobs GitHub : identité des copies octet pour octet, selon le contrôle consigné.
- ZIP : test CRC réussi sur les huit archives, aucune erreur rapportée.
- Extraction vidéo : 16 MP4 entiers et un MP4 supplémentaire nommé 1000130161.mp4, reconstitué par concaténation de .part01, .part02 et .part03, soit 17 vidéos distinctes.
- 17/17 vidéos reconnues par ffprobe avec métadonnées de format et durée. Le décodage intégral image par image avec ffmpeg n'a PAS été achevé; ne pas présenter cela comme certifié.
- SHA-256 annoncés calculés sur 59 photos, 17 MP4 et huit ZIP : 84 fichiers. Registre local COSTA_VALIDATION/REGISTRE_SHA256.csv; ses 84 valeurs ne sont pas publiées ici.
- Mise à jour GitHub de validation : commit 51b506e093cd6f5afa1b264c159b18f770833e8a.
### Demande de télécharger tous les médias
- L'assistant a proposé COSTA_PHOTOS_59_VALIDEES.zip (~25 Mo), COSTA_VIDEOS_17_VALIDEES.zip (~328 Mo) et COSTA_VALIDATION/REGISTRE_SHA256.csv via des liens de session sandbox:/mnt/data/.
- Ces liens de session ne constituent PAS des liens permanents GitHub ou Drive. Ne pas en déduire que les archives ZIP finales sont hébergées sur GitHub.
- Les originaux vidéo demeurent dans Google Drive, et les 59 photos sont accessibles sur GitHub. Aucun des 17 MP4 n'a été ajouté au dépôt public dans ces opérations.
- Aucun fichier communiqué automatiquement à l'assureur.

## 4. Inventaire exhaustif des 59 JPEG sur GitHub
Les tailles ci-dessous ont été recoupées avec Drive. Le SHA est le SHA-1 d'objet blob GitHub, et non le SHA-256 du fichier.

| Photo | Octets GitHub | SHA-1 blob GitHub | Taille Drive |
|---|---:|---|---|
| [PHOTO-COSTA-001.jpg](../medias/photos/PHOTO-COSTA-001.jpg) | 444685 | d2cbb40ec2b9db900114ed01a308fa6d0275018f | Concordante |
| [PHOTO-COSTA-002.jpg](../medias/photos/PHOTO-COSTA-002.jpg) | 505146 | 9c676c4e4914855b7da066fe5b6f69526cc68895 | Concordante |
| [PHOTO-COSTA-003.jpg](../medias/photos/PHOTO-COSTA-003.jpg) | 422409 | c8bb58769f89dc46c6a941260c7efa5265892f47 | Concordante |
| [PHOTO-COSTA-004.jpg](../medias/photos/PHOTO-COSTA-004.jpg) | 360598 | 6ca039a8762c5fc14c7a48ee5967b2a7f9c35062 | Concordante |
| [PHOTO-COSTA-005.jpg](../medias/photos/PHOTO-COSTA-005.jpg) | 320305 | 50ec62c10b39db73fcc58418c96fe968769ed0eb | Concordante |
| [PHOTO-COSTA-006.jpg](../medias/photos/PHOTO-COSTA-006.jpg) | 194425 | 1be7ec5d4d2a89185db716089499cdf9cf1c8835 | Concordante |
| [PHOTO-COSTA-007.jpg](../medias/photos/PHOTO-COSTA-007.jpg) | 261891 | 44515de94f7c9622a20a0abb22b73108dd6ade70 | Concordante |
| [PHOTO-COSTA-008.jpg](../medias/photos/PHOTO-COSTA-008.jpg) | 175588 | 48ebcb193e09af3414a8e22cb7a1a0087045fda0 | Concordante |
| [PHOTO-COSTA-009.jpg](../medias/photos/PHOTO-COSTA-009.jpg) | 247237 | 000c835c42349b84a9c3eda29f1bb709defa1c57 | Concordante |
| [PHOTO-COSTA-010.jpg](../medias/photos/PHOTO-COSTA-010.jpg) | 481561 | 48662623a75630995a2feabf8086a67ea1827640 | Concordante |
| [PHOTO-COSTA-011.jpg](../medias/photos/PHOTO-COSTA-011.jpg) | 472811 | deb05f8a27bbba2b7f8849964bde847ca6ca1088 | Concordante |
| [PHOTO-COSTA-012.jpg](../medias/photos/PHOTO-COSTA-012.jpg) | 426140 | a5dff6035897d6a5627c4ae9c83d6c44c49ce489 | Concordante |
| [PHOTO-COSTA-013.jpg](../medias/photos/PHOTO-COSTA-013.jpg) | 427207 | 5ec1f7f4e69475cb0fa323b96d32116303bf850f | Concordante |
| [PHOTO-COSTA-014.jpg](../medias/photos/PHOTO-COSTA-014.jpg) | 445105 | 830fd9663e3c097ba22e2262f306fc27b7c296c6 | Concordante |
| [PHOTO-COSTA-015.jpg](../medias/photos/PHOTO-COSTA-015.jpg) | 490434 | 62795ccb3ce0ac9963ff733173c1779d60bb6bdb | Concordante |
| [PHOTO-COSTA-016.jpg](../medias/photos/PHOTO-COSTA-016.jpg) | 406752 | b7d73e8be9a48e0f5c8db0a0e2b2af1ff905e305 | Concordante |
| [PHOTO-COSTA-017.jpg](../medias/photos/PHOTO-COSTA-017.jpg) | 626328 | f7e255626c8eb96b5d83033429b3b9f0538eaf75 | Concordante |
| [PHOTO-COSTA-018.jpg](../medias/photos/PHOTO-COSTA-018.jpg) | 683476 | ffa916359a6135477a0d9c3eb2e277d0c5366d3b | Concordante |
| [PHOTO-COSTA-019.jpg](../medias/photos/PHOTO-COSTA-019.jpg) | 835982 | 20fe1db85b8519b4fa28e40b175ade3e087a6fbe | Concordante |
| [PHOTO-COSTA-020.jpg](../medias/photos/PHOTO-COSTA-020.jpg) | 537241 | a95b321c012748f959628227ee291c9db266d113 | Concordante |
| [PHOTO-COSTA-021.jpg](../medias/photos/PHOTO-COSTA-021.jpg) | 820791 | dca7e2fe0b65f26d1ce76708945c6d4412c88b10 | Concordante |
| [PHOTO-COSTA-022.jpg](../medias/photos/PHOTO-COSTA-022.jpg) | 351076 | bf473c1bf8a99330fc45bdfdd66ef907df45a9b5 | Concordante |
| [PHOTO-COSTA-023.jpg](../medias/photos/PHOTO-COSTA-023.jpg) | 318546 | 1e6a4a709111df18eee424c96cce1e4070b88b3e | Concordante |
| [PHOTO-COSTA-024.jpg](../medias/photos/PHOTO-COSTA-024.jpg) | 220901 | d1bb973a9617bd59a34ed4506931d30c5bc6f95d | Concordante |
| [PHOTO-COSTA-025.jpg](../medias/photos/PHOTO-COSTA-025.jpg) | 715279 | e88943ced7d910150e0fef43a89438d356850e77 | Concordante |
| [PHOTO-COSTA-026.jpg](../medias/photos/PHOTO-COSTA-026.jpg) | 276831 | 464d16d896266c4accab2407c0b5458a73c00739 | Concordante |
| [PHOTO-COSTA-027.jpg](../medias/photos/PHOTO-COSTA-027.jpg) | 363769 | 6de3052191b96ec212aa4ad14b7da70b36c3b1ce | Concordante |
| [PHOTO-COSTA-028.jpg](../medias/photos/PHOTO-COSTA-028.jpg) | 384152 | 1126f72133891fa74430c290aea3673fe10185f4 | Concordante |
| [PHOTO-COSTA-029.jpg](../medias/photos/PHOTO-COSTA-029.jpg) | 680982 | 912e12ed721cc63a87dfacd045cb0ab67f1c5b07 | Concordante |
| [PHOTO-COSTA-030.jpg](../medias/photos/PHOTO-COSTA-030.jpg) | 716379 | 78c48ea4b591ae4c4d6549c540750ee13b2b48d1 | Concordante |
| [PHOTO-COSTA-031.jpg](../medias/photos/PHOTO-COSTA-031.jpg) | 519505 | 4f387e761f47a766d0c592e81bc37ec8af38d4ba | Concordante |
| [PHOTO-COSTA-032.jpg](../medias/photos/PHOTO-COSTA-032.jpg) | 526880 | e8fe6433a37da23a560aee4037a1cba711d55489 | Concordante |
| [PHOTO-COSTA-033.jpg](../medias/photos/PHOTO-COSTA-033.jpg) | 363283 | df4ea0fbd14cdcb1bdd7b67ec75d0b1cc8100803 | Concordante |
| [PHOTO-COSTA-034.jpg](../medias/photos/PHOTO-COSTA-034.jpg) | 660644 | 7d9667578e6fb135159edb079ce1280d11a3e8db | Concordante |
| [PHOTO-COSTA-035.jpg](../medias/photos/PHOTO-COSTA-035.jpg) | 559147 | 3b85ce1f3e76224da275ecc3e97b36938188334c | Concordante |
| [PHOTO-COSTA-036.jpg](../medias/photos/PHOTO-COSTA-036.jpg) | 283787 | 17627e4b9761b40f95075c43f5fff25edac9e17b | Concordante |
| [PHOTO-COSTA-037.jpg](../medias/photos/PHOTO-COSTA-037.jpg) | 345514 | 22a3371950a4b389ffe5a9a380e8024adbdf1e53 | Concordante |
| [PHOTO-COSTA-038.jpg](../medias/photos/PHOTO-COSTA-038.jpg) | 400597 | 235eb037add0c915049e6d794b4603e9b4e8adad | Concordante |
| [PHOTO-COSTA-039.jpg](../medias/photos/PHOTO-COSTA-039.jpg) | 350990 | c9e9c918505fe3778bd779b0e5311d2f0f30cb8c | Concordante |
| [PHOTO-COSTA-040.jpg](../medias/photos/PHOTO-COSTA-040.jpg) | 341396 | f1d277424131562eeef5c4f6a3f71ce2b8afbcae | Concordante |
| [PHOTO-COSTA-041.jpg](../medias/photos/PHOTO-COSTA-041.jpg) | 546552 | 6b34df662ba3d573c88fff096765370c35a69ea7 | Concordante |
| [PHOTO-COSTA-042.jpg](../medias/photos/PHOTO-COSTA-042.jpg) | 441570 | c469c559c804a7e5fe5a04aa8db41f1a25cc69b6 | Concordante |
| [PHOTO-COSTA-043.jpg](../medias/photos/PHOTO-COSTA-043.jpg) | 603211 | e7283d9c957156095dcbb5db007b6487c113a5f3 | Concordante |
| [PHOTO-COSTA-044.jpg](../medias/photos/PHOTO-COSTA-044.jpg) | 278553 | 9cc72db2e2f93f91f16ebf3f2eb28e1066b80022 | Concordante |
| [PHOTO-COSTA-045.jpg](../medias/photos/PHOTO-COSTA-045.jpg) | 454898 | cb949448f6426cfd7d0a2302b79e1f00978bef54 | Concordante |
| [PHOTO-COSTA-046.jpg](../medias/photos/PHOTO-COSTA-046.jpg) | 183527 | 991d7e216bddcb72560fccb2d2b91ad9d3e5461b | Concordante |
| [PHOTO-COSTA-047.jpg](../medias/photos/PHOTO-COSTA-047.jpg) | 374175 | 7816621b57f98209bcdc9871b04a717fd7a8c22e | Concordante |
| [PHOTO-COSTA-048.jpg](../medias/photos/PHOTO-COSTA-048.jpg) | 306119 | eeb53e4d104188014326a425711e5920d41ede49 | Concordante |
| [PHOTO-COSTA-049.jpg](../medias/photos/PHOTO-COSTA-049.jpg) | 402049 | e9a17e06f08e8baff9e2d8fcd9554e733d50b8a7 | Concordante |
| [PHOTO-COSTA-050.jpg](../medias/photos/PHOTO-COSTA-050.jpg) | 453279 | 4df78a60163ff97c2a06ec6afcf9f1002595a576 | Concordante |
| [PHOTO-COSTA-051.jpg](../medias/photos/PHOTO-COSTA-051.jpg) | 529636 | 8bbc0eb87bf9b27c501a82543436b6921bc591f9 | Concordante |
| [PHOTO-COSTA-052.jpg](../medias/photos/PHOTO-COSTA-052.jpg) | 566899 | 9fac11b9f2df0bc7880babecbd3a32797fafdcbd | Concordante |
| [PHOTO-COSTA-053.jpg](../medias/photos/PHOTO-COSTA-053.jpg) | 471199 | df92a827afea4ba94b6179505cc5a011c75a5417 | Concordante |
| [PHOTO-COSTA-054.jpg](../medias/photos/PHOTO-COSTA-054.jpg) | 238580 | caf61fc2d4561f11a598023567c8a06d8c6288c9 | Concordante |
| [PHOTO-COSTA-055.jpg](../medias/photos/PHOTO-COSTA-055.jpg) | 714873 | 1c15728f46af4b19e1e4a2dfdbdef6ae29bf753f | Concordante |
| [PHOTO-COSTA-056.jpg](../medias/photos/PHOTO-COSTA-056.jpg) | 456711 | ec72d792f8df86a159eb562c16dfb61c9193dc2d | Concordante |
| [PHOTO-COSTA-057.jpg](../medias/photos/PHOTO-COSTA-057.jpg) | 378007 | 5f774a4d44dd86221c504297bedb63fa937e7287 | Concordante |
| [PHOTO-COSTA-058.jpg](../medias/photos/PHOTO-COSTA-058.jpg) | 493269 | ea02dce497d7bfb175b6af748361e44aba79418d | Concordante |
| [PHOTO-COSTA-059.jpg](../medias/photos/PHOTO-COSTA-059.jpg) | 279008 | 29674792ad15b1e17ab9413e642ceb5b8b947c10 | Concordante |

## 5. Inventaire exhaustif des huit archives ZIP de vidéos
| Lot | Archive Drive | Taille (octets) |
|---:|---|---:|
| 1 | COSTA_VIDEOS_LOT_01_SUR_08.zip | 43884443 |
| 2 | COSTA_VIDEOS_LOT_02_SUR_08.zip | 43300851 |
| 3 | COSTA_VIDEOS_LOT_03_SUR_08.zip | 42681647 |
| 4 | COSTA_VIDEOS_LOT_04_SUR_08.zip | 43330326 |
| 5 | COSTA_VIDEOS_LOT_05_SUR_08.zip | 42900142 |
| 6 | COSTA_VIDEOS_LOT_06_SUR_08.zip | 42698816 |
| 7 | COSTA_VIDEOS_LOT_07_SUR_08.zip | 42360115 |
| 8 | COSTA_VIDEOS_LOT_08_SUR_08.zip | 42405773 |

- Guide retrouvé : COSTA_CHAMBLY_VIDEOS_GUIDE_VERIFICATION_V10.zip (4 928 octets).
- Autres archives repérées : R2NETTE_Costa_Chambly_Pieces_Photos_Originales_V7.zip, COSTA_PHOTOS_V7.zip.part-000, COSTA_CHAMBLY_OCR_INDEX_COMPLET_V10.zip.
- Autre image repérée : 1000130174.jpg, non comprise dans la séquence des 59 photos numérotées.
- Le contenu intégral des 17 MP4 et leur liste de SHA-256 ne sont pas placés dans ce registre public. Les vidéos sont dans les ZIP du dossier Drive indiqué plus haut.

## 6. Autres documents Costa repérés par métadonnées dans Google Drive
- R2NETTE_Costa_Chambly_Dossier_Provisoire_V9.pdf — 19 283 290 octets.
- COSTA CHAMBLY — TRANSCRIPTION INTÉGRALE TEXTE V9 (81 PAGES) — Google Doc.
- COSTA CHAMBLY — BesoinAvocat — FICHE DOSSIER, CHRONOLOGIE ET PIÈCES — 2026-11-10 — Google Doc.
- COSTA_CHAMBLY_Assurance_Portes_Avant_Arriere_V1.pdf — 98 527 octets.
- COSTA_CHAMBLY_Assurance_Portes_Avant_Arriere_V1.docx — 40 808 octets.
- R2NETTE_Costa_Chambly_Facture_Proforma_V9.pdf — 100 652 octets.
- Le README du dépôt décrit un dossier provisoire et non certifié, les 59 photos, 17 vidéos et deux photos justificatives, des travaux envisagés sur quatre jours avec quatre intervenants, ainsi qu'un devis pro forma de 9 000 CAD HT / 10 347,75 CAD TTC. Cela ne constitue ni une facture acquittée ni une constatation de paiement.

## 7. Contexte supplémentaire de conversations antérieures (extraits visibles, non transcription complète)
- 11 août 2026 : demande d'extraire intégralement du texte de plusieurs images, de remettre les pièces en séquence, de lister preuves et équipements et de signaler les éléments illisibles; ensuite « ENVOYER A CODEX » et « TOUS LES IMAGES ET VIDEO ».
- 17 novembre 2026 : demande de préparer pour l'assureur un dossier succinct, avec montants, factures et sans hypothèses; demande liée à R2NETTE.CA / 9394-2621 QC INC et consultation GitHub/Google Drive.
- Pour la présente opération photos/vidéos, la consigne conservée est AUCUN ENVOI À L'ASSUREUR.

## 8. Limites, préservation, statut final
- 59 JPEG disponibles sur GitHub; 8 ZIP vidéo dans Google Drive contenant, après assemblage annoncé, 17 MP4.
- Tests des médias : intégrité des ZIP et JPEG et lecture des en-têtes MP4. Pas d'authentification juridique des scènes, des dates ou des appareils; pas de certification de chaîne de possession historique.
- 84 empreintes SHA-256 annoncées produites dans un registre local, non publiées ici. Aucune valeur cryptographique non visible n'est inventée.
- Aucun nouveau média binaire transféré dans ce dépôt lors des opérations décrites. Le dépôt GitHub étant public, éviter d'y verser des vidéos, des preuves confidentielles ou des identifiants privés.
- Les liens temporaires sandbox:/mnt/data/ du chat peuvent expirer; pour une récupération durable, utiliser le dossier Google Drive et le dépôt GitHub.
- Aucun document envoyé à l'assureur.
- Limite d'exhaustivité : toutes les informations matérielles accessibles dans ce fil et les extraits antérieurs disponibles ont été rassemblés; les discussions non accessibles en intégralité, journaux internes, octets de fichiers et métadonnées privées non publiées ne peuvent être transcrits ici.

_Document de suivi et d'archivage, non expertise juridique._

---

# Annexe commerciale — R2NETTE / RAPIDE 2 NETTE — facture pro forma COSTA

**Ajout : 17 novembre 2026.** Cette annexe complète sans supprimer ni reformuler les transcriptions, inventaires et résultats de contrôles conservés plus haut.

## Émetteur
- RAPIDE 2 NETTE — R2NETTE.CA
- 9394-2621 Québec inc.
- Adresse professionnelle, numéros TPS/TVQ et numéro définitif de facture : non établis dans les sources actuellement accessibles. Ne pas les inventer.

## Site et dossier
- Client / dossier : COSTA — Chambly; identité légale du destinataire de la facture non fixée par les sources consultées.
- Adresse du site : 1336, avenue Bourgogne, Chambly (Québec).
- Référence documentaire : R2N-COSTA-V9 / FIN-COSTA-001.
- Nature : travaux de nettoyage et remise en état après sinistre, selon devis R2NETTE V9.

## Bordereau pro forma documenté
| Ligne | Description | Montant CAD |
|---|---|---:|
| 1 | Ensemble des services R2NETTE selon estimation V9, incluant une provision de conteneur de 600,00 $ à ne pas ajouter séparément | 9 000,00 $ HT |
| | Taxes selon le total indiqué dans l'estimation V9 | 1 347,75 $ |
| | **Total pro forma** | **10 347,75 $ TTC** |

**Base de calcul du devis :** quatre journées prévues, quatre personnes prévues et 128 heures-personnes budgétaires (4 × 8 h × 4 jours). Il ne s'agit pas d'un relevé d'heures signé.

## Autres justificatifs financiers non cumulés automatiquement
- Recybac R-104619-697, 24 août 2026 : 685,00 $ HT / 787,58 $ TTC, conteneur 20 verges C.R.D. Provision de 600,00 $ déjà incluse dans le devis; écart HT de 85,00 $.
- Plomberie no 1071, 29 octobre 2026 (travaux indiqués le 15 août) : 1 500,00 $ HT / 1 724,63 $ TTC; prestation distincte.
- Les deux justificatifs de fournisseurs représentent ensemble 2 185,00 $ HT / 2 512,21 $ TTC et ne s'ajoutent pas automatiquement au total R2NETTE.

## Liens internes et conservation
- Registre de rapprochement : [RAPPROCHEMENT_FINANCIER.md](RAPPROCHEMENT_FINANCIER.md).
- Index : [INDEX.md](INDEX.md).
- Annexe/facture pro forma distincte : [FACTURE_PRO_FORMA_R2NETTE_COSTA_2026-11-17.md](FACTURE_PRO_FORMA_R2NETTE_COSTA_2026-11-17.md).
- La déclaration policière mentionne « Nettoyage des lieux — RAPIDE 2 NETTE — Émilie ».
- L'inventaire comporte 59 photographies, 17 MP4 et les cinq JPEG du chat, avec les distinctions détaillées plus haut; les 27 postes d'équipements et leur transcription restent intégralement conservés.
- Aucune facture n'a été envoyée à l'assureur par cette opération.

**Statut : pro forma documentaire, non facture acquittée ni certification d'exécution des heures prévues.**
