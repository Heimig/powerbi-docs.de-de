---
title: KPI-Visualisierungen (Key Performance Indicator)
description: Erstellen von KPI-Visualisierungen (Key Performance Indicator) in Power BI
author: mihart
manager: kvivek
ms.reviewer: ''
featuredvideoid: xmja6EpqaO0
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: tutorial
ms.date: 06/24/2019
ms.author: mihart
LocalizationGroup: Visualizations
ms.openlocfilehash: 8fa39c7cc57e24f0c19e1a484c0e925bfeec94f7
ms.sourcegitcommit: 1c96b65a03ec0a0612e851dd58c363f4d56bca38
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/25/2019
ms.locfileid: "67389559"
---
# <a name="key-performance-indicator-kpi-visuals"></a>KPI-Visualisierungen (Key Performance Indicator)

Ein Key Performance Indicator (KPI) ist ein visueller Hinweis, mit dem der Fortschritt in Bezug auf ein messbares Ziel kommuniziert wird. Weitere Informationen über KPIs finden Sie unter [Key Performance Indicators (KPIs) in PowerPivot](/previous-versions/sql/sql-server-2012/hh272050(v=sql.110)).

Schauen Sie Will beim Erstellen von Einzelmetrikvisualisierungen wie Messgeräten, Karten und KPIs zu.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xmja6EpqaO0?list=PL1N57mwBHtN0JFoKSR0n-tBkUJHeMP2cP" frameborder="0" allowfullscreen></iframe>

## <a name="when-to-use-a-kpi"></a>Einsatzmöglichkeiten von KPIs

KPIs sind für folgende Zwecke gut geeignet:

* Um den Fortschritt zu messen. Zum Beantworten der Frage: „Wie weit bin ich voraus bzw. im Rückstand?“

* Um die Entfernung zu einem Ziel zu messen. Zum Beantworten der Frage: „Wie weit bin ich voraus bzw. im Rückstand?“

## <a name="kpi-requirements"></a>KPI-Anforderungen

Ein Designer verwendet ein bestimmtes Measure als Basis für eine KPI-Visualisierung. Die KPI soll Ihnen helfen, den aktuellen Wert und Status einer Metrik anhand eines definierten Ziels zu bewerten. Eine KPI-Visualisierung erfordert eine *Basiskennzahl*, die im Hinblick auf einen Wert ausgewertet wird, eine *Zielkennzahl* bzw. einen Zielwert sowie einen *Schwellenwert* oder ein *Ziel*.

Ein KPI-Dataset muss Zielwerte für eine KPI enthalten. Wenn Ihr Dataset keine Zielwerte enthält, können Sie sie erstellen, indem Sie dem Datenmodell oder der PBIX-Datei ein Excel-Arbeitsblatt mit Zielen hinzufügen.

## <a name="prerequisites"></a>Voraussetzungen

Wenn Sie noch nicht bei Power BI registriert sind, müssen Sie sich zuerst für eine [kostenlose Testversion registrieren](https://app.powerbi.com/signupredirect?pbi_source=web).

* [Power BI Desktop](https://powerbi.microsoft.com/get-started/) – kostenlos!

* [PBIX-Datei mit einem Analysebeispiel für den Einzelhandel](http://download.microsoft.com/download/9/6/D/96DDC2FF-2568-491D-AAFA-AFDD6F763AE3/Retail%20Analysis%20Sample%20PBIX.pbix)

## <a name="how-to-create-a-kpi"></a>Erstellen eines KPI

Öffnen Sie die [PBIX-Datei mit einem Analysebeispiel für den Einzelhandel](http://download.microsoft.com/download/9/6/D/96DDC2FF-2568-491D-AAFA-AFDD6F763AE3/Retail%20Analysis%20Sample%20PBIX.pbix) in Power BI Desktop. Im Folgenden erstellen Sie eine KPI, die Ihren Fortschritt beim Erreichen von Umsatzzielen misst.

1. Öffnen Sie das **Analysebeispiel für den Einzelhandel** in der Berichtsansicht ![Screenshot des Berichtsansichtssymbols.](media/power-bi-visualization-kpi/power-bi-report-view.png).

1. Auswählen ![Screenshot der gelben Registerkarte.,](media/power-bi-visualization-kpi/power-bi-yellow-tab.png) um eine neue Seite hinzuzufügen.

1. Wählen Sie im Bereich **Felder** **Verkäufe > Gesamte Einheiten in diesem Jahr** aus.  Dieser Wert wird der Indikator.

1. Fügen Sie **Zeit > FiscalMonth** hinzu.  Dieser Wert stellt den Trend dar.

1. Wählen Sie in der oberen rechten Ecke des Visuals die Auslassungspunkte aus, und überprüfen Sie, ob Power BI die Spalten in aufsteigender Reihenfolge nach **FiscalMonth** sortiert hat.

    > [!IMPORTANT]
    > Nachdem Sie die Visualisierung in eine KPI konvertiert haben, ist **keine** Option zum Sortieren vorhanden. Sie müssen sie jetzt ordnungsgemäß sortieren.

    ![Screenshot des erweiterten Auslassungspunktemenüs mit aufsteigender Sortierreihenfolge und Auswahl von FiscalMonth.](media/power-bi-visualization-kpi/power-bi-ascending-by-fiscal-month.png)

    Nach ordnungsgemäßer Sortierung sieht Ihre Visualisierung wie folgt aus:

    ![Screenshot des ordnungsgemäß sortierten visuellen Elements.](media/power-bi-visualization-kpi/power-bi-chart.png)

1. Wandeln Sie die Visualisierung in eine KPI um, indem Sie im Bereich **Visualisierung** das **KPI**-Symbol auswählen.

    ![Screenshot des Bereichs „Visualisierungen“ mit hervorgehobenem KPI-Symbol.](media/power-bi-visualization-kpi/power-bi-kpi-template.png)

1. Um ein Ziel hinzuzufügen, ziehen Sie **Gesamte Einheiten im letzten Jahr** auf das Feld **Ziel**.

    ![Screenshot der fertiggestellten KPI-Visualisierung und des Bereichs „Felder“ mit Darstellung der Werte.](media/power-bi-visualization-kpi/power-bi-kpi-done.png)

1. Optional können Sie den KPI formatieren. Wählen Sie dazu das Farbrollensymbol aus, um den Formatierungsbereich zu öffnen.

    * **Indikator**: Dient zum Steuern der Anzeigeeinheiten und der Dezimalstellen des Indikators.

    * **Trendachse**: Wenn hier **Ein** festgelegt ist, zeigt das Visual die Trendachse als Hintergrund der KPI-Visualisierung an.  

    * **Ziele**: Wenn hier **Ein** festgelegt ist, zeigt das Visual das Ziel und die Entfernung vom Ziel als Prozentsatz an.

    * **Farbcodierung > Richtung**: Manche schätzen einige KPIs als besser für *höhere* Werte und andere als besser für *niedrigere* Werte ein. Nehmen Sie als Beispiel Erlös und Wartezeit. Im Gegensatz zur Wartezeit ist beim Erlös ist ein höherer Wert besser. Wählen Sie **Hoch ist gut** aus, und ändern Sie optional die Farbeinstellungen.

KPIs sind auch im Power BI-Dienst und auf Ihren Mobilgeräten verfügbar. So verlieren Sie nie den Kontakt zu den essentiellen Vorgängen in Ihrem Unternehmen.

## <a name="considerations-and-troubleshooting"></a>Zu beachtende Aspekte und Problembehandlung

Wenn die KPI nicht wie in der Abbildung oben aussieht, haben Sie möglicherweise keine Sortierung nach **FiscalMonth** ausgeführt. KPIs haben keine Sortieroption. Sie müssen neu beginnen und nach **FiscalMonth** sortieren, *bevor* Sie die Visualisierung in eine KPI umwandeln.

## <a name="next-steps"></a>Nächste Schritte

* [Tipps und Tricks für Power BI-Kartenvisualisierungen](power-bi-map-tips-and-tricks.md)

* [Visualisierungstypen in Power BI](power-bi-visualization-types-for-reports-and-q-and-a.md)

Weitere Fragen? [Wenden Sie sich an die Power BI-Community](http://community.powerbi.com/)
