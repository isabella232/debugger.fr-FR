---
description: Notes de mise à jour d’Experience Platform Debugger
keywords: debugger;extension Experience Platform Debugger;chrome;extension;notes de mise à jour
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: Notes de mise à jour
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 026ce852ded530e89f36bb01274d7481e07731c0
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 11%

---

# Notes de mise à jour{#release-notes}

## Notes de mise à jour {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 1.2.0 26 octobre 2021

## Nouvelles fonctionnalités

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Fonctionnalité </th>
   <th colname="col2" class="entry"> Description </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Événements de tous les onglets du navigateur visibles dans la vue réseau </p> </td>
   <td colname="col2"> <p> Affichez les événements de tous les onglets du navigateur dans la vue réseau. Pour afficher uniquement les événements de l’onglet actif, cliquez sur l’icône de verrouillage dans le coin inférieur droit du débogueur.</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Modifications apportées à la marque </p> </td>
   <td colname="col2"> <p> Le SDK Web AEP devient SDK Web Adobe Experience Platform et Launch devient des balises Adobe Experience Platform.</p> </td>
  </tr>
 </tbody>
</table>

## Version 1.1.0 5 octobre 2021

## Nouvelles fonctionnalités

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Fonctionnalité </th>
   <th colname="col2" class="entry"> Description </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Visualisation de débogage à distance </p> </td>
   <td colname="col2"> <p> Organisez les événements de débogage à distance dans un diagramme de flux visuel dans la section SDK web Adobe Experience Platform &gt; Transactions Edge . En outre, vous devez demander à l’organisation IMS du SDK Web Adobe Experience Platform utilisée sur la page de correspondre à l’organisation connectée lors du démarrage d’une nouvelle session de débogage à distance. Filtrez les transactions de périphérie selon l’onglet connecté.</p> <p> <b>Remarque :</b> Les journaux de suivi de Target sont toujours disponibles dans la section Journaux &gt; Edge .</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Améliorations de la section de configuration du SDK Web Adobe Experience Platform </p> </td>
   <td colname="col2"> <p> Autorisez le remplacement de la configuration de l’ID de flux de données distinct pour chaque instance de la page. Ajoutez le bouton bascule debug enabled .</p> </td>
  </tr>
 </tbody>
</table>

## Correctifs

* Correction d’un problème en raison duquel le jeton de trace Adobe Target n’était pas toujours envoyé avec les sessions de débogage à distance pour le SDK Web de Adobe Experience Platform.

## Version 1.0.0 5 mai 2021

## Nouvelles fonctionnalités

<table id="table_7EFCAF456B14404FAF3715FC56519AAF">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Fonctionnalité </th>
   <th colname="col2" class="entry"> Description </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Version initiale </p> </td>
   <td colname="col2"> <p> Première version principale du débogueur Experience Platform. Destiné à remplacer l’Experience Cloud Debugger. </p> </td>
  </tr>
 </tbody>
</table>
