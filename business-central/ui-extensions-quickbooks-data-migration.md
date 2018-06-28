---
title: Utilisation de l'extension QuickBooks Data Migration | Microsoft Docs
description: "Décrit comment utiliser l'extension pour importer des clients, des fournisseurs, des articles, et des comptes de QuickBooks Desktop à Business Central."
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: ad1b888d475c0523c5a905e804a3f89ab4531b28
ms.openlocfilehash: c7348ff75e2f9660611d0d2aed0fa1beacfa259c
ms.contentlocale: fr-ch
ms.lasthandoff: 05/17/2018

---
# <a name="the-quickbooks-data-migration-extension-for-business-central"></a>Extension QuickBooks Data Migration pour Business Central
Cette extension facilite la migration des clients, des fournisseurs, des articles et des comptes de QuickBooks vers [!INCLUDE[d365fin](includes/d365fin_md.md)]. Si votre entreprise utilise QuickBooks aujourd'hui, vous pouvez exporter les informations appropriées puis ouvrir un guide de configuration assistée pour télécharger les données vers [!INCLUDE[d365fin](includes/d365fin_md.md)].  
Pour plus d'informations, voir [Importation des données métier à partir d'autres systèmes financiers](across-import-data-configuration-packages.md).

## <a name="exporting-data-from-quickbooks-desktop"></a>Exportation des données à partir de QuickBooks Desktop
Vous devez avoir exporté une partie ou la totalité de vos clients, fournisseurs, articles en stock et comptes existants vers un fichier IIF (Intuit Interchange Format). L'extension QuickBooks Data Migration inclut un mappage par défaut des données QuickBooks, ce qui vous permet d'utiliser vos données existantes pour tester votre nouvelle société [!INCLUDE[d365fin](includes/d365fin_md.md)]. Le mappage par défaut est suffisant dans l'immense majorité des cas, mais vous pouvez le modifier dans le guide de configuration assistée.  
Dans QuickBooks, le menu Fichier comprend un utilitaire permettant d'exporter les listes. Pour les besoins de [!INCLUDE[d365fin](includes/d365fin_md.md)], vous pouvez exporter les listes suivantes :

* Liste des clients  
* Liste des fournisseurs  
* Liste des articles  
* Liste des comptes  

Les données exportées sont enregistrées en tant que fichier IIF que vous pouvez ensuite télécharger vers [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="finding-the-quickbooks-data-migration-extension"></a>Recherche de l'extension QuickBooks Data Migration
L'extension QuickBooks Data Migration est installée et prête à être utilisée comme partie intégrante du guide de configuration assistée Migration des données. Si vous êtes prêt à commencer et que vous avez exporté vos données depuis QuickBooks, sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Configuration assistée**, puis sélectionnez le lien connexe. Choisissez **Migrer des données métier**, puis suivez les étapes du guide.  

## <a name="see-also"></a>Voir aussi
[Importation des données métier à partir d'autres systèmes financiers](across-import-data-configuration-packages.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions ](ui-extensions.md)  
