---
title: 'Taxe sur la valeur ajoutée, Suisse [CH]'
description: Cet article explique plusieurs améliorations apportées aux fonctions de déclaration de TVA en Suisse.
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: null
ms.date: 06/25/2021
ms.author: edupont
---
# <a name="swiss-value-added-tax" />Taxe sur la valeur ajoutée, Suisse

[!INCLUDE[prod_short](../../includes/prod_short.md)] inclut les améliorations suivantes à la déclaration de TVA en Suisse :  

- Ajustement automatique des montants de TVA pour les factures, en fonction des comptes.  
- Taux de change de la TVA supplémentaires pour les factures en devises étrangères.  

Pour plus d'informations sur la déclaration et les exigences de codage de TVA en Suisse, voir [Informations sur la TVA en Suisse](https://www.estv.admin.ch/estv/en/home/value-added-tax.html). Ces informations sont disponibles en français, allemand, italien et en anglais.  

## <a name="vat-amounts-and-vat-exchange-rates" />Montants TVA et taux de change TVA

Conformément aux lois locales sur la TVA, le montant de base de TVA pour une facture peut être réduit de l'escompte accordé si une remise est accordée. Pour autoriser l'ajustement automatique de TVA pour un escompte sur une facture, le champ **Ajuster pour escompte** est activé par défaut dans la page **Paramètres comptabilité**. Vous pouvez également activer cette fonction dans les paramètres comptabilisation TVA. Pour plus d'informations, voir la table Paramètres comptabilité et la table Paramètres comptabilisation TVA.  

### <a name="currency-exchange-rates-for-vat-reporting" />Taux de change pour la déclaration de la TVA

Pour les factures en devise étrangère, vous devez utiliser le taux de change fourni par le gouvernement pour le calcul de la TVA proprement dit. Vous pouvez également définir des taux de change supplémentaires pour la TVA, que vous pouvez utiliser pour d'autres aspects de la facture que le calcul de la TVA. Vous pouvez indiquer le taux de change de TVA gouvernemental correct pour chaque devise étrangère pertinente dans la configuration du taux de change pour les factures. Pour plus d'informations, voir la table Taux de change devise.  

Vous pouvez ajuster tous les montants TVA dans les écritures TVA qui résultent des transactions en devise étrangère. Lorsque vous activez la fonction Ajuster le taux de change de la TVA, les taux de change de la TVA sont ajustés automatiquement. Les différences positives qui résultent des taux de change sont validées dans les comptes de gain de change. Les différences négatives qui résultent des taux de change sont validées dans les comptes de perte de change. Pour plus d'informations, reportez-vous au traitement par lots Ajuster taux de change.  

Des informations supplémentaires, telles que le taux de TVA et le montant en devise d'origine, sont transférées vers les écritures de TVA. Pour plus d'informations, voir la table Écriture TVA.  

## <a name="see-also" />Voir aussi

[Taux de TVA pour la Suisse](vat-rates-for-switzerland.md)   
[Créer et imprimer une déclaration de TVA, Suisse](how-to-create-and-print-a-swiss-vat-statement.md)   
[Fonctionnalité locale, Suisse](switzerland-local-functionality.md)   


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
