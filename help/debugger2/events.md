---
description: Écran Événements d'Experience Platform Debugger
keywords: debugger;experience platform debugger extension;chrome;extension;events;dtm;target
seo-description: Écran Événements d'Experience Platform Debugger
seo-title: Événements
title: Événements
translation-type: tm+mt
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 100%

---


# Événements {#events}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger  est actuellement en version bêta. La documentation et les fonctionnalités peuvent changer.

L’écran Événements fournit une vue graphique des événements qui se produisent, avec un affichage chronologique.

![](assets/events.jpg)

Pour chaque événement, l’icône correspondant à la solution concernée apparaît sur la chronologie. Les icônes montrent également les modifications apportées à la couche de données (si l’option est activée). Passez la souris sur une icône pour obtenir un résumé de l’événement. Cliquez sur l’événement pour plus d’informations. Vous pouvez cliquer en maintenant la touche Maj ou Ctrl enfoncée pour afficher plusieurs événements.

![](assets/events-details.jpg)

Cliquez sur un détail pour en savoir plus.

![](assets/events-details-more.jpg)

## Suivi des modifications apportées à la couche de données

Pour activer le suivi des modifications apportées à la couche de données dans la chronologie :

1. Cliquez sur l’icône en forme d’engrenage en haut à droite.
1. Entrez le nom de la couche de données.

   ![](assets/event-datalayer.jpg)

1. Cliquez sur **[!UICONTROL Save]**.

Les détails des modifications apportées à la couche de données indiquent tout élément qui a été supprimé ou ajouté. Vous pouvez cliquer sur **{}** pour analyser plus en détail la couche de données.

## Téléchargement des informations sur l’événement

Cliquez sur **[!UICONTROL Download]** pour télécharger un fichier Excel contenant des informations sur les appels de pages.