---
title: Comment bloquer les ventes aux articles clients depuis les ventes ou les achats
description: "Dans Business Central, un article peut être signalé comme bloqué pour la vente, bloqué pour l'achat ou bloqué dans tous les cas."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/01/2018
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 9dbd92409ba02281f008246194f3ce0c53e4e001
ms.openlocfilehash: 268d098318b77cb89a369e8edc14729a44bedae6
ms.contentlocale: fr-ch
ms.lasthandoff: 09/28/2018

---
# <a name="block-customers"></a>Bloquer des clients
Vous pouvez bloquer un client, par exemple à cause de son insolvabilité, afin que le client ne puisse pas être ajouté aux documents vente ou afin d'empêcher que d'autres transactions soient validées pour ce client.

En plus de bloquer un client, vous pouvez définir des transactions Comptabilité client pour le client soit en attente en association avec les relances. Pour plus d'informations, voir [Collecte des soldes restants](receivables-collect-outstanding-balances.md).   

Le tableau suivant décrit les différentes options de blocage.  

|Option|Désignation|  
|--------------------|------------|  
|**Vide**|Les transactions sont autorisés pour ce client.|
|**Expédier**|Vous ne pouvez pas créer des commandes et des expéditions pour ce client. Vous pouvez facturer les expéditions existantes qui ne l'ont pas encore été.|  
|**Facture**|Vous ne pouvez pas créer de commandes, d'expéditions ni de factures pour ce client. Vous ne pouvez pas facturer les expéditions existantes qui ne l'ont pas encore été.|  
|**Tous**|Ce client n'est autorisé à effectuer aucune transaction, pas même un paiement.|  

## <a name="to-block-a-customer"></a>Pour bloquer un client  
1. Choisissez l'icône ![Ampoule qui ouvre la fonction Tell Me](media/ui-search/search_small.png "Dites-moi ce que vous voulez faire"), saisissez **Clients**, puis sélectionnez le lien associé.
2. Sélectionnez un client, puis cliquez sur **Modifier**.
3. Renseignez le champ **Bloqué** avec l'une des options décrites ci-dessus.

## <a name="see-also"></a>Voir aussi  
[Enregistrer de nouveaux clients](sales-how-register-new-customers.md)  
[Collecte des soldes restants](receivables-collect-outstanding-balances.md)  
[Gestion des comptes client](receivables-manage-receivables.md)  
