---
title: 'Démarrage rapide : Bibliothèque de client Form Recognizer'
titleSuffix: Azure Cognitive Services
description: Utilisez la bibliothèque de client Form Recognizer afin de créer une application de traitement des formulaires qui extrait des paires clé/valeur et des données de table de vos documents personnalisés.
services: cognitive-services
author: PatrickFarley
manager: nitinme
ms.service: cognitive-services
ms.subservice: forms-recognizer
ms.topic: quickstart
ms.date: 09/21/2020
ms.author: pafarley
zone_pivot_groups: programming-languages-set-formre
ms.custom: devx-track-js, devx-track-csharp, cog-serv-seo-aug-2020
keywords: traitement des formulaires, traitement de données automatisé
ms.openlocfilehash: f01adc472f94d679366af50c136ddc020b79b811
ms.sourcegitcommit: 02ed9acd4390b86c8432cad29075e2204f6b1bc3
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/29/2020
ms.locfileid: "97808570"
---
# <a name="quickstart-use-the-form-recognizer-client-library"></a>Démarrage rapide : Utiliser la bibliothèque de client Form Recognizer

Découvrez comment bien démarrer avec Form Recognizer dans le langage de votre choix. Azure Form Recognizer est un service cognitif qui vous permet de créer des logiciels de traitement de données automatisé à l’aide des technologies du Machine Learning. Identifiez et extrayez du texte, des paires clé/valeur et des données de table de vos formulaires : le service génère des données structurées qui incluent les relations dans le fichier d’origine. Suivez les étapes suivantes pour installer le package du SDK et essayer l’exemple de code pour les tâches de base. La bibliothèque de client Form Recognizer cible actuellement la version 2.0 du service Form Recognizer.

La bibliothèque de client Form Recognizer vous permet de :

* [Reconnaître le contenu d’un formulaire](#recognize-form-content)
* [Reconnaître les tickets de caisse](#recognize-receipts)
* [Reconnaître les cartes de visite](#recognize-business-cards)
* [Reconnaître les factures](#recognize-invoices)
* [Entraîner un modèle personnalisé](#train-a-custom-model)
* [Analyser les formulaires avec un modèle personnalisé](#analyze-forms-with-a-custom-model)
* [Gérer vos connecteurs personnalisés](#manage-your-custom-models)

::: zone pivot="programming-language-csharp"

[!INCLUDE [C# SDK quickstart](../includes/quickstarts/csharp-sdk.md)]

::: zone-end

::: zone pivot="programming-language-java"

[!INCLUDE [Java SDK quickstart](../includes/quickstarts/java-sdk.md)]

::: zone-end

::: zone pivot="programming-language-javascript"

[!INCLUDE [NodeJS SDK quickstart](../includes/quickstarts/javascript-sdk.md)]

::: zone-end

::: zone pivot="programming-language-python"

[!INCLUDE [Python SDK quickstart](../includes/quickstarts/python-sdk.md)]

::: zone-end

::: zone pivot="programming-language-rest-api"

[!INCLUDE [REST API quickstart](../includes/quickstarts/rest-api.md)]

::: zone-end