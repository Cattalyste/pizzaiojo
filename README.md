# Pizzaïo’jo

## Introduction

Une pizzeria a collecté les données de ses ventes sur une année complète et il est temps de leur donner du sens !

L’ensemble de données contient des informations détaillées sur les commandes de
pizzas, y compris des précisions sur les variantes de pizzas, les quantités, les prix, les
dates et d’autres caractéristiques :
  ➔ order_id : Identifiant unique pour chaque commande passée par client.
  ➔ order_details_id : Identifiant unique pour chaque pizza placée dans chaque
      commande (les pizzas de même type et de même taille sont conservées dans la
      même ligne, et la quantité augmente).
  ➔ pizza_id : Identifiant clé unique qui relie la pizza commandée à ses détails, tels
      que la taille et le prix.
  ➔ quantity : Quantité commandée pour chaque pizza de même type et de même
      taille.
  ➔ order_date : date à laquelle la commande a été passée (saisie dans le système
      avant la cuisson et le service).
  ➔ order_time : Heure à laquelle la commande a été passée (saisie dans le système
      avant la cuisson et le service).
  ➔ unit_price : Prix de la pizza en euros.
  ➔ total_price : unit_price X quantity.
  ➔ pizza_size : Taille de la pizza (petite, moyenne, grande, XL ou XXL).
  ➔ pizza_category : Catégorie de la pizza dans le menu (Classique, Poulet, Suprême
      ou Végétarien).
  ➔ pizza_ingredients : Ingrédients utilisés dans la pizza, tels qu'indiqués dans le
      menu (ils comprennent tous du fromage Mozzarella, même si cela n'est pas
      spécifié ; et ils comprennent tous de la sauce tomate, à moins qu'une autre sauce
      ne soit spécifiée).
  ➔ pizza_name : nom de la pizza tel qu'indiqué dans le menu

## Resultat des analyses

### 1. Horraires et jours

Les horraires et les jours d'ouverture semblent correspondre à la demande des clients. Le graphe qui présente l'évolution du nombre de pizza vendues permet au gérant
de planifier ses vacances en fonctione des périodes creuse.

### 2. Modification de la carte

Il serait necessaire de supprimer de la carte les pizza XL et XXL car il est necessaire de préparer et de conserver des paton de pate à pizza pret en tout temps alors que très peu de pizzas de cette taille sont vendues.

