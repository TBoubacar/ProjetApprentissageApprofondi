# ProjetApprentissageApprofondi
Construction de réseaux génériques NN qui étend nn.Module avec mise en place et exécution tests sur les modèles linéaires multi-couches en utilisant le langage Python via Jupyter Notebook.

# Installation de Jupiter NoteBook sur sa machine Linux
  1. sudo pip3 install torch torchvision torchaudio
  2. sudo pip3 install scikit-learn
  3. sudo pip3 install numpy pandas
  4. sudo pip3 install jupyterlab
  5. sudo pip3 install notebook

# Créer un script bash avec les commandes suivantes
  1. sudo nano ./juptiter.sh
  2. écrire copié - collé les lignes suivantes dans le fichier :
      #!/bin/bash

      echo "------------------ DEMARRAGE DU LOGICIEL JUPITER NOTEBOOK --------------------"
      cd ./met-ici-le-chemin-vers-ton-repertoire-de-travail/MonRepertoireDeTravail | python3 -m jupyterlab &
  3. Enregistré le fichier, puis donné tous les droits au fichier avec les commandes suivantes :
    3.1. sudo chmod 777 -R ./jupiter.sh
    3.2. exécuté le script en tapant : ./jupiter.sh
  4. Tout est bon normalement
  
Auteur : TOURE Boubacar, étudiant - alternant à la faculté des sciences d'Angers au sein de l'entreprise Capgemini.
