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


---

# Consolidation intégrale du chat ChatGPT — dossier POLICE COSTA

Cette section ajoute au présent inventaire le contenu documentaire qui a été extrait et organisé dans la conversation ChatGPT liée au dossier. Elle ne remplace pas les contrôles techniques ci-dessus. Les formulations « probable », « illisible » et « impossible à lire » sont conservées pour éviter toute invention.

## Demande formulée dans le chat

La demande était d'extraire « tout le contexte, tout le texte, tout mot pour mot », de remettre les documents en séquence de A à Z, d'inclure la preuve et les équipements listés, et d'indiquer expressément tout élément impossible à lire.

Deux demandes supplémentaires ont ensuite été formulées :
- « ENVOYER A CODEX »
- « TOUS LES IMAGES ET VIDEO »

Un paquet de travail destiné à Codex a été généré sous le nom :
- `DOSSIER_POLICE_COSTA_POUR_CODEX.zip`

Un paquet regroupant tous les médias directement accessibles dans cette conversation au moment de sa création a aussi été généré sous le nom :
- `POLICE_COSTA_TOUS_IMAGES_ET_VIDEOS.zip`

## Médias directement fournis dans cette conversation

Les cinq images directement accessibles dans le chat étaient :
1. `1000130186.jpg`
2. `1000130187.jpg`
3. `1000130194.jpg`
4. `1000130195.jpg`
5. `1000130196.jpg`

Au moment où le paquet du chat a été créé, **aucune vidéo n'était directement attachée ou accessible dans cette conversation**. Cette observation ne contredit pas l'inventaire technique général ci-dessus, qui recense **17 MP4** provenant du dossier Drive privé et des archives ZIP.

## Identification du document policier visible

Organisme :
**RÉGIE INTERMUNICIPALE DE POLICE RICHELIEU-SAINT-LAURENT**

Numéro inscrit sur la déclaration, lecture probable :
**RSL 26 / 08 / 10 / 034**

Lieu de prise de déclaration :
**Chambly**

Date inscrite au début :
**26-08-11**

Heure :
**environ 21h00**

La case **Travail** semble cochée.

Noms inscrits au bas du formulaire :
- **Lacombe Maëlle** — prénom lu comme « Maëlle » avec réserve sur l'orthographe exacte.
- **Pichette Laurie**

Matricules visibles :
- **965**
- **823**

Une signature apparaît dans la première case de signature. La graphie n'est pas suffisamment nette pour attribuer avec certitude un nom à partir de la signature seule.

## Déclaration — première partie — transcription conservée

Texte imprimé d'introduction :
**« Je déclare solennellement que »**

1. Constantinos Chionis, étant propriétaire
2. des lieux 1336 Av Bourgogne CHAMBLY. J’ai opéré
3. le restaurant au 1336 Av Bourgogne, Presque 40 Ans
4. J’ai louer Mon ENTREPRISE, CELA FAIT MAINTENANT
5. 5 Ans que Je loue le Local A DES Fins
6. de Restauration. Le premier locataire ÉTAIT
7. KAYALI [nom/prénom difficile à lire], Il est Rester ENVIRONT 2 ANS.
8. la Franchise a ÉTÉ VENDU A “BRIAN” les
9. occupant on opéré les derniers 3 ANS. Récement
10. au mois de MARS Je commence A Avoir
11. DES Problèmes de Loyer J’ESSAYE DE REJOINDRE
12. le Responsable des lieux “Brian” Je doit FAIRE
13. UNE MISE EN DEMEURE le 17 Avril 2026 Pour
14. Considéré l’occupation ILLEGAL DES Lieux
15. CARL Brian est Introuvable. Nous MANDATONS
16. Matthieu Pour signifier la parti ADVERSE
17. au 1336 Av Bourgogne que TOUS OCCUPANT
18. Doit quitter les lieux dans le 48 hrs,
19. [mot rayé] Brian Appel Costa le 17 Avril 2026
20. pour l’informer qu’il A Vendu le Restaurant
21. A un MEMBRE de son ENTOURAGE, ET qu’il
22. Allait Rappeller dans Pas grand Temps.
23. UNE PERSONNE Nous Rappelle 15 min. Plus TARD
24. Nous Expliquer qu’il ALLAIT PAYER le loyer
25. Et convenir A un Arrangement EFFECTUER
26. UN nouveau Bail - UN CHECK DE 5000$

Le montant lu est **5000 $**.

Texte imprimé suivant la déclaration :
**« Et je fais cette déclaration, la croyant consciencieusement vraie et sachant qu’elle a la même force et le même effet que si elle était faite sous serment. »**

Une signature de déclarant apparaît ensuite. Elle semble correspondre au nom Constantinos Chionis, mais le nom écrit dans le corps de la déclaration doit être distingué de l'interprétation de la signature elle-même.

## Déclaration — continuation — transcription conservée

La feuille suivante continue directement après « UN nouveau Bail - UN CHECK DE 5000$ ».

1. Le CHECK A ÉTÉ RETOURNER ET LA BANQUE
2. Nous a CHARGER DES FRAIS de 45.00$. Nous
3. Avons Alors pris la décision de faire
4. Respecter la mise EN DEMEURE et Nous Avons
5. CHANGER LA SERRURE. Nous NE CONSTATONS
6. pas les dommage, qui on été causé A la
7. porte. L’es occupant se sont Présenter
8. Lundi Et Nous Avons Constater qu’il y a
9. Eu un **[MOT ENTIÈREMENT NOIRCI / IMPOSSIBLE À LIRE]** VANDALISME, Le local, MANQUE
10. les Équipement dans le Local, Nous Contactons
11. le 9-1-1, Nous Sécurisons les lieux.
12. Nous Contactons Notre ASSURANCE.
13. -Nous sommes donnez comme consigne
14. [ligne vide]
15. - Rapport Police
16. - Barricade les Lieux     Vitrerie CHAMBLY     Stephane
17. - Nettoyage des Lieux     RAPIDE 2 NETTE     Émilie

Une grande flèche manuscrite et une signature apparaissent au bas de cette page.

### Mot noirci avant « VANDALISME »

Le mot placé avant « VANDALISME » est physiquement recouvert/noirci. Il a donc été classé **impossible à lire** et n'a pas été reconstruit.

## Chronologie A à Z extraite de la déclaration

A. Constantinos Chionis déclare être propriétaire des lieux situés au **1336, avenue Bourgogne, Chambly**.

B. Il indique avoir exploité le restaurant à cette adresse pendant **presque 40 ans**.

C. Il déclare louer ensuite l'entreprise/le local à des fins de restauration depuis environ **5 ans**.

D. Le premier locataire est identifié par un nom commençant par **KAYALI**; la seconde partie du nom est difficile à lire. Il serait resté environ **2 ans**.

E. La déclaration indique que la franchise a ensuite été vendue à **« BRIAN »**.

F. Les occupants auraient exploité le commerce pendant les **3 années suivantes**.

G. Au mois de **mars 2026**, des problèmes de loyer sont rapportés.

H. Constantinos tente de joindre le responsable des lieux, « Brian ».

I. Une **mise en demeure datée du 17 avril 2026** est faite relativement à ce qui est décrit dans la déclaration comme une **occupation illégale des lieux**.

J. La déclaration précise ensuite que **« CARL Brian est Introuvable »**.

K. « Matthieu » est mandaté pour signifier la partie adverse au **1336 avenue Bourgogne**.

L. Il est indiqué que **tous les occupants doivent quitter les lieux dans les 48 heures**.

M. Brian appelle « Costa » le **17 avril 2026** et dit avoir vendu le restaurant à un membre de son entourage.

N. Une autre personne rappelle environ **15 minutes plus tard**.

O. Cette personne explique qu'elle allait payer le loyer, convenir d'un arrangement et effectuer **un nouveau bail**.

P. Un **chèque de 5 000 $** est remis.

Q. Le chèque est ensuite **retourné par la banque**.

R. La banque charge **45,00 $ de frais**.

S. La déclaration indique qu'ils décident alors de **faire respecter la mise en demeure**.

T. La serrure est changée : **« Nous avons changer la serrure. »**

U. La formulation manuscrite concernant les dommages à la porte est grammaticalement ambiguë; aucun sens plus précis n'est ajouté au texte source.

V. Les occupants se présentent un lundi.

W. La déclaration indique qu'un constat de **vandalisme** est fait.

X. Le document affirme que des **équipements manquent dans le local**.

Y. Le **9-1-1** est contacté.

Z. Les lieux sont sécurisés et l'assurance est contactée.

Consignes inscrites :
- Rapport Police
- Barricade les lieux
- Vitrerie Chambly — Stéphane
- Nettoyage des lieux — Rapide 2 Nette — Émilie

## Liste des biens volés — structure du formulaire

Titre imprimé :
**LISTE DES BIENS VOLÉS**

Colonnes imprimées :
- ARTICLE
- Numéro de série
- CRPQ inscrit
- Marque
- Modèle
- Inscription, particularité, couleur, date et prix d'achat
- Valeur

## Liste complète des 27 lignes de biens ou groupes d'équipements

1. **TABLE SALADE REF (5 port.)** — marque **TZANET** — particularité **STAINLESS**
2. **TOASTER Convoyeur** — marque **STAR** — particularité **STAINLESS**
3. **MACHINE CAFÉ** — marque **BUNN** — particularité **2 TÊTE**
4. **LAVE - VAISSELLE** — marque **HOBART** — particularité **Auto CLEAN**
5. **Bureau Commande**
6. **TABLETTE (RACKING?)** — « RACKING » est une lecture probable
7. **Compresseur & CHAMBRE Froid**
8. **Évaporateur Frigidaire**
9. **CHAMBRE Congélation**
10. **Compresseur & Évaporateur**
11. **Frigidaire (2 porte Pepsi)** — marque **PEPSI**
12. **MACHINE A GLACE** — marque **TZANET**
13. **Comptoir Réception**
14. **MEUBLE Reception**
15. **Air Climatiseur** — marque **LG**
16. **Système Ventilation**
17. **CAMERA SURVEILLANCE** — marque lue probablement **ALARM**
18. **Système Co²** — marque **Mr. Extincteur**
19. **Système tuyauterie Gaz**
20. **Plaque 48 pouce** — marque **MIRACLEAN** — particularité **Miroir Plaque**
21. **Four Pizza** — marque **Lincoln** — particularité **48 pouce convoyeur**
22. **Congélateur (Vertical)** — marque **MKE**
23. **TABLE PIZZA (3 porte)** — marque **TZANET**
24. **TABLE Prep pizza (4 porte)** — marque **TZANET**
25. **Steam table (6 Pans)** — marque **TZANET**
26. **table Refrigerer (3 port)** — marque **TZANET**
27. **Frigideur (2 Porte)** — marque **MKE**

Certaines lignes regroupent plusieurs composants. Par conséquent, **27 lignes ne signifie pas nécessairement 27 pièces physiques distinctes**.

## Texte imprimé important sur les formulaires de biens volés

Mise en garde imprimée :
**« Mise en garde : L’article 140 du Code criminel stipule que quiconque, avec l’intention de tromper, amène un agent de la paix à commencer ou à continuer une enquête en rapportant qu’une infraction a été commise quand elle ne l’a pas été, est passible d’un emprisonnement maximal de (5) ans. »**

Attestation imprimée :
**« Je certifie que les renseignements fournis ci-dessus sont véridiques et exacts. »**

Champs également visibles :
- Nom et prénom (en lettres moulées)
- Signature du plaignant
- Date (a-m-j)
- Signature
- Matricule
- Équipe/unité
- Récupéré par (nom, prénom en lettres moulées)

## Éléments documentaires visibles dans les cinq images du chat

Les images montrent matériellement :
- une déclaration écrite et signée attribuée dans son contenu à **Constantinos Chionis**;
- un numéro RSL inscrit sur la déclaration;
- une date de prise de déclaration du **11 août 2026**;
- la ville de **Chambly**;
- deux noms inscrits au bas du formulaire, avec les matricules **965** et **823**;
- une chronologie mentionnant la mise en demeure du **17 avril 2026**;
- un délai de **48 heures**;
- un chèque de **5 000 $**;
- le retour du chèque;
- **45 $** de frais;
- le changement de serrure;
- un constat de vandalisme;
- des équipements manquants;
- l'appel au **9-1-1**;
- la sécurisation des lieux;
- le contact avec l'assurance;
- trois formulaires policiers intitulés **« LISTE DES BIENS VOLÉS »** comprenant au total **27 lignes d'équipement ou groupes d'équipements**.

Dans les photos fournies dans le chat, les **numéros de série, modèles, valeurs monétaires et prix d'achat** ne sont généralement pas remplis, sauf certaines indications descriptives. Les cases « numéro d'événement RSL » des trois listes paraissent également vides, et les sections d'attestation/signature au bas de ces trois feuilles paraissent non remplies sur les photos disponibles. Cela ne signifie pas que ces renseignements n'existent pas ailleurs; seulement qu'ils ne sont pas visibles sur ces trois feuilles photographiées.

## Éléments impossibles ou incertains à lire

1. **Mot entièrement noirci avant « VANDALISME »** : impossible à lire.
2. **Nom complet après « KAYALI »** : seconde partie non lisible avec certitude.
3. **« Lacombe Maëlle »** : prénom probable, orthographe exacte non garantie à 100 %.
4. **Signature manuscrite du policier** : non lisible de façon suffisamment fiable pour en tirer un nom.
5. **« TABLETTE (RACKING?) »** : « RACKING » probable.
6. **« Frigideur (2 Porte) »** : lecture littérale probable; pourrait correspondre à une faute d'écriture pour « frigidaire », sans correction imposée.
7. **Marque de la caméra** : « ALARM » est la lecture probable.

## Paquet préparé pour Codex dans le chat

Le paquet `DOSSIER_POLICE_COSTA_POUR_CODEX.zip` a été préparé avec :
- les 5 images directement accessibles dans le chat;
- un fichier Markdown `DOSSIER_POLICE_COSTA_CODEX.md`;
- la transcription;
- la chronologie;
- les 27 lignes d'équipements;
- les éléments incertains ou impossibles à lire;
- une instruction de ne pas inventer les mots ou valeurs absents et de conserver les images source avec la transcription.

Instruction donnée dans ce paquet :
**Utiliser ce dossier comme base documentaire. Ne pas inventer les mots ou valeurs absents. Préserver les montants et dates tels qu'ils apparaissent dans la source. Traiter les éléments indiqués « illisible », « noirci » ou « probable » comme incertains. Conserver les images source avec la transcription afin de permettre une vérification visuelle.**

## Paquet « tous images et vidéos » préparé dans le chat

Le paquet `POLICE_COSTA_TOUS_IMAGES_ET_VIDEOS.zip` a été préparé avec les **5 médias directement accessibles dans cette conversation**, soit les cinq JPEG nommés plus haut.

Le contrôle local de cette conversation a indiqué :
- **5 fichiers médias inclus**
- **aucune vidéo directement accessible/attachée dans ce chat au moment de la création du paquet**

Cette limitation est spécifique à l'environnement du chat et ne doit pas être confondue avec l'inventaire Drive/GitHub du début du présent document, qui fait état de **59 JPEG et 17 MP4**.

## Règle de conservation documentaire

Pour toute utilisation future du dossier :
- conserver les formulations sources;
- ne pas transformer une lecture probable en fait certain;
- ne pas inventer de numéro de série, modèle, valeur ou prix d'achat absent;
- conserver la distinction entre ce qui est lisible, probable, illisible ou physiquement noirci;
- conserver les originaux et leurs empreintes lorsque disponibles;
- distinguer les constatations documentaires des conclusions juridiques;
- utiliser les images originales pour toute vérification visuelle.

## État de cette consolidation

La présente section consolide le contenu substantiel du chat relatif aux cinq documents policiers fournis, à leur transcription, à leur remise en ordre, à l'inventaire des équipements, aux éléments de preuve visibles, aux incertitudes de lecture et aux paquets préparés pour Codex et pour les médias.

Mise à jour du fichier GitHub effectuée le **17 novembre 2026** à la demande de l'utilisateur.
