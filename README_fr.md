[🇫🇷 Retour à la sélection de la langue](./README.md)
# Qu'est-ce que Utaun ?  
  
Utaun est un logiciel Windows qui génère des banques de voix CV (Consonne-Voyelle) pour UTAU en utilisant exclusivement une modélisation sinusoïdale composite (synthèse vocale CSM) purement inanimée.  
Il prend en charge la génération automatique d'archives ZIP de banques de voix dans votre dossier Documents, ainsi que l'exportation directe vers divers logiciels compatibles UTAU.  

# Fonctionnalités  

* Génère automatiquement un fichier ZIP de banque de voix dans votre dossier Documents ou l'exporte directement vers un logiciel compatible dès son exécution.  
* Génère des voyelles (A, I, U, E, O, N) grâce à une modélisation sinusoïdale composite (synthèse vocale CSM) purement inanimée.  
* Configurez les dossiers de consonnes et de sons voisés inclus dans votre répertoire Documents pour générer des banques de voix CV.  
* Génère automatiquement les lignes m, n, y et w dans le programme.  
* Prend en charge les alias en Hiragana + les alias en Romaji anglais (tous prononcés en japonais).  
* Génère automatiquement `oto.ini`, `character.txt` et `readme.txt`.  
* Convertit simultanément les images PNG aux formats JPG et BMP (Remarque : le JPG est utilisé pour `character.txt`).  
* L'encodage de `readme.txt` et `character.txt` peut être choisi entre **Shift-JIS (ANSI)** et **UTF-8** (Remarque : l'UTF-8 assure la compatibilité avec OpenUTAU et autres).  
* Permet de modifier la fréquence fondamentale (hauteur de voix).  
* Nom de banque de voix (nom du personnage) entièrement personnalisable.  
* **Prend en charge les modes Clair et Sombre.**  
* **Permet de choisir la destination d'exportation.**  

# Utilisation prévue  

* Lorsque vous souhaitez créer des banques de voix UTAU en utilisant des voix inanimées ou artificielles.  
* Pour la production de banques de voix si vous trouvez difficile ou inconfortable d'enregistrer avec votre propre voix.  
* Recherche de matériaux audio basés sur la modélisation sinusoïdale composite (synthèse vocale CSM).  
* Prototypage de banques de voix personnalisées.  
* Décompresser le ZIP généré pour l'utiliser directement comme des ressources de vocaloid simulées par l'humain.  
* Utilisation comme matériaux audio pour des remixes vidéo (par exemple, OtoMAD, YTPMV).  

# Comment utiliser Utaun  

① Téléchargez la dernière version d'Utaun sur **[GitHub Releases](#Releases)**.  
② Si vous téléchargez la version en dossier ZIP, **placez les dossiers "Consonant/Voiced Sound" et `oto.ini` directement dans votre dossier "Documents" (les documents OneDrive sont également pris en charge).** (Remarque : ils sont placés automatiquement si vous utilisez la version installeur).  
③ Placez `Utaun.exe` dans le dossier de votre choix.  
④ Lancez `Utaun.exe` et suivez les instructions à l'écran pour créer votre banque de voix.  
⑤ Pour l'emplacement d'enregistrement des données, vous pouvez choisir entre la sortie ZIP (Documents, etc.) ou l'exportation directe de dossier vers UTAU et OpenUTAU.  
*Remarque : La fonction de mise à jour automatique sera disponible dans les versions futures.*  

# UI
**UI (Écran d'opération - Clair)**   
 ![Test Image 3](UI/IMG_5542.jpeg)  
**UI (Écran des paramètres - Clair)**  
![Test Image4](UI/IMG_5538.jpeg)
**UI (Écran d'opération - Sombre)**  
![Test Image5](UI/IMG_5540.jpeg)  
**UI (Écran des paramètres - Sombre)**  
![Test Image6](UI/IMG_5541.jpeg)  
**UI (Écran d'exportation en cours)**  
![Test Image7](UI/IMG_5536.jpeg)  
**UI (Écran des notes de mise à jour)**  
![Test Image8](UI/IMG_5539.jpeg)  
**UI (Écran de mise à jour)**  
![Test Image9](UI/IMG_5537.jpeg)

# Compatibilité et utilisation des banques de voix générées  

* **UTAU**  
  Exportez directement sous forme de dossier de banque de voix non compressé dans votre dossier `voice` depuis l'application et utilisez-le immédiatement.  
* **OpenUTAU**  
  Exportez directement sous forme de dossier de banque de voix non compressé dans votre dossier `Singers` depuis l'application et utilisez-le immédiatement.  
* **UtauTTS**  
  Extrayez le fichier ZIP exporté et placez-le dans le dossier `voice` de `utauTTS`.  
* **UtauV**  
  Glissez-déposez le fichier ZIP dans la fenêtre de l'application UtaunV en cours d'exécution.  
* **UTAlet (Version Web)**  
  Glissez-déposez le fichier ZIP sur l'écran du site officiel.  
*Remarque : Pour des instructions d'utilisation spécifiques dans chaque logiciel ou environnement web, veuillez vous référer à leurs fichiers d'aide, manuels ou documentation officielle respectifs.*  

# Configuration système requise  

* Windows 10 à 11 (compatible 64 bits / 32 bits)  
**(Remarque : La version 32 bits est utilisée comme base pour des raisons de taille de fichier, mais le programme fonctionne également sans problème sur Windows 64 bits.)**  

# Fonctionnalités non prises en charge  

* Voyelles voisées (あ゙, い゙, ゔ, え゙, お゙)  
* Variations expressives telles que chuchotements, respirations ou composantes de souffle  
* Sons palatalisés (ex. : kya, kyu, kyo / sha, shu, sho)  
* VCV (Voyelles continues)  
* CVVC  
* Autres prononciations spéciales  

# Conditions d'utilisation  

Les actions suivantes sont strictement interdites concernant l'application Utaun elle-même (`Utaun.exe`) :  
* Modification  
* Édition  
* Altération  
* Utilisation commerciale  
* Redistribution  
* Décompilation (désassemblage)  

# Contenu généré  

(Banques de voix, fichiers `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini`, etc.)  
Vous êtes libre (en tant que distributeur) de définir vos propres conditions d'utilisation pour les contenus générés.  
Veuillez écrire vos conditions de licence préférées dans `readme.txt`.  

Pour plus d'informations sur les mises à jour et les détails, consultez la page **Releases** sur GitHub.  

# Releases  
[Download French Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇫🇷)

