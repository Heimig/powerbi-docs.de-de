---
title: Grundlegendes Flächendiagramm
description: Grundlegendes Flächendiagramm.
author: mihart
manager: kvivek
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 09/24/2018
ms.author: mihart
LocalizationGroup: Visualizations
ms.openlocfilehash: 02d81a4ebb92ec199887109c7f2d9afcb6449eda
ms.sourcegitcommit: c8c126c1b2ab4527a16a4fb8f5208e0f7fa5ff5a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/15/2019
ms.locfileid: "54276121"
---
# <a name="basic-area-chart"></a>Grundlegendes Flächendiagramm
Das grundlegende Flächendiagramm (d.h. überlappendes Flächendiagramm) basiert auf dem Liniendiagramm. Der Bereich zwischen der Achse und der Zeile ist mit Farben gefüllt, um Volumen anzuzeigen. 

Flächendiagramme betonen das Ausmaß von Veränderungen im Laufe der Zeit und können dazu genutzt werden, um den gesamten Wert über einen Trend hinweg hervorzuheben. Beispielsweise können Daten, die den Gewinn im Zeitverlauf darstellen, in ein Flächendiagramm gezeichnet werden, um den Gesamtgewinn zu verdeutlichen.

![](media/power-bi-visualization-basic-area-chart/powerbi-area-chartnew.png)

## <a name="when-to-use-a-basic-area-chart"></a>Wann ein einfaches Flächendiagramm verwendet werden sollte
Einfache Flächendiagramme sind gut geeignet,

* um den Volumentrend über Zeit und Reihe hinweg anzuzeigen und zu vergleichen 
* für individuelle Reihen, die einen physisch zählbaren Satz darstellen

### <a name="prerequisites"></a>Voraussetzungen
 - Power BI-Dienst
 - Analysebeispiel für den Einzelhandel

Melden Sie sich bei Power BI an, wählen Sie **Daten abrufen\> Beispiele \> Analysebeispiel für Einzelhandel > Verbinden** aus, und wählen Sie **Zum Dashboard wechseln**. 

## <a name="create-a-basic-area-chart"></a>Erstellen eines grundlegenden Flächendiagramms
 

1. Wählen Sie im Dashboard „Analysebeispiel für Einzelhandel“ die Kachel **Läden gesamt** aus, um den Bericht „Analysebeispiel für Einzelhandel“ zu öffnen.
2. Wählen Sie **Bericht bearbeiten** , um den Bericht in der Bearbeitungsansicht zu öffnen.
3. Fügen Sie eine neue Berichtsseite hinzu, indem Sie auf das gelbe Pluszeichen (+) am unteren Rand des Berichts klicken.
4. Erstellen Sie ein Flächendiagramm, das den Absatz des laufenden Jahres und den des Vorjahres pro Monat anzeigt.
   
   a. Wählen Sie im Bereich „FELDER“ die Option **Verkäufe \> Verkäufe im Vorjahr** und **Verkäufe in diesem Jahr > Wert** aus.

   ![](media/power-bi-visualization-basic-area-chart/power-bi-bar-chart.png)

   b.  Konvertieren Sie das Diagramm in ein grundlegendes Flächendiagramm, indem Sie im Bereich „Visualisierungen“ das Symbol „Flächendiagramm“ auswählen.

   ![](media/power-bi-visualization-basic-area-chart/convertchart.png)
   
   c.  Wählen Sie **Zeit \> Monat**, um es dem Bereich **Achse** hinzuzufügen.   
   ![](media/power-bi-visualization-basic-area-chart/powerbi-area-chartnew.png)
   
   d.  Wählen Sie die Auslassungspunkte in der oberen, rechten Ecke der Visualisierung aus, und wählen Sie **Nach FiscalMonth sortieren**, um das Diagramm sortiert nach Monaten anzuzeigen. Wenn Sie die Sortierreihenfolge ändern möchten, klicken Sie erneut auf die Auslassungspunkte und anschließend auf **Aufsteigend sortieren** oder **Absteigend sortieren**.

## <a name="highlighting-and-cross-filtering"></a>Hervorheben und Kreuzfiltern
Informationen zur Verwendung des Filterbereichs finden Sie unter [Hinzufügen eines Filters zu einem Bericht in Power BI](../power-bi-report-add-filter.md).

Um einen bestimmten Bereich im Diagramm hervorheben, wählen Sie diesen Bereich oder seinen oberen Rahmen aus.  Im Gegensatz zu anderen Visualisierungstypen erfolgt durch Hervorheben eines grundlegenden Flächendiagramms keine Kreuzfilterung der anderen Visualisierungen auf der Berichtsseite (sofern auf derselben Seite weitere Visualisierungen vorhanden sind). Flächendiagramme sind jedoch ein Ziel für das Kreuzfiltern, das von anderen Visualisierungen auf der Berichtsseite ausgelöst wird. 

1. Probieren Sie es aus, indem Sie Ihr Flächendiagramm auswählen und in eine andere Berichtsseite kopieren (mit STRG+C und STRG+V).
2. Wählen Sie eine der schattierten Flächen aus, und wählen Sie dann die andere schattierte Fläche aus. Es sollten keine Auswirkungen auf die anderen Visualisierungen auf der Seite zu sehen sein.

    ![Die ausgewählte Visualisierung für die Verkäufe dieses Jahres als Flächendiagramm](media/power-bi-visualization-basic-area-chart/power-bi-select-area.png)

3. Wählen Sie nun ein Element einer anderen Visualisierung auf der Seite aus, z.B. eine Säule eines Säulendiagramms oder einen Monat in einem Liniendiagramm. Beachten Sie die Auswirkungen auf das Flächendiagramm. Es wird gefiltert.  

    ![Die ausgewählte Säule „Ft Oglethorpe“](media/power-bi-visualization-basic-area-chart/power-bi-filter.png) 

Weitere Informationen finden Sie unter [Interaktionen mit Visuals in einem Power BI-Bericht](../service-reports-visual-interactions.md)


## <a name="considerations-and-troubleshooting"></a>Zu beachtende Aspekte und Problembehandlung   
* [Den Bericht zugänglicher für Menschen mit Behinderungen machen](../desktop-accessibility.md)
* Grundlegende Flächendiagramme sind beim Vergleichen der Werte nicht effektiv, was am Einschluss der überlappenden Bereiche liegt. Power BI verwendet Transparenz, um die Überlappung von Bereichen anzuzeigen. Dies funktioniert jedoch nur mit zwei oder drei unterschiedlichen Bereiche gut. Wenn Sie den Trend für mehr als drei Measures vergleichen möchten, sollten Sie Liniendiagramme verwenden. Wenn Sie das Volumen für mehr als drei Measures vergleichen möchten, sollten Sie Treemaps verwenden.

## <a name="next-step"></a>Nächster Schritt
[Berichte in Power BI](power-bi-visualization-card.md)  

