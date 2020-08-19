---
description: Écran de résumé de l'Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Écran de résumé de l'Experience Cloud Debugger
seo-title: Écran récapitulatif
title: Écran récapitulatif
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: tm+mt
source-wordcount: '948'
ht-degree: 98%

---


# Écran récapitulatif {#summary-screen}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 est actuellement en version bêta. La documentation et la fonctionnalité peuvent changer.

Pour exécuter l’Adobe Experience Platform Debugger, cliquez sur l’icône dans la barre de votre navigateur, puis ouvrez la page à examiner dans le navigateur.

![](assets/start-icon.jpg)

L’écran récapitulatif d’Adobe Experience Platform Debugger s’affiche.

![](assets/summary.jpg)

Cet écran affiche également des informations sur chaque solution Adobe Experience Cloud. Les informations affichées varient selon la solution, mais comprennent généralement des données telles que la bibliothèque et la version de la solution (par exemple, « AppMeasurement v2.9 ») et les identifiants de compte (tels que l’identifiant de suite de rapports Analytics, le code client Target, l’identifiant partenaire d’Audience Manager, etc.).

## Informations affichées dans Debugger

Debugger affiche les informations suivantes pour chaque solution :

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Suite(s) de rapports </p> </td> 
   <td colname="col2"> <p>Une <a href="https://experiencecloud.adobe.com/resources/help/fr_FR/reference/report_suites_admin.html" format="html" scope="external">suite de rapports</a> définit les rapports indépendants et complets d’un site web choisi, d’un ensemble de sites web ou d’un sous-ensemble de pages web. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version d’<a href="https://docs.adobe.com/content/help/fr-FR/analytics/implementation/js/migrate-from-hcode.html" format="html" scope="external">AppMeasurement</a> définie pour la page. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version du visiteur </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque <a href="https://docs.adobe.com/content/help/fr-FR/analytics/components/metrics/unique-visitors.translate.html" format="html" scope="external">d’identifiants visiteur</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de la page </p> </td> 
   <td colname="col2"> <p>Variable <a href="https://docs.adobe.com/content/help/fr-FR/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external">pageName</a> envoyée à Analytics qui contient un nom convivial du site. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Modules </p> </td> 
   <td colname="col2"> <p>Modules chargés par Adobe Analytics. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partenaire </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">Nom du partenaire</a> pour l’instance DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external">Numéro de version</a> de l’instance DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external">ID utilisateur unique</a> associé à l’instance DIL. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external"> propriété </a>Adobe Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de version </p> </td> 
   <td colname="col2"> <p>Date de version de la <a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/publish/libraries.html" format="https" scope="external"> bibliothèque</a> Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/publish/environments.html" format="https" scope="external">Environnement</a> utilisé par la bibliothèque Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Extensions </p> </td> 
   <td colname="col2"> <p>Extensions utilisées sur la page. </p> </td> 
  </tr> 
 </tbody> 
</table>

**SDK Web Adobe**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Version de la bibliothèque </p> </td> 
   <td colname="col2"> <p>Le numéro de la <a href="https://docs.adobe.com/content/help/fr-FR/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">version de la bibliothèque</a> SDK Web AEB. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namespace (Espace de nom du visiteur)</p> </td> 
   <td colname="col2"> <p>Le nom identifié dans l’extension.</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID de propriété </p> </td> 
   <td colname="col2"> <p>Le nom de la propriété Launch spécifié dans l’extension. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Domaine Edge </p> </td> 
   <td colname="col2"> <p>Le domaine vers lequel/à partir duquel l’extension Adobe Experience Platform envoie et reçoit des données. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Identifiant IMS de l’organisation </p> </td> 
   <td colname="col2"> <p>L’organisation à laquelle vous souhaitez envoyer les données chez Adobe, comme indiqué dans l’extension. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Journalisation activée </p> </td> 
   <td colname="col2"> <p>Indique si la journalisation a été activée pour cette propriété.</p> </td> 
  </tr> 
 </tbody> 
</table>

**Service Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID (ID d’organisation d’Experience Cloud) </p> </td> 
   <td colname="col2"> <p>Votre <a href="https://experiencecloud.adobe.com/resources/help/fr_FR/mcvid/" format="https" scope="external"> ID d’organisation</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque<a href="https://docs.adobe.com/content/help/fr-FR/analytics/components/metrics/unique-visitors.translate.html" format="html" scope="external"> d’identifiants visiteur</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Code client </p> </td> 
   <td colname="col2"> <p>Votre <a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> code client </a>Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Votre version actuelle d’<a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> ou de mbox.js. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom global de la demande </p> </td> 
   <td colname="col2"> <p>La<a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox globale</a> désigne l’appel de serveur unique effectué en haut de chaque page web dans votre mise en œuvre Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Événement de chargement de page </p> </td> 
   <td colname="col2"> <p>Type d’<a href="https://docs.adobe.com/content/help/fr-FR/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">événement</a> qui se déclenche au chargement de la page. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de la demande </p> </td> 
   <td colname="col2"> <p>Le nom d’une requête autour d’un <a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> emplacement</a> sur la page. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de l’activité </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobe.com/content/help/fr-FR/target/using/activities/activities.html" format="html" scope="external"> campagne ou de l’activité</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Code d’activité </p> </td> 
   <td colname="col2"> <p>ID de l’activité de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de l’expérience </p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/fr-FR/target/using/experiences/experiences.html" format="html" scope="external"> l’expérience</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’expérience </p> </td> 
   <td colname="col2"> <p>ID de l’expérience Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offre   Nom</p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/fr-FR/target/using/experiences/offers/manage-content.html" format="html" scope="external"> l’offre</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’offre </p> </td> 
   <td colname="col2"> <p>ID de l’offre de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

