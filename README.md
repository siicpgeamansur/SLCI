# SLCI – Simulateurs interactifs pour les Sciences de l'Ingénieur

Collection d'interfaces web interactives pour visualiser et comprendre les notions de **Systèmes Linéaires Continus et Invariants (SLCI)** et de **capteurs / actionneurs**, en classes préparatoires (CPGE – SII).

Aucune installation : chaque outil s'ouvre directement dans le navigateur.

---

## Sommaire

- [Automatique et asservissements](#automatique-et-asservissements)
- [Capteurs](#capteurs)
- [Énergie et actionneurs](#énergie-et-actionneurs)
- [Utilisation en local](#utilisation-en-local)
- [Contribuer](#contribuer)

---

## Automatique et asservissements

| Outil | Description |
|---|---|
| [Réponse temporelle du second ordre et abaques](https://siicpgeamansur.github.io/SLCI/abaques_reponse_echelon_unitaire.html) | Visualiser le lien entre les abaques et la réponse d'un système du second ordre à un échelon unitaire. |
| [Diagramme de Bode](https://siicpgeamansur.github.io/SLCI/Bode.html) | Tracer le diagramme de Bode d'un produit de fonctions de transfert et lire les marges de stabilité (gain et phase). |
| [Correcteurs P, PI et PID](https://siicpgeamansur.github.io/SLCI/asservissement_P_PI_PID.html) | Observer l'effet des correcteurs proportionnel, intégral et dérivé sur un asservissement. |
| [Correcteurs SLCI : vision physique](https://siicpgeamansur.github.io/SLCI/correcteur_SLCI_vision_physique.html) | Comprendre ce que fait chaque correcteur (P, I, PI, PD, PID, avance de phase) sur la stabilité, la précision et la rapidité. Simulateur avec réponse temporelle, dérivée de l'erreur, contribution de chaque action à la commande et Bode de la FTBO avec marges. Inclut les démarches de réglage pas à pas, un quiz, un mode examen chronométré et un exercice type concours sur le PI. Thème clair ou sombre. |

## Capteurs

| Outil | Description |
|---|---|
| [Codeur incrémental](https://siicpgeamansur.github.io/SLCI/codeur_incremental.html) | Principe et signaux d'un codeur incrémental. |
| [Codeur absolu](https://siicpgeamansur.github.io/SLCI/codeur_absolu.html) | Principe et codage d'un codeur absolu. |
| [Potentiomètre rotatif](https://siicpgeamansur.github.io/SLCI/potentiometre_rotatif.html) | Fonctionnement d'un potentiomètre rotatif comme capteur de position angulaire. |
| [Pont de Wheatstone](https://siicpgeamansur.github.io/SLCI/pont_Wheatstone.html) | Étude du pont de Wheatstone pour le conditionnement de capteurs résistifs. |

## Énergie et actionneurs

| Outil | Description |
|---|---|
| [Alimentation réglable AC ou DC](https://siicpgeamansur.github.io/SLCI/alimentation_elec.html) | Principe d'une alimentation réglable en alternatif ou en continu. |
| [Moteurs électriques](https://siicpgeamansur.github.io/SLCI/moteurs_electriques.html) | Fonctionnement et caractéristiques des moteurs électriques. |
| [Identification d'une MCC](https://siicpgeamansur.github.io/SLCI/identification_mcc.html) | Identification des paramètres d'un moteur à courant continu (MCC). |

---

## Utilisation en local

```bash
git clone https://github.com/siicpgeamansur/SLCI.git
cd SLCI
```

Ouvrez ensuite le fichier `.html` de votre choix dans un navigateur récent (Chrome, Firefox, Edge, Safari).

## Contribuer

Les suggestions, corrections et idées de nouveaux simulateurs sont les bienvenues : ouvrez une [issue](https://github.com/siicpgeamansur/SLCI/issues) ou proposez une *pull request*.
