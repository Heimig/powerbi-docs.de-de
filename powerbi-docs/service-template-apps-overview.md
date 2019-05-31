---
title: Was sind Power BI-Vorlagen-Apps? (Vorschau)
description: Dieser Artikel enthält eine Übersicht über Vorlagen-Apps in Power BI. Erfahren Sie, wie Sie Power BI-Apps ohne oder mit nur wenig Code erstellen, und diese dann für Power BI-Kunden bereitstellen.
author: maggiesMSFT
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-service
ms.topic: conceptual
ms.date: 04/26/2019
ms.author: maggies
ms.openlocfilehash: 0ea8f19fa36bf1f9ceb5f8f0b92bd53ebdfa2a01
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "64578526"
---
# <a name="what-are-power-bi-template-apps-preview"></a>Was sind Power BI-Vorlagen-Apps? (Vorschau)

Mit den neuen *Vorlagen-Apps* von Power BI können Power BI-Partner Power BI-Apps ohne oder mit nur wenig Code erstellen und für Power BI-Kunden bereitstellen.  Dieser Artikel enthält eine Übersicht über Vorlagen-Apps in Power BI.

Vorlagen-Apps sind ein Ersatz für die aktuellen Dienstinhaltspakete. Als Power BI-Partner erstellen Sie sofort verfügbare Inhalte für Ihre Kunden und veröffentlichen diese selbst.  

Sie können Vorlagen-Apps erstellen, mit denen Ihre Kunden eine Verbindung mit ihren eigenen Konten herstellen und diese instanziieren können. Als Domänenexperten können sie die Daten so freigeben, dass diese von ihren Geschäftskunden mühelos genutzt werden können.  

Sie übermitteln Ihre Vorlage apps zu Cloud-Partnerportal. Die Apps werden dann im Power BI-App-Katalog (app.powerbi.com/getdata/services) und in Microsoft AppSource (appsource.microsoft.com) öffentlich zur Verfügung gestellt. So sieht ein allgemeinen Überblick über die Umgebung für die Erstellung der app die public-Vorlage aus.  

## <a name="process"></a>Verfahren
Der allgemeine Prozess zum Entwickeln und übermitteln die Vorlagen-app umfasst mehrere Phasen. Einige Phasen können mehr als eine Aktivität zur gleichen Zeit enthalten.


| Phase | Power BI Desktop |  |Power BI-Dienst  |  |Cloud-Partnerportal  |
|---|--------|--|---------|---------|---------|
| **Eins** | Erstellen Sie ein Datenmodell und einen Bericht in einer PBIX-Datei. |  | Erstellen Sie einen Arbeitsbereich, importieren Sie die PBIX-Datei, und erstellen Sie ein komplementäres Dashboard.  |  | Registrieren Sie sich als Partner |
| **Zwei** |  |  | Erstellen Sie ein Testpaket, und führen Sie die interne Validierung aus.        |  | |
| **Drei** | |  | Stufen Sie das Testpaket auf die Präproduktion für die Validierung außerhalb Ihres Power BI-Mandanten auf, und übermitteln Sie es an AppSource.  |  | Erstellen Sie ein Angebot für Ihre Power BI-Vorlagen-App mit Ihrem Präproduktionspaket, und starten Sie den Validierungsprozess. |
| **Vier** | |  | Stufen Sie das Präproduktionspaket zur Produktion auf. |  | Schalten Sie die App „Live“. |

## <a name="requirements"></a>Anforderungen

Zum Erstellen der Vorlagen-App benötigen Sie zunächst die erforderlichen Berechtigungen. Informationen dazu finden Sie in den Vorlagen-App-Einstellungen im Power BI-Verwaltungsportal. 

Zum Veröffentlichen einer Vorlagen-App im Power BI-Dienst und in AppSource müssen Sie die Anforderungen unter [Weg zum Cloud Marketplace-Herausgeber](https://docs.microsoft.com/azure/marketplace/become-publisher) erfüllen.
 
## <a name="high-level-steps"></a>Allgemeine Schritte

Im Folgenden werden die allgemeinen Schritte aufgeführt. 

1. [Überprüfen Sie die Anforderungen](#requirements), um sicherzustellen, dass Sie sie erfüllen. 

1. Erstellen Sie einen Bericht in Power BI Desktop. Verwenden Sie Parameter, damit Sie den Bericht als Datei speichern können, die von anderen benutzt werden kann. 

1. Erstellen Sie einen Arbeitsbereich für Ihre Vorlagen-App in Ihrem Mandanten im Power BI-Dienst (app.powerbi.com). 

1. Importieren Sie Ihre PBIX-Datei, und fügen Sie Inhalte, z.B. ein Dashboard, zu Ihrer App hinzu. 

1. Erstellen Sie ein Testpaket, um die Vorlagen-App innerhalb Ihrer Organisation selbst zu testen. 

1. Stufen Sie die Test-App zur Präproduktion auf, um die App für die Validierung an AppSource zu übermitteln und sie außerhalb Ihres eigenen Mandanten zu testen. 

1. Übermitteln Sie den Inhalt zur Veröffentlichung an das Cloud-Partnerportal. 

1. Stellen Sie Ihr Angebot in AppSource „Live“, und verschieben Sie Ihre App in Power BI in die Produktion.
2. Sie können jetzt mit der Entwicklung der nächsten Version im gleichen Arbeitsbereich in der Präproduktion beginnen. 

## <a name="requirements"></a>Anforderungen

Zum Erstellen der Vorlagen-App benötigen Sie zunächst die erforderlichen Berechtigungen. Details finden Sie unter Power BI-[Verwaltungsportal > Vorlagen-App-Einstellungen](service-admin-portal.md#template-apps-settings-preview). 

Zum Veröffentlichen einer Vorlagen-App im Power BI-Dienst und in AppSource müssen Sie die Anforderungen unter [Weg zum Cloud Marketplace-Herausgeber](https://docs.microsoft.com/azure/marketplace/become-publisher) erfüllen.

## <a name="tips"></a>Tipps 

- Stellen Sie sicher, dass Ihre App Beispieldaten enthält, damit sie mit nur einem Klick verwendet werden kann. 
- Überprüfen Sie Ihre Anwendung sorgfältig, indem Sie sie in Ihrem Mandanten und einem sekundären Mandanten installieren. Stellen Sie sicher, dass Kunden nur das angezeigt bekommen, was sie sehen sollen. 
- Verwenden Sie AppSource als Onlineshop zum Hosten Ihrer Anwendung. Auf diese Weise können alle Power BI-Benutzer Ihre App finden. 
- Erwägen Sie die Bereitstellung mehrerer Vorlagen-Apps für verschiedene spezifische Szenarios. 
- Aktivieren Sie die Datenanpassung, um beispielsweise benutzerdefinierte Verbindungs- und Parameterkonfiguration durch den Installer zu unterstützen.

Weitere Vorschläge finden Sie unter [Tips for authoring template apps in Power BI (preview) (Tipps für die Erstellung von Vorlagen-Apps in Power BI (Vorschau))](service-template-apps-tips.md).

## <a name="support"></a>Support
Unterstützung während der Entwicklung finden Sie unter [https://powerbi.microsoft.com/support](https://powerbi.microsoft.com/support). Diese Website wird aktiv überwacht und verwaltet. Kundenanfragen werden schnell an das entsprechende Team weitergeleitet.

## <a name="next-steps"></a>Nächste Schritte

[Create a template app (Erstellen einer Vorlagen-App)](service-template-apps-create.md)