---
description: Utilisation des onglets Solution dans Adobe Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;récapitulatif;effacer;solutions;solution;information;analytics;target;audience manager;media optimizer;service amo;service d’identification
seo-description: Utilisation des onglets Solution dans Adobe Debugger
seo-title: Onglets Solution dans Adobe Debugger
title: Onglets Solution
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '1085'
ht-degree: 100%

---


# Onglets Solution {#solution-tabs}

Cliquez sur les onglets Solution pour afficher les résultats de solutions Adobe Experience Cloud spécifiques.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

L’onglet Analytics fournit des informations sur votre implémentation d’[Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html).

**Accès**

Par défaut, tous les appels de serveur effectués sur la même suite de rapports sont réduits.

![](assets/analytics-hits.jpg)

**Télécharger :** téléchargez des informations sur toutes les suites de rapports affichées en tant que feuille de calcul Excel.

**Effacer toutes les requêtes :** supprimez toutes les requêtes affichées depuis la vue Analytics. Une fois les requêtes effacées, de nouvelles requêtes s’affichent lorsqu’elles se produisent.

Cliquez sur l’identifiant de la suite de rapports pour développer la vue :

![](assets/analytics-hits-expand.jpg)

Cet écran affiche toutes les requêtes depuis l’ouverture d’Adobe Experience Platform Debugger ou leur effacement. Les paramètres par défaut sont automatiquement mappés à des noms conviviaux. Les variables [prop et eVar](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/vars/page-vars/evar.html) peuvent être mappées à vos noms conviviaux personnalisés (par exemple, « prop1 » peut s’afficher en tant que « Type d’utilisateur ») si vous vous authentifiez à l’aide de la fonction « Lier Analytics » (voir ci-dessous). Les requêtes sont affichées de manière séquentielle de gauche à droite.

**Télécharger :** enregistrez toutes les requêtes adressées à la suite de rapports en tant que feuille de calcul Excel.

**Effacer les requêtes :** supprimez toutes les requêtes adressées à cette suite de rapports. De nouvelles requêtes apparaissent au fur et à mesure.

**Comptes liés (hérités)**

Cliquez sur **[!UICONTROL Link Account]**, puis entrez les informations demandées pour lier un compte Analytics à Platform Debugger.

>[!NOTE]
>
>Actuellement, cette fonctionnalité n’est prise en charge que pour les informations de connexion héritées d’un utilisateur Analytics.

![](assets/analytics-link-account.jpg)

**Récupérer les accès après traitement**

Activez l’option Récupérer les accès après traitement si vous souhaitez afficher les valeurs sur les accès à Analytics après l’exécution des règles de traitement. Vous devez être connecté à Adobe Experience Cloud pour que cette fonctionnalité fonctionne.

Lorsque cette option est activée, un paramètre de débogage est ajouté à vos requêtes Analytics. Les accès continuent d’être traités comme tout autre accès. Platform Debugger interroge l’API de débogage Analytics pour récupérer les valeurs des règles après traitement pour tous les accès ayant un identifiant d’accès d’origine. Les accès après traitement ont un arrière-plan violet et s’affichent en regard de l’accès d’origine.

Pour la plupart des mises en œuvre d’Analytics, les informations des règles après traitement sont disponibles en quelques minutes. La mise en œuvre d’Analytics pour Target (A4T) prend beaucoup plus de temps.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Utilisez l’onglet Target pour afficher les requêtes [Target](https://docs.adobe.com/content/help/fr-FR/target/using/target-home.html) ou les détails de réponse de suivi de [mbox Trace](https://docs.adobe.com/content/help/fr-FR/target/using/activities/troubleshoot-activities/content-trouble.html).

Cliquez sur **[!UICONTROL Requests]**, puis développez l’environnement pour afficher des informations sur Target.

![](assets/target-requests.jpg)

Cliquez sur **[!UICONTROL Clear All Requests]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.

Vous pouvez également utiliser le filtre Target pour [activer mbox Trace à des fins de débogage de Target](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html).

Vous devez disposer d’un onglet Chrome ouvert authentifié dans Experience Cloud pour activer mbox Trace. Une fois activé, il affiche le nom d’utilisateur de votre Adobe ID. Développez votre nom d’utilisateur pour exposer les codes client Target associés aux organisations Experience Cloud auxquelles vous avez accès. Cliquez sur le code client pour lequel vous souhaitez activer mbox Trace et vérifiez que la coche verte apparaît. Toutes les requêtes Target contenant des informations mbox Trace s’affichent désormais, regroupées par code client. Pour explorer les informations mbox Trace, développez la requête afin d’afficher les onglets :

* [Activités](https://docs.adobe.com/content/help/fr-FR/target/using/activities/activities.html) L’onglet Activités affiche toutes les activités associées au nom de la demande Target, que vous soyez qualifié pour l’activité ou non. Les « Activités mises en correspondance » sont les activités pour lesquelles vous êtes qualifié et dont les offres ont été fournies dans la réponse. Vous pouvez développer le nom de l’activité pour confirmer l’expérience dans laquelle vous vous trouvez, ainsi que les conditions d’audience et de ciblage qui vous ont permis de vous qualifier pour l’activité. Les « Activités évaluées » sont toutes les activités évaluées, que vous soyez qualifié ou non. Pour savoir pourquoi vous n’êtes pas qualifié pour une activité qui a été « évaluée », mais pas « mise en correspondance », développez le nom de l’activité et consultez la section « Audiences non correspondantes ».

* Requête

   L’onglet Requête de suivi de [mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) est similaire à l’onglet de requête principal. Vous pouvez afficher tous les paramètres transmis par la requête Target, en plus des en-têtes de la requête.
* Profil

   Développez la section Instantané de profil pour afficher les [informations de profil](https://docs.adobe.com/content/help/fr-FR/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) stockées qui vous concernent en tant que visiteur dans la base de données de profil de Target. Tous les profils internes à la mbox et de script sont présentés ici, ainsi que certains profils système. La colonne Statut indique les profils modifiés dans le cadre de cette requête, ainsi que leurs valeurs avant et après la saisie de la requête dans le système de profil.
* Audience Manager

   Les sections « segmentIds » et « cachedSegmentIds » de l’onglet Audience Manager présentent les identifiants des [audiences](https://docs.adobe.com/content/help/fr-FR/target/using/audiences/target.html) partagées à partir d’Experience Cloud vers Target et pour lesquelles vous êtes qualifié. Il peut s’agir d’audiences créées dans Audience Manager, Analytics ou dans le créateur d’audience du service clé People. Ces identifiants peuvent être recherchés dans l’interface utilisateur d’Audience Manager afin de trouver le nom de l’audience.

La vidéo suivante présente la fonctionnalité générale de Target :

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)

La vidéo suivante présente mbox Trace :

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Utilisez l’onglet [Audience Manager](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/aam-home.html) pour afficher les détails des [événements](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/api-and-sdk-code/dcs/dcs-event-calls/dcs-event-calls.html). Cliquez sur l’organisation pour la développer et afficher les informations.

![](assets/audience-manager.jpg)

Cliquez sur **[!UICONTROL Clear All Events]** pour réinitialiser les informations affichées. Les nouveaux événements apparaissent au fur et à mesure.

**Synchronisation des identifiants**

La synchronisation des identifiants est la première étape du processus de transfert des données asynchrones et entrantes. Au cours de cette étape, Audience Manager et le fournisseur comparent les identifiants des visiteurs de leur site respectifs et les font correspondre.

![](assets/aam-idsync.jpg)

Pour plus d’informations, voir [Synchronisation des identifiants pour les transferts de données entrants](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/id-sync-http.html) dans la documentation du produit Audience Manager.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Utilisez l’onglet Advertising Cloud pour afficher les requêtes Advertising Cloud.

Cliquez sur **[!UICONTROL Requests]**, puis développez l’environnement pour afficher des informations sur Advertising Cloud.

Cliquez sur **[!UICONTROL Clear All Requests]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.

## Service Experience Cloud ID {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Utilisez l’onglet Service Experience Cloud ID pour afficher les requêtes du [service Experience Cloud ID](https://docs.adobe.com/content/help/fr-FR/id-service/using/home.html).

Cliquez sur **[!UICONTROL Requests]**, puis développez l’environnement pour afficher des informations sur le service Experience Cloud ID.

Cliquez sur **[!UICONTROL Clear All Requests]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.
