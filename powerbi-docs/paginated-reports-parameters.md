---
title: Erstellen von Parametern für paginierte Berichte im Power BI-Dienst
description: In diesem Artikel erfahren Sie, wie Sie Parameter für paginierte Berichte im Power BI-Dienst erstellen.
author: maggiesMSFT
ms.author: maggies
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: report-builder
ms.topic: conceptual
ms.date: 06/06/2019
ms.openlocfilehash: adec7af0032772022a330e3ab25377205de9ace5
ms.sourcegitcommit: 797bb40f691384cb1b23dd08c1634f672b4a82bb
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/12/2019
ms.locfileid: "66838980"
---
# <a name="create-parameters-for-paginated-reports-in-the-power-bi-service"></a>Erstellen von Parametern für paginierte Berichte im Power BI-Dienst

In diesem Artikel erfahren Sie, wie Sie Parameter für paginierte Berichte im Power BI-Dienst erstellen.  Mit Berichtsparametern können Sie Berichtsdaten auswählen und die Berichtsdarstellung anpassen. Sie haben die Möglichkeit, einen Standardwert und eine Liste der verfügbaren Werte anzugeben, auf deren Grundlage Ihre Berichtsleser die Auswahl ändern.  

Die folgende Abbildung zeigt die Designansicht im Power BI-Berichts-Generator für einen Bericht mit den Parametern @BuyingGroup, @Customer, @FromDate und @ToDate. 
  
![Parameter im Berichts-Generator](media/paginated-reports-parameters/power-bi-paginated-parameters-report-builder.png)
  
1.  Die Berichtsparameter im Bereich „Berichtsdaten“.  
  
2.  Die Tabelle mit einem Parameter im Dataset.  
  
3.  Der Bereich „Parameter“. Im Bereich „Parameter“ können Sie das Layout von Parametern anpassen. 
  
4.  Die Parameter @FromDate und @ToDate verfügen über den Datentyp **DateTime**. Beim Anzeigen des Berichts können Sie ein Datum in das Textfeld eingeben oder im Kalendersteuerelement auswählen. 

5.  Ein Parameter im Dialogfeld **Dataseteigenschaften**.  

  
## <a name="create-or-edit-a-report-parameter"></a>Erstellen oder Bearbeiten eines Berichtsparameters  
  
1.  Öffnen Sie Ihren paginierten Bericht im Power BI-Berichts-Generator.

1. Klicken Sie im Bereich **Berichtsdaten** mit der rechten Maustaste auf den Knoten **Parameter** > **Parameter hinzufügen**. Daraufhin wird das Dialogfeld **Berichtsparametereigenschaften** geöffnet.  
  
2.  Geben Sie unter **Name** einen Namen für den Parameter ein, oder übernehmen Sie den Standardnamen.  
  
3.  Geben Sie unter **Eingabeaufforderung** Text ein, der beim Ausführen des Berichts durch den Benutzer neben dem Textfeld „Parameter“ angezeigt wird.  
  
4.  Wählen Sie unter **Datentyp** den Datentyp für den Parameterwert aus.  
  
5.  Wenn für den Parameter ein leerer Wert ausgewählt werden darf, wählen Sie **Leeren Wert zulassen** aus.  
  
6.  Wenn für den Parameter ein Nullwert ausgewählt werden darf, wählen Sie **Nullwert zulassen** aus.  
  
7.  Damit Benutzer mehrere Werte für den Parameter auswählen können, wählen Sie **Mehrere Werte zulassen** aus.  
  
8.  Legen Sie die Sichtbarkeitsoption fest.  
  
    -   Um den Parameter in der Symbolleiste oben im Bericht anzuzeigen, wählen Sie **Sichtbar** aus.  
  
    -   Um den Parameter auszublenden, sodass er nicht in der Symbolleiste angezeigt wird, wählen Sie **Ausgeblendet** aus.  
  
    -   Um den Parameter auszublenden und vor Änderungen auf dem Berichtsserver nach der Veröffentlichung des Berichts zu schützen, wählen Sie **Intern** aus. Der Berichtsparameter lässt sich dann nur noch in der Berichtsdefinition anzeigen. Bei dieser Option müssen Sie einen Standardwert festlegen oder einen Nullwert für den Parameter zulassen.  
  
9. Wählen Sie **OK**aus. 
  
## <a name="next-steps"></a>Nächste Schritte

Unter [Anzeigen von Parametern für paginierte Berichte](paginated-reports-view-parameters.md) erfahren Sie, wie die Parameter im Power BI-Dienst angezeigt werden.

Ausführliche Informationen zu Parametern in paginierten Berichten finden Sie unter [Report parameters in Power BI Report Builder (Berichtsparameter im Power BI-Berichts-Generator)](report-builder-parameters.md).
