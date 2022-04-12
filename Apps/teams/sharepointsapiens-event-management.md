---
title: Anwendungsinformationen für die Ereignisverwaltung nach SharePoint| Sapiens
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für die Ereignisverwaltung, ihre Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 8f3f587291aaea4d195299db6857e80466e02467
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784254"
---
# <a name="event-management"></a>Ereignisverwaltung

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 22. März 2022</p>

* <a href="https://teams.microsoft.com/l/app/2b8b9b59-d595-46b3-ba0a-602024bab0cc" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000714" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von SharePoint| Sapiens an Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Ereignisverwaltung |
| ID | WA200000714 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | \|SharePoint Sapiens |
| Website des Unternehmens | [https://www.sharepointsapiens.com](https://www.sharepointsapiens.com) |
| Nutzungsbedingungen der App | [https://addins.sharepointsapiens.com/licensing/services-agr...](https://addins.sharepointsapiens.com/licensing/services-agreement.html) |
| Kernfunktionen der App | Das Ereignisverwaltungs-Add-In hilft Ihnen, verschiedene Arten von Ereignissen zu organisieren. Ereignisse können in wenigen einfachen Schritten in kürzester Zeit geplant werden. Die Teilnehmer können sich mit nur einem Klick online registrieren. Als Organisator können Sie auch interne oder externe Benutzer im Auftrag registrieren oder Einladungen per E-Mail versenden. Teilnehmer erhalten Besprechungsanfragen und Updates per E-Mail, um sicherzustellen, dass sie immer über die neuesten Informationen in ihrem Outlook Kalender verfügen. Das Add-In verfolgt alle Teilnehmer an einem Ort. |
| Hauptsitz des Unternehmens | Österreich |
| App-Infoseite | [https://www.sharepointsapiens.com/event-management-office36...](https://www.sharepointsapiens.com/event-management-office365/documentation/teams/) |
| Was ist die Hostingumgebung oder das Dienstmodell, die zum Ausführen Ihrer App verwendet wird? | Paas |
| Welche Hosting-Cloudanbieter verwendet die App? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SharePoint| Sapiens darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

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
| Führen Sie jährliche Penetrationstests für die App durch? | Ja |
| Verfügt die App über einen dokumentierten Notfallwiederherstellungsplan, einschließlich einer Sicherungs- und Wiederherstellungsstrategie? | Nein |
| Verwendet Ihre Umgebung herkömmlichen Schutz vor Schadsoftware oder Anwendungssteuerelemente? | ApplicationControls |
| Haben Sie einen etablierten Prozess zum Einrücken und Zurverfolgen von Sicherheitsrisiken? | Nein |
| Verfügen Sie über eine Richtlinie, die Ihre Service Level Agreement (SLA) für die Anwendung von Patches regelt? | Nein |
| Führen Sie Patchverwaltungsaktivitäten gemäß Ihren Patchingrichtlinien-SLAs durch? | Nein |
| Verfügt Ihre Umgebung über nicht unterstützte Betriebssysteme oder Software? | Nein |
| Führen Sie vierteljährliche Überprüfungen von Sicherheitsrisiken in Ihrer App und deren Unterstützung durch? | Nein |
| Haben Sie eine Firewall an Der Grenze des externen Netzwerks installiert? | Nein |
| Verfügen Sie über einen etablierten Änderungsverwaltungsprozess, der verwendet wird, um Änderungsanforderungen zu überprüfen und zu genehmigen, bevor sie in der Produktion bereitgestellt werden? | Nein |
| Überprüft und genehmigt eine zusätzliche Person alle Codeänderungsanforderungen, die vom ursprünglichen Entwickler an die Produktion gesendet werden? | Nein |
| Berücksichtigen sichere Codierungspraktiken allgemeine Sicherheitsrisikenklassen wie OWASP Top 10? | Ja |
| Mehrstufige Authentifizierung (MFA) aktiviert für: | CodeRepositories, Anmeldeinformationen |
| Haben Sie einen etablierten Prozess für die Bereitstellung, Änderung und Löschung von Mitarbeiterkonten? | Ja |
| Verfügen Sie über IdPS-Software (Intrusion Detection and Prevention), die am Rand der Netzwerkgrenze bereitgestellt wird, die Ihre App unterstützt? | Nicht zutreffend |
| Haben Sie die Ereignisprotokollierung für alle Systemkomponenten eingerichtet, die Ihre App unterstützen? | Ja |
| Werden alle Protokolle regelmäßig von menschlichen oder automatisierten Tools überprüft, um potenzielle Sicherheitsereignisse zu erkennen? | Ja|
| Wenn ein Sicherheitsereignis erkannt wird, werden Benachrichtigungen automatisch zur Triage an einen Mitarbeiter gesendet? | Ja |
| Haben Sie einen formalen Risikomanagementprozess für die Informationssicherheit eingerichtet? | Nein |
| Haben Sie einen formalen Prozess zur Reaktion auf Sicherheitsvorfälle dokumentiert und eingerichtet? |  |
| Melden Sie Verletzungen von App- oder Dienstdaten innerhalb von 72 Stunden nach Erkennung an Aufsichtsbehörden und personen, die von der Verletzung betroffen sind?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| Entspricht die App dem Health Insurance Portability and Accounting Act (HIPAA)? | N/V |
| Entspricht die App der Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/V |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 1)? | N/V |
| Neuestes SOC1-Zertifizierungsdatum |   |
| Entspricht die App den Steuerelementen der Dienstorganisation (SERVICE Organization Controls, SOC 2)? | Nein |
| Welche SOC 2-Zertifizierung haben Sie erreicht? | |
| Neuestes SOC2-Zertifizierungsdatum | |
| Entspricht die App den Steuerelementen der Dienstorganisation (SOC 3)? | Nein |
| Neuestes SOC3-Zertifizierungsdatum | |
| Führen Sie jährliche PCI DSS-Bewertungen für die App und ihre unterstützende Umgebung durch? | N/V |
| Ist die App International Organization for Standardization (ISO 27001) zertifiziert? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27018)? | N/V |
| Entspricht die App der International Organization for Standardization (ISO 27017)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27002)? | Nein |
| Ist das Federal Risk and Authorization Management Program (FedRAMP) der App konform? | Nein |
| Entspricht die App dem Family Educational Rights and Privacy Act (FERPA)? | N/V |
| Entspricht die App dem Children es Online Privacy Protection Act (COPPA)? | N/V |
| Entspricht die App Sarbanes-Oxley Act (SOX)? | N/V |
| Entspricht die App NIST 800-171? | Nicht zutreffend |
| Wurde die App cloudsicherheitsallianz (CSA Star) zertifiziert? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Haben Sie DSGVO oder andere Datenschutz- oder Datenschutzanforderungen oder -pflichten (z. B. CCPA)? | Ja |
| Verfügt die App über einen externen Datenschutzhinweis, der beschreibt, wie Kundendaten gesammelt, verwendet, freigegeben und gespeichert werden? | Ja |
| URL der Datenschutzrichtlinie | https://addins.sharepointsapiens.com/licensing/data-processing-agreement.html |
| Führt die App automatisierte Entscheidungsfindung durch, einschließlich Profilerstellung, die rechtliche Auswirkungen oder ähnliche Auswirkungen haben könnte? | Nein |
| Verarbeitet die App Kundendaten zu einem sekundären Zweck, der nicht in der Datenschutzerklärung beschrieben ist (z. B. Marketing, Analysen)? | Nein |
| Verarbeiten Sie spezielle Kategorien vertraulicher Daten (z. B. rassische oder ethnische Herkunft, politische Meinung, religiöse oder philosophische Überzeugungen, genetische oder biometrische Daten, Gesundheitsdaten) oder Kategorien von Daten, die Benachrichtigungsgesetzen unterliegen? | Nein |
| Sammelt oder verarbeitet die App Daten von Minderjährigen (d. h. Personen unter 16 Jahren)? | Nein |
| Verfügt die App über die Möglichkeit, die personenbezogenen Daten einer Person auf Anfrage zu löschen? | Nicht zutreffend |
| Verfügt die App über Funktionen, um die Verarbeitung der personenbezogenen Daten einer Person auf Anfrage einzuschränken oder einzuschränken? | N/V |
| Bietet die App Einzelpersonen die Möglichkeit, ihre personenbezogenen Daten zu korrigieren oder zu aktualisieren? | N/V |
| Werden regelmäßige Datenschutz- und Datenschutzüberprüfungen (z. B. Datenschutz-Folgenabschätzungen oder Datenschutzrisikobewertungen) durchgeführt, um Risiken im Zusammenhang mit der Verarbeitung personenbezogener Daten für die App zu identifizieren? | N/V |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Ist Ihre Anwendung in Microsoft Identity Platform (Azure AD) für einmaliges Anmelden, API-Zugriff usw. integriert? | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind? | Ja |
| Verwendet Ihre App die neueste Version von MSAL (Microsoft Authentication Library) oder Microsoft Identity Web für die Authentifizierung? | Ja |
| Welche Authentifizierungsbibliotheken werden verwendet, wenn Ihre App keine der oben genannten Bibliotheken verwendet? |  |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Unterstützt Ihre App die kontinuierliche Zugriffsauswertung (Continuous Access Evaluation, CAE) | Nein |
| Speichert Ihre App Anmeldeinformationen im Code? | Nein |
| Apps und Add-Ins für Microsoft 365 verwenden möglicherweise zusätzliche Microsoft-APIs außerhalb von Microsoft Graph. Verwendet Ihre App oder Ihr Add-In zusätzliche Microsoft-APIs? | Ja |

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

>|   **Graph Berechtigung**  | **Berechtigungstyp** |          **Justification**          | **Azure AD App-ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.ReadBasic.All | Delegiert | Grundlegende Benutzerinformationen lesen, um Exchange Raumbuchung zu aktivieren | [9e8e113c-8a08-4606-b08a-de4decc7252f](../azure/9e8e113c-8a08-4606-b08a-de4decc7252f.md) |

>Diese Anwendung verfügt nicht über zusätzliche APIs.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

