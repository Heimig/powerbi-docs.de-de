---
title: 'Fehler: Wir konnten nicht in Ihrer Excel-Arbeitsmappe keine Daten gefunden.'
description: 'Fehler: Wir konnten nicht in Ihrer Excel-Arbeitsmappe keine Daten gefunden.'
author: mgblythe
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 04/30/2019
ms.author: mblythe
ms.custom: seodec18
LocalizationGroup: Troubleshooting
ms.openlocfilehash: 6fb02e6cbaca30859aa00f58ae07c9a3fd7f6fe0
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/29/2019
ms.locfileid: "65101426"
---
# <a name="error-we-couldnt-find-any-data-in-your-excel-workbook"></a>Fehler: Wir konnten nicht in Ihrer Excel-Arbeitsmappe keine Daten gefunden.

>[!NOTE]  
>Dieser Artikel gilt für Excel 2007 und höher.

Beim Importieren einer Excel-Arbeitsmappe in Power BI wird möglicherweise die folgende Fehlermeldung angezeigt:

*Fehler: Es konnte nicht als Tabelle formatierten Daten gefunden. Um aus Excel in Power BI-Dienst importieren möchten, müssen Sie die Daten als Tabelle formatieren. Wählen Sie alle Daten in der Tabelle soll, und drücken Sie STRG + T.*

![Daten in Arbeitsmappe nicht gefunden](media/service-admin-troubleshoot-excel-workbook-data/power-bi-we-couldnt-find-any-data.png)

## <a name="quick-solution"></a>Schnelle Lösung
1. Bearbeiten Sie die Arbeitsmappe in Excel.
2. Wählen Sie den Zellenbereich aus, der Ihre Daten enthält. Die erste Zeile sollte die Spaltenüberschriften (Spaltennamen) enthalten.
3. Drücken Sie **STRG+T** , um eine Tabelle zu erstellen.
4. Speichern Sie die Arbeitsmappe.
5. Kehren Sie zu Power BI zurück, und importieren Sie die Arbeitsmappe erneut. Wenn Sie in Excel 2016 arbeiten und die Arbeitsmappe bei OneDrive for Business gespeichert haben, klicken Sie in Excel auf „Datei > Veröffentlichen“.

## <a name="details"></a>Details
### <a name="cause"></a>Ursache
In Excel können Sie aus einem Zellenbereich eine **Tabelle** erstellen, wodurch die Daten einfacher sortiert, gefiltert und formatiert werden können.

Wenn Sie eine Excel-Arbeitsmappe importieren, sucht Power BI nach diesen Tabellen und importiert sie in ein Dataset. Wenn keine Tabellen gefunden werden, wird diese Fehlermeldung angezeigt.

### <a name="solution"></a>Lösung
1. Öffnen Sie die Arbeitsmappe in Excel. 
    >[!NOTE]
    >Die hier verwendeten Abbildungen zeigen Excel 2013. Wenn Sie eine andere Version verwenden, sind die Schritte identisch, die Abbildungen können jedoch leicht abweichen.
    
    ![Arbeitsmappe öffnen](media/service-admin-troubleshoot-excel-workbook-data/power-bi-troubleshoot-excel-worksheet-1.png)
2. Wählen Sie den Zellenbereich aus, der Ihre Daten enthält. Die erste Zeile sollte die Spaltenüberschriften (Spaltennamen) enthalten:
   
    ![Auswählen des Zellbereichs](media/service-admin-troubleshoot-excel-workbook-data/power-bi-troubleshoot-excel-worksheet-2.png)
3. Klicken Sie auf dem Menüband auf der Registerkarte **EINFÜGEN** auf **Tabelle**. (Als Tastenkombination können Sie auch **STRG+T**drücken.)
   
    ![Tabelle einfügen](media/service-admin-troubleshoot-excel-workbook-data/power-bi-troubleshoot-excel-worksheet-3.png)
4. Das folgende Dialogfeld wird angezeigt. Stellen Sie sicher, dass **Meine Tabelle hat Überschriften** aktiviert ist, und klicken Sie dann auf **OK**:
   
    ![Tabelle erstellen](media/service-admin-troubleshoot-excel-workbook-data/power-bi-troubleshoot-excel-create-table.png)
5. Jetzt werden die Daten als Tabelle formatiert:
   
    ![Als Tabelle formatierte Daten](media/service-admin-troubleshoot-excel-workbook-data/power-bi-troubleshoot-excel-table.png)
6. Speichern Sie die Arbeitsmappe.
7. Kehren Sie zu Power BI zurück. Wählen Sie unten im linken Navigationsbereich „Daten abrufen“ aus.
   
    ![Daten abrufen](media/service-admin-troubleshoot-excel-workbook-data/power-bi-get-data.png)
8. Wählen Sie im Feld **Dateien** die Option **Abrufen**aus.
   
    ![Dateien abrufen](media/service-admin-troubleshoot-excel-workbook-data/power-bi-get-files.png)
9. Importieren Sie die Excel-Arbeitsmappe erneut. Dieses Mal sollte der Importvorgang die Tabelle finden und erfolgreich ausgeführt werden.
   
    Wenn der Importvorgang weiterhin fehlschlägt, teilen Sie es uns mit, indem Sie im Hilfemenü auf **Community** klicken:
   
    ![Link „Community“](media/service-admin-troubleshoot-excel-workbook-data/power-bi-question-menu-community.png)
