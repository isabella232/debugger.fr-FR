---
description: valeur nulle
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: Écran récapitulatif
title: Écran récapitulatif
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 2c3d056451c5b7b4bf5603c22bf3bbdbc693491f

---


# Écran récapitulatif {#summary-screen}

Pour exécuter Experience Cloud Debugger, cliquez sur l’icône d’extension dans la barre d’extension, puis ouvrez la page à examiner dans Chrome.

![](assets/start-icon.jpg)

L’écran récapitulatif d’Adobe Experience Cloud Debugger s’affiche.

![](assets/summary.jpg)

Cet écran affiche des informations sur chaque solution Adobe Experience Cloud. Les informations affichées varient selon la solution, mais comprennent généralement des données telles que la bibliothèque et la version de la solution (par exemple, « AppMeasurement v2.9 ») et les identifiants de compte (tels que l’identifiant de suite de rapports Analytics, le code client Target, l’identifiant partenaire d’Audience Manager, etc.).


## Exécution d’un audit dans Auditor {#section-82bc57440406461ebf27a16855b71655}

Vous pouvez utiliser Adobe Auditor pour exécuter une série d’audits sur votre page. To run Auditor, click **[!UICONTROL Auditor]** in the top menu, then click **[!UICONTROL Audit Page Now]**. Pour ouvrir Adobe auditeur, cliquez sur **[!UICONTROL Run Multi-Page Audit Now]**.

## Informations affichées dans Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Debugger affiche les informations suivantes pour chaque solution :

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Suite(s) de rapports </p> </td> 
   <td colname="col2"> <p>Une <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external">suite de rapports</a> définit les rapports indépendants et complets d’un site web choisi, d’un ensemble de sites web ou d’un sous-ensemble de pages web. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version d’<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external">AppMeasurement</a> définie pour la page. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version du visiteur </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external">d’identifiants visiteur</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de la page </p> </td> 
   <td colname="col2"> <p>Variable <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external">pageName</a> envoyée à Analytics qui contient un nom convivial du site. </p> </td> 
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
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external">Nom du partenaire</a> pour l’instance DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external">Numéro de version</a> de l’instance DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external">ID utilisateur unique</a> associé à l’instance DIL </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> propriété </a>Adobe Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de version </p> </td> 
   <td colname="col2"> <p>Date de version de la <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> bibliothèque</a> Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external">Environnement</a> utilisé par la bibliothèque Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Répertoire de script </p> </td> 
   <td colname="col2"> <p>Répertoire dans lequel est stocké le script Launch. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom de la bibliothèque </p> </td> 
   <td colname="col2"> <p>Nom de la<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> bibliothèque</a> Adobe DTM </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de version </p> </td> 
   <td colname="col2"> <p>Date de version de la <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> bibliothèque</a> Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p>Environnement utilisé par la bibliothèque DTM </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Répertoire de script </p> </td> 
   <td colname="col2"> <p>Répertoire dans lequel est stocké le script DTM. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Service Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID (ID d’organisation d’Experience Cloud) </p> </td> 
   <td colname="col2"> <p>Votre <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> ID d’organisation</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> d’identifiants visiteur</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Code client </p> </td> 
   <td colname="col2"> <p>Votre <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> code client Target </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Votre version actuelle d’<a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> ou de mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de mbox globale </p> </td> 
   <td colname="col2"> <p>La<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox globale</a> désigne l’appel de serveur unique effectué en haut de chaque page web dans votre mise en œuvre Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de mbox </p> </td> 
   <td colname="col2"> <p>Nom d’une mbox autour d’un <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> emplacement</a> sur la page. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de l’activité </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> campagne ou de l’activité</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Code d’activité </p> </td> 
   <td colname="col2"> <p>ID de l’activité de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de recette </p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> l’expérience</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Identifiant de recette </p> </td> 
   <td colname="col2"> <p>ID de la recette de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offre </p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> l’offre</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’offre </p> </td> 
   <td colname="col2"> <p>ID de l’offre de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

