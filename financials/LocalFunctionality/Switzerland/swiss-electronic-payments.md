---
title: "Paiements électroniques, Suisse"
description: "Les améliorations suisses vous permettent d'envoyer des factures aux clients par voie électronique. Les factures sont présentées et payées directement à l'aide du logiciel bancaire en ligne du client."
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
ms.openlocfilehash: 5cbcf1172d29ccbfebd1045c0eb7798f1aef2f24
ms.contentlocale: fr-ch
ms.lasthandoff: 03/22/2018

---
# <a name="swiss-electronic-payments"></a>Paiements électroniques, Suisse
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] vous permet d'envoyer des factures aux clients par voie électronique. Les factures sont présentées et payées directement à l'aide du logiciel bancaire en ligne du client.  

## <a name="electronic-payment-methods"></a>Modes de paiement électronique  
Vous pouvez effectuer des paiements électroniques en utilisant les modes suivants :  

- Einzahlungsschein mit Referenznummer (ESR)  
- Lastschrift Verfahren (LSV+)  
- Virements SEPA  

## <a name="esr"></a>ESR  
ESR est un service de prélèvement électronique qui utilise des bordereaux de paiement pour prélever de l'argent. C'est le système de paiement électronique standard créé par la Poste suisse. Vous pouvez imprimer des bordereaux de paiement ESR en tant que pièces jointes à une facture, calculer des numéros de référence ESR et importer des fichiers ESR contenant des informations de paiement provenant de banques. Pour plus d'informations, voir [Paiements électroniques suisses avec le mode ESR](how-to-print-esr-invoices.md). Vous pouvez également effectuer des paiements ESR et ESR+ à l'aide de la version de la banque de ce mode de règlement, intitulé Bank-ESR (BESR).  

## <a name="lsv"></a>LSV+  
LSV+ est un service de prélèvement utilisé pour traiter les paiements. Les sociétés peuvent lancer des paiements client directement de la banque du client à l'aide du prélèvement. Vous pouvez demander et encaisser des paiements clients en utilisant le prélèvement au format banque LSV+ ou au format PostFinance DebitDirect. Pour plus d'informations, voir [Paiements électroniques suisses avec le mode LSV+](swiss-electronic-payments-using-lsv-.md).  

## <a name="sepa-credit-transfers"></a>Virements SEPA  
Pour exporter des paiements selon la norme SEPA, vous devez utiliser un compte bancaire. Pour vous assurer que les écritures comptables correspondantes sont cohérentes avec celles générées pour des modes de règlement suisses locaux (voir ci-dessus), la valeur dans le champ **Groupe compta. banque** dans la fenêtre **Fiche compte bancaire archivé** doit indiquer le compte général approprié. Pour plus d'informations sur l'exportation des paiements SEPA, voir [Procédure : créer des écritures de collection prélèvement automatique SEPA et les exporter vers un fichier bancaire](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).  

## <a name="see-also"></a>Voir aussi  
 [Importer des numéros de compensation d'une banque suisse](how-to-import-swiss-bank-clearing-numbers.md)   
 [Paiements électroniques à l'aide de ESR+, Suisse](swiss-electronic-payments-using-esr.md)   
 [Imprimer des factures ESR](how-to-print-esr-invoices.md)   
 [Paiements électroniques à l'aide de LSV+, Suisse](swiss-electronic-payments-using-lsv-.md)   
 [Fonctionnalité locale, Suisse](switzerland-local-functionality.md)  ' [Créer des écritures de collection prélèvement automatique SEPA et les exporter vers un fichier bancaire](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)  
 [Effectuer des paiements](../../payables-make-payments.md)
