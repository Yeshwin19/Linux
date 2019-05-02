# Linux

Pendant ce cours on a eu un projet à faire où on doit écrire 3 script:

- Script pour un jeu de plus ou moins.

- Script pour un outil de sauvegarde.

- Script pour extraire l'audio d'une vidéo de Youtube.


## Le jeu de plus ou moins.

J'ai testé le script en entier et ensuit mettre des caractères que le script ne doit pas prendre en considération pour m'assurer que mon script gère les cas inattendu.


## Un outil de sauvegarde.

C'est là que j'ai eu des soucis, je recevais toujours des erreur comme `command not found`. J'ai essayé deux trois petits trucs. Mias c'était la parti la plus complèxe.


# Extraction de l'audio d'une vidéo de Youtube.

- C'était la partie la plus facile. Ce script invite l'utilisateur à inserer l'url du vidéo à convertir et puis finalement il convertit la vidéo sans grand effort et le télécharge dans le dossiers où la commande est lancé. Pour pourvoir écrire ce script on doit bien manipuler les commandes suivantes:

- `sudo wget https://yt-dl.org/latest/youtube-dl -O /usr/local/bin/youtube-dl` pour telecharger Youtube-dl.

- `sudo chmod a+x /usr/local/bin/youtube-dl` c'est là où on autorise l'application à éxécuter.

- `hash -r` utilise pour rechercher des chemins complets vers les commandes que vous tapez.




