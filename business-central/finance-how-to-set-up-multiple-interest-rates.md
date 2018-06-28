---
title: "Comment paramétrer plusieurs taux d'intérêt"
description: "Vous pouvez calculer les intérêts avec plusieurs taux d'intérêts pour une période donnée. Le calcul des intérêts ressemble à tous les intérêts financiers, avec une variation uniquement du taux d'intérêt pour une période donnée."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 12/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 0af01fe46f6b7df1149825c35a9fc0cc19482403
ms.contentlocale: fr-ch
ms.lasthandoff: 03/22/2018

---
# <a name="set-up-multiple-interest-rates"></a>Paramétrer plusieurs taux d'intérêt
Plusieurs taux d'intérêt multiples sont utilisés pour différentes périodes pour les paiements retardés dans les transactions commerciales. Par exemple, un gouvernement définit l'intérêt maximum à prélever pour un consommateur. Ce taux d'intérêt peut être modifié deux fois par an le 1er janvier et le 1er juillet inclus. Le taux d'intérêt entre les sociétés (B2B) est accepté par les parties et il n'existe aucune limite à ce groupe de clients. Le taux annoncé est généralement quatre fois supérieur aux intérêts bancaires normaux.

Lorsque vous créez des conditions d'intérêts de retard et les conditions de relance, pour la pénalité de retard de paiement, vous pouvez spécifier plusieurs taux d'intérêt afin que les frais de pénalité soient calculés sur la base de plusieurs taux d'intérêt à différentes périodes. Pour plus d'informations, voir [Collecte des soldes restants](receivables-collect-outstanding-balances.md).

## <a name="to-set-up-multiple-interest-rates"></a>Pour paramétrer plusieurs taux d'intérêt  
1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Conditions intérêts de retard**, puis sélectionnez le lien connexe.  
2.  Sur la fenêtre **Conditions intérêts de retard**, sélectionnez les conditions d'intérêt, puis sélectionnez l'action **Taux d'intérêt**.  
3.  Renseignez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  Cliquez sur le bouton **OK**.  
5.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Conditions de relance**, puis sélectionnez le lien connexe.  
6.  Sur la fenêtre **Conditions de relance**, sélectionnez les conditions de relance, puis sélectionnez l'action **Niveaux**.  
7.  Sur la fenêtre **Niveaux relance**, sélectionnez le champ **Calculer intérêts**.  

Lorsque vous émettez une facture d'intérêts, a facture affiche les frais financiers avec plusieurs taux d'intérêt pour une période donnée. La facture affiche également les informations contact du client, de la société émettant la facture, du montant supplémentaire, et du montant total. L'écriture ouverture sur la facture est affichée en gras. Les intérêts sont calculés avec plusieurs taux d'intérêt pour une période spécifique et sont imprimés après l'écriture ouverture de la facture.  

## <a name="see-also"></a>Voir aussi  
[Collecte des soldes restants](receivables-collect-outstanding-balances.md)  
[Configuration de Finance](finance-setup-finance.md)
