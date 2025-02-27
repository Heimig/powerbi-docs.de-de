---
title: 'Drittanbieterdienst: Google Analytics-Connector'
description: 'Drittanbieterdienst: Google Analytics-Connector für Power BI Desktop'
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.custom: seodec18
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 05/08/2019
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: ad2c67e73fe8afbd0f379c149181db56f12e9b17
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "65514382"
---
# <a name="google-analytics-connector-for-power-bi-desktop"></a>Google Analytics-Connector für Power BI Desktop
> [!NOTE]
> Das Google Analytics-Inhaltspaket und der Connector in Power BI Desktop basieren auf der Google Analytics Core Reporting-API. Daher können Funktionen und Verfügbarkeit im Laufe der Zeit variieren.

Sie können mithilfe des **Google Analytics**-Connectors eine Verbindung zu Google Analytics-Daten herstellen. Gehen Sie dazu folgendermaßen vor:

1. Wählen Sie in **Power BI Desktop** auf der Registerkarte des Menübands **Start** den Eintrag **Daten abrufen**.
2. Wählen Sie im Fenster **Daten abrufen** aus den Kategorien im linken Bereich **Onlinedienste**.
3. Wählen Sie **Google Analytics** aus der Auswahl im rechten Bereich aus.
4. Wählen Sie am unteren Rand des Fensters **Verbinden**aus.  
   ![](media/service-google-analytics-connector/tps_googleanalytics_1.png)

Es erscheint ein Dialogfeld, in dem neben anderen Klarstellungen erläutert wird, dass der Connector ein Dienst von Drittanbietern ist, und in dem davor gewarnt wird, wie Funktionen und Verfügbarkeit sich im Laufe der Zeit ändern können.  
![](media/service-google-analytics-connector/tps_googleanalytics_2.png)

Wenn Sie **Weiter** wählen, werden Sie dazu aufgefordert, sich bei Google Analytics anzumelden.  
![](media/service-google-analytics-connector/tps_googleanalytics_3.png)

Wenn Sie Ihre Anmeldeinformationen eingeben, wird Ihnen mitgeteilt, dass Power BI den Offlinezugriff möchte. So nutzen Sie **Power BI Desktop** zum Zugriff auf Ihre Google Analytics-Daten.  

Sobald Sie dies akzeptiert haben, zeigt **Power BI Desktop** an, dass Sie derzeit angemeldet sind.  
![](media/service-google-analytics-connector/tps_googleanalytics_5.png)

Wählen Sie **Verbinden**. Ihre Google Analytics-Daten sind mit **Power BI Desktop** verbunden, und die Daten werden geladen.  
![](media/service-google-analytics-connector/tps_googleanalytics_6.png)

## <a name="changes-to-the-api"></a>Änderungen an der API
Obwohl wir versuchen, gemäß allen Änderungen Updates zu veröffentlichen, könnte die API so abgeändert werden, dass sich dies auf die Ergebnisse der generierten Abfragen auswirkt. In einigen Fällen könnten bestimmte Abfragen nicht mehr unterstützt werden. Aufgrund dieser Abhängigkeit können wir die Ergebnisse Ihrer Abfragen nicht garantieren, wenn Sie diesen Connector verwenden.

Weitere Informationen zu Änderungen an der Google Analytics-API finden Sie im [Änderungsprotokoll](https://developers.google.com/analytics/devguides/changelog).

