# 📡 Antenne Patch Imprimée à Balayage Électronique – 2,4 GHz

## Présentation du projet
Ce projet porte sur le **dimensionnement analytique**, la **conception**, la **simulation électromagnétique** et la **validation expérimentale** d’un **réseau d’antennes patch micro-ruban à balayage électronique**, fonctionnant dans la **bande WiFi 2,4 GHz**.

Le travail a été réalisé dans le cadre d’un **projet scolaire** pour [CoHoMa](https://www.defense.gouv.fr/aid/actualites/cohoma-iii-ledition-consolidation)

---

## Cahier des charges
- **Bande de fréquence** : 2,40 – 2,48 GHz  
- **Gain cible** : 20 dBi  
- **Ouverture via le balayage électronique** : −60° à +60°  
- **Ouverture angulaire verticale (HPBW)** : ≈ 30°  
- **Polarisation** : linéaire  
- **Balayage** : électronique par contrôle de phase  

---

## Architecture de l’antenne
- **Élément rayonnant** : patch micro-ruban carré (mode TM₁₀)  
- **Substrat** : εr = 2,6, h = 1,524 mm, tanδ faible  
- **Réseau** : matrice **4 × 4 (16 éléments)**  
- **Excitation** : uniforme, broadside  
- **Réseau d’alimentation** : arborescence micro-ruban symétrique  

---

## Dimensionnement analytique
Le projet repose sur une **chaîne de calcul analytique complète**, couvrant à la fois l’élément rayonnant, le réseau d’antennes et le réseau d’alimentation :

- Calcul des dimensions du patch micro-ruban  
  (λ₀, λg, εeff, effets de bord, résonance TM₁₀)
- Estimation du **gain élémentaire** par modèle d’ouverture équivalente
- Calcul de l’**angle d’ouverture à −3 dB (HPBW)** du patch
- Détermination de l’**impédance d’entrée du patch**  
  (modèle cavité à deux fentes rayonnantes)
- Dimensionnement du **réseau d’antennes**  
  (nombre d’éléments, espacement inter-éléments, facteur de réseau)
- Conception de l’**arborescence d’alimentation micro-ruban** :
  - diviseurs de puissance symétriques,
  - adaptation d’impédance (50 Ω, quarts d’onde),
  - égalisation des longueurs électriques (excitation en phase)
- Intégration de **déphaseurs** pour le balayage électronique :
  - calcul du déphasage requis en fonction de l’angle de pointage,
  - choix d’un déphaseur numérique (résolution angulaire),
  - prise en compte de l’impact du déphasage sur le diagramme de rayonnement

L’ensemble des calculs a été implémenté dans une **feuille Excel de pré-dimensionnement**, permettant l’exploration rapide de différentes architectures et scénarios de réseau.

# Résultats

|   Fichier   |   Image/Lien | 
|---    |:-:    |
|   Rapport du projet PDF   |      |  
| Fichiers de conception et simulation ADS   |     | 

## Visualisation

<p align="center"><img src="" width="600" /></p> 
<p align="center"><img src="" width="600" /></p> 


