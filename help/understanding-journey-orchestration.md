---
title: Présentation de Journey Orchestration
description: Explorez le concept de Journey Orchestration, les types d’utilisation possibles et les éléments clés de son fonctionnement.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 100%

---

# Présentation de [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] permet de créer des cas d’utilisation d’orchestration en temps réel à l’aide de données contextuelles stockées dans des événements ou des sources de données.

## Vue d’ensemble de [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] est un service applicatif intégré à Adobe Experience Platform. Il offre un écosystème intelligent et ouvert pour activer toutes les données actives pertinentes grâce à un engagement évolutif et basé sur les événements à travers tous les canaux dont votre entreprise a besoin, depuis le marketing jusqu’aux opérations, en passant par le service. [!UICONTROL Journey Orchestration] peut utiliser toutes les données d’Adobe Experience Platform et n’importe quel système de diffusion externe pour créer et diffuser des expériences attrayantes.

La vidéo ci-dessous présente :

* le concept de [!UICONTROL Journey Orchestration] ;
* les types de cas d’utilisation proposés ;
* les éléments essentiels du fonctionnement de [!UICONTROL Journey Orchestration].

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## Configuration d’un parcours

Les principales étapes de préparation à la création de parcours sont les suivantes :

1. [Configuration des événements de diffusion en continu](/help/configuring-journey-orchestration/configure-streaming-events.md) : cette configuration est obligatoire, car [!UICONTROL Journey Orchestration] est conçu pour écouter les événements.
1. [Configuration des sources de données](/help/configuring-journey-orchestration/configure-data-sources.md) : cette configuration n’est pas obligatoire si les parcours utilisent uniquement des données locales provenant d’une payload d’événement.
1. [Configuration des actions personnalisées](/help/configuring-journey-orchestration/configure-actions.md) : cette configuration est obligatoire si vous souhaitez utiliser un service d’un fournisseur tiers qui peut être contacté via une [!DNL REST API] avec une payload au format JSON.

>[!NOTE]
>
>Ces étapes de configuration nécessitent des connaissances techniques. Vous devez connaître le [Modèle de données d’expérience (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=fr) et savoir [comment composer des schémas d’événement d’expérience XDM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=fr).

## Création, publication et analyse d’un parcours

1. [Créer un parcours](/help/building-a-journey/creating-a-journey.md)
1. [Valider et publier un parcours](/help/validate-and-publish-a-journey.md)
1. [Analyser un parcours au moyen d’outils de reporting](/help/analyze-a-journey-via-reporting-tools.md)

## Ressources supplémentaires

* [Centre d’aide de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr)
* [Tutoriels Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=fr)
* [Accès à l’aide de Journey Orchestration](/help/understanding-journey-orchestration.md)
* [SDK mobile Adobe Experience Platform - Launch](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=fr)
* [Adobe Experience Platform Location Service](https://experienceleague.adobe.com/docs/places/using/home.html?lang=fr)
