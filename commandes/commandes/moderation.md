---
description: Ici nous verrons les commandes de modération.
---

# Modération



{% hint style="warning" %}
Les commandes sont à préfixer d'un / . Dans les arguments les arguments entouré de `[ ]` sont des arguments optionnels les autres sont obligatoires. Les données entourées de chevrons `< >` sont des données de type pour vous préciser ce qui est attendu de cet argument.
{% endhint %}

<details>

<summary>Channel</summary>

#### Description

Cette commande permet de manipuler les salons avec le bot.

#### Arguments

* Channel delete

```
salon <Salon> - Le salon à supprimer.
```

* Channel clone

```
salon <Salon> - Le salon à cloner.
```

* Channel rename

```
salon <Salon> - Le salon à renommer.
```

```
nom <Texte> - Le nouveau nom du salon.
```

* Channel nsfw

```
salon <Salon> - Le salon ou changer le nsfw.
```

```
nswf <true | false> - Choisir si il faut activer ou désactiver.
```

* Channel sujet

```
salon <Salon> - Le salon ou vous voulez changer le sujet.
```

```
sujet <Texte> - Le nouveau sujet.
```

* Channel lock

```
salon <Salon> - Le salon à vérouiller.
```

```
[raison] <Texte> - La raison du vérouillage.
```

* Channel unlock

```
salon <Salon> - Le salon à déverouiller.
```

* Channel slowmode

```
salon <Salon> - Le salon à modifier.
```

```
secondes <Nombre> - Le nombre de secondes du slowmode.
```

</details>

<details>

<summary>Clear</summary>

#### Description

Cette commande permet de supprimer des messages avec le bot.

#### Arguments

* Clear nombre

```
nombre <Nombre> - Le nombre de messages à supprimer.
```

* Clear bots

```
nombre <Nombre> - Le nombre de messages de bot à supprimer.
```

* Clear utilisateur

```
utilisateur <Membre> - Le membre dont vous voulez supprimer les messages.
```

```
nombre <Nombre> - Le nombre de messages que vous voulez supprimer.
```

* Clear tout

```
salon <Salon> - Le salon que vous voulez vider.
```

</details>

<details>

<summary>Autorole</summary>

#### Description

Cette commande permet de configurer un autorole sur le serveur.

#### Arguments

* Autorole créer

```
role <Role> - Le premier role de l'autorole.
```

```
[titre] <Texte> - Le titre de l'embed d'autorole.
```

```
[description] <Texte> - La description de l'embed d'autorole.
```

* Autorole ajouter

_Un autorole peut contenir au maximum 4 rôles._

```
role <Role> - Le rôle à ajouter à l'autorole.
```

```
message-id <ID> - L'id du message d'autorole.
```

* Autorole retirer

```
role <Role> - Le rôle à retirer de l'autorole.
```

```
message-id <ID> - L'id du message d'autorole. 
```

</details>

