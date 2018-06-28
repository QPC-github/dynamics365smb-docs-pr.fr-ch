---
title: "Détails de conception - Périodes inventaire | Microsoft Docs"
description: "Des transactions antidatées ou des ajustement des coûts affectent souvent les soldes et les évaluations du stock pour des périodes comptables qui peuvent être considérées comme clôturées. Ceci peut avoir des effets négatifs sur la précision des rapports, notamment dans des sociétés internationales. La fonction Périodes inventaire permet d'éviter ces problèmes en ouvrant ou en clôturant des périodes d'inventaire pour limiter la validation dans une période définie."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 99aa0cacdbe6933c5ba16443297d1838b8bfd3ac
ms.contentlocale: fr-ch
ms.lasthandoff: 03/22/2018

---
# <a name="design-details-inventory-periods"></a>Détails de conception : périodes inventaire
Des transactions antidatées ou des ajustement des coûts affectent souvent les soldes et les évaluations du stock pour des périodes comptables qui peuvent être considérées comme clôturées. Ceci peut avoir des effets négatifs sur la précision des rapports, notamment dans des sociétés internationales. La fonction Périodes inventaire permet d'éviter ces problèmes en ouvrant ou en clôturant des périodes d'inventaire pour limiter la validation dans une période définie.  

 Une période inventaire est une période, définie par une date de fin, pendant laquelle vous validez des mouvements de stock. Lorsque vous fermez une période d'inventaire, aucun changement de valeur ne peut être validé dans la période clôturée. Cela inclut de nouvelles validations de valeur, des validations prévues ou facturées, des modifications sur les valeurs existantes et des ajustements de coûts. Cependant, vous pouvez toujours lettrer une écriture comptable article ouverte qui se trouve dans la période clôturée. Pour plus d'informations, voir [Détails de conception : traçabilité](design-details-item-application.md).  

 Pour s'assurer que toutes les écritures de transaction dans une période clôturée sont finales, les conditions suivantes doivent être remplies avant qu'une période d'inventaire ne soit fermée :  

-   Toutes les écritures comptables article sortantes de la période doivent être fermées (aucun stock négatif).  
-   Tous les coûts des articles pour la période doivent être ajustés.  
-   Tous les ordres de fabrication lancés et terminés dans la période doivent faire l'objet d'un ajustement des coûts.  

 Lorsque vous fermez une période inventaire, une écriture période d'inventaire est créée à l'aide du numéro du dernier enregistrement article tombant dans la période d'inventaire. En outre, le délai, la date et le code utilisateur de l'utilisateur clôturant la période sont enregistrés dans l'écriture période inventaire. À l'aide des informations associée au dernier historique article de la période précédente, vous pouvez visualiser les mouvements de stock qui ont été validés pour la période inventaire. Il est également possible de rouvrir des périodes inventaire si vous devez valider dans une période clôturée. Lorsque vous rouvrez une période inventaire, une écriture période inventaire est créée.  

## <a name="see-also"></a>Voir aussi  
 [Détails de conception : Coûts ajustés](design-details-inventory-costing.md) [Gestion des coûts ajustés](finance-manage-inventory-costs.md) [Finance](finance.md)  
 [Utilisation de Financials](ui-work-product.md)
