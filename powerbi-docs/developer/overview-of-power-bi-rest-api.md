---
title: Was kann ich mit der Power BI-API tun
description: Was kann ich mit der Power BI-API tun
author: rkarlin
ms.author: rkarlin
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-developer
ms.topic: conceptual
ms.date: 03/25/2019
ms.openlocfilehash: fd49c69a14d3dac6b1a045f6aba407ec7aac0deb
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "61269445"
---
# <a name="what-can-developers-do-with-the-power-bi-api"></a>Welche Möglichkeiten bietet die Power BI-API für Entwickler?

Sie können mithilfe der Power BI-REST-API Apps erstellen, die mit Power BI-Berichten, -Dashboards und -Kacheln integriert werden können.

Zudem können Sie die Power BI-REST-API verwenden, um Verwaltungsaufgaben für Power BI-Objekte wie Berichte, Datasets und Arbeitsbereiche auszuführen.

Einige der Möglichkeiten, die die Power BI-APIs bieten:

| **Um mehr zu erfahren** | **Diese Informationen verweisen** |
|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| Einbetten von Dashboards, Berichten und Kacheln für Benutzer, die Power BI verwenden und nicht verwenden | [So können Sie Ihre Power BI-Dashboards, Berichten und Kacheln einbetten ](embedding-content.md) |
| Ausführen von Verwaltungsaufgaben für Power BI-Objekte | [Referenz zur Power BI-REST-API](https://docs.microsoft.com/rest/api/power-bi/) |
| Erweitern eines vorhandenen Geschäftsworkflows, um wichtige Daten per Push in ein Power BI-Dashboard zu übertragen. | [Übertragen von Daten in einem dashboard ](walkthrough-push-data.md) |
| Authentifizieren bei Power BI. | [Authentifizieren bei Powerbi ](get-azuread-access-token.md) |

> [!NOTE]
> Die APIs von Power BI verweisen weiterhin in Gruppen auf Arbeitsbereiche. Alle Verweise auf Gruppen bedeuten, dass Sie mit App-Arbeitsbereichen arbeiten.

## <a name="api-developer-tools"></a>API-Entwicklertools

| Tool(s) | Beschreibung |  |  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|---|---|
| [Arbeiten mit Tools](https://microsoft.github.io/PowerBI-JavaScript/demo) | Sie erhalten ein vollständiges Beispiel zur Verwendung der Power BI-JavaScript-APIs. Mit diesem Tool können Sie schnell verschiedene Arten von Power BI Embedded-Beispielen ausprobieren. |  |  |
| [Power BI-JavaScript-wiki](https://github.com/Microsoft/powerbi-javascript/wiki) | Weitere Informationen zu Power BI-JavaScript-APIs |  |  |
| [Postman](https://www.getpostman.com/) | Zum Ausführen von Anforderungen, zum Testen, Debuggen, Überwachen und Ausführen automatisierter Tests uvm. |

## <a name="push-data-into-power-bi"></a>Übertragen von Daten in Power BI per Push

Sie können die Power BI-API zum [Übertragen von Daten in ein Dataset mithilfe von Push](walkthrough-push-data.md) verwenden. Mithilfe dieser Funktion können Sie eine Zeile zu einer Tabelle in einem Dataset hinzufügen. Die neuen Daten werden dann in Kacheln in einem Dashboard und in Visuals in einem Bericht angezeigt.

![Beispiel für das Übertragen von Daten per Push](media/what-can-you-do/powerbi-push-data.png)

## <a name="github-repositories"></a>GitHub-Repositorys

* [Power BI-Beispiele für Entwickler](https://github.com/Microsoft/PowerBI-Developer-Samples)
* [.NET SDK](https://github.com/Microsoft/PowerBI-CSharp)
* [JavaScript API](https://github.com/Microsoft/PowerBI-JavaScript)

## <a name="next-steps"></a>Nächste Schritte

* [Übertragen von Daten in ein Dataset per Push](walkthrough-push-data.md)
* [Entwickeln eines benutzerdefinierten Visuals für Power BI](custom-visual-develop-tutorial.md)
* [Power BI-REST-API-Referenz](rest-api-reference.md)
* [Power BI-REST-APIs](https://docs.microsoft.com/rest/api/power-bi/)

Weitere Fragen? [Stellen Sie Ihre Frage in der Power BI-Community.](http://community.powerbi.com/)
