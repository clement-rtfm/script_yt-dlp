# 🎵 yt-audio-downloader.sh

Un script Bash simple et efficace pour télécharger des **vidéos ou playlists YouTube en MP3**, avec **métadonnées et miniatures intégrées**, directement dans ton dossier Musique.

---

## 🚀 Fonctionnalités

- ✅ Télécharge une **vidéo ou une playlist YouTube**
- 🎧 Convertit automatiquement en **MP3**
- 🖼 Ajoute la **miniature comme pochette d’album**
- 📝 Intègre les **métadonnées** de la vidéo
- 📁 Organise les fichiers par **nom de playlist**
- 🧩 Enregistre les erreurs dans un fichier `errors.log`

---

## 📦 Pré-requis

Tu dois avoir [`yt-dlp`](https://github.com/yt-dlp/yt-dlp) installé **manuellement** (pas via `apt`) :

sudo curl -L https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -o /usr/local/bin/yt-dlp
sudo chmod a+rx /usr/local/bin/yt-dlp



🛠 Installation du script
Clone ce dépôt ou télécharge le fichier : git clone https://github.com/ton-utilisateur/yt-audio-downloader.git
cd yt-audio-downloader

Rends le script exécutable : chmod +x yt-audio.sh

🎬 Utilisation
Lance simplement le script depuis ton terminal : ./yt-audio.sh

Tu verras : Colle l'URL YouTube (vidéo ou playlist) :

Colle ton lien YouTube et laisse faire la magie.

📁 Emplacement des fichiers
Les MP3 seront enregistrés dans :
~/Musique/YT-Audio/Nom_de_la_Playlist/nom_de_la_video.mp3

⚠️ En cas de problème
Si tu obtiens des erreurs pendant le téléchargement, consulte le fichier : ~/Musique/YT-Audio/errors.log

📜 Licence
Ce script est distribué sous la licence MIT. Utilisation à but personnel uniquement, conformément aux conditions d’utilisation de YouTube.
