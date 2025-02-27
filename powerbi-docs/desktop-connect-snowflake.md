---
title: Herstellen einer Verbindung mit einem Snowflake Computing-Warehouse in Power BI Desktop
description: Sie können in Power BI Desktop einfach eine Verbindung mit einem Snowflake Computing-Warehouse herstellen und dieses verwenden
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 05/08/2019
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: c02eda44ec81fe31972055548996ae357bc4c4b9
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "65513827"
---
# <a name="connect-to-snowflake-in-power-bi-desktop"></a>Verbinden mit Snowflake in Power BI Desktop
In Power BI Desktop können Sie eine Verbindung mit einem **Snowflake Computing**-Warehouse herstellen und die zugrunde liegenden Daten wie jede andere Datenquelle in Power BI Desktop verwenden. 

> [!NOTE]
> Sie *müssen* zudem auf Computern, die den **Snowflake**-Connector verwenden, den **Snowflake-ODBC-Treiber installieren.** Dessen Architektur – 32 Bit oder 64 Bit – muss der Installation von **Power BI Desktop** entsprechen. Klicken Sie einfach auf den folgenden Link und [laden Sie den entsprechenden Snowflake-ODBC-Treiber herunter](http://go.microsoft.com/fwlink/?LinkID=823762).
> 
> 

## <a name="connect-to-a-snowflake-computing-warehouse"></a>Verbinden mit einem Snowflake Computing-Warehouse
Klicken Sie in Power BI Desktop im Menüband **Start** auf **Daten abrufen**, um eine Verbindung mit einem **Snowflake Computing**-Warehouse herzustellen. Wählen Sie in den Kategorien auf der linken Seite **Datenbank** aus. Anschließend wird **Snowflake** angezeigt.

![](media/desktop-connect-snowflake/connect_snowflake_2b.png)

Geben Sie im angezeigten Fenster **Snowflake** den Namen des Snowflake Computing-Warehouse in das Feld ein, oder fügen Sie ihn ein, und klicken Sie auf **OK**. Sie können Daten entweder direkt in Power BI **importieren** oder **DirectQuery** verwenden. Weitere Informationen finden Sie unter [Verwendung von DirectQuery](desktop-use-directquery.md).

![](media/desktop-connect-snowflake/connect_snowflake_3.png)

Wenn Sie dazu aufgefordert werden, geben Sie Ihren Benutzernamen und Ihr Kennwort ein.

![](media/desktop-connect-snowflake/connect_snowflake_4.png)

> [!NOTE]
> Wenn Sie Ihren Benutzernamen und Ihr Kennwort für einen bestimmten **Snowflake**-Server eingefügt haben, werden von Power BI Desktop für anschließende Verbindungen die gleichen Anmeldeinformationen verwendet. Sie können diese Anmeldeinformationen unter **Datei > Optionen und Einstellungen > Datenquelleneinstellungen** ändern.
> 
> 

Nachdem die Verbindung erfolgreich hergestellt wurde, wird das Fenster **Navigator** mit den auf dem Server verfügbaren Daten angezeigt. Aus diesen können Sie ein oder mehrere Elemente auswählen, die importiert und in **Power BI Desktop** verwendet werden sollen.

![](media/desktop-connect-snowflake/connect_snowflake_5.png)

Sie können die ausgewählte Tabelle **laden**, um die gesamte Tabelle in **Power BI Desktop** zu importieren, oder Sie können die Abfrage **bearbeiten**. Wenn Sie „Bearbeiten“ auswählen, wird der **Abfrage-Editor** geöffnet, sodass Sie den Satz der zu verwendenden Daten filtern und aufbereiten können, um diesen aufbereiteten Satz von Daten anschließend in **Power BI Desktop** zu laden.

## <a name="next-steps"></a>Nächste Schritte
Sie können mithilfe von Power BI Desktop eine Verbindung mit Daten jeglicher Art herstellen. Weitere Informationen zu Datenquellen finden Sie in folgenden Ressourcen:

* [Was ist Power BI Desktop?](desktop-what-is-desktop.md)
* [Datenquellen in Power BI Desktop](desktop-data-sources.md)
* [Strukturieren und Kombinieren von Daten mit Power BI Desktop](desktop-shape-and-combine-data.md)
* [Verbinden mit Excel in Power BI Desktop](desktop-connect-excel.md)   
* [Eingeben von Daten direkt in Power BI Desktop](desktop-enter-data-directly-into-desktop.md)   

