---
title: "Gérer des comptes bancaires| Microsoft Docs"
description: "Vous devez régulièrement rapprocher les écritures comptables bancaires dans Financials des transactions bancaires associées à vos comptes bancaires."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reconcile
ms.date: 05/15/2018
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: ad1b888d475c0523c5a905e804a3f89ab4531b28
ms.openlocfilehash: dd3068cc1af6a16a43f982d3b48cdec42a7d7eca
ms.contentlocale: fr-ch
ms.lasthandoff: 05/17/2018

---
# <a name="managing-bank-accounts"></a>Gestion des comptes bancaires
Vous devez rapprocher régulièrement vos écritures comptables banque dans [!INCLUDE[d365fin](includes/d365fin_md.md)] avec les transactions bancaires associées dans les comptes bancaires de votre banque, puis valider le solde sur votre compte bancaire. Vous pouvez effectuer cette tâche soit dans le cadre du traitement des paiements représentés sur un relevé bancaire dans la **Feuille rapprochement bancaire**. Vous pouvez également effectuer la tâche séparément du traitement des paiements, dans la fenêtre **Rapprochement bancaire**, où vous mettez en correspondance (rapprochez) les lignes de relevé bancaire dans le volet gauche avec vos écritures comptables compte bancaire internes dans le volet droit. Dans les deux fenêtres, vous pouvez renseigner les informations de relevé bancaire en important un fichier ou un flux, et vous pouvez utiliser les suggestions de correspondance automatique.

> [!NOTE]  
> Dans les versions nord-américaines, vous pouvez également effectuer le rapprochement bancaire dans la fenêtre **Feuille rapprochement bancaire**, qui est mieux adaptée pour les chèques et les acomptes, mais ne prend pas en charge l'importation de fichiers de relevé bancaire. Pour utiliser cette fenêtre à la place de la fenêtre **Rapprochement bancaire**, désélectionnez le champ **Rapprochement bancaire avec correspondance auto.** dans la fenêtre **Paramètres comptabilité**. Pour plus d'informations, voir la section « Rapprocher des comptes bancaires » sous Fonctionnalité locale, États-Unis.

Parfois, vous devez transférer les montants entre comptes bancaires dans [!INCLUDE[d365fin](includes/d365fin_md.md)] pour refléter les transferts effectués au niveau de votre banque. Vous effectuez cette tâche dans la fenêtre **Feuille comptabilité**, de différentes manières en fonction de la devise des fonds.

Avant de pouvoir gérer des comptes bancaires, vous devez configurer chaque compte bancaire en tant que fiche compte bancaire. En outre, vous devez configurer les services électroniques que vous pouvez utiliser pour l'importation de relevés bancaires et l'exportation de fichiers de paiement. Pour plus d'informations, reportez vous à [Configuration de comptes bancaires](bank-setup-banking.md).

Le tableau suivant décrit une série de tâches et inclut des liens vers les rubriques qui les décrivent.

| Pour | Voir |
| --- | --- |
| Rapprocher des comptes bancaires en relation avec le traitement des paiements dans la fenêtre **Feuille rapprochement bancaire**. |[Lettrage automatique des paiements et rapprochement des comptes bancaires](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| Rapprocher des comptes bancaires, y compris les écritures comptables chèque, en tant que tâche distincte dans la fenêtre **Rapprochement bancaire**. |[Rapprocher des comptes bancaires séparément](bank-how-reconcile-bank-accounts-separately.md) |
| Valider des transferts entre comptes bancaires dans la même devise ou dans des devises différentes. |[Transfert de fonds à la banque](bank-how-transfer-bank-funds.md) |

## <a name="see-also"></a>Voir aussi
[Paramétrage des opérations bancaires](bank-setup-banking.md)  
[Gestion des comptes client](receivables-manage-receivables.md)  
[Gestion des comptes fournisseur](payables-manage-payables.md)    
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Fonctionnalités marché](ui-across-business-areas.md)  

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  
## [!INCLUDE[d365fin](includes/training_link_md.md)]
