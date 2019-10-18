---
description: valeur nulle
keywords: débogueur;Expérience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: valeur nulle
seo-title: Outils
title: Outils
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Outils{#tools}

Dans l’écran Outils, vous pouvez activer ou désactiver divers outils pour la solution installée. Par exemple, vous pouvez activer les instructions de débogage de console de Target ou utiliser la bibliothèque d’évaluation de la gestion dynamique des balises. Ces outils ne sont disponibles que si Target et la gestion dynamique des balises sont installés sur votre page.

![](assets/tools.jpg)

Vous pouvez insérer dynamiquement Launch ou DTM sur n’importe quelle page pour tester quelque chose sur une page sur laquelle Launch ou DTM n’est pas installé. Cliquez sur l’icône Code **[!UICONTROL incorporé]** , entrez votre code [](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) incorporé, puis cliquez sur **[!UICONTROL Enregistrer]**.

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
   <td colname="col2"> <p>Cet outil expose les instructions de débogage spécifiques à la gestion dynamique des balises à la console du navigateur. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Utiliser la bibliothèque d’évaluation </p> </td> 
   <td colname="col2"> <p>Cet outil utilise la bibliothèque d’évaluation pour les informations de débogage de la gestion dynamique des balises. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Désactiver DTM </p> </td> 
   <td colname="col2"> <p>Cet outil empêche la vérification des informations de gestion dynamique des balises. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Insertion dynamique de la gestion dynamique des balises </p> </td> 
   <td colname="col2"> <p> Cet outil insère le code DTM sur votre page. Utilisez l’éditeur Code incorporé pour modifier le code inséré. </p> </td> 
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
   <td colname="col2"> <p><span class="codeph"> Cet outil expose les instructions de débogage spécifiques à Target dans la console du navigateur, toutes commençant par </span> AT : en ajoutant un cookie appelé <span class="codeph"> mboxDebug=true</span> à votre navigateur. Actuellement, les instructions de la console n’apparaissent pas dans l’écran Journaux du débogueur, mais sont visibles dans la console de débogage native du navigateur. </p> <p> Cet outil requiert at.js 0.9.6+. Si vous utilisez une ancienne version d’at.js, vous pouvez ajouter le paramètre de chaîne de requête <span class="codeph"> ?mboxDebug=true</span> à votre URL afin d’activer la journalisation de la console. Si vous utilisez mbox.js, vous pouvez ajouter le paramètre <span class="codeph"> ?_AT_Debug=console</span> pour activer la journalisation de la console limitée aux activités du compositeur d’expérience visuelle. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Activer les suivis de mbox </p> </td> 
   <td colname="col2"> <p>Cet outil ajoute des informations détaillées aux réponses Target, qui peuvent être explorées dans l’écran <span class="uicontrol"> &gt;Suivi</span> des mbox Target du débogueur. </p> <p> Vous devez être connecté à Experience Cloud dans l’un de vos onglets Chrome pour activer cet outil. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Désactiver Target </p> </td> 
   <td colname="col2"> <p>Cet outil désactive toutes les requêtes Target en ajoutant un cookie appelé <span class="codeph"> mboxDisable=true</span> à votre navigateur. </p> <p> Cet outil requiert at.js 0.9.6+. Si vous utilisez une ancienne version, vous pouvez ajouter le paramètre de chaîne de <span class="codeph"> </span>requête ?mboxDisable=true à votre URL pour désactiver les mbox. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox Highlight </p> </td> 
   <td colname="col2"> <p> Cet outil trace une zone rouge autour des mbox héritées, de style encapsulé. </p> </td> 
  </tr> 
 </tbody> 
</table>

La vidéo suivante explique comment utiliser l’extension Débogueur avec Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=fre_fr)
