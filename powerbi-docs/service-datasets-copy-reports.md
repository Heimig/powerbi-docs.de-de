---
title: 'Kopieren von Berichten aus anderen Arbeitsbereichen (Vorschau): Power BI'
description: Erfahren Sie, wie Sie ein Dataset mit Benutzern in der gesamten Organisation teilen können. Dann können diese in ihren eigenen Arbeitsbereichen Berichte erstellen, die auf Ihrem Dataset basieren.
author: maggiesMSFT
manager: kfile
ms.reviewer: chbraun
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 07/03/2019
ms.author: maggies
LocalizationGroup: Share your work
ms.openlocfilehash: 2db4c23b50071e387913ed79b4d01daeafb928a4
ms.sourcegitcommit: b439ded53bfbbb58be27ecedf93d618f5158df33
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/04/2019
ms.locfileid: "67567385"
---
# <a name="copy-reports-from-other-workspaces-preview"></a>Kopieren von Berichten aus anderen Arbeitsbereichen (Vorschau)

Wenn Sie in einem Arbeitsbereich oder einer App einen Bericht gefunden haben, der Ihnen gefällt, können Sie eine Kopie davon erstellen und sie in einem anderen Arbeitsbereich speichern. Anschließend können Sie diesen Bericht ändern, Visuals und andere Elemente hinzufügen oder löschen. Sie brauchen sich nicht mit der Erstellung des Datenmodells abzugeben. Das wurde bereits für Sie erstellt. Und es ist viel einfacher, einen vorhandenen Bericht zu ändern, als einen von Grund auf neuen zu erstellen. Jedoch können Sie Ihre Kopie des Berichts nicht vom neuen Arbeitsbereich aus in einer App veröffentlichen. Mehr dazu finden Sie in der Liste der weiteren [Überlegungen und Einschränkungen](service-datasets-across-workspaces.md#considerations-and-limitations) im Artikel „Verwenden von Datasets in mehreren Arbeitsbereichen“.

## <a name="save-a-copy-of-a-report"></a>Speichern einer Kopie eines Berichts

1. Navigieren Sie in einer App oder einem Arbeitsbereich zur Listenansicht „Berichte“.

1. Wählen Sie unter **Aktionen** **Kopie speichern** aus.

    ![Speichern einer Kopie eines Berichts](media/service-datasets-copy-reports/power-bi-dataset-save-report-copy.png)

    Sie sehen nur das Symbol **Kopie speichern**, wenn sich der Bericht in einem Arbeitsbereich mit neuer Benutzeroberfläche befindet und Sie über [Erstellungsberechtigungen](service-datasets-build-permissions.md#build-permissions-for-shared-datasets) verfügen. Selbst wenn Sie Zugriff auf den Arbeitsbereich haben, benötigen Sie Erstellungsberechtigungen für das Dataset.

3. Geben Sie dem Bericht in **Eine Kopie dieses Berichts speichern** einen Namen, und wählen Sie den Zielarbeitsbereich aus.

    ![Kopie speichern (Dialogfeld)](media/service-datasets-copy-reports/power-bi-dataset-save-report.png)

    Sie können den Bericht im aktuellen Arbeitsbereich oder einem anderen im Power BI-Dienst speichern. Sie sehen nur Arbeitsbereiche mit neuer Benutzeroberfläche, bei denen Sie Mitglied sind.
  
4. Wählen Sie **Speichern**.

    Wenn Sie eine Kopie des Berichts speichern, erstellen Sie eine Liveverbindung zum Dataset, und Sie können die Oberfläche zur Berichterstellung öffnen und haben das gesamte Dataset zur Verfügung. Sie haben keine Kopie des Datasets erstellt. Das Dataset befindet sich weiterhin an seinem ursprünglichen Speicherort. Sie können alle im Dataset enthaltenen Tabellen und Measures in Ihrem eigenen Bericht verwenden. Es gelten Einschränkungen durch Sicherheit auf Zeilenebene (Row-Level Security, RLS) für das Dataset, sodass Sie nur Daten sehen können, zu deren Anzeige Sie gemäß Ihrer RLS-Rolle berechtigt sind.

    Power BI erstellt automatisch einen Eintrag in der Liste der Datasets, wenn der Bericht auf einem Dataset basiert, das außerhalb des Arbeitsbereichs liegt. Das Symbol für ein solches Dataset unterscheidet sich vom Symbol für Datasets im Arbeitsbereich: ![Symbol „Freigegebenes Dataset“](media/service-datasets-discover-across-workspaces/power-bi-shared-dataset-icon.png)


    Auf diese Weise können Mitglieder des Arbeitsbereichs erkennen, welche Berichte und Dashboards Datasets verwenden, die sich außerhalb des Arbeitsbereichs befinden. Der Eintrag zeigt Informationen über das Dataset und einige ausgewählte Aktionen an.

    ![Datasetaktionen](media/service-datasets-across-workspaces/power-bi-dataset-actions.png)

## <a name="view-related-datasets"></a>Zugehörige Datasets anzeigen

Wenn Sie über einen Bericht in Ihrem Arbeitsbereich verfügen, müssen Sie möglicherweise wissen, auf welchem Dataset er basiert.

1. Wählen Sie in der Listenansicht der Berichte **Verwandte Inhalte anzeigen** aus.

    ![„Verwandte Inhalte anzeigen“](media/service-datasets-copy-reports/power-bi-dataset-view-related.png)

1. Im Dialogfeld **Verwandte Inhalte** werden alle verwandten Elemente angezeigt. In dieser Liste sieht das Dataset aus wie jedes andere. Es lässt sich nicht feststellen, dass es in einem anderen Arbeitsbereich gespeichert ist. Dieses Problem ist bekannt.
 
    ![Verwandte Inhalte (Dialogfeld)](media/service-datasets-copy-reports/power-bi-dataset-related.png)

## <a name="delete-a-report-and-its-shared-dataset"></a>Löschen eines Berichts und seines freigegebenen Datasets

Sie können sich entscheiden, dass Sie den Bericht und sein zugehöriges freigegebenes Dataset nicht mehr im Arbeitsbereich benötigen.

1. Löschen Sie den Bericht. Wählen Sie in der Liste der Berichte im Arbeitsbereich das Symbol **Löschen** aus.

    ![Symbol „Bericht löschen“](media/service-datasets-across-workspaces/power-bi-datasets-delete-report.png)

2. In der Liste der Datasets können Sie sehen, dass es für die freigegebenen Datasets kein Symbol **Löschen** gibt. Aktualisieren Sie die Seite, oder wechseln Sie zu einer anderen Seite, und kehren Sie dann zurück. Das Dataset ist nicht mehr vorhanden. Überprüfen Sie andernfalls **Verwandte Inhalte anzeigen**. Es hat möglicherweise einen Bezug zu einer anderen Tabelle in Ihrem Arbeitsbereich.

    ![„Verwandte Inhalte anzeigen“](media/service-datasets-across-workspaces/power-bi-dataset-view-related-icon.png)

    > [!NOTE]
    > Durch das Löschen des freigegebenen Datasets in diesem Arbeitsbereich wird das Dataset nicht gelöscht. Es löscht nur den Verweis darauf.


## <a name="next-steps"></a>Nächste Schritte

- [Verwenden von Datasets in mehreren Arbeitsbereichen (Vorschau)](service-datasets-across-workspaces.md)
- Haben Sie Fragen? [Stellen Sie Ihre Frage in der Power BI-Community.](http://community.powerbi.com/)
