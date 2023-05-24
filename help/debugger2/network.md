---
title: Onglet Réseau
description: Découvrez comment utiliser l’onglet Réseau dans Adobe Experience Platform Debugger.
keywords: debugger;extension Experience Platform Debugger;chrome;extension;réseau;informations
seo-description: Experience Platform Debugger Network screen
seo-title: Network Tab
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: ed0579ef-ec26-43df-9453-a395c105038a
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 60%

---

# Onglet Réseau

Le **Réseau** agrège tous les appels de solution Adobe Experience Cloud effectués sur la page et les affiche dans l’ordre de gauche à droite. Les paramètres standard sont automatiquement étiquetés avec des noms conviviaux et organisés pour regrouper des paramètres communs sur le même rôle.

![](assets/network.jpg)

Cet écran est utile pour comparer des paires clé-valeur entre les accès. Vous pouvez confirmer que les paramètres utilisés pour les intégrations, tels que l’identifiant visiteur Experience Cloud ou l’ID de données supplémentaires, sont cohérents entre les intégrations.

>[!NOTE]
>
>Actuellement, tous les paramètres transmis dans les appels de solution (par exemple, les variables contextuelles Analytics, les paramètres personnalisés Target ou les ID de client du service Experience Cloud ID) ne sont pas visibles dans l’écran Réseau.

Pour modifier les informations par solution, sélectionnez la solution que vous souhaitez afficher depuis la liste dans le volet de navigation de gauche. L’exemple suivant est filtré pour n’afficher qu’Analytics :

![](assets/network-analytics.jpg)

Pour revenir à l’affichage de toutes les solutions, sélectionnez **[!UICONTROL Network]**

Sélectionnez sur un élément de la vue Réseau pour afficher une vue étendue. Vous pouvez copier les informations affichées dans le Presse-papiers à partir de la fenêtre d’affichage agrandie.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Pour effacer la liste, sélectionnez **[!UICONTROL Remove Events]**.

Pour télécharger un fichier Excel contenant les informations de cet écran, sélectionnez **[!UICONTROL Download]**.
