---
title: "Affichage et modification des paramètres de base dans Financials| Microsoft Docs"
description: "Découvrez comment modifier certains des paramètres de base de Financials, par exemple, le Tableau de bord, la société, ou la date de travail."
services: project-madeira
documentationcenter: 
author: SusanneWindfeldPedersen
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: change Role Center, notification, change company, change work date
ms.date: 03/02/2018
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fceff1a6cf728608a49182a9704f187d31767fe
ms.openlocfilehash: f71b0e7d53138be0f89abe4e7935ab7c21437d8e
ms.contentlocale: fr-ch
ms.lasthandoff: 05/28/2018

---
# <a name="changing-basic-settings"></a>Modification des paramètres de base
Dans la fenêtre **Mes paramètres**, vous pouvez afficher et modifier les paramètres de base de [!INCLUDE[d365fin](includes/d365fin_md.md)]. Vos modifications affectent uniquement votre espace de travail, et non les espaces de travail des autres utilisateurs.  

## <a name="role-center"></a>Tableau de bord
Le tableau de bord représente la page d'accueil, un écran de démarrage conçu pour les exigences d'un rôle spécifique dans une organisation. Selon votre rôle, le tableau de bord donne une vue d'ensemble de l'entreprise, de votre département ou de vos tâches personnelles. Il vous permet également d'accéder à vos tâches quotidiennes et de rechercher les tâches qui vous sont affectées.

-   En haut, la navigation vous permet de permuter entre les clients, les fournisseurs, les articles et d'autres listes d'informations importantes. De même, les actions vous permettent de lancer des tâches, comme la création d'une facture vente, directement à partir du tableau de bord.

-   Au centre, vous trouverez les **Activités**. Les activités affichent les données actuelles et vous pouvez cliquer ou appuyer dessus pour afficher des informations plus détaillées. Les indicateurs de performance clés peuvent être configurés de sorte à afficher un graphique sélectionné pour une représentation visuelle, par exemple, de la trésorerie ou des revenus et des dépenses. Vous pouvez également générer la liste des clients favoris sur la page d'accueil pour les comptes avec lesquels vous travaillez souvent ou auxquels vous devez accorder une attention particulière.

### <a name="to-change-role-center"></a>Pour modifier le tableau de bord
Le Tableau de bord par défaut est **Gestionnaire d'activité**, mais vous pouvez sélectionner un autre Tableau de bord qui correspond mieux à vos besoins mieux.
1. Dans le coin supérieur droit, sélectionnez l'icône **Paramètres** ![Paramètres](media/ui-experience/settings_icon_small.png "Icône Paramètres du tableau de bord"), puis sélectionnez **Mes paramètres**.
2. Dans la fenêtre **Mes paramètres**, dans le champ **Tableau de bord** , sélectionnez le Tableau de bord que vous souhaitez définir comme standard. Par exemple, sélectionnez **Comptable**.
3. Cliquez sur le bouton **OK**.

## <a name="company"></a>Société
Dans [!INCLUDE[d365fin](includes/d365fin_md.md)], une société fonctionne comme un conteneur de données. Il peut y avoir plusieurs sociétés dans une seule base de données, mais une seule peut être sélectionnée à la fois.

La société par défaut est appelée CRONUS et contient uniquement des données de démonstration.

> [!TIP]  
>   Pour afficher un nom différent pour votre société dans l'application (par exemple sur le Tableau de bord), définissez le champ **Nom** sur la page **Informations société** ou le champ **Nom d'affichage** sur la page **Sociétés**.  

## <a name="work-date"></a>Date de travail
La date de travail par défaut est généralement la date du jour. Vous pouvez être amené à modifier temporairement la date de travail pour effectuer des tâches telles que l'exécution de transactions à une date différente de la date actuelle, .

> [!TIP]  
>   Pour entrer rapidement la date de travail dans un champ de date, tapez **w**. Pour entrer la date actuelle dans le champ de date, tapez **t**.

> [!IMPORTANT]  
>   La date de travail est seulement modifiée jusqu'à ce que vous fermiez la société ou que la date change. Si vous ouvrez une autre société, ou si vous ouvrez la même société le lendemain, et si vous souhaitez toujours utiliser une date qui n'est pas la date programme, il faut à nouveau établir la date de travail.

## <a name="region"></a>Région
Le paramètre **Région** détermine la manière dont les dates, heures, nombres et devises sont affichés ou mis en forme.   


## <a name="language"></a>Langue
Modifie la langue d'affichage. Ce champ s'affiche uniquement lorsque vous avez le choix entre plusieurs langues. 

La langue initiale est déterminée par l'administrateur ou par les paramètres de votre navigateur lorsque vous vous inscrivez à [!INCLUDE[d365fin](includes/d365fin_md.md)]. La langue définie est utilisée sur tous les appareils à partir desquels vous vous connectez, par exemple un téléphone ou une tablette. 

## <a name="changing-when-i-receive-notifications"></a>Modification lorsque je reçois des notifications
Sélectionnez ce lien pour afficher ou modifier les notifications que vous recevez au sujet de certains événements ou modification de statut, lorsque vous êtes sur le point de facturer un client avec des écritures échues, ou lorsque le stock disponible est inférieur à la quantité que vous êtes sur le point de vendre. Pour plus d'informations, voir [Notifications intelligentes](ui-smart-notifications.md).

## <a name="see-also"></a>Voir aussi
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Modification des fonctionnalités affichées](ui-experiences.md)  
