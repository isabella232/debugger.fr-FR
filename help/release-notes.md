---
description: valeur nulle
keywords: débogueur;Expérience cloud debugger extension;chrome;extension;notes de mise à jour
seo-description: valeur nulle
seo-title: Notes de mise à jour
title: Notes de mise à jour
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Notes de mise à jour{#release-notes}

## Notes de mise à jour {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Nouvelles fonctionnalités {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Données d’accès après traitement </p> </td> 
   <td colname="col2"> <p> Ajout de la capacité d’ <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> afficher les valeurs sur les accès Analytics après l’exécution</a>des règles de traitement. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Version 0.0.810 - 6 mars 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Nouvelles fonctionnalités {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Tests du vérificateur </p> </td> 
   <td colname="col2"> <p> Ajout de tests <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> Auditeur</a> au débogueur </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Débogueur affiche désormais les réponses AAM </p> </td> 
  </tr> 
 </tbody> 
</table>

## Corrections de bogues {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Correction d’un problème en raison duquel le pied de page masquait le contenu au bas de la page.

* Mise à jour du pied de page du débogueur
* Correction d’un problème en raison duquel une terminologie obsolète était utilisée pour Target.

## Version 0.0.809, 28 février 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Nouvelles fonctionnalités {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Incorporer les fonctions de code </p> </td> 
   <td colname="col2"> <p> Divisez les fonctions de remplacement et d’insertion de code incorporé. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Améliorations {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Correction d’une vulnérabilité potentielle causée par une entrée utilisateur non expurgée.

## Corrections de bogues {#section-556417ff055848c1bf037354dd43cbd0}

* Correction d’un problème en raison duquel les événements DIL AAM n’étaient pas capturés dans l’onglet AAM.

* Correction d’un problème dans Lancement d’insertion dynamique en raison duquel l’interface utilisateur semblait mapper à un autre code incorporé lorsqu’il n’était pas actif.
* Correction d’un problème dans Lancement de l’insertion dynamique en raison duquel une URL incorrecte continuait à s’afficher.
* Correction d’un problème en raison duquel le débogueur continuait à remplacer les codes incorporés même lorsque la fenêtre du débogueur était fermée.

## Version 0.0.806 10 septembre 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Nouvelles fonctionnalités {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Lien Analytics sur l’onglet Outils </p> </td> 
   <td colname="col2"> <p>Affichez les noms conviviaux des variables evar/prop via l’API Analytics via la connexion IMS. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Insérer dynamiquement le lancement </p> </td> 
   <td colname="col2"> <p>Dans l’onglet Outils, vous pouvez insérer dynamiquement le lancement sur une page afin de tester quelque chose sur une page sur laquelle le lancement n’est pas installé. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Améliorations de Target </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Ajout de minutages de performances pour les demandes Target. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Capture d’adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Améliorations {#section-56003a12c32f4998bf1cf2a25a518592}

* Amélioration de l’affichage de l’onglet Réseau de sorte que la hauteur du tableau ne soit pas trop grande et force l’utilisateur à faire défiler verticalement avant de pouvoir faire défiler horizontalement. Auparavant, les barres de défilement s’affichaient au bas du tableau. Comme le tableau pouvait devenir assez grand, les utilisateurs devaient faire défiler tout le contenu verticalement pour pouvoir le voir.
* Mise à jour du lien vers ObservePoint à partir de l’onglet Outils.

## Corrections de bogues {#section-d9231f5c77254d0888347e5f569a8b1d}

* Correction d’un problème en raison duquel l’onglet Experience Cloud n’était pas mis à jour.

* Correction d’un problème en raison duquel "Media Optimizer" s’affichait dans la ligne Solution de l’onglet Réseau, plutôt que dans le nom actuel "Advertising Cloud".
* Correction d’un problème en raison duquel le débogueur injectait _satellite sur chaque page.

## Version 0.0.803 10 août 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

La version 0.0.803 n’inclut aucune modification destinée aux clients.

## Version 0.0.802 1er août 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Nouvelles fonctionnalités {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Lien Auditeur sur l’onglet Outils </p> </td> 
   <td colname="col2"> <p>Ajout d’un lien vers l’auditeur à partir du débogueur </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Onglets réduits </p> </td> 
   <td colname="col2"> <p>Les onglets réduits persistent dans les onglets Résumé et Outil </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Cliquez pour afficher </p> </td> 
   <td colname="col2"> <p> Ajout d’une fonctionnalité de clic sur affichage à tous les onglets </p> </td> 
  </tr> 
 </tbody> 
</table>

## Améliorations {#section-0e7090e3e6a645f085d4553b983ecff8}

* Nom de Media Optimizer remplacé par Advertising Cloud
* Solutions supprimées de l'onglet Réseau si introuvables

## Corrections de bogues {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Correction d’un problème en raison duquel la fonction "Cliquer sur la cellule pour afficher" n’était pas mise à jour.
* Correction d’un problème en raison duquel les accès AAM n’étaient pas affichés sur l’onglet AAM.

## Version 0.0.798, 14 juin 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Nouvelles fonctionnalités {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Option d’exportation Excel </p> </td> 
   <td colname="col2"> <p>Ajout d’une option d’exportation Excel à l’onglet Réseau. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aspect amélioré </p> </td> 
   <td colname="col2"> <p>Mise à jour de la police de l’extension Chrome vers Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Fonctionnalité de glissement du pavé tactile </p> </td> 
   <td colname="col2"> <p>Désactivation de la fonctionnalité de glissement du pavé tactile avant/arrière. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indicateur d'appel au serveur brut </p> </td> 
   <td colname="col2"> <p>Ajout d’un indicateur indiquant que la chaîne d’appel du serveur brut a été copiée. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Onglet Journaux de nettoyage </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Masquer les solutions dans le filtre de solutions si aucune ligne pour cette solution n’est trouvée dans les journaux </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Masquer le filtre de niveau si aucun appel de la gestion dynamique des balises n’est trouvé, car il s’applique uniquement à la gestion dynamique des balises </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Modifiez les icônes affichées dans la colonne Niveau afin qu’elles ne soient pas cliquables lorsque rien ne se passe lorsque vous cliquez </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Normaliser le formatage de "Afficher le code" sur les éléments de ligne de la gestion dynamique des balises </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mise à jour du lien d’aide dans le pied de page </p> </td> 
   <td colname="col2"> <p>Mettre à jour le lien de l’aide dans le pied de page <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Corrections de bogues {#section-c292cf7dcb17463bb1928de73bd55121}

* Correction d’un problème en raison duquel le numéro de badge n’était pas effacé.
* Correction d’un problème en raison duquel un client signalait des détails de résumé vides.

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Nouvelles fonctionnalités {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Fonction </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox bascule </p> </td> 
   <td colname="col2"> <p>Les bascules de mbox ont été ajoutés à l’onglet Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Les paramètres de filtre restent collants </p> </td> 
   <td colname="col2"> <p>Les paramètres de filtre s’appliquent désormais en haut de l’écran sur le réseau et aux onglets de journalisation. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Affichage et copie des valeurs réseau </p> </td> 
   <td colname="col2"> <p>Vous pouvez afficher les détails et copier la valeur de n’importe quelle cellule dans l’onglet réseau. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Liens de pied de page légaux et copyright </p> </td> 
   <td colname="col2"> <p>Ajout d’un lien de pied de page légal et d’informations de copyright à l’interface utilisateur. </p> </td> 
  </tr> 
 </tbody> 
</table>

