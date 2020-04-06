---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: Outils
title: Outils
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# Outils {#tools}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 est actuellement en version bêta. La documentation et la fonctionnalité peuvent changer.

Dans l’écran Outils, vous pouvez activer ou désactiver divers outils pour la solution installée. Par exemple, vous pouvez activer les instructions de débogage de console de Target ou utiliser la bibliothèque d’évaluation de la gestion dynamique des balises. Ces outils ne sont disponibles que si Target et DTM sont installés sur votre page.

![](assets/tools.jpg)

Vous pouvez effectuer une insertion dynamique de Launch ou DTM sur n’importe quelle page pour tester quelque chose sur une page sur laquelle Launch ou DTM n’est pas installé. Cliquez sur l’icône **[!UICONTROL Embed Code]**, puis saisissez votre [code intégré](https://experiencecloud.adobe.com/resources/help/fr_FR/dtm/deployment.html) et cliquez sur **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## Informations sur la gestion dynamique des balises {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Outil </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> Journalisation de la console DTM </p> </td> 
   <td colname="col2"> <p>Cet outil expose les instructions de débogage spécifiques à la gestion dynamique des balises adressées à la console du navigateur. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Utiliser la bibliothèque d’évaluation </p> </td> 
   <td colname="col2"> <p>Cet outil utilise la bibliothèque d’évaluation pour les informations de débogage de la gestion dynamique des balises. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Désactiver DTM </p> </td> 
   <td colname="col2"> <p>Cet outil empêche la vérification des informations sur la gestion dynamique des balises. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Insertion dynamique de la gestion dynamique des balises </p> </td> 
   <td colname="col2"> <p> Cet outil insère le code DTM sur votre page. Utilisez l’éditeur Code intégré pour modifier le code inséré. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Informations sur Target {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Outil </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Journalisation de la console Target </p> </td> 
   <td colname="col2"> <p>Cet outil présente les instructions de débogage spécifiques à Target dans la console du navigateur, commençant toutes par <span class="codeph"> AT :</span> en ajoutant un cookie appelé <span class="codeph"> mboxDebug=true</span> à votre navigateur. Actuellement, les instructions de la console n’apparaissent pas dans l’écran Journaux de Debugger, mais elles sont visibles dans la console de débogage native du navigateur. </p> <p> Cet outil exige at.js 0.9.6+. Si vous utilisez une ancienne version d’at.js, vous pouvez ajouter le paramètre de chaîne de requête <span class="codeph"> ?mboxDebug=true</span> à votre URL afin d’activer la journalisation de la console. Si vous utilisez mbox.js, vous pouvez ajouter le paramètre <span class="codeph"> ?_AT_Debug=console</span> pour activer la journalisation de la console limitée aux activités du compositeur d’expérience visuelle. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Activer mboxTraces </p> </td> 
   <td colname="col2"> <p>Cet outil ajoute des informations détaillées aux réponses Target, qui peuvent être explorées dans l’écran <span class="uicontrol"> Target&gt; mboxTrace</span> de Debugger. </p> <p> Vous devez être connecté à Experience Cloud dans l’un de vos onglets Chrome pour activer cet outil. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Désactiver Target </p> </td> 
   <td colname="col2"> <p>Cet outil désactive toutes les requêtes Target en ajoutant un cookie appelé <span class="codeph"> mboxDisable=true</span> à votre navigateur. </p> <p> Cet outil exige at.js 0.9.6+. Si vous utilisez une ancienne version, vous pouvez ajouter le paramètre de chaîne de requête <span class="codeph"> ?mboxDisable=true</span> à votre URL pour désactiver les mbox. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mise en surbrillance de mbox </p> </td> 
   <td colname="col2"> <p> Cet outil trace une zone rouge autour des mbox héritées, de style encapsulé. </p> </td> 
  </tr> 
 </tbody> 
</table>

La vidéo suivante explique comment utiliser l’extension Debugger avec Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
