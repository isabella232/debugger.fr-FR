---
description: valeur nulle
keywords: débogueur;Expérience cloud debugger extension;chrome;extension;summary;clear;request;summary screen;solution;analytics;target;dtm;audience manager;launch;id service
seo-description: valeur nulle
seo-title: Écran Résumé
title: Écran Résumé
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Écran Résumé{#summary-screen}

Pour exécuter le débogueur Experience Cloud, cliquez sur l’icône d’extension dans la barre d’extension, puis ouvrez la page à examiner dans Chrome.

![](assets/start-icon.jpg)

L’écran Résumé du débogueur Adobe Experience Cloud s’affiche.

![](assets/summary.jpg)

Cet écran affiche une miniature de la page, ainsi que l’URL et le titre de la page. Il affiche également des informations sur chaque solution Adobe Experience Cloud. Les informations affichées varient selon la solution, mais comprennent généralement des informations, notamment la bibliothèque et la version de la solution (par exemple, "AppMeasurement v2.9") et les identifiants de compte (tels que l’identifiant de la suite de rapports Analytics, le code client Target, l’identifiant partenaire d’Audience Manager, etc.).

Les numéros en bleu en regard des onglets dans la partie supérieure de la fenêtre indiquent le nombre d'appels serveur qui ont été effectués. Vous pouvez les réinitialiser à zéro en cliquant sur **[!UICONTROL Effacer toutes les requêtes]** dans l’onglet correspondant.

Par exemple, l’illustration suivante présente des informations sur Adobe Target. Pour exposer les détails de l’activité illustrés ci-dessous sans authentification, vous devez mettre en oeuvre l’écouteur d’événement de débogage dans votre code ou gestionnaire de balises et activer les jetons [de](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) réponse nécessaires dans l’interface utilisateur de Target.

![](assets/summary-target2.jpg)

## Exécution d’un audit dans l’auditeur {#section-82bc57440406461ebf27a16855b71655}

Vous pouvez utiliser Adobe Audit pour exécuter une série d’audits sur votre page. Pour exécuter le vérificateur, cliquez sur **[!UICONTROL Vérificateur]** dans le menu supérieur, puis cliquez sur **[!UICONTROL Vérifier la page maintenant]**. Pour ouvrir Adobe Audit, cliquez sur **[!UICONTROL Exécuter l’audit multi-page maintenant]**.

## Informations affichées dans le débogueur {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Le débogueur affiche les informations suivantes pour chaque solution :

**Informations sur la page**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Capture d'écran de la page </p> </td> 
   <td colname="col2"> <p>Miniature de la page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL de la page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Title (Titre) </p> </td> 
   <td colname="col2"> <p>Nom spécifié dans la balise <span class="codeph"> &lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics** 

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Report Suite(s) </p> </td> 
   <td colname="col2"> <p>Une <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external">suite de rapports</a> définit les rapports indépendants et complets d’un site web choisi, d’un ensemble de sites web ou d’un sous-ensemble de pages web </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>Version <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> définie pour la page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version du visiteur </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque d’identifiants <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> des</a> visiteurs. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Page Name (Nom de la page) </p> </td> 
   <td colname="col2"> <p>Variable <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> envoyée à Analytics qui contient un nom convivial du site. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Modules </p> </td> 
   <td colname="col2"> <p>Modules chargés par Adobe Analytics </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partenaire </p> </td> 
   <td colname="col2"> <p>Nom <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> du</a> partenaire pour l’instance DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>Numéro<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> de version</a> de l’instance DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>ID <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> utilisateur</a> unique associé à l’instance DIL </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> propriété Adobe Launch</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>La version de <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de création </p> </td> 
   <td colname="col2"> <p>Date de création de la bibliothèque <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"></a> de lancement </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p>Environnement <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"></a> utilisé par la bibliothèque de lancement </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Répertoire de script </p> </td> 
   <td colname="col2"> <p>Répertoire dans lequel le script de lancement est stocké </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nom de la bibliothèque </p> </td> 
   <td colname="col2"> <p>Nom de la bibliothèque Adobe DTM<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> .</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>La version de Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Date de création </p> </td> 
   <td colname="col2"> <p>Date de création de la bibliothèque <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"></a> de lancement </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environnement </p> </td> 
   <td colname="col2"> <p>Environnement utilisé par la bibliothèque DTM </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Répertoire de script </p> </td> 
   <td colname="col2"> <p>Répertoire dans lequel est stocké le script DTM </p> </td> 
  </tr> 
 </tbody> 
</table>

**Service Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ID d’entreprise Experience Cloud </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>Version de la bibliothèque d’identifiants<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> visiteurs</a> . </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Client Code (Code client) </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version   </p> </td> 
   <td colname="col2"> <p>Votre version actuelle <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> ou mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Global Mbox Name (Nom de mbox globale) </p> </td> 
   <td colname="col2"> <p>La<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox</a> globale fait référence à l’appel serveur unique effectué en haut de chaque page Web dans votre implémentation Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de mbox </p> </td> 
   <td colname="col2"> <p>Nom d’une mbox entourant un emplacement <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"></a> sur la page. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de l’activité </p> </td> 
   <td colname="col2"> <p>Nom de la <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> campagne ou de l’activité</a>Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’activité </p> </td> 
   <td colname="col2"> <p>ID de l’activité Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nom de recette </p> </td> 
   <td colname="col2"> <p>Nom de l’expérience <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"></a>Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Identifiant de recette </p> </td> 
   <td colname="col2"> <p>ID de la recette Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offre </p> </td> 
   <td colname="col2"> <p>Nom de l’ <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> offre</a>Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID d’offre </p> </td> 
   <td colname="col2"> <p>ID de l’offre Target. Disponible sans authentification uniquement si vous implémentez l’écouteur d’événement Debugging dans votre code ou gestionnaire de balises et activez les jetons <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> de</a> réponse nécessaires dans l’interface utilisateur de Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

