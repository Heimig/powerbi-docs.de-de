---
title: Ausgehender Datenverkehr in Power BI und Azure
description: Informationen zu den Preisen für ausgehenden Datenverkehr in Azure und Power BI basierend auf dem Standort des Mandanten und Power BI Premium
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 05/08/2019
ms.author: davidi
LocalizationGroup: Data from databases
ms.openlocfilehash: 720ef2f059c3c87be84c3d8db98e89400c161ad0
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "65514403"
---
# <a name="power-bi-and-azure-egress"></a>Ausgehender Datenverkehr in Power BI und Azure

Wenn Sie Power BI mit Azure-Datenquellen verwenden, können Sie Kosten für ausgehenden Azure-Datenverkehr vermeiden, indem Sie darauf achten, dass sich Ihr Power BI-Mandant in derselben Region wie Ihre Azure-Datenquelle befindet.

Wenn Ihr Power BI-Mandant in der gleichen Azure-Region wie Ihre Datenquellen bereitgestellt wird, entstehen keine Kosten für ausgehenden Datenverkehr für geplante Aktualisierungen und DirectQuery-Interaktionen. 

## <a name="determining-where-your-power-bi-tenant-is-located"></a>Bestimmen der Region des Power BI-Mandanten

Im Artikel [Where is my Power BI tenant located?](service-admin-where-is-my-tenant-located.md) erfahren Sie, wie Sie herauszufinden, in welcher Region sich Ihr Power BI-Mandant befindet.

Wenn Sie Multi-Geo von Power BI Premium verwenden und sich ihr Power BI-Mandant nicht in der optimalen Region für einige Azure-basierte Datenquellen befindet, können Sie Multi-Geo von Power BI Premium in der gewünschten Azure-Region bereitstellen und so Ihren Power BI-Mandaten und die Azure-Datenquellen in derselben Azure-Region nutzen.

## <a name="next-steps"></a>Nächste Schritte

Weitere Informationen zu Power BI Premium oder Multi-Geo finden Sie in den folgenden Artikeln:

* [Was ist Microsoft Power BI Premium?](service-premium-what-is.md)
* [Erwerben von Power BI Premium](service-admin-premium-purchase.md)
* [Multi-Geo-Unterstützung für Power BI Premium (Vorschau)](service-admin-premium-multi-geo.md)
* [Wo befindet sich mein Power BI-Mandant?](service-admin-where-is-my-tenant-located.md)
* [Power BI Premium – Häufig gestellte Fragen (FAQ)](service-premium-faq.md)


