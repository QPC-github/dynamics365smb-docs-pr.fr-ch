---
title: "Comment répartir des lignes activité entrepôt | Microsoft Docs"
description: "Dans le cadre de rangements, mouvements ou prélèvements entrepôt et de rangements et prélèvements stock, des emplacements sont proposés pour le prélèvement et le rangement des articles . Il arrive parfois que la quantité réelle disponible dans l'emplacement soit insuffisante ou que l'espace de l'emplacement proposé soit insuffisant pour le rangement de la quantité nécessaire. Dans ces cas, vous devez répartir la ligne de telle sorte que les articles d'une ligne soient prélevés ou placés dans plusieurs emplacements."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2c13559bb3dc44cdb61697f5135c5b931e34d2a8
ms.openlocfilehash: a3a78c0622698975119cb64007cee9fb40db9f1b
ms.contentlocale: fr-ch
ms.lasthandoff: 09/22/2017

---
# <a name="how-to-split-warehouse-activity-lines"></a>Comment éclater des lignes activité entrepôt
Dans le cadre de rangements, mouvements ou prélèvements entrepôt et de rangements et prélèvements stock, des emplacements sont proposés pour le prélèvement et le rangement des articles . Il arrive parfois que la quantité réelle disponible dans l'emplacement soit insuffisante ou que l'espace de l'emplacement proposé soit insuffisant pour le rangement de la quantité nécessaire. Dans ces cas, vous devez répartir la ligne de telle sorte que les articles d'une ligne soient prélevés ou placés dans plusieurs emplacements.  

La procédure suivante s'applique aux documents entrepôt, à savoir les lignes de rangement, de mouvement et de prélèvement entrepôt, ainsi que les lignes de rangement, de mouvement et de prélèvement stock.  

## <a name="to-split-warehouse-activity-lines"></a>Pour éclater des lignes activité entrepôt  
1.  Ouvrez une ligne activité entrepôt dans laquelle vous tentez de traiter une quantité insuffisante.  
2.  Dans le champ **Quantité à traiter**, entrez la quantité réduite que vous pouvez gérer.  
3.  Sur le raccourci **Lignes**, choisissez l'action **Actions**, choisissez **Fonctions**, puis choisissez l'action **Eclater ligne**. Une nouvelle ligne s'affiche. Il s'agit d'une copie de la ligne d'origine, à la différence près que la quantité que vous avez retirée de la ligne d'origine figure dans le champ **Quantité à traiter**.  
4.  Affectez à cette nouvelle ligne un emplacement approprié, ainsi qu'une zone en cas d'utilisation d'un prélèvement et d'un rangement suggérés, ou continuez à répartir la ligne autant de fois que nécessaire jusqu'à ce que vous ayez trouvé des emplacements appropriés pour toute la quantité.  

> [!NOTE]  
>  Si, en cas d'utilisation d'un prélèvement et d'un rangement suggérés dans l'entrepôt, vous répartissez les lignes, vous devez bien connaître l'entrepôt et être capable de choisir un emplacement répondant aux conditions de stockage de l'article et aux exigences générales du document entrepôt. Par exemple, vous n'allez pas répartir une ligne d'un document prélèvement et placer certains articles au niveau du stockage en vrac.  

## <a name="see-also"></a>Voir aussi  
[Gestion d'entrepôt](warehouse-manage-warehouse.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)     
[Gestion des assemblages](assembly-assemble-items.md)    
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
