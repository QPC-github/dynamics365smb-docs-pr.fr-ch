---
title: "Comptes généraux, Suisse"
description: "Les améliorations suisses comprennent des fonctions spéciales liées aux comptes généraux."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 96ab1080c5417ce1fc7721730963559cf7e90514
ms.contentlocale: fr-ch
ms.lasthandoff: 03/22/2018

---
# <a name="swiss-general-ledger-accounts"></a>Comptes généraux, Suisse
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] inclut les améliorations suisses apportées aux fonctions spéciales liées aux comptes généraux.

- Conserver les soldes en devises d'un compte bancaire dans les comptes généraux.  
- Trier les numéros de comptes généraux dans la fenêtre **Plan comptable**.  
- Prévisualiser les effets que la validation des feuilles comptabilité auraient sur les soldes de certains comptes généraux avant leur validation réelle.  

## <a name="general-ledger-accounts-and-general-journals"></a>Comptes généraux et feuilles comptabilité  
Les entreprises ont souvent des comptes bancaires différents pour les devises étrangères et disposent d'un compte général pour chaque compte bancaire. Dans [!INCLUDE[d365fin](../../includes/d365fin_md.md)], vous pouvez définir un code devise et les informations de solde en devise étrangère dans la fenêtre **Plan comptable**. Cela vous permet de conserver le solde de départ en devises d'un compte bancaire. Pour plus d'informations, voir [Fenêtre Plan comptable](assetId:///fa407624-b670-44b6-8397-91aa606e4c39) et [Table Compte général](assetId:///a65c2b09-9bb2-43db-8c53-c047bfc49777).  

Par exemple, une société a deux comptes bancaires : une pour la devise société (DS) et une pour les euros (EUR). Vous devez créer des écritures comptables pour chaque compte bancaire. Pour le compte en euros, définissez le code devise **EUR** et validez les feuilles en EUR ou DS.  

Lorsque le taux de change pour EUR et DS change, vous pouvez mettre à jour et ajuster le solde de la devise locale pour le grand livre EUR à l'aide du traitement par lots Ajuster taux de change. Ce traitement par lots crée et valide des écritures d'ajustement de devise dans le grand livre et met à jour le solde DS.  

## <a name="data-type-for-general-ledger-accounts"></a>Type de données pour les comptes du grand livre général  
Le type de données est défini en texte pour le numéro de compte du grand livre général ou le code de compte afin de prendre en charge les exigences de tri pour le plan comptable standardisé Swiss Kontenrahmen Käfer (KMU). Pour plus d'informations, reportez-vous à [Fenêtre Plan comptable](assetId:///fa407624-b670-44b6-8397-91aa606e4c39). La liste des numéros de compte est triée selon le type de données de texte. Le plan comptable KMU indique les numéros de compte suivants :  

- 1176  
- 119.0  
- 1190  

## <a name="viewing-temporary-balances-in-general-journals"></a>Affichage des soldes temporaires dans les feuilles comptabilité  
Avant de valider une feuille comptabilité, vous pouvez prévisualiser l'effet que cette validation aurait sur les soldes de certains comptes généraux. Vous pouvez ouvrir une fenêtre de statistiques qui affiche les soldes des comptes et les soldes des lignes actives qui incluaient les valeurs non intégrées pour le journal en cours. Pour plus d'informations, voir [Affichage des soldes temporaires dans les feuilles comptabilisation immobilisation](how-to-view-temporary-balances-in-general-ledger-journals.md).  

## <a name="see-also"></a>Voir aussi  
 [Afficher les soldes temporaires dans les feuilles comptabilisation immobilisation](how-to-view-temporary-balances-in-general-ledger-journals.md)   
 [Fonctionnalité locale, Suisse](switzerland-local-functionality.md)
