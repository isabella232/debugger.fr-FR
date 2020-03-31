---
description: Debugger examine vos pages web et vous aide à résoudre les problèmes liés à la mise en œuvre des solutions Experience Cloud.
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Documentation technique pour l’extension Adobe Experience Cloud Debugger 2.0 pour Chrome et Firefox - examiner vos pages web et comprendre les problèmes liés aux mises en œuvre de solutions Experience Cloud.
seo-title: Adobe Experience Platform Debugger Chrome et Firefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: dc723f0848c56794e9a1a6eda405de2f4ea6b8fa

---


# (Bêta) Débogueur Adobe Experience Platform 2.0 {#adobe-experience-platform-debugger}

> [!IMPORTANT]
>
> Adobe Experience Cloud Debugger 2.0 est actuellement en version bêta. La documentation et la fonctionnalité peuvent changer.

The [Adobe Experience Platform Debugger for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

Utilisez le débogueur Adobe Experience Platform avec les autres solutions de Adobe  pour un flux de travaux du type suivant :

1. Utilisez [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) ou [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) pour insérer du code qui active les solutions [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) sur vos pages.

1. Utilisez [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) pour tester vos mises en œuvre.
1. Utilisez le débogueur Adobe Experience Platform pour déboguer les problèmes détectés par le vérificateur ou pour examiner d’autres informations sur vos implémentations.

Les étapes ci-dessus ne sont pas nécessairement effectuées dans cet ordre, mais il s’agit d’un processus courant.

Bien que vous puissiez exécuter Debugger sur n’importe quelle page web, toutes les données non publiques ne sont disponibles dans l’extension qu’à condition d’être authentifié dans Experience Cloud dans l’un de vos onglets Chrome ouverts.

## Cas d’utilisation {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Utilisez Debugger pour recueillir des informations qui vous aident à comprendre comment vos solutions Experience Cloud sont mises en œuvre. Par exemple :

* **Lancement :** déterminer la propriété,   de, à générer qui sont déployées sur une page ;
* **Target :** découvrez les activités pour lesquelles vous remplissez les critères ou non, et pourquoi.
