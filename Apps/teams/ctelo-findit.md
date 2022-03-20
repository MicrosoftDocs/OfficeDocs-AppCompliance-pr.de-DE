---
title: Anwendungsinformationen für Findit von CTELO
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/14/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Findit, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 103c9a2a461951dde50d8f1a564834a51d741d91
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/17/2022
ms.locfileid: "63553484"
---
# <a name="findit"></a>Findit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 25, 2022</p>

* <a href="https://teams.microsoft.com/l/app/ccb8d21c-9c7b-492f-b372-438621384db8" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003849" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von CTELO für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Findit |
| ID | WA200003849 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | CTELO |
| Website des Unternehmens | [https://www.ctelo.com](https://www.ctelo.com) |
| Nutzungsbedingungen der App | [https://www.ctelo.com/terms-conditions](https://www.ctelo.com/terms-conditions) |
| Kernfunktionen der App | Hier finden Sie kostenlose Kalenderplätze für Kollegen, Teams Status und Kontaktinformationen. |
| Firmenstandort | Norwegen |
| Seite "App-Informationen" | |
| Welche Hostingumgebung oder welches Dienstmodell wird zum Ausführen Ihrer App verwendet? | Iaas |
| Welche Hosting-Cloudanbieter verwendet die App? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von CTELO darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

| **Information** | **Response** |
|:----------------|:-------------|
| Verarbeitet die App oder die zugrunde liegende Infrastruktur Daten, die sich auf einen Microsoft-Kunden oder sein Gerät beziehen? | Ja |
| Welche Daten werden von Ihrer App verarbeitet? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| Unterstützt die App TLS 1.1 oder höher? | Ja |
| Speichert die App oder die zugrunde liegende Infrastruktur Microsoft-Kundendaten? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

| **Information** | **Response** |
|:----------------|:-------------|
| Führen Sie jährliche Penetrationstests für die App durch? | Nein |
| Verfügt die App über einen dokumentierten Notfallwiederherstellungsplan, einschließlich einer Sicherungs- und Wiederherstellungsstrategie? | Ja |
| Verwendet Ihre Umgebung herkömmliche Anti-Malware-Schutz- oder Anwendungssteuerelemente? | ApplicationControls |
| Verfügen Sie über einen etablierten Prozess für die Einrückung und Risikobewertung von Sicherheitsrisiken? | Nein |
| Verfügen Sie über eine Richtlinie, die Ihren Service Level Agreement (SLA) für das Anwenden von Patches regelt? | Ja |
| Führen Sie Patchverwaltungsaktivitäten gemäß Ihren Patchrichtlinien-SLAs aus? | Ja |
| Verfügt Ihre Umgebung über nicht unterstützte Betriebssysteme oder Software? | Nein |
| Führen Sie vierteljährliche Sicherheitsrisikoüberprüfungen für Ihre App und die Struktur durch, die sie unterstützt? | Nein |
| Haben Sie eine Firewall an Der Grenze für das externe Netzwerk installiert? | Ja |
| Haben Sie einen eingerichteten Change Management-Prozess verwendet, um Änderungsanforderungen zu überprüfen und zu genehmigen, bevor sie in der Produktion bereitgestellt werden? | Ja |
| Überprüft und genehmigt eine zusätzliche Person alle Codeänderungsanforderungen, die vom ursprünglichen Entwickler an die Produktion übermittelt wurden? | Ja |
| Berücksichtigen sichere Codierungspraktiken allgemeine Sicherheitsrisikoklassen wie OWASP Top 10? | Ja |
| Mehrstufige Authentifizierung (MFA) aktiviert für: | CodeRepositories, DNSManagement, Credential |
| Verfügen Sie über einen etablierten Prozess für die Bereitstellung, Änderung und Löschung von Mitarbeiterkonten? | Ja |
| Haben Sie Software zur Erkennung und Verhinderung von Eindringversuchen (Intrusion Detection and Prevention, IDPS) am Umkreis der Netzwerkgrenze bereitgestellt, die Ihre App unterstützt? | Ja |
| Haben Sie die Ereignisprotokollierung für alle Systemkomponenten eingerichtet, die Ihre App unterstützen? | Ja |
| Werden alle Protokolle regelmäßig von menschlichen oder automatisierten Tools überprüft, um potenzielle Sicherheitsereignisse zu erkennen? | Ja|
| Wenn ein Sicherheitsereignis erkannt wird, werden Warnungen automatisch zur Triage an einen Mitarbeiter gesendet? | Nein |
| Haben Sie einen formalen Informationssicherheits-Risikomanagementprozess eingerichtet? | Nein |
| Haben Sie einen formalen Prozess zur Reaktion auf Sicherheitsvorfälle dokumentiert und eingerichtet? |  |
| Melden Sie App- oder Dienstdatenverstöße innerhalb von 72 Stunden nach der Erkennung an Aufsichtsbehörden und Einzelpersonen, die von der Verletzung betroffen sind?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| Entspricht die App dem Health Insurance Portability and Accounting Act (HIPAA)? | Nicht zutreffend |
| Entspricht die App health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Nicht zutreffend |
| Entspricht die App den Kontrollen der Serviceorganisation (SOC 1)? | Nicht zutreffend |
| Letztes SOC1-Zertifizierungsdatum |   |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 2)? | Nein |
| Welche SOC 2-Zertifizierung haben Sie erreicht? | |
| Letztes SOC2-Zertifizierungsdatum | |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 3)? | Nein |
| Letztes SOC3-Zertifizierungsdatum | |
| Führen Sie jährliche PCI DSS-Bewertungen für die App und ihre unterstützende Umgebung durch? | Nicht zutreffend |
| Ist die App International Organization for Standardization (ISO 27001) zertifiziert? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27018)? | Nicht zutreffend |
| Entspricht die App der International Organization for Standardization (ISO 27017)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27002)? | Nein |
| Ist die App FedRAMP (Federal Risk and Authorization Management Program) konform? | Nein |
| Entspricht die App dem FERPA (Family Educational Rights and Privacy Act)? | Nicht zutreffend |
| Entspricht die App dem Children's Online Privacy Protection Act (COPPA)? | Nicht zutreffend |
| Entspricht die App Sarbanes-Oxley Act (SOX)? | Nicht zutreffend |
| Entspricht die App NIST 800-171? | Nicht zutreffend |
| Wurde die App von der Cloud Security Alliance (CSA Star) zertifiziert? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Haben Sie die DSGVO oder andere Datenschutz- oder Datenschutzanforderungen oder -verpflichtungen (z. B. CCPA)? | Nein |
| Verfügt die App über einen externen Datenschutzhinweis, der beschreibt, wie Kundendaten gesammelt, verwendet, freigaben und gespeichert werden? | Nein |
| Führt die App eine automatisierte Entscheidungsfindung durch, einschließlich Profilerstellung, die rechtliche Auswirkungen oder ähnliche Auswirkungen haben könnte? | Nein |
| Verarbeitet die App Kundendaten für einen sekundären Zweck, der nicht in der Datenschutzerklärung (d. h. Marketing, Analyse) beschrieben ist? | Nein |
| Verarbeiten Sie besondere Kategorien vertraulicher Daten (z. B. ethnische Herkunft, politische Meinung, religiöse oder religiöse Überzeugungen, genetischen oder biometrischen Daten, Gesundheitsdaten) oder Kategorien von Daten, die gegen Benachrichtigungsgesetze verstoßen? | Nein |
| Erfasst oder verarbeitet die App Daten von Minderjährigen (d. h. Personen unter 16 Jahren)? | Nein |
| Verfügt die App über Funktionen zum Löschen der personenbezogenen Daten einer Person auf Anfrage? |  |
| Verfügt die App über Funktionen zum Einschränken oder Einschränken der Verarbeitung personenbezogener Daten einer Person auf Anfrage? |  |
| Bietet die App Einzelpersonen die Möglichkeit, ihre personenbezogenen Daten zu korrigieren oder zu aktualisieren? |  |
| Werden regelmäßige Datenschutz- und Datenschutzüberprüfungen (z. B. Datenschutz-Folgenabschätzungen oder Datenschutzrisikobewertungen) durchgeführt, um Risiken im Zusammenhang mit der Verarbeitung personenbezogener Daten für die App zu identifizieren? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Ist Ihre Anwendung in die Microsoft Identity Platform (Azure AD) für einmaliges Anmelden, API-Zugriff usw. integriert? | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt? | Ja |
| Verwendet Ihre App die neueste Version von MSAL (Microsoft-Authentifizierungsbibliothek) oder Microsoft Identity Web für die Authentifizierung? | Ja |
| Welche Authentifizierungsbibliotheken werden von Ihrer App verwendet, wenn sie keine der oben genannten Bibliotheken verwendet? |  |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Unterstützt Ihre App continuous Access Evaluation (CAE) | Nein |
| Speichert Ihre App Anmeldeinformationen im Code? | Nein |
| Apps und Add-Ins für Microsoft 365 verwenden möglicherweise zusätzliche Microsoft-APIs außerhalb von Microsoft Graph. Verwendet Ihre App oder Ihr Add-In zusätzliche Microsoft-APIs? | Nein |

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

>|   **Graph-Berechtigung**  | **Berechtigungstyp** |          **Justification**          | **Azure AD-App-ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Zulassen, dass die App Ereignisse in Benutzerkalendern liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |
>| Contacts.Read | Delegiert | Zulassen, dass die App Benutzerkontakte liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |
>| Group.Read.All | Delegiert | Zulassen, dass die App Benutzergruppen liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |
>| Presence.Read.All | Delegiert | Zulassen, dass die App Anwesenheitsinformationen aller Benutzer liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |
>| User.Read | Delegiert | Zulassen, dass die App das Benutzerprofil liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |
>| User.Read.All | Delegiert | Zulassen, dass die App alle Benutzerprofile liest. | [2e57054c-4326-46ed-8482-40d9a6d20e79](../azure/2e57054c-4326-46ed-8482-40d9a6d20e79.md) |

>Diese Anwendung verfügt nicht über zusätzliche APIs.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

