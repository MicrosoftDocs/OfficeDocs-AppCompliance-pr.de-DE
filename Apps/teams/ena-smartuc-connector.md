---
title: Anwendungsinformationen für ENA SmartUC Connector von ENA
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ENA SmartUC Connector, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: d2095a16fc5f3d9a0e28f8cf782ae292c330a947
ms.sourcegitcommit: 62e60dfc73f78900307418e60318353faf8d9a57
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/12/2022
ms.locfileid: "63459792"
---
# <a name="ena-smartuc-connector"></a>ENA SmartUC-Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2022</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ENA für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | ENA SmartUC-Connector |
| ID | WA200003354 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | ENA |
| Website des Unternehmens | [https://www.ena.com](https://www.ena.com) |
| Nutzungsbedingungen der App | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| Kernfunktionen der App | Die App verbindet den ENA SmartUC-Produktsatz mit der Teams-App, sodass Endbenutzer ENA SmartUC-gesicherte Telefonanrufe innerhalb Teams tätigen können. |
| Firmenstandort | Vereinigte Staaten von Amerika |
| Seite "App-Informationen" | |
| Welche Hostingumgebung oder welches Dienstmodell wird zum Ausführen Ihrer App verwendet? | Hybrid |
| Welche Hosting-Cloudanbieter verwendet die App? | Andere, die Von Metaswitch betriebenen Teile des Diensts werden in Azure gehostet. Sie sollten auch Details dazu angeben, wie Ihre eigene Infrastruktur (z. B. EAS-Server) gehostet wird. |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ENA darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

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
| Verfügt die App über einen dokumentierten Notfallwiederherstellungsplan, einschließlich einer Sicherungs- und Wiederherstellungsstrategie? | Nein |
| Verwendet Ihre Umgebung herkömmliche Anti-Malware-Schutz- oder Anwendungssteuerelemente? | TraditionalAntiMalware |
| Verfügen Sie über einen etablierten Prozess für die Einrückung und Risikobewertung von Sicherheitsrisiken? | Ja |
| Verfügen Sie über eine Richtlinie, die Ihren Service Level Agreement (SLA) für das Anwenden von Patches regelt? | Ja |
| Führen Sie Patchverwaltungsaktivitäten gemäß Ihren Patchrichtlinien-SLAs aus? | Ja |
| Verfügt Ihre Umgebung über nicht unterstützte Betriebssysteme oder Software? | Nein |
| Führen Sie vierteljährliche Sicherheitsrisikoüberprüfungen für Ihre App und die Struktur durch, die sie unterstützt? | Ja |
| Haben Sie eine Firewall an Der Grenze für das externe Netzwerk installiert? | Ja |
| Haben Sie einen eingerichteten Change Management-Prozess verwendet, um Änderungsanforderungen zu überprüfen und zu genehmigen, bevor sie in der Produktion bereitgestellt werden? | Ja |
| Überprüft und genehmigt eine zusätzliche Person alle Codeänderungsanforderungen, die vom ursprünglichen Entwickler an die Produktion übermittelt wurden? | Ja |
| Berücksichtigen sichere Codierungspraktiken allgemeine Sicherheitsrisikoklassen wie OWASP Top 10? | Nein |
| Mehrstufige Authentifizierung (MFA) aktiviert für: | CodeRepositories, DNSManagement |
| Verfügen Sie über einen etablierten Prozess für die Bereitstellung, Änderung und Löschung von Mitarbeiterkonten? | Ja |
| Haben Sie Software zur Erkennung und Verhinderung von Eindringversuchen (Intrusion Detection and Prevention, IDPS) am Umkreis der Netzwerkgrenze bereitgestellt, die Ihre App unterstützt? | Nein |
| Haben Sie die Ereignisprotokollierung für alle Systemkomponenten eingerichtet, die Ihre App unterstützen? | Ja |
| Werden alle Protokolle regelmäßig von menschlichen oder automatisierten Tools überprüft, um potenzielle Sicherheitsereignisse zu erkennen? | Nein|
| Wenn ein Sicherheitsereignis erkannt wird, werden Warnungen automatisch zur Triage an einen Mitarbeiter gesendet? | Nein |
| Haben Sie einen formalen Informationssicherheits-Risikomanagementprozess eingerichtet? | Ja |
| Haben Sie einen formalen Prozess zur Reaktion auf Sicherheitsvorfälle dokumentiert und eingerichtet? |  |
| Melden Sie App- oder Dienstdatenverstöße innerhalb von 72 Stunden nach der Erkennung an Aufsichtsbehörden und Einzelpersonen, die von der Verletzung betroffen sind?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| Entspricht die App dem Health Insurance Portability and Accounting Act (HIPAA)? | Nein |
| Entspricht die App health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Nein |
| Entspricht die App den Kontrollen der Serviceorganisation (SOC 1)? | Nein |
| Letztes SOC1-Zertifizierungsdatum |   |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 2)? | Nein |
| Welche SOC 2-Zertifizierung haben Sie erreicht? | |
| Letztes SOC2-Zertifizierungsdatum | |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 3)? | Nein |
| Letztes SOC3-Zertifizierungsdatum | |
| Führen Sie jährliche PCI DSS-Bewertungen für die App und ihre unterstützende Umgebung durch? | Nein |
| Ist die App International Organization for Standardization (ISO 27001) zertifiziert? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27018)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27017)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27002)? | Nein |
| Ist die App FedRAMP (Federal Risk and Authorization Management Program) konform? | Nein |
| Entspricht die App dem FERPA (Family Educational Rights and Privacy Act)? | Nicht zutreffend |
| Entspricht die App dem Children's Online Privacy Protection Act (COPPA)? | Nicht zutreffend |
| Entspricht die App Sarbanes-Oxley Act (SOX)? | Nein |
| Entspricht die App NIST 800-171? | Nein |
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
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt? | Nein |
| Verwendet Ihre App die neueste Version von MSAL (Microsoft-Authentifizierungsbibliothek) oder Microsoft Identity Web für die Authentifizierung? | Ja |
| Welche Authentifizierungsbibliotheken werden von Ihrer App verwendet, wenn sie keine der oben genannten Bibliotheken verwendet? |  |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Unterstützt Ihre App continuous Access Evaluation (CAE) | Nein |
| Speichert Ihre App Anmeldeinformationen im Code? | Ja |
| Apps und Add-Ins für Microsoft 365 verwenden möglicherweise zusätzliche Microsoft-APIs außerhalb von Microsoft Graph. Verwendet Ihre App oder Ihr Add-In zusätzliche Microsoft-APIs? | Ja |

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

>|   **Graph-Berechtigung**  | **Berechtigungstyp** |          **Justification**          | **Azure AD-App-ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Kanals/Chats. Die App verwendet dies, um dem Benutzer eine Liste der Kanal-/Chatmitglieder anzuzeigen, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| Chat.ReadBasic | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Chats. Die App verwendet dies, um dem Benutzer eine Liste der Chatmitglieder zu präsentieren, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| People.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Teams. Die App verwendet dies, um dem Benutzer eine Liste der Teammitglieder anzuzeigen, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| User.Read.All | Delegiert | Die Geschäftlichen und Mobiltelefonnummern der Benutzer. Dies ist erforderlich, damit Anrufe zu diesen Nummern initiiert werden können. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| offline_access | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph API-Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity Platform-Anwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| openid | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph API-Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity Platform-Anwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| Profil | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph API-Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity Platform-Anwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |

>Diese Anwendung verfügt nicht über zusätzliche APIs.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

