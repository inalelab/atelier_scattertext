# Atelier Scattertext pour la comparaison de corpus d'émissions TV

Support pour un atelier de découverte du package Python [Scattertext](https://github.com/JasonKessler/scattertext), à travers une analyse comparative du discours sur les chaînes TV d'information en continu françaises.  

Scattertext propose une visualisation très simple et intuitive des termes sous forme de nuages de points répartis en fonction de leur fréquence dans deux corpus A et B. Il introduit également une mesure d'association spécifique de termes à une variable. 

Le code dans ce dépôt s'appuie sur un jeu de données au format CSV, non fourni, qui porte sur 1 mois x 5 chaînes d'info en continu françaises, incluant la transcription [Whisper](https://github.com/openai/whisper), le genre des locuteurs [Inaspeechsegmenter](https://github.com/ina-foss/inaSpeechSegmenter), ainsi que les notices documentaires décrivant ces programmes. L'accès à ces données est soumis à la signature d'une convention de recherche avec [le lab INA](https://inalelab.hypotheses.org/).

### Exemple avec CNews (cliquer pour la version interactive)
Chaque point représente un terme. Les coordonnées représentent la fréquence du terme sur Cnews (axe vertical), et sa fréquence sur les autres chaînes (axe horizontal).
La couleur du point représente le score d'association.
[![Scattertext Example](figs/fig1.png)](https://inalelab.github.io/atelier_scattertext/figs/1_cnews_vs_reste_f%C3%A9v22.html)

### Autres visualisations

Les visualisations créées dans le cadre de l'atelier sont visibles ici en version interactive :
- [http://inalelab.github.io/atelier_scattertext](https://inalelab.github.io/atelier_scattertext/figs/)

Sources :
- Jason S. Kessler. Scattertext: a Browser-Based Tool for Visualizing how Corpora Differ. _ACL System Demonstrations._ 2017. [Article](https://arxiv.org/abs/1703.00565), [github](https://github.com/JasonKessler/scattertext)  
- INAspeechsegmenter: Doukhan et al. An Open-Source Speaker Gender Detection Framework for Monitoring Gender Equality. _Acoustics Speech and Signal Processing (ICASSP),_  2018.  [github](https://github.com/ina-foss/inaSpeechSegmenter)
- Whisper : Robust Speech Recognition via Large-Scale Weak Supervision. _Proceedings of the 40th International Conference on Machine Learning, PMLR 202:28492-28518, 2023_. [github](https://github.com/openai/whisper)
- Arthur Lezer. L'analyse des médias au lab INA. _INA le lab_. 2022. https://doi.org/10.58079/12yb1

L'atelier a eu lieu en ligne le 22 avril 2025 dans le cadre du programme d'animation scientifique [du lab INA](https://inalelab.hypotheses.org/ateliers).
