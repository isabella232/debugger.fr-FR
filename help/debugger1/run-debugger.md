---
description: Exécution du Débogueur Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Exécution du Débogueur Experience Cloud
seo-title: Écran récapitulatif
title: Écran récapitulatif
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '1047'
ht-degree: 100%

---


# Écran récapitulatif {#summary-screen}

Pour exécuter Adobe Experience Cloud Debugger, cliquez sur l’icône d’extension dans la barre d’extension, puis ouvrez la page à examiner dans Chrome.

![](assets/start-icon.jpg)

L’écran récapitulatif d’Experience Cloud Debugger s’affiche.

![](assets/summary.jpg)

Cet écran affiche une miniature de la page, ainsi que son URL et son titre. Il affiche également des informations sur chaque solution Adobe Experience Cloud. Les informations affichées varient selon la solution, mais comprennent généralement des données telles que la bibliothèque et la version de la solution (par exemple, « AppMeasurement v2.9 ») et les identifiants de compte (tels que l’identifiant de suite de rapports Analytics, le code client Target, l’identifiant partenaire d’Audience Manager, etc.).

Les numéros en bleu en regard des onglets dans la partie supérieure de la fenêtre indiquent le nombre d’appels au serveur qui ont été effectués. Vous pouvez les remettre à zéro en cliquant sur **[!UICONTROL Clear All Requests]** dans l’onglet correspondant.

Par exemple, l’illustration suivante présente des informations sur Adobe Target. Pour exposer les détails de l’activité illustrés ci-dessous sans authentification, vous devez mettre en œuvre le récepteur d’événement de débogage dans votre gestionnaire de codes ou de balises et activer les [jetons de réponse](https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html) nécessaires dans l’interface utilisateur de Target.

![](assets/summary-target2.jpg)

## Exécution d’un audit dans Adobe Experience Platform Auditor {#section-82bc57440406461ebf27a16855b71655}

Vous pouvez utiliser Platform Auditor pour exécuter une série d’audits sur votre page. Pour exécuter Platform Auditor, cliquez sur **[!UICONTROL Auditor]** dans le menu supérieur, puis sur **[!UICONTROL Audit Page Now]**. Pour ouvrir Platform Auditor, cliquez sur **[!UICONTROL Run Multi-Page Audit Now]**.

## Informations affichées dans Experience Cloud Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger affiche les informations suivantes pour chaque solution :

**Informations sur la page**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Copie d’écran de la page </p> </td> 
   <td colname="col2"> <p>Miniature de la page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL de la page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titre </p> </td> 
   <td colname="col2"> <p>Nom spécifié dans la balise <span class="codeph"> &lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Suite(s) de rapports </p> </td> 
   <td colname="col2"> <p>Une <a href="https://docs.adobe.com/content/help/fr-FR/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">suite de rapports</a> définit les rapports indépendants et complets d’un site web choisi, d’un ensemble de sites web ou d’un sous-ensemble de pages web. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version d’<a href="https://docs.adobe.com/content/help/fr-FR/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a> définie pour la page. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version du visiteur </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque <a href="https://docs.adobe.com/content/help/fr-FR/analytics/components/metrics/unique-visitors.html" format="html" scope="external">d’identifiants visiteur</a>. </p> </td> 
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

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">propriété </a> Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external"> Turbine</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de version </p> </td> 
   <td colname="col2"> <p>Date de version de la <a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/publish/libraries.html" format="https" scope="external">bibliothèque</a> Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/fr-FR/launch/using/reference/publish/environments.html" format="https" scope="external">Environnement</a> utilisé par la bibliothèque Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Répertoire de script </p> </td> 
   <td colname="col2"> <p>Répertoire dans lequel est stocké le script Platform Launch. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom de la bibliothèque </p> </td> 
   <td colname="col2"> <p>Nom de la<a href="https://docs.adobe.com/content/help/fr-FR/dtm/using/library-management.html" format="html" scope="external"> bibliothèque</a> Adobe DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de Turbine. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de version </p> </td> 
   <td colname="col2"> <p>Date de version de la <a href="https://docs.adobe.com/content/help/fr-FR/dtm/using/library-management.html" format="html" scope="external">bibliothèque</a> Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p>Environnement utilisé par la bibliothèque DTM. </p> </td> 
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
   <td colname="col1"> <p>ID d’organisation d’Experience Cloud </p> </td> 
   <td colname="col2"> <p>Votre <a href="https://docs.adobe.com/content/help/fr-FR/id-service/using/home.html" format="https" scope="external"> ID d’organisation</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque<a href="https://docs.adobe.com/content/help/fr-FR/analytics/components/metrics/unique-visitors.html" format="html" scope="external"> d’identifiants visiteur</a>. </p> </td> 
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
   <td colname="col2"> <p>Votre version actuelle d’<a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> ou de mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de mbox globale </p> </td> 
   <td colname="col2"> <p>La<a href="https://docs.adobe.com/help/fr-FR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox globale</a> désigne l’appel de serveur unique effectué en haut de chaque page web dans votre mise en œuvre Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de mbox </p> </td> 
   <td colname="col2"> <p>Nom d’une mbox autour d’un <a href="https://docs.adobe.com/content/help/fr-FR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> emplacement</a> sur la page. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
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
   <td colname="col1"> <p>Nom de recette </p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/fr-FR/target/using/experiences/experiences.html" format="html" scope="external"> l’expérience</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Identifiant de recette </p> </td> 
   <td colname="col2"> <p>ID de la recette de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offre </p> </td> 
   <td colname="col2"> <p>Nom de <a href="https://docs.adobe.com/content/help/fr-FR/target/using/experiences/offers/manage-content.html" format="html" scope="external"> l’offre</a> de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’offre </p> </td> 
   <td colname="col2"> <p>ID de l’offre de Target. Disponible sans authentification uniquement si vous implémentez le récepteur d’événements de débogage dans votre gestionnaire de codes ou de balises et si vous activez les <a href="https://docs.adobe.com/content/help/fr-FR/target/using/administer/response-tokens.html" format="html" scope="external"> jetons de réponse</a> nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

