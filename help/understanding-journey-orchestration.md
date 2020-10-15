---
title: Présentation de Journey Orchestration
description: Découvrez le concept de Journey Orchestration, les types de cas d’utilisation proposés et les éléments essentiels du fonctionnement de ce service.
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
ht-degree: 100%

---


# Présentation de [!UICONTROL Journey Orchestration]

## Vue d’ensemble de [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] permet de créer des cas d’utilisation d’orchestration en temps réel à l’aide de données contextuelles stockées dans des événements ou des sources de données.

[!UICONTROL Journey Orchestration] est un service d’application intégré avec Adobe Experience Platform. Il offre un écosystème intelligent et ouvert pour activer toutes les données actives pertinentes grâce à un engagement évolutif et basé sur les événements à travers tous les canaux dont votre entreprise a besoin, depuis le marketing jusqu’aux opérations, en passant par le service. [!UICONTROL Journey Orchestration] peut utiliser n’importe quelle donnée d’Adobe Experience Platform et n’importe quel système de diffusion externe pour créer et diffuser des expériences attrayantes.

La vidéo ci-dessous présente :

* le concept de [!UICONTROL Journey Orchestration] ;
* les types de cas d’utilisation proposés ;
* les éléments essentiels du fonctionnement de [!UICONTROL Journey Orchestration].

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## Configuration d’un parcours

Les principales étapes de préparation à la création de parcours sont les suivantes :

1. [Configuration des événements de diffusion en continu](/help/configuring-journey-orchestration/configure-streaming-events.md) : cette configuration est obligatoire, car [!UICONTROL Journey Orchestration] est conçu pour écouter les événements.
1. [Configuration des sources de données](/help/configuring-journey-orchestration/configure-data-sources.md) : cette configuration n’est pas obligatoire si les parcours utilisent uniquement des données locales provenant d’une payload d’événement.
1. [Configuration des actions personnalisées](/help/configuring-journey-orchestration/configure-actions.md) : cette configuration est obligatoire si vous souhaitez utiliser un service d’un fournisseur tiers qui peut être appelé par le biais d’une [!DNL REST API] avec une payload au format JSON.

>[!NOTE]
>
>Ces étapes de configuration nécessitent des connaissances techniques. Vous devez connaître le [modèle XDM](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) et savoir [comment composer des schémas d’événement d’expérience XDM](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Création, publication et analyse d’un parcours

1. [Création d’un parcours](/help/create-a-journey.md)
1. [Validation et publication d’un parcours](/help/validate-and-publish-a-journey.md)
1. [Analyse d’un parcours au moyen d’outils de reporting](/help/analyze-a-journey-via-reporting-tools.md)

## Autres ressources

* [Centre d’aide de Journey Orchestration](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html)
* [Tutoriels Adobe Experience Platform](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [Accès à l’aide de Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK mobile Adobe Experience Platform - Launch](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform Location Service](https://docs.adobe.com/content/help/fr-FR/places/using/home.html)
