---
title: Ausführen und Anzeigen von Einblicken auf Dashboardkacheln
description: Hier erfahren Sie, wie Sie als Power BI-Endbenutzer Einblicke in Ihre Datasets und Dashboardkacheln erhalten.
author: mihart
manager: kvivek
ms.reviewer: ''
featuredvideoid: et_MLSL2sA8
ms.custom: seodec18
ms.service: powerbi
ms.subservice: powerbi-consumer
ms.topic: conceptual
ms.date: 12/06/2018
ms.author: mihart
LocalizationGroup: Dashboards
ms.openlocfilehash: fcfb16de53b4e6c67b7c46fec87ab614d07cb9b1
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "61049247"
---
# <a name="view-data-insights-on-dashboard-tiles-with-power-bi"></a>Anzeigen von Einblicken auf Dashboardkacheldaten mit Power BI
Jede Visualisierungskachel in Ihrem Dashboard ist ein Ausgangspunkt für das Durchsuchen von Daten. Wenn Sie eine Kachel auswählen, wird ein Bericht geöffnet, in dem Sie filtern und sortieren und das dem Bericht zugrunde liegende Dataset detailliert analysieren können. Und wenn Sie Einblicke ausführen, erledigt Power BI das Durchsuchen der Daten für Sie.

Führen Sie schnelle Einblicke aus, um interessante interaktive Visualisierungen auf Grundlage Ihrer Daten zu generieren. Quick Insights (schnelle Einblicke) können für eine bestimmte Dashboardkachel ausgeführt werden, und Sie können sogar Einblicke für einen Einblick durchführen.

Das Feature „Einblicke“ basiert auf einer wachsenden Reihe [erweiterter analytischer Algorithmen](end-user-insight-types.md), die in Verbindung mit Microsoft Research entwickelt wurden. Wir möchten damit auch in Zukunft noch mehr Benutzern auf neue und intuitive Weise Einblicke in ihre Daten bieten.

## <a name="run-insights-on-a-dashboard-tile"></a>Ausführen von Einblicken auf einer Dashboardkachel
Wenn Sie Einblicke für eine Dashboardkachel ausführen, durchsucht Power BI nur die Daten, die zum Erstellen dieser einzelnen Dashboardkachel verwendet wurden. 

1. [Öffnen Sie ein Dashboard](end-user-dashboards.md).
2. Zeigen Sie auf eine Kachel. Wählen Sie die Auslassungspunkte (...) aus, und wählen Sie dann **Einblicke anzeigen** aus. 

    ![Auslassungspunkte-Menümodus](./media/end-user-insights/power-bi-hover.png)


3. Die Kachel wird im [Fokusmodus](end-user-focus.md) geöffnet. Die Einblickkarten werden rechts angezeigt.    
   
    ![Fokusmodus](./media/end-user-insights/pbi-insights-tile.png)    
4. Ist einer der Einblicke für Sie interessant? Wählen Sie die entsprechende Einblickkarte aus, um weitere Informationen zu erhalten. Der ausgewählte Einblick wird auf der linken Seite angezeigt, und neue Einblickkarten (ausschließlich abhängig von den Daten in diesem Einblick) werden rechts angezeigt.    

 ## <a name="interact-with-the-insight-cards"></a>Interaktion mit Karten für Einblicke
Wenn Sie einen Einblick geöffnet haben, können Sie ihn weiter durchsuchen.

   * Filtern Sie das Visual im Zeichenbereich.  Um die Filter anzuzeigen, wählen Sie in der oberen rechten Ecke das Pfeilsymbol aus, um den Filterbereich zu erweitern.

     ![Einblick im Menü „Filter“ erweitert](./media/end-user-insights/power-bi-insights-on-insights.png)
   
   * Führen Sie Einblicke für die Karte „Einblick“ selbst aus. Dies wird häufig auch als **verwandte Einblicke** bezeichnet. Wählen Sie in der oberen rechten Ecke das Glühbirnensymbol ![„Einblicke erhalten“-Symbol](./media/end-user-insights/power-bi-bulb-icon.png) oder **Einblicke erhalten** aus.
     
     ![Menüleiste mit dem Symbol „Einblicke erhalten“](./media/end-user-insights/power-bi-autoinsights-tile.png)
     
     Der Einblick wird auf der linken Seite angezeigt, und neue Karten (ausschließlich abhängig von den Daten in diesem Einblick) werden rechts angezeigt.
     
     ![Einblicke in Einblicke](./media/end-user-insights/power-bi-insights-on-insights-new.png)

Um zum ursprünglichen Bereich für Einblicke zurückzukehren, wählen Sie in der oberen linken Ecke **Fokusmodus beenden** aus.

## <a name="considerations-and-troubleshooting"></a>Zu beachtende Aspekte und Problembehandlung
- **Einblicke anzeigen** funktioniert nicht mit DirectQuery. Das Feature kann nur für in Power BI hochgeladene Daten verwendet werden.
- **Einblicke anzeigen** funktioniert nicht mit allen Arten von Dashboardkacheln. Beispielsweise ist es nicht für benutzerdefinierte visuelle Elemente verfügbar.<!--[custom visuals](end-user-custom-visuals.md)-->


## <a name="next-steps"></a>Nächste Schritte
Erfahren Sie mehr über die [Typen verfügbarer schneller Einblicke](end-user-insight-types.md).

