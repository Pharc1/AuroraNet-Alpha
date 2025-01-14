# AuroraNet 🚀  
AuroraNet est un modèle de deep learning conçu pour générer des **coordonnées faciales** à partir d'entrées audio, en transformant des spectrogrammes en animations faciales réalistes.  
🌟 Cette première version s'appuie sur le dataset public **VocaSet** pour valider le concept.  

---

## 🌟 Fonctionnalités principales  
- 🎙️ **Conversion audio -> expressions faciales** : Synchronisation visuelle basée sur des spectrogrammes audio.  
- 🛠️ **Première étape** vers une interaction audio-visuelle immersive.  

---

## 🔧 Technologies utilisées  
- 🐍 **Python** : Langage principal.  
- 🔬 **TensorFlow** : Framework de deep learning pour l'entraînement du modèle.  
- 🎵 **Librosa** : Analyse audio et génération de spectrogrammes.  
- 📊 **Seaborn** : Visualisation des résultats pour analyse des performances.  

---

## 🚀 Étapes futures  
🎯 Une fois l'idée validée avec **VocaSet**, l'objectif est de **passer à un dataset personnalisé**. Ce dataset permettra :  
- 🤩 **Reconnaître les expressions faciales** avec une meilleure précision.  
- 🤖 **Détecter les mouvements de tête** pour une interaction encore plus naturelle et dynamique.  

🔍 **Applications possibles** :  
- 🎮 **Jeux vidéo et mondes virtuels** : Synchronisation labiale et expressions réalistes pour des avatars.  
- 🎥 **Cinéma et animation** : Amélioration des dialogues animés.  
- 🧑‍💻 **Visioconférences** : Avatars interactifs qui réagissent naturellement.  

---

### 💡 Pourquoi AuroraNet ?  
AuroraNet apporte une nouvelle dimension aux interactions homme-machine grâce à son approche innovante. Ce projet a pour ambition de repousser les limites de la technologie audio-visuelle !

### 📚 Références  
Le dataset **VocazSet** utilisé pour cette première version d'AuroraNet est basé sur l'article suivant :

```bibtex
@inproceedings{VOCA2019,
    title = {Capture, Learning, and Synthesis of {3D} Speaking Styles},
    author = {Cudeiro, Daniel and Bolkart, Timo and Laidlaw, Cassidy and Ranjan, Anurag and Black, Michael},
    booktitle = {Proceedings IEEE Conf. on Computer Vision and Pattern Recognition (CVPR)},
    pages = {10101--10111},
    year = {2019},
    url = {http://voca.is.tue.mpg.de/}
}

VocazSet est un dataset utilisé pour la capture et l'apprentissage des styles de parole en 3D. Il a été présenté dans l'article "Capture, Learning, and Synthesis of 3D Speaking Styles" (Cudeiro et al., 2019). Pour plus d'informations, vous pouvez consulter le site officiel du dataset ici.
