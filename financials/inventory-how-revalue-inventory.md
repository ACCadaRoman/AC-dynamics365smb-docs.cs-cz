---
title: Vytvoření nových Položek ocenění pro zboží ve skladě | Microsoft Docs
description: 'Popisuje, jak ocenit nebo odepsat položky ocenění jednoho nebo více zboží v zásobách zaúčtováním jejich aktuální vypočtené hodnoty.'
services: project-madeira
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'costing, inventory cost, value entries'
ms.date: 08/07/2017
ms.author: sgroespe
---
# <a name="revalue-inventory"></a>Přecenění zásob
Chcete-li ocenit nebo odepsat zboží nebo specifickou položku zboží, musíte použít deník přecenění.

## <a name="to-revalue-inventory"></a>Přecenění zásob
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník přecenění** a pak vyberte související odkaz.
2. Vyberte akci **Vypočítat hodnotu zásob**.
3. V okně **Vypočítat hodnotu zásob** vyplňte pole podle potřeby. [!INCLUDE [tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Zvolte tlačítko **OK**.
5. Na každém řádku v okně **Přecenění deníku** v poli **Pořizovací cena (přeceněno)** zadejte novou pořizovací cenu. Případně zadejte novou celkovou částku do pole **Hodnota zásob (přeceněno)**.

    Příslušná pole jsou automaticky aktualizována. Všimněte si, že pole **Částka** zobrazuje skutečnou změnu hodnoty zásob pro vybranou položku zboží. Vypočítá rozdíl mezi polem **Hodnota zásob (vypočítaná)** a **Hodnota zásob (přeceněná)** .
6. Jakmile dokončíte všechny řádky v deníku přecenění, vyberte akci **Zaúčtovat**.

Nové položky přecenění jsou nyní vytvořeny tak, aby odrážely přecenění, která jste zaúčtovali. Nové hodnoty můžete vidět na příslušných kartách zboží.

## <a name="see-also"></a>Viz také
[Podrobnosti návrhu: Přecenění](design-details-revaluation.md)  
[Zásoby](inventory-manage-inventory.md)  
[Prodej](sales-manage-sales.md)  
[Nakupování](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
