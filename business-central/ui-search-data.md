---
title: Recherche de données spécifiques
description: Vous pouvez utiliser la recherche si vous avez besoin de trouver un enregistrement spécifique.
author: brentholtorf
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: data, search, record
ms.search.form: ''
ms.date: 09/20/2022
ms.author: bholtorf
ms.openlocfilehash: a97668a12b6571b11b21a56f0737a8aea9387b01
ms.sourcegitcommit: 8ad79e0ec6e625796af298f756a142624f514cf3
ms.translationtype: HT
ms.contentlocale: fr-CH
ms.lasthandoff: 09/30/2022
ms.locfileid: "9608308"
---
# <a name="search-for-a-record-in-your-data"></a>Rechercher un enregistrement dans vos données

Lorsque vous souhaitez rechercher un enregistrement ou une valeur en particulier, utilisez la fonctionnalité **Rechercher des données**. Lancez une recherche sur votre tableau de bord des manières suivantes :

* Utiliser l’action **Rechercher des données**
* Utilisez la combinaison de touches de raccourci Ctrl+Alt+F.

## <a name="how-search-works"></a>Fonctionnement de la recherche

Après avoir entré vos mots-clés, [!INCLUDE[prod_short](includes/prod_short.md)] lance votre recherche en arrière-plan et parcourt chaque table à la fois. Les résultats de la recherche commencent à apparaître après avoir terminé chaque table. 

Si vous entrez plus d’un mot-clé, les résultats n’incluront que les enregistrements contenant tous les mots dans l’un des champs sélectionnés.

La page de résultats affiche les trois derniers enregistrements mis à jour. S’il y en a plus de trois, vous pouvez choisir **Afficher tout** pour les afficher.

Chaque fois que vous choisissez un résultat de recherche, vous augmentez la popularité de la table et elle apparaîtra plus haut dans les résultats. De plus, l’enregistrement sera trouvé plus rapidement si vous le recherchez ultérieurement.

> [!NOTE]
> Les en-têtes des documents de vente, d’achat et de service représentent en fait différents types de documents, tels que les devis, les factures et les commandes. Les en-têtes sont traités comme s’il s’agissait de tables. Si votre mot-clé a été trouvé dans une ligne sur l’un de ces documents, lorsque vous choisissez le résultat de la recherche, la page du document s’affiche, et pas seulement la ligne.

## <a name="getting-started"></a>Mise en route

Vous pouvez accélérer les résultats en choisissant les champs des tables que vous souhaitez inclure dans vos recherches. Les tables et les champs parmi lesquels vous pouvez choisir varient en fonction de votre tableau de bord. Par défaut, toutes les tables et tous les champs sont choisis, ce qui peut ralentir la recherche. Nous vous recommandons d’exclure autant de tables et de champs que possible.

## <a name="see-also"></a>Voir aussi

[Recherche de pages et d’informations avec Tell Me](ui-search.md)  
[Saisie de données](ui-enter-data.md)  