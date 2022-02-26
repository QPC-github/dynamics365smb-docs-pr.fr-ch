---
author: edupont04
ms.service: dynamics365-business-central
ms.topic: include
ms.date: 04/01/2021
ms.author: edupont
ms.openlocfilehash: e66b50cec6d3f9e2606f3f698e12a06eccdd5cf6
ms.sourcegitcommit: 2c972dfc94d27245eaa99efcf638d030dedafb22
ms.translationtype: HT
ms.contentlocale: fr-CH
ms.lasthandoff: 02/09/2022
ms.locfileid: "8104441"
---
Le tableau suivant décrit certains des principaux états dans les états de comptabilité fournisseur.

| État | ID d’objet | Description |
|--|--|--|
| **Comptabilité fournisseur âgée** | 322|Affiche les soldes échus pour les fournisseurs dans les intervalles de temps en souffrance. Les montants en souffrance peuvent être affichés par date d’échéance, date de validation ou par date de document selon les besoins. Vous pouvez choisir d’afficher les montants en devise locale (DS) et d’imprimer les détails des documents en retard. Les intervalles de temps peuvent avoir des en-têtes avec des dates ou avec un nombre de dates échues, par rapport à l’ancienneté spécifiée par type.<br>Ce rapport est le rapport principal pour le rapprochement des écritures comptables fournisseur avec la comptabilité. En supposant que vous n’ayez pas autorisé la comptabilisation directe sur les comptes utilisés dans la comptabilité fournisseurs des groupes comptabilisation, ce rapport est une spécification des montants que vous trouvez en comptabilité.|
| **Fournisseur : Solde cumulé** | 321 | Affiche le solde du fournisseur à la date de fin de la plage de dates spécifiée. Vous pouvez choisir d’afficher le solde du fournisseur dans votre devise locale (DS). Sélectionnez le champ **Inclure les écritures non lettrées** pour afficher les écritures qui ont été clôturées à la date de fin, mais qui ont été délettrées (ouvertes) à une date ultérieure. Sélectionnez le champ **Afficher les écritures avec un solde nul** pour afficher les fournisseurs avec un solde nul selon la date de fin du filtre de date. Le filtre de date s’applique aux écritures détaillées de la comptabilité fournisseur pour les écritures de l’état. Si vous avez des paiements postérieurs à la date de fin qui ont été appliqués à des factures dans la plage de dates, les factures apparaîtront dans l’état, car elles n’ont pas été clôturées à la date de fin. |
| **Balance fournisseurs** | 329 | Affiche les soldes périodes pour les fournisseurs pour la période spécifiée dans le filtre de date ainsi que les soldes périodes depuis le début de l’exercice correspondant à la période sélectionnée. L’état est regroupé par groupes comptabilisation des fournisseurs et donne une vue différente de la comptabilité fournisseur que l’état **Comptabilité fournisseur âgée**. **Noter** : si vous n’avez pas configuré de période comptable, le système ne saura pas quel exercice utiliser et affichera le cumul annuel à partir du dernier exercice défini ou sélectionnera simplement la période, qui peut ou non être dès le début d’une année.|
| **Grand livre fournisseurs** | 304 | Affiche toutes les écritures comptables fournisseur dans le filtre de date spécifié. L’état affiche les soldes d’ouverture du fournisseur par rapport au filtre de date. |
| **Statistiques achat** |312 |[!INCLUDE [reports-purchase-statistics](reports-purchase-statistics.md)]<br>Cet état peut également être utilisé dans la comptabilité fournisseurs, car il est plus facile d’effectuer une recherche rapide des paiements, remises et autres transactions validés pour un fournisseur donné.|
|**Fournisseur : Échéancier**|305| État hérité pour la comptabilité fournisseur âgée. Nous vous recommandons d’utiliser l’état **Comptabilité fournisseur âgée** à la place. Vous pouvez choisir une durée de période et une date à définir comme date *échue*.|
|**Paiements suspendus**|319|Affiche les écritures comptables fournisseurs où le champ **En attente** n’est pas vide.|
|**Feuille acompte fournisseur**|317|Affiche le journal des paiements avec les informations de remise et de tolérance. Le rapport peut être utilisé pour vérifier les paiements avant de créer des fichiers de paiement et de valider le journal. **Noter** : Le rapport affichera les remises de paiement de manière incorrecte lorsque plusieurs notes de crédit ont été utilisées dans une application. Dans ce cas, l’escompte de paiement pour les avoirs supplémentaires sera affiché comme montant non appliqué.|
|**Liste des fournisseurs**|301|Affiche diverses informations de base sur les fournisseurs, par exemple le groupe comptabilisation, le groupe remise, les informations sur les remises et le paiement, la priorité, et la devise par défaut du fournisseur, ainsi que le solde actuel du fournisseur (en devise société). L’état peut être utilisé, par exemple, pour maintenir à jour les informations de la table Fournisseur.|