RFC YYNN : Modèle de RFC
========================

## Statut

Brouillon

## Objet

Cette RFC décrit un modèle de RFC à suivre.

## Motivation

Un modèle est utile pour que toutes les RFC soient décrites de la même façon.

## Proposition

Ce document est un modèle simple de RFC, permettant d'en écrire d'autres en reprenant ce template.

La RFC est caractérisée par un numéro : YYNN, où YY est l'année, et NN le numéro de RFC dans cette année.

*Exemple : RFC 1401*

La RFC doit décrire tout d'abord son statut puis son objet, succintement. Puis un paragraphe reprend la motivation, soit ce qui a poussé à écrire cette RFC. La proposition détaillée vient ensuite.

Les statuts d'une RFC peuvent être :
* Brouillon : en cours de rédaction
* Finale : prête à être votée
* Approuvée le XXXXX : la RFC a été votée et approuvée
* Rejetée le XXXXX : la RFC a été votée et rejetée

Les RFC sont gérées sur un dépôt Git, afin de pouvoir suivre les modifications de contenu et de statut, ainsi que les auteurs facilement. Lors d'un vote, la RFC approuvée est mergée depuis sa branche vers la branche master.

