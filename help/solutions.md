---
description: Utilisation des onglets Solution dans Adobe Debugger
keywords: débogueur;Expérience cloud debugger extension;chrome;extension;summary;clear;solutions;solution;information;analytics;target;audience manager;media optimizer;service amo;id
seo-description: Utilisation des onglets Solution dans Adobe Debugger
seo-title: Onglets de solution dans Adobe Debugger
title: Onglets de solution
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Onglets de solution{#solution-tabs}

Cliquez sur les onglets de la solution pour afficher les résultats de solutions Adobe Experience Cloud spécifiques.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

L’onglet Analytics fournit des informations sur votre implémentation [Analytics](https://experiencecloud.adobe.com/resources/help/en_US/reference/) .

**Accès**

Par défaut, tous les appels serveur effectués sur la même suite de rapports sont réduits.

![](assets/analytics-hits.jpg)

**** Télécharger : Téléchargez des informations sur toutes les suites de rapports affichées sous forme de feuille de calcul Excel.

**** Effacer toutes les requêtes : Supprimez toutes les requêtes affichées de la vue Analytics. Une fois les requêtes effacées, les nouvelles requêtes s’affichent lorsqu’elles se produisent.

Cliquez sur l’identifiant de la suite de rapports pour développer la vue :

![](assets/analytics-hits-expand.jpg)

Cet écran affiche toutes les requêtes depuis l’ouverture du débogueur ou leur effacement. Les paramètres par défaut sont automatiquement associés à des noms conviviaux. [Les variables prop et eVar](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) peuvent être associées à vos noms conviviaux personnalisés (par exemple, "prop1" peut s’afficher sous la forme "Type d’utilisateur") si vous vous authentifiez à l’aide de la fonction "Analyses de liens" (voir ci-dessous). Les requêtes sont affichées dans l’ordre de gauche à droite.

**** Télécharger : Enregistrez toutes les requêtes effectuées dans la suite de rapports sous forme de feuille de calcul Excel.

**** Effacer les requêtes : Supprimez toutes les requêtes effectuées dans cette suite de rapports. Les nouvelles requêtes apparaissent au fur et à mesure.

**Comptes liés (hérités)**

Cliquez sur **[!UICONTROL Lier le compte]**, puis entrez les informations demandées pour lier un compte Analytics au débogueur.

>[!NOTE]
>
>Actuellement, cette fonctionnalité n’est prise en charge que pour les informations de connexion héritées d’Analytics.

![](assets/analytics-link-account.jpg)

**Récupérer les accès post-traités**

Activez l’option Récupérer les accès post-traités si vous souhaitez afficher les valeurs des accès Analytics après l’exécution des règles de traitement. Vous devez être connecté à Adobe Experience Cloud pour que cette fonctionnalité fonctionne.

Lorsque cette option est activée, un paramètre de débogage est ajouté à vos requêtes Analytics. Les accès continuent d’être traités comme tout autre accès. Le débogueur sonde l’API de débogage Analytics pour récupérer les valeurs des règles de post-traitement pour tous les accès ayant un identifiant d’accès d’origine. Les accès post-traités ont un arrière-plan violet et s’affichent en regard de l’accès d’origine.

Pour la plupart des implémentations d’Analytics, les informations des règles de post-traitement sont disponibles en quelques minutes. La mise en oeuvre d’Analytics pour Target (A4T) prend beaucoup plus de temps.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Utilisez l’onglet Target pour afficher les requêtes [Target](https://docs.adobe.com/content/help/en/target/using/target-home.html) ou les détails de réponse de suivi de [mbox](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) .

Cliquez sur **[!UICONTROL Demandes]**, puis développez l’environnement pour afficher des informations sur Target.

![](assets/target-requests.jpg)

Cliquez sur **[!UICONTROL Effacer toutes les requêtes]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.

Vous pouvez également utiliser le filtre Target pour [activer le suivi de la mbox à des fins](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)de débogage Target.

Vous devez disposer d’un onglet Chrome ouvert authentifié dans Experience Cloud pour activer le suivi des mbox. Une fois activé, il affiche le nom d’utilisateur de votre ID Adobe. Développez votre nom d’utilisateur pour exposer les codes client Target associés aux organisations Experience Cloud auxquelles vous avez accès. Cliquez sur le code client pour lequel vous souhaitez activer le suivi de mbox et vérifiez que la coche verte apparaît. Toutes les requêtes Target avec des informations de suivi de mbox s’affichent désormais, regroupées par code client. Pour explorer les informations de suivi de mbox, développez la requête afin d’afficher les onglets :

* [Activités](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) L’onglet Activités affiche toutes les activités associées au nom de la demande Target, que vous soyez qualifié pour l’activité ou non. Les "Activités mises en correspondance" sont les activités pour lesquelles vous avez qualifié et dont les offres ont été diffusées dans la réponse. Vous pouvez développer le nom de l’activité pour confirmer l’expérience dans laquelle vous vous trouvez et les audiences et conditions de ciblage qui vous ont qualifié pour l’activité. Les "Activités évaluées" sont toutes les activités évaluées, que vous soyez qualifié ou non. Pour savoir pourquoi vous n’êtes pas admissible pour une activité qui a été "évaluée" mais pas "Correspondante", développez le nom de l’activité et consultez la section "Audiences sans correspondance".

* Demande

   L’onglet de requête du suivi [de](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) mbox est similaire à l’onglet de requête principal. Vous pouvez afficher tous les paramètres transmis par la requête Target, en plus des en-têtes de requête.
* Profil

   Développez la section Instantané de profil pour afficher les informations [de](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) profil stockées sur vous en tant que visiteur dans la base de données de profil Target. Tous les profils internes à la mbox et de script sont présentés ici, ainsi que certains profils système. La colonne État indique les profils modifiés dans le cadre de cette requête, ainsi que leurs valeurs avant et après la saisie de la requête dans le système de profil.
* Audience Manager

   Les sections "segmentIds" et "cachedSegmentIds" de l’onglet Audience Manager exposent les identifiants des [audiences](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) partagées à partir d’Experience Cloud vers Target et pour lesquelles vous avez des qualifications. Il peut s’agir d’audiences créées dans Audience Manager, Analytics ou dans le créateur d’audiences du service principal Personnes. Ces identifiants peuvent être recherchés dans l’interface utilisateur d’Audience Manager pour trouver le nom de l’audience.

La vidéo suivante présente la fonctionnalité générale de Target :

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=fre_fr)

La vidéo suivante présente le suivi des mbox :

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=fre_fr)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Utilisez l’onglet [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) pour afficher les détails des [événements](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html). Cliquez sur l’organisation pour la développer et afficher les informations.

![](assets/audience-manager.jpg)

Cliquez sur **[!UICONTROL Effacer tous les événements]** pour réinitialiser les informations affichées. Les nouveaux événements s’affichent au fur et à mesure.

**Synchronisation des identifiants**

La synchronisation des identifiants est la première étape du processus de transfert des données asynchrones et entrantes. Au cours de cette étape, Audience Manager et le fournisseur comparent les identifiants des visiteurs de leur site respectifs et les font correspondre.

![](assets/aam-idsync.jpg)

Pour plus d’informations, voir Synchronisation des [identifiants pour les transferts](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) de données entrants dans la documentation du produit Audience Manager.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Utilisez l’onglet Advertising Cloud pour afficher les requêtes Advertising Cloud.

Cliquez sur **[!UICONTROL Demandes]**, puis développez l’environnement pour afficher des informations sur Advertising Cloud.

Cliquez sur **[!UICONTROL Effacer toutes les requêtes]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.

## Service Experience Cloud ID {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Utilisez l’onglet Service d’ID d’expérience pour afficher les demandes du service [d’ID d’](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) expérience Cloud.

Cliquez sur **[!UICONTROL Demandes]**, puis développez l’environnement pour afficher des informations sur le service d’ID Experience Cloud.

Cliquez sur **[!UICONTROL Effacer toutes les requêtes]** pour supprimer les requêtes actuellement affichées. D’autres requêtes apparaissent au fur et à mesure.
