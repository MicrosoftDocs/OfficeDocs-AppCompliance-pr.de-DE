---
title: Automatisieren Microsoft 365 Zertifizierung mit dem App Compliance Automation Tool für Microsoft 365
description: Verwenden des App Compliance Automation Tool für Microsoft 365 (ACAT) zum Automatisieren der Microsoft 365 Zertifizierung.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: c81ccf3626d6039333f52a487e98233364f7174e
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433433"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Automatisieren Microsoft 365 Zertifizierung mit dem App Compliance Automation Tool für Microsoft 365

Das App Compliance Automation Tool für Microsoft 365 (ACAT) arbeitet mit dem Microsoft 365 App-Complianceprogramm zusammen, um einige der erforderlichen Steuerelemente für die Microsoft 365 Zertifizierung zu erfüllen. Dieser Artikel hilft Ihnen bei den ersten Schritte mit ACAT und verwendet die Compliancebewertungen mit der Microsoft 365 Zertifizierung.

> [!IMPORTANT]
> ACAT befindet sich derzeit in der privaten Vorschau. Wenn Sie am privaten Vorschauprogramm teilnehmen möchten, melden Sie sich [bitte hier](https://aka.ms/acat/private/signup) an.

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>Erstellen Ihres ersten Complianceberichts zum Onboarding von ACAT

Mit ACAT können Sie sich auf die Compliance Ihrer Anwendung oder einer bestimmten Umgebung einer Anwendung (z. B. Produktion, Staging usw.) konzentrieren. Sie können einen **Compliancebericht** erstellen, in dem Sie die Compliancegrenze basierend auf der Cloudinfrastruktur Ihrer Anwendung oder einer bestimmten Umgebung einer Anwendung definieren können.

> [!IMPORTANT]
> Da sich ACAT in der privaten Vorschau befindet, können Sie es *https://portal.azure.com* nicht direkt durchsuchen. Verwenden Sie die folgenden Optionen, um ACAT zu starten.

- Suchen und starten Sie ***das App Compliance Automation Tool für Microsoft 365*** in [Azure-Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D&microsoft_azure_marketplace_ItemHideKey=Microsoft_Azure_AppComplianceAutomationHidden), oder starten Sie es direkt mit [dem Deep-Link von ACAT](https://portal.azure.com/#blade/Microsoft_Azure_AppComplianceAutomation/AcatMenuBlade/overview).
- Wechseln Sie von links zu ***"Berichte*** ".

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="Erstellen eines Complianceberichts":::
   Wechseln Sie zu "Berichte", um einen neuen Compliancebericht zu erstellen. :::image-end:::

- Wählen Sie ***"Neuen Bericht erstellen*** " aus, um mit dem Erstellen Ihres ersten Complianceberichts mit der richtigen Konfiguration zu beginnen. 
    - **Grundlagen**
        - **Berichtsname**: Der Name des Complianceberichts ist erforderlich und kann innerhalb des Mandanten nicht dupliziert werden. Dabei kann es sich um eine Kombination aus Zahlen, Alphabeten und Unterstrichen handeln. Es wird empfohlen, einen aussagekräftigen Namen mit dem Compliancebericht zu verwenden, z. B. die spezifische Anwendung oder Umgebung anzugeben.
        - **Triggerzeit**: ACAT generiert täglich die Compliance-Bewertungen für den Compliancebericht. Diese Konfiguration wird verwendet, um anzugeben, wann die Generierung ausgelöst werden soll. 
        - **Abonnement auswählen**: In der privaten Vorschau können Sie mit ACAT den Umfang des Complianceberichts definieren, indem Sie die Azure-Ressourcen in einem bestimmten Abonnement auswählen. Sie können das richtige Abonnement basierend auf Ihrer Cloudinfrastruktur auswählen. Wenn das Abonnement für Ihre Anwendung nicht in der Liste enthalten ist, müssen Sie die Berechtigung von Ihrem Administrator anfordern. 
        - **Ressourcen auswählen**: Nachdem das Abonnement angegeben wurde, wählen Sie die richtigen Ressourcen basierend auf Ihrer Cloudinfrastruktur aus. Standardmäßig werden alle Ressourcen automatisch ausgewählt. Sie können die Ressourcen auch nach Filtern durchsuchen (z. B. Ressourcengruppe, Tag usw.), und dann die Ressourcen auswählen. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="Grundlegende Konfiguration":::
       Grundlegende Konfiguration für den Compliancebericht :::image-end:::

    - **Microsoft 365 Zertifizierung**: Die Microsoft 365 Zertifizierungskonfiguration ist während der Erstellung optional.  Sie kann später konfiguriert werden, sobald Sie mit der Veröffentlichung Ihrer App beginnen.
        - **Angebots-GUID**: Die Angebots-GUID ist der eindeutige Bezeichner für das Marketplace-Angebot im [Microsoft Partner Network](https://partner.microsoft.com/dashboard). Wählen Sie die Option *"Weitere Informationen* " aus, um eine schrittweise Anleitung zum Abrufen des eindeutigen Bezeichners abzurufen.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365 Zertifizierungskonfiguration":::
       Konfiguration der Microsoft 365-Zertifizierung:::image-end:::

Nachdem Sie die Konfiguration bestätigt und den Compliancebericht erstellt haben, sammelt ACAT die Compliance-bezogenen Daten automatisch aus den folgenden Quellen. 

- Aktivieren Sie die [Microsoft Defender für Cloud](https://azure.microsoft.com/services/defender-for-cloud/) (kostenlose Stufe) für Ihr Abonnement. 
- Aktivieren Sie einige benutzerdefinierte Richtlinien für Ihr Abonnement. 

> [!NOTE]
> Wenn die Erstellung erfolgreich ist, beginnt ACAT mit dem Sammeln und Generieren der Compliancebewertungen für Ihren Compliancebericht ab dem folgenden Tag. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>Überwachen der Compliancebewertungen mit Ihrem Compliancebericht

Mit ACAT können Sie den Laufzeitstatus des Complianceberichts erlernen und die Compliancebewertungen problemlos überwachen. 

- Wechseln Sie von links zu ***"Berichte*** ". Sie können eine kurze Zusammenfassung der vorhandenen Complianceberichte erhalten.
    - **Laufzeitstatus**: Der Laufzeitstatus gibt an, ob ACAT den Compliancebericht in der letzten Generation noch ordnungsgemäß verwaltet. Es gibt drei Zustände für den Laufzeitstatus. 
        - **Aktiv**: Der Compliancebericht wird kontinuierlich und erfolgreich ausgeführt. 
        - **Fehler**: ACAT konnte die Compliancebewertungen für diesen Compliancebericht für die letzte Generation nicht generieren. Dieser Zustand kann aus mehreren Gründen auftreten, z. B. gibt es eine falsche Konfiguration in Ihrem Abonnement, um die an ACAT weitergeleiteten Compliancedaten zu blockieren, es ist ein Systemfehler oder -ausfall bei ACAT aufgetreten usw. 
        - **Deaktiviert**: Dieser Compliancebericht wird von Ihnen manuell deaktiviert (angehalten). Dieses Feature ist in der privaten Vorschau nicht aktiviert. 
    - **Zeitpunkt des letzten und** **nächsten Auslösers**: ACAT generiert täglich die Compliancebewertungen für den Compliancebericht. *Die letzte Triggerzeit* gibt an, wann die letzte Generation ausgelöst wurde, und die *Nächste Triggerzeit* gibt die Triggerzeit für die kommende Generation an. 
    - **Microsoft 365 Zertifizierung**: Grundlegendes zum Status Ihres Complianceberichts für Microsoft 365 Zertifizierungssteuerelemente. Zu den drei Zuständen für den Microsoft 365 Zertifizierungscompliancestatus gehören:
        - **Bestanden**: Es gibt keine Fehler für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente.
        - **Fehler**: Für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
        - **Manuell**: Dieser Zustand umfasst zwei Arten von Steuerelementen: die *teilweise automatisierte manuelle Steuerung* , die teilweise von ACAT automatisiert wird und dennoch manuellen Aufwand erfordert, um Compliance-Nachweise zu sammeln, und die *manuelle Steuerung* , die vollständig manuellen Aufwand erfordert, um Compliance-Nachweise zu sammeln. ACAT automatisiert Teile der Kundenverantwortung für die teilweise automatisierte Steuerung. Sie können den Konformitätsstatus des Zertifikats als Referenz verwenden, aber nicht direkt für Microsoft 365 Zertifizierungsüberwachung verwenden.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="Liste der Compliance-Berichte":::
       Liste der vorhandenen Compliance-Berichte.
    :::image-end:::

Neben dem Erlernen der allgemeinen Zusammenfassung der vorhandenen Complianceberichte können Sie auch die Compliance-Bewertungsdetails mit Ihrem Team in ACAT überwachen. Rufen Sie die Details zur Compliancebewertung für den jeweiligen Compliancebericht ab, indem Sie auf den Namen des Berichts klicken. ACAT zeigt die Details wie unten dargestellt an.

- **Einstellungen**: Sie können die Konfiguration des Complianceberichts mit *Einstellungen* ändern. In der privaten Vorschau können Sie die Microsoft 365 Zertifizierungskonfiguration ändern. 
- **Downloadbericht**: Mit ACAT können Sie die Bewertungen des Complianceberichts als CSV-Dateien in einem Format herunterladen, das für die Zusammenarbeit mit Partnern freigegeben werden kann.
    - **Cloudinfrastrukturinventar**: Diese Datei enthält die Ressourcendetails dieses Complianceberichts. Es kann verwendet werden, um den Cloudinventar Ihrer Anwendung zu beschreiben. 
    - **Microsoft 365 Zertifizierungscompliancebewertung**: Diese Datei enthält die Compliancebewertungen Ihres Complianceberichts aus der Sicht Microsoft 365 Zertifizierungskontrolle. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="Symbolleiste für Compliance-Berichte":::
    Symbolleiste für den Compliancebericht.
:::image-end:::

- **Grundlagen**: In diesem Abschnitt werden der Status und die Konfiguration des Complianceberichts angegeben. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="Grundlagen des Complianceberichts":::
    Grundlagen für den Compliancebericht.
:::image-end:::

- **Bewertungsergebnisse**
    - Der Compliancestatus des Microsoft 365 Zertifizierungssteuerelements ist in fünf Kategorien unterteilt. 
        - **Bestanden**: Es gibt keine Fehler für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente.
        - **Fehler**: Für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
        - **Bestanden – Zusätzliche Nachweise erforderlich**: Es gibt keine Fehler für die teilweise automatisierten Microsoft 365 Zertifizierungssteuerelemente. Sie müssen weiterhin manuell zusätzliche Nachweise für die Steuerelemente sammeln.
        - **Fehler – Zusätzliche Nachweise erforderlich**: Für die teilweise automatisierten Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
        - **Manuelle Steuerung**: ACAT automatisiert keine Kundenverantwortung für die Microsoft 365 Zertifizierungssteuerelemente. 
    - Die Compliancebewertungen werden nach Microsoft 365 Zertifizierungskontrollfamilie und -kontrolle organisiert. 
        - Erfahren Sie mehr über die Details des Compliance-Steuerelements und wie Sie Compliance-Nachweise für die manuelle Steuerung sammeln, indem Sie auf den Namen des Steuerelements klicken. 
        - Wenn Sie die vollautomatisierte und teilweise automatisierte Steuerung erweitern, können Sie weitere Compliancedetails der Kundenverantwortung für dieses Steuerelement erfahren. 
        - Für jede Kundenverantwortung können Sie auch den Compliancestatus verwandter Ressourcen und Korrekturschritte für fehlgeschlagene Ressourcen ermitteln, indem Sie auf die Interaktive Schaltfläche klicken. 
            - **Fehlerhafte Ressourcen**: Sie müssen die Korrekturschritte ausführen, um die fehlerhaften Ressourcen zu beheben. 
            - **Nicht zutreffende Ressourcen**: Sie müssen den GRUND für die Einrichtung der Ressourcen nachverfolgen, und dann kann ACAT die Compliancebewertungen für die Ressourcen sammeln.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="Complianceberichtsbewertungen":::
    Compliancebewertungen für den Compliancebericht.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Verwenden Ihres ersten Complianceberichts mit der Microsoft r365-Zertifizierungsüberwachung

Bevor Sie den Compliancebericht mit Microsoft 365 Zertifizierung verwenden, müssen Sie die Angebots-GUID so konfigurieren, dass der Compliancebericht Ihrem Marketplace-Angebot zugeordnet wird. Es gibt zwei Möglichkeiten: 

- Konfigurieren Sie während des Erstellungsprozesses des Complianceberichts die Angebots-GUID auf *Microsoft 365 Zertifizierungsregisterkarte*. 
- Wenn der Compliancebericht bereits erstellt wurde, wechseln Sie zum *Einstellungen* dieses Complianceberichts, um die Angebots-GUID zu konfigurieren.

Nachdem die Angebots-GUID konfiguriert wurde, wechseln Sie zum [Microsoft Partner Network](https://partner.microsoft.com/dashboard) , um die App-Compliance zu starten. Die *Erstdokumentation* ist die erste Phase der Microsoft 365 Zertifizierung. Wenn Sie in dieser Phase für die Frage, ob Sie ACAT verwenden, " *Ja* " auswählen, können Sie den richtigen Compliancebericht für diese Überwachung auswählen. Die Microsoft 365 Zertifizierung übermittelt automatisch die Compliancebewertungen vollautomatisierter Kontrollen an den Auditor, wodurch Sie Zeit und Mühe sparen. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>Allgemeine Übersicht über Ihre Complianceberichte 

Die ***Übersicht*** gibt Ihnen ein besseres Verständnis des allgemeinen Status für Ihre Complianceberichte. 

- **Laufzeitstatus des Complianceberichts**: In dieser Übersicht erhalten Sie die Statistik des Laufzeitstatus für Ihre Complianceberichte.
    - **Aktiv**: Der Compliancebericht wird kontinuierlich und erfolgreich ausgeführt. 
    - **Fehler**: ACAT konnte die Compliancebewertungen für diesen Compliancebericht in der letzten Generation nicht generieren. Dieser Zustand kann aus mehreren Gründen auftreten, z. B. gibt es eine falsche Konfiguration in Ihrem Abonnement, um die an ACAT weitergeleiteten Compliancedaten zu blockieren, es ist ein Systemfehler oder ein Ausfall mit ACAT aufgetreten usw. 
    - **Deaktiviert**: Dieser Compliancebericht wird von Ihnen manuell deaktiviert (angehalten). Dieses Feature ist in der privaten Vorschau nicht aktiviert. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="Übersicht über den Laufzeitstatus":::
    Übersicht über den Laufzeitstatus des Complianceberichts.
:::image-end:::

- **Aktive Complianceberichte für gesetzliche Vorschriften**: In dieser Übersicht erhalten Sie die Statistik der Complianceergebnisse für jeden *aktiven* Compliancebericht.
    - **Bestanden**: Es gibt keine Fehler für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente.
    - **Fehler**: Für die vollautomatisierten Microsoft 365 Zertifizierungssteuerelemente wurden fehlgeschlagene Kundenverantwortlichkeiten erkannt.
    - **Manuell**: Dieser Zustand umfasst zwei Arten von Steuerelementen: die *teilweise automatisierte manuelle Steuerung* , die teilweise von ACAT automatisiert wird und dennoch manuellen Aufwand erfordert, um Compliance-Nachweise zu sammeln, und die *manuelle Steuerung* , die vollständig manuellen Aufwand erfordert, um Compliance-Nachweise zu sammeln. ACAT automatisiert Teile der Kundenverantwortung für die teilweise automatisierte Steuerung. Sie können den Konformitätsstatus des Zertifikats als Referenz verwenden, aber nicht direkt für Microsoft 365 Zertifizierungsüberwachung verwenden.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="Übersicht über den Compliancestatus":::
    Übersicht über den Compliancestatus für aktive Complianceberichte.
:::image-end:::

## <a name="troubleshooting"></a>Problembehandlung 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>Warum ist der erstellte Compliancebericht aufgrund eines Autorisierungsfehlers fehlgeschlagen? 

Beim Erstellen eines Complianceberichts richtet ACAT eine Umgebung mit Ihrem Abonnement ein, um die Compliancedaten automatisch zu sammeln, und diese Aktion erfordert eine bestimmte Berechtigung des Abonnements. Sie können Ihre Abonnementberechtigung wie unten beschrieben überprüfen. 

- Suchen und starten Sie die **Abonnements** in [Azure-Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
- Wechseln Sie zu dem Abonnement, das Sie zum Erstellen des Complianceberichts verwenden möchten. 
- Wechseln Sie auf der linken Seite zum **Zugriffssteuerelement (Access Control, IAM** ). 
- Wählen Sie **"Meinen Zugriff anzeigen** " aus, um Ihre Berechtigung zu überprüfen.
    - Wenn Ihre Organisation [integrierte Azure-Rollen](/azure/role-based-access-control/built-in-roles) verwendet, sollten Ihre Rollenzuweisungen mindestens eine der folgenden Rollen enthalten:
        - [Ressourcenrichtlinienmitwirkender](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) und [Sicherheitsadministrator](/azure/role-based-access-control/built-in-roles#security-admin)
        - Andere Rollenzuweisung mit höheren Berechtigungen (z. B. [Besitzer](/azure/role-based-access-control/built-in-roles#owner) usw.)

### <a name="how-to-report-an-acat-issue-or-warning"></a>Wie melden Sie ein ACAT-Problem oder eine Warnung? 

Wenn ein Problem in ACAT auftritt und Sie sich an das [private ACAT-Vorschauprogramm](mailto:acatprivatepreview@microsoft.com) wenden möchten, benötigen wir Ihre Hilfe, um die Beweise zu sammeln, um Ihr Szenario besser zu verstehen.

- Abrufen der Details des ACAT-Fehlers oder der ACAT-Warnung
    - Wechseln Sie zu den **Benachrichtigungen** über [Azure-Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Weitere **Ereignisse im Aktivitätsprotokoll auswählen** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="ACAT-Benachrichtigungen":::
        Wechseln Sie zum Aktivitätsprotokoll, um ACAT-Benachrichtigungen zu überprüfen.
    :::image-end:::
    
    - Ändern Sie den **Zeitbereich** ordnungsgemäß, um Den ACAT-Fehler oder die ACAT-Warnung im Aktivitätsprotokoll herauszufiltern. 
    - Ermitteln Sie Ihren ACAT-Fehler oder Ihre ACAT-Warnung, wählen Sie aus, um die Details abzurufen und die Details als Datei zu speichern.
    
- Überprüfen Sie, ob Ihr Abonnement von ACAT ordnungsgemäß eingerichtet wurde. 
    - Suchen und starten Sie die **Abonnements** in [Azure-Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Wechseln Sie zu dem Abonnement, das Sie zum Erstellen des Complianceberichts verwenden möchten. 
    - Wählen Sie **"Ressourcenanbieter"** aus, um zu überprüfen, ob der Status dieser Anbieter *registriert* ist.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Zurück [Azure-Portal,](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) und starten **Sie Resource Graph Explorer**.
    - **Neue Abfrage** auswählen
    - Führen Sie diese Abfrage aus, um die Richtlinienzuweisung zu überprüfen und das Ergebnis als CSV herunterzuladen. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - Führen Sie diese Abfrage aus, um die Automatisierung zu überprüfen und das Ergebnis als CSV herunterzuladen.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - Führen Sie diese Abfrage aus, um die Bewertung zu überprüfen und das Ergebnis als CSV herunterzuladen. Sie müssen den Platzhalter ***"Your-subscriptionId"*** durch das bestimmte Abonnement ersetzen, das Sie abfragen möchten.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```