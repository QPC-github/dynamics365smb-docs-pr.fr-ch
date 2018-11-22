---
title: Forum Aux Questions sur Tell Me | Microsoft Docs
description: "Cet article fournit des réponses aux questions que nos partenaires et clients posent souvent sur Tell Me."
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: find
ms.date: 10/01/2018
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 9dbd92409ba02281f008246194f3ce0c53e4e001
ms.openlocfilehash: 70ab7fb07cda5ce9d86b3f39dd14321829e85a52
ms.contentlocale: fr-ch
ms.lasthandoff: 09/28/2018

---
# <a name="tell-me-faq"></a>FAQ Tell Me
Cette rubrique répond aux questions que nos utilisateurs avancés posent souvent sur la nouvelle fonction Tell Me, qui a remplacé la fonction Recherche de page précédente connue comme **Recherche de pages et d'états**.

### <a name="are-all-actions-from-my-current-page-discoverable-in-tell-me"></a>Toutes les actions de ma page actuelle sont-elles détectables dans Tell Me ?
Non. Les actions dans les parties, telles que la partie Lignes vente ou Récapitulatifs, ne sont pas affichées dans Tell Me.

### <a name="are-the-results-in-tell-me-filtered-by-permissions"></a>Les résultats dans Tell Me sont-ils filtrés par autorisations ?
Si l'utilisateur n'a pas AccessByPermissions, les actions ne s'affichent pas. Cependant, les pages et les états sont visibles dans les résultats mais nécessitent que l'utilisateur soit autorisé à y accéder. Un message s'affiche si l'utilisateur n'est pas autorisé à afficher l'objet.

### <a name="does-tell-me-display-content-from-my-customizations-or-installed-third-party-extensions"></a>La fonction Tell Me affiche-t-elle le contenu de mes personnalisations ou des extensions tierces installées ?
Les actions, les pages, et les états qui proviennent d'extensions sont extraits par Tell Me, mais la documentation d'aide personnalisée ne l'est pas. Pour des informations techniques sur la manière rédiger des pages et des états personnalisés détectables, voir [Ajout de pages et d'états à rechercher](/dynamics365/business-central/dev-itpro/developer/devenv-al-menusuite-functionality).

### <a name="what-makes-this-different-from-what-was-previously-known-as-page-search"></a>Quelles sont les différences avec la recherche de page précédente ?
La recherche de page s'est transformée en Tell Me pour vous aider à obtenir rapidement des résultats. La recherche de page pouvait uniquement vous aider à accéder aux pages ou aux états. À un niveau technique, Tell Me n'est plus basé sur le concept MenuSuite hérité.

### <a name="i-use-on-premises-included365finincludesd365finmdmd-does-that-include-tell-me"></a>J'utilise [!INCLUDE[d365fin](includes/d365fin_md.md)] local. La fonction Tell Me est-elle incluse ?
Vous pouvez utiliser Tell Me dans le client Web local pour trouver des actions, des pages, et des états, mais pas la documentation. Les utilisateurs se connectant à [!INCLUDE[d365fin](includes/d365fin_md.md)] depuis le client Dynamics NAV continuent d'utiliser la recherche de page.

### <a name="is-tell-me-available-for-all-form-factors"></a>La fonction Tell Me est-elle disponible pour tous les facteurs d'écrans ?
Tell Me est uniquement disponible dans le client Web ou l'application de bureau Windows.

### <a name="are-the-documentation-results-available-in-any-language"></a>Les résultats de la documentation sont-ils disponibles dans toutes les langues ?
Les articles de l'aide s'affichent dans la langue spécifiée dans **Mes paramètres**, si l'aide est disponible dans cette langue.

## <a name="see-also"></a>Voir aussi  
[Recherche de fonctions et d'informations](ui-search.md)
