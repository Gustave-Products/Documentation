---
description: Ici nous verrons les commandes de musique.
---

# Musique

{% hint style="warning" %}
Les commandes sont à préfixer d'un / . Dans les arguments les arguments entouré de `[ ]` sont des arguments optionnels les autres sont obligatoires. Les données entourées de chevrons `< >` sont des données de type pour vous préciser ce qui est attendu de cet argument.
{% endhint %}

<details>

<summary>Play</summary>

#### Description

Cette commande vous permet de lancer un titre ou une playlist sur le serveur.

#### Arguments

```
[titre] <Texte | Lien> - Le nom ou le lien de la chansson à jouer.
```

```
[playlist] <Lien> - Le lien de la playlist à jouer.
```

_L'argument titre dispose d'une auto complétion. Des titres vous seront donc proposé pendant que vous rechercherez._

</details>

<details>

<summary>Volume</summary>

#### Description

Cette commande vous permet de changer le volume du bot.

#### Arguments

```
pourcentage <Nombre> - Le nouveau pourcentage de volume du bot.
```

</details>

<details>

<summary>Skip</summary>

#### Description

Permet de passer une ou plusieurs musiques dans la liste de lecture du bot.

#### Arguments

```
[position] <Nombre> - Le nombre de chanssons à passer.
```

_Si aucun argument n'est précisé le bot passera une seule musique._

</details>

<details>

<summary>Autoplay</summary>

#### Description

Active ou désactive la fonctionnalité d'autoplay sur le serveur.&#x20;

#### Arguments

```
Aucun
```

</details>

<details>

<summary>Stop</summary>

#### Description

Coupe la musique sur le serveur.

#### Arguments

```
Aucun
```

</details>

<details>

<summary>Boucle</summary>

#### Description

Active ou désactive la boucle de lecture sur le serveur

#### Arguments

* Boucle playlist

```
Aucun - Active la boucle de lecture sur la playlist actuelle.
```

* Boucle titre

```
Aucun - Active la boucle de lecture sur le titre actuel.
```

* Boucle désactiver

```
Aucun - Désactive la boucle de lecture sur le serveur.
```

</details>

