# Arborescence du projet SAE5.VCOD.SIG

Cette page représente l'arborescence des fichiers et répertoires du projet **SAE5.VCOD.SIG**. Vous trouverez ci-dessous une vue structurée de tous les fichiers et répertoires présents dans le dossier du projet.

```mermaid
graph TD;
    A[SAE5.VCOD.SIG] --> B[carte.php]
    A[SAE5.VCOD.SIG] --> C[index.php]
    A[SAE5.VCOD.SIG] --> D[bdd]
    A[SAE5.VCOD.SIG] --> E[Cahier de charge]
    A[SAE5.VCOD.SIG] --> F[Config]
    A[SAE5.VCOD.SIG] --> G[html]
    A[SAE5.VCOD.SIG] --> H[images]
    A[SAE5.VCOD.SIG] --> I[includes]
    A[SAE5.VCOD.SIG] --> J[sidebars]

    D --> D1[bdd_sae.backup]
    D --> D2[Looping.exe]
    D --> D3[Looping.zip]
    D --> D4[LoopingImage.jpg]
    D --> D5[Looping_32bits.exe]
    D --> D6[MCD SAE5 et 6.VCOD.01 Projet complet SIG.loo]
    D --> D7[projet FME.fmw]
    D --> D8[projet FME.log]
    D --> D9[requete.sql]

    E --> E1[NBRE de crop.txt]
    E --> E2[S5 - Projet SIG complet - Instructions sur Projet à réaliser et rendre - 2024_2025 v2.pdf]

    F --> F1[connexion.php]
    F --> F2[global.php]
    F --> F3[session.php]

    G --> G1[requete.php]

    H --> H1[Crop circle]
    H --> H2[Icone leaflet]
    H --> H3[Image du site]
    H --> H4[Site megalithique]

    H1 --> H1_1[2_2004.jpg]
    H2 --> H2_1[base_nucleaire.png]
    H3 --> H3_1[cropcrircle.jpg]
    H4 --> H4_1[image_1.jpg]

    I --> I1[footer.php]
    I --> I2[header.php]

    J --> J1[index.html]
    J --> J2[sidebars.css]
    J --> J3[sidebars.js]
