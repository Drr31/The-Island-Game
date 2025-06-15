# The Island – Projet POO IATIC 3

## Description

Ce projet est une adaptation en Java du jeu de société *The Island*. Il a été réalisé dans le cadre du module d’Approche Orientée Objet (POO) à l’IATIC 3 (Université de Technologie de Troyes, 2021/2022).

L’objectif principal est de proposer une version informatique du jeu jouable en local, avec plusieurs joueurs humains, sur une seule machine. Le programme repose sur Java et utilise la bibliothèque Swing pour l’interface graphique.

## Règles du Jeu

Chaque joueur dirige 10 explorateurs et doit les sauver d’une île en train de sombrer. L’île est composée de tuiles (plage, forêt, montagne) disposées aléatoirement au début de la partie. À chaque tour, le joueur :
1. Joue une tuile terrain (facultatif).
2. Déplace ses explorateurs et/ou bateaux (3 déplacements possibles).
3. Retire une tuile terrain (selon l’ordre plage → forêt → montagne).
4. Lance un dé pour déplacer une créature (serpent de mer, requin, baleine).

Des événements comme les tourbillons, dauphins, et le volcan (fin de partie) ajoutent du suspense et de la stratégie au jeu.

## Fonctionnalités

- Interface en Java Swing.
- Système de tuiles à effet immédiat ou différé.
- Mécanique de déplacement avec vérifications des règles.
- Déplacement des créatures en fonction du lancer de dé.
- Système de score basé sur les points cachés des explorateurs.
- Multi-joueurs local (1 machine).

## Technologies utilisées

- **Langage** : Java
- **Interface graphique** : Swing
- **Outils** : Maven, Javadoc
- **Normes** : Conventions de nommage SUN, documentation Javadoc

## Structure du projet

- `src/` : code source Java
- `resources/` : images, tuiles, fichiers de configuration
- `doc/` : documentation Javadoc
- `README.md` : ce fichier
- `TheIsland.jar` : exécutable Java

## Compilation et Exécution

Ce projet est compilable avec Maven. Un fichier `.jar` exécutable est fourni.

```bash
# Compilation
mvn clean install

# Lancement
java -jar target/TheIsland.jar
```

## Équipe projet

- Dhekra Abouda – dhekra.abouda@gmail.com
- Groupe de 5 étudiant·es de l’IATIC 3

## Livraison

- Rapport final
- Code source complet (avec `.jar`)
- Support de soutenance


---

> Projet universitaire encadré par l’équipe pédagogique de l’IATIC 3.
> IATIC 3 – 2021/2022
