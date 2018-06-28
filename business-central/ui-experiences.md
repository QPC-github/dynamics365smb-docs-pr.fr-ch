---
title: "Choix de l'expérience utilisateur pour masquer ou afficher des fonctions avancées | Microsoft Docs"
description: "En savoir plus sur ce que signifie le niveau d'expérience Basic et Essentiel pour l'interface utilisateur, les domaines d'application, et votre société."
documentationcenter: 
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: essential, basic, user interface, application area, experience
ms.date: 04/17/2018
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: dc7e739bc2b8ac9e8efce3a0f52acb945352416e
ms.openlocfilehash: 0a94d94e58b2aa3f04639a00904b5370c91b1132
ms.contentlocale: fr-ch
ms.lasthandoff: 04/19/2018

---
# <a name="changing-which-features-are-displayed"></a>Modification des fonctionnalités affichées
[!INCLUDE[d365fin](includes/d365fin_md.md)] est conçu pour vous aider à gérer vos affaires, sans vous soucier du secteur d'activité dans lequel vous vous trouvez. Au centre de [!INCLUDE[d365fin](includes/d365fin_md.md)], vous trouverez les états financiers ainsi que les processus vente et achat. Vous pouvez y ajouter des expériences en fonction des besoins de votre activité en ajoutant des extensions à partir d'AppSource ou en modifiant le paramètre Expérience de votre société. Pour plus d'informations, voir [Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md) ou la section « Choix de l'expérience utilisateur pour masquer ou afficher des fonctions » ci-après.

## <a name="choosing-a-user-experience-to-show-or-hide-features"></a>Choix de l'expérience utilisateur pour masquer ou afficher des fonctions
L'expérience utilisateur détermine le degré de visibilité de la fonctionnalité principale quand vos collègues et vous-même utilisez [!INCLUDE[d365fin](includes/d365fin_md.md)]. Vous pouvez choisir l'expérience utilisateur pour votre société dans la fenêtre **Informations société** du champ **Expérience**.

> [!NOTE]  
> Ce paramètre s'applique à tous les utilisateurs au sein de votre société. Les utilisateurs peuvent personnaliser leur propre expérience en modifiant les mises en page et le contenu. Pour plus d'informations, voir [Personnalisation de votre espace de travail et des pages](ui-personalization-user.md).  

Le tableau suivant répertorie les expériences actuellement disponibles.

| Expérience | Impact sur l'interface utilisateur |
| --- | --- |
| **Basique** |Affiche uniquement les actions et les champs de base relatifs aux fonctionnalités d'entreprise les plus courantes, telles que les ventes, les achats, les stocks et les finances. |
| **Essentiel** |Affiche tous les champs et actions pour toutes les fonctionnalités d'entreprise communes.|
| **Premium** |Affiche tous les champs et actions pour toutes les fonctionnalités d'entreprise, y compris la fabrication et la gestion des services.|

> [!NOTE]  
> Les expériences que vous pouvez sélectionner dans [!INCLUDE[d365fin](includes/d365fin_md.md)] dépendent de votre licence de solution, appelé un abonnement. Pour plus d'informations sur les abonnements **Essentiel** et **Premium**, consultez [Business Central](https://go.microsoft.com/fwlink/?linkid=870242) sur le site Microsoft Dynamics 365 Marketing.

> [!IMPORTANT]  
> Tous les utilisateurs réguliers d'une solution doivent avoir le même plan, Essential ou Premium, pour pouvoir sélectionner l'expérience pour la société. En conséquence, un utilisateur ne peut pas accéder aux fonctionnalités Premium si un ou plusieurs autres utilisateurs peuvent uniquement accéder aux fonctionnalités Essential. Ce n'est pas le cas pour les utilisateurs non réguliers du type Membre de l'équipe, Administrateur interne, Comptable externe et Administrateur délégué, qui peuvent avoir un plan différent de celui des autres utilisateurs de la solution.

## <a name="enabling-premium-features-after-upgrading-a-plan"></a>Activation des fonctionnalités Premium après mise à niveau d'un plan
Les utilisateurs sont affectés à des plans dans le centre d'administration Office 365 dans le cadre de la tâche générale de création des utilisateurs Business Central. Pour plus d'informations, voir [Ajouter des utilisateurs à Office 365 for business](https://support.office.com/en-us/article/Add-users-to-Office-365-for-business-435ccec3-09dd-4587-9ebd-2f3cad6bc2bc).

Vous pouvez ensuite définir les fonctions et fenêtres spécifiques de l'expérience auxquelles ces utilisateurs sont autorisés à accéder en affectant des ensembles d'autorisations. Pour plus d'informations, voir [Gestion des utilisateurs et des autorisations](ui-how-users-permissions.md).

### <a name="to-update-plan-changes-in-users-groups"></a>Pour mettre à jour les modifications de plan des groupes d'utilisateurs
Si vous avez modifié les plans des utilisateurs dans le centre d'administration Office 365, par exemple en affectant plus d'utilisateurs au plan Premium, vous devez refléter les modifications dans [!INCLUDE[d365fin](includes/d365fin_md.md)].

1. Connectez-vous en tant qu'administrateur.
2. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Utilisateurs**, puis sélectionnez le lien connexe.
3. Dans la fenêtre **Utilisateurs**, sélectionnez l'option **Actualiser tous les groupes d'utilisateurs**.

Toutes les nouvelles informations relatives aux plans des utilisateurs et aux groupes d'utilisateurs qui leur sont affectés sont maintenant mises à jour en fonction des modifications du plan.

### <a name="to-select-the-premium-experience"></a>Pour sélectionner l'expérience Premium
Vous pouvez maintenant sélectionner la nouvelle expérience.
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Informations société**, puis sélectionnez le lien connexe.
2. Dans la fenêtre **Informations société**, dans le raccourci **Expérience utilisateur**, sélectionnez Premium dans le champ **Expérience**.

## <a name="see-also"></a>Voir aussi .
[Création de sociétés](about-new-company.md)  
[Gestion des utilisateurs et des autorisations](ui-how-users-permissions.md)    
[Modification des paramètres de base](ui-change-basic-settings.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  
## [!INCLUDE[d365fin](includes/training_link_md.md)]
