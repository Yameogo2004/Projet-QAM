# Projet-QAM-et-Netspot
Ce projet a pour objectif la conception et l’implémentation en Python d’un modem QAM (Quadrature Amplitude Modulation) complet, capable de transmettre des données numériques (y compris des images) de manière efficace en milieu bruité.
# Projet_QAM

## 📋 Cahier des charges

1. Conception pour M symboles          ➤ Entrée : nombre de symboles ou nombre de bits par symbole
2. Ajout d’une option de codage Gray  
3. Génération du tableau de correspondance  ➤ Contenu : symbole, bits, décimal, I, Q, énergie, phase
4. Calcul des bilans d’énergie et de phase ➤ calcul de energie totale, energie moyenne, energie minimale et maximale et la variance de l'energie et pour bilan de phase nombre totale de phase nombre de phase unique phase minimale et maxmale de meme que phase de declenchement
5. Visualisation de la constellation IQ (Tx), configurable
6. Visualisation de la constellation IQ (Rx) avec bruit au choix
7. Calcul du BER et du SNR
8. Représentation du BER en fonction du SNR
9. Application à la transmission d’une image (couleur, traitement par canaux) ➤ Traitement séparé des canaux (R, G, B) + filtrage à la réception

## 💻 Technologies utilisées

- Python 3.x
- NumPy
- Matplotlib
- Pillow
- Random, math

## 📊 Résultats attendus

- Graphiques de constellations (avant/après bruit)
- Fichiers CSV de la constellation
- PDF de bilan d’énergie/phase de courbe de BER et SNR
- Images reçues comparées aux originales
- Courbes BER vs SNR

 👤 Auteur  **Yameogo2004**
