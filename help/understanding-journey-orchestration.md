---
title: Comprendre le Journey Orchestration
description: Comprendre le concept de Journey Orchestration, les types de cas d'utilisation qu'il permet et les éléments clés du fonctionnement du Journey Orchestration.
feature: Journey Orchestration
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: dafd8b529ec4326dd04fcf4ad766b0856cb3cfcc
workflow-type: tm+mt
source-wordcount: '342'
ht-degree: 0%

---


# Compréhension du [!UICONTROL Journey Orchestration]

## Présentation du [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] vous permet de créer des cas d’utilisation d’orchestration en temps réel en exploitant des données contextuelles stockées dans des événements ou des sources de données.

[!UICONTROL Journey Orchestration] est un service d&#39;application intégré à l&#39;Adobe Experience Platform. Il fournit un écosystème intelligent et ouvert pour activer toutes les données actives pertinentes grâce à un engagement évolutif et basé sur le événement dans tous les canaux dont votre entreprise a besoin, du marketing aux opérations en passant par le service. [!UICONTROL Le Journey Orchestration] peut exploiter n’importe quelle donnée de l’Adobe Experience Platform et de tout système de diffusion externe pour créer et diffuser des expériences fascinantes.

La vidéo ci-dessous présente :

* Le concept de [!UICONTROL Journey Orchestration]
* Types de cas d&#39;utilisation qu&#39;il active
* Les éléments clés du fonctionnement du [!UICONTROL Journey Orchestration]

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Comment configurer un voyage

Les principales étapes de préparation des voyages sont les suivantes :

1. [Configuration des Événements](/help/configuring-journey-orchestration/configure-streaming-events.md) de diffusion en continu - Cette configuration est obligatoire, car le [!UICONTROL Journey Orchestration] est conçu pour écouter les événements.
1. [Configurer les sources](/help/configuring-journey-orchestration/configure-data-sources.md) de données : cette configuration n&#39;est pas requise si vos voyages utilisent uniquement les données locales provenant d&#39;une charge utile de événement.
1. [Configurer des actions](/help/configuring-journey-orchestration/configure-actions.md)personnalisées : Obligatoire si vous souhaitez utiliser un service de n’importe quel fournisseur tiers qui peut être appelé par le biais d’une [!DNL REST API] charge utile au format JSON.

>[!NOTE]
>
>Ces étapes de configuration nécessitent des connaissances techniques. Vous devez connaître le modèle de données d’ [expérience (XDM)](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) et [comment composer des schémas](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html)de événement d’expérience XDM.

## Création, publication et analyse d’un parcours

1. [Créer un voyage](/help/create-a-journey.md)
1. [Validation et publication d’un voyage](/help/validate-and-publish-a-journey.md)
1. [Analyser un parcours au moyen d&#39;outils de rapports](/help/analyze-a-journey-via-reporting-tools.md)

## Autres ressources

* [Centre d’aide Journey Orchestration](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Didacticiels sur l’Adobe Experience Platform](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Comment trouver de l&#39;aide avec le Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Lancement](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform Location Service](https://docs.adobe.com/content/help/en/places/using/home.html)
