---
title: App Compliance Automation Tool für Microsoft 365
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: App Compliance Automation Tool für Microsoft 365 Übersicht
keywords: Microsoft 365 der App-Zertifizierungsautomatisierung
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 5e3fbc062c1887a205a7b99a85a292ad9a64f8d0
ms.sourcegitcommit: 0865622c8abffc11115e56d966729e5318d67ab9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/20/2022
ms.locfileid: "65608805"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>App Compliance Automation Tool für Microsoft 365
In diesem Artikel erfahren Sie, was das App Compliance Automation Tool für Microsoft 365 (ACAT) ist und wie es die Compliance vereinfacht und die Microsoft 365 Zertifizierung erhält.

> [!IMPORTANT]
> ACAT befindet sich derzeit in der privaten Vorschau. Wenn Sie am privaten Vorschauprogramm teilnehmen möchten, melden Sie sich [bitte hier](https://aka.ms/acat/private/signup) an.

> [!NOTE]
> Wenn Sie Feedback zu einer privaten ACAT-Vorschau geben möchten, können Sie mit diesem [Formular](https://aka.ms/acat/feedback) beginnen. Das ACAT-Produktteam wird Sie so schnell wie möglich weiter verfolgen, sobald wir Ihre Nachrichten erhalten haben. 

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>Was ist das App Compliance Automation Tool für Microsoft 365
Das App Compliance Automation Tool für Microsoft 365 (ACAT) ist ein Dienst im Azure-Portal, der die Compliance-Reise für jede App vereinfacht, die Microsoft 365 Kundendaten nutzt und über das Partner Center veröffentlicht wird. Das App Compliance Automation Tool für Microsoft 365 ist ein anwendungsorientiertes Complianceautomatisierungs-Tool, mit dem Sie Microsoft 365 Zertifizierung einfacher und bequemer abschließen können. In der privaten Vorschau ist ACAT für Apps verfügbar, die in Azure ausgeführt werden.

Mit diesem Tool können Sie schnell die Compliancegrenze für Ihre Anwendungen definieren, die Complianceergebnisse automatisch überwachen und die Complianceüberwachung einfacher abschließen. Die Compliancegrenze ist die Cloudinfrastruktur, die die Bereitstellung der App und aller Back-End-Systeme unterstützt, mit denen die App möglicherweise kommuniziert.

ACAT bietet nicht nur einen schnelleren Überblick über Microsoft 365 Zertifizierung, sie kann Ihnen auch bei verschiedenen Complianceszenarien für Microsoft 365 Anwendungen helfen:

- Detaillierte Ansichts- und Korrekturschritte für Microsoft 365 Zertifizierungsaufgaben.
- Automatische tägliche Berichte, die Ihnen helfen, kontinuierlich Complianceergebnisse zu erhalten.
- Bewährte Methoden für Sicherheit und Compliance, die als Leitfaden in der frühen Phase Ihres Anwendungslebenszyklus verwendet werden können.

## <a name="benefits-of-acat"></a>Vorteile von ACAT
Anwendungsorientierte Compliance-Reise.
- ACAT meldet täglich den Compliancestatus für die Cloudumgebung Ihrer Anwendungen, die Sie in Ihre aktuelle Cloudinfrastruktur-Compliancestrategie integrieren können.
- Entwickler können ACAT auch während der App-Entwicklungsphase aufrufen.

Beschleunigt den Prozess der Zertifizierung Microsoft 365.
- ACAT automatisiert bestimmte Microsoft 365 Zertifizierungssteuerelemente vollständig.
- Es gibt eine ständig wachsende Automatisierungsliste, die von Microsoft aktiv entwickelt wird.

Native Integration in Microsoft 365 Zertifizierungsworkflow.
- ACAT ist für Microsoft 365 Zertifizierungszwecke vollständig in das Partner Center integriert.

## <a name="concepts-of-acat"></a>Konzepte von ACAT
### <a name="regulatory-compliance-report"></a>Bericht zur Einhaltung gesetzlicher Vorschriften 
In ACAT können Sie den Compliancestatus der Anwendung überwachen, indem Sie dafür einen Compliancebericht erstellen. Sie können die Compliancegrenze für Ihre Anwendung definieren, indem Sie die Azure-Ressourcen angeben, die die Anwendung erstellen. Erstellen Sie mehrere Berichte für eine Anwendung, basierend auf unterschiedlichen Entwicklungsumgebungen und Phasen.

Nachdem der Bericht erstellt wurde, beginnt ACAT, die Compliancedaten zu Ihrer vordefinierten Auslösezeit zu sammeln und dann die Complianceergebnisse als Bericht für Sie zu generieren. In der Zwischenzeit überwacht ACAT die Complianceänderungen für Ihren Compliancebericht kontinuierlich, bis Sie sich entscheiden, den Bericht zu löschen.

### <a name="microsoft-365-certification-control-results"></a>Ergebnisse der Microsoft 365 Zertifizierungskontrolle
Im Bericht über die Einhaltung gesetzlicher Vorschriften werden die Complianceergebnisse nach Steuerelementen organisiert, deren entsprechende Zustände von ACAT gekennzeichnet sind:
- **Bestanden**: Es gibt keine Fehler für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente.
- **Fehler**: Für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
- **Bestanden – Zusätzliche Nachweise erforderlich**: Es gibt keine Fehler für die *teilweise automatisierten* Microsoft 365 Zertifizierungssteuerelemente.
- **Fehler – Zusätzliche Nachweise erforderlich**: Für die *teilweise automatisierten* Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
- **Manuelle Steuerung**: ACAT automatisiert keine Kundenverantwortung für die Microsoft 365 Zertifizierungssteuerelemente.

### <a name="customer-responsibility"></a>Verantwortlichkeit des Kunden
Jedem Steuerelement sind eine Reihe von Kundenverantwortlichkeiten zugeordnet, die erfüllt werden müssen. Sie sind Verantwortlichkeiten, die Von Ihnen in den folgenden Bereichen aufbewahrt werden: Daten, Endpunkte, Konto, Zugriffsverwaltung usw.

ACAT sammelt Daten für jede Kundenverantwortung und gibt dafür ein Bewertungsergebnis zurück. Es bietet Ihnen auch eine Abhilfemaßnahme, die unsere Anleitung ist, die Ihnen hilft, Microsoft 365 Zertifizierungsstandards einzuhalten.


## <a name="faq"></a>Häufig gestellte Fragen
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>Was sind manuelle Und teilweise automatisierte Steuerelemente?
Jedes Compliance-Steuerelement ist einer Reihe von Kundenverantwortlichkeiten zugeordnet, für die ACAT Compliancedaten sammelt. Ab sofort werden jedoch nicht alle Steuerelemente für Microsoft 365 Zertifizierung von ACAT abgedeckt (es wird kontinuierlich versucht, die Abdeckung zu erweitern). Für die teilweise automatisierte Steuerung automatisiert ACAT Teile der Kundenverantwortung. Sie können den Konformitätsstatus des Zertifikats als Referenz verwenden, aber nicht direkt für Microsoft 365 Zertifizierungsüberwachung verwenden. Bei den manuellen Steuerelementen automatisiert ACAT derzeit keine Kundenaufgaben.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>Ich habe die vorgeschlagenen Änderungen basierend auf dem Korrekturvorschlag vorgenommen, aber das Steuerelement schlägt immer noch fehl.
Nachdem Sie maßnahmen zum Beheben des Fehlers ausgeführt haben, müssen Sie warten, bis ACAT die aktualisierten Bewertungsergebnisse abruft, um den Steuerelementstatus zu aktualisieren. Bewertungen werden alle 24 Stunden zur voreingestellten Triggerzeit ausgeführt.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>Wie wird der Compliancebericht im Zertifizierungsprozess verwendet?
ACAT ist nahtlos in [Partner Center](https://partner.microsoft.com/dashboard) integriert, um Ihre Microsoft 365 Zertifizierungsreise abzuschließen. Während der Erstellung des Complianceberichts können Sie die Microsoft 365 Zertifizierungskonfiguration bearbeiten, d. h. die Angebots-GUID. Es ist optional während der Erstellung, und Sie können es später konfigurieren, wenn Sie mit der Veröffentlichung der Anwendung beginnen.

## <a name="learn-more"></a>Weitere Informationen

* [Erste Schritte mit ACAT](https://aka.ms/acat/getstarted)
* [Weitere Informationen zur Microsoft 365 Zertifizierung](https://aka.ms/acat/m365cert)
