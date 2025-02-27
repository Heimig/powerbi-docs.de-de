---
title: Herstellen einer Verbindung mit IntelliBoard mithilfe von Power BI
description: IntelliBoard für Power BI
author: SarinaJoan
manager: kfile
ms.reviewer: maggiesMSFT
ms.service: powerbi
ms.subservice: powerbi-template-apps
ms.topic: conceptual
ms.date: 10/16/2017
ms.author: sarinas
LocalizationGroup: Connect to services
ms.openlocfilehash: ab5ded52c6d8d8bfa150ce3f53e89516dc025cb2
ms.sourcegitcommit: 797bb40f691384cb1b23dd08c1634f672b4a82bb
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/12/2019
ms.locfileid: "66838906"
---
# <a name="connect-to-intelliboard-with-power-bi"></a>Herstellen einer Verbindung mit IntelliBoard mithilfe von Power BI
IntelliBoard bietet vereinfachten Zugriff auf Ihre Moodle-Lernmanagementsystem-Daten über Reporting Services. Das IntelliBoard-Inhaltspaket für Power BI bietet zusätzliche Analysen, einschließlich Metriken auf Ihre Kurse, registrierter Benutzer, der Gesamtleistung und Ihrer LMS-Aktivität.

Stellen Sie eine Verbindung mit dem [IntelliBoard-Inhaltspaket](https://app.powerbi.com/getdata/services/intelliboard) für Power BI her.

## <a name="how-to-connect"></a>Herstellen der Verbindung
1. Wählen Sie unten im linken Navigationsbereich **Daten abrufen** aus.  
   
    ![](media/service-connect-to-intelliboard/getdata.png)
2. Wählen Sie im Feld **Dienste** die Option **Abrufen**aus.  
   
    ![](media/service-connect-to-intelliboard/services.png)
3. Wählen Sie **IntelliBoard** und anschließend **Abrufen** aus.  
   
    ![](media/service-connect-to-intelliboard/intelliboard.png)
4. Wählen Sie **OAuth 2** und anschließend **Anmelden** aus. Geben Sie Ihre IntelliBoard-Anmeldeinformationen an, wenn Sie dazu aufgefordert werden.
   
    ![](media/service-connect-to-intelliboard/creds.png)
   
    ![](media/service-connect-to-intelliboard/creds2.png)
5. Sobald Sie verbunden sind, werden ein Dashboard, ein Bericht und ein Dataset automatisch geladen. Anschließend werden die Kacheln mit Daten aus Ihrem IntelliBoard-Konto aktualisiert.
   
    ![](media/service-connect-to-intelliboard/dashboard.png)

**Was nun?**

* Versuchen Sie, am oberen Rand des Dashboards [im Q&A-Feld eine Frage zu stellen](consumer/end-user-q-and-a.md).
* [Ändern Sie die Kacheln](service-dashboard-edit-tile.md) im Dashboard.
* [Wählen Sie eine Kachel aus](consumer/end-user-tiles.md), um den zugrunde liegenden Bericht zu öffnen.
* Zwar ist Ihr Dataset auf tägliche Aktualisierung festgelegt, jedoch können Sie das Aktualisierungsintervall ändern oder über **Jetzt aktualisieren** nach Bedarf aktualisieren.

## <a name="whats-included"></a>Inhalt
Das Inhaltspaket umfasst Daten aus den folgenden Tabellen:  

    - Activity  
    - Agents  
    - Auth (Authentifizierung)  
    - Länder  
    - CoursesProgress (Kursfortschritt)  
    - Enrollments (Registrierungen)
    - Lang (Sprache)  
    - Platform (Plattform)  
    - Totals (Gesamtergebnisse)  
    - UsersProgress (Benutzerfortschritt)    

## <a name="system-requirements"></a>Systemanforderungen
Ein IntelliBoard-Konto mit Berechtigungen für die obigen Tabellen wird benötigt, um dieses Inhaltspaket zu instanziieren.

## <a name="next-steps"></a>Nächste Schritte
[Was ist Power BI?](power-bi-overview.md)

[Grundlegende Konzepte für Designer im Power BI-Dienst](service-basic-concepts.md)

