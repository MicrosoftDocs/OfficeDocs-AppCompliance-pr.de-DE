---
title: Anwendungsinformationen für ENA SmartUC Connector von ENA
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ENA SmartUC Connector, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 3f2f49283d559d7d1392339969884fb50ba2a777
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2022
ms.locfileid: "64876402"
---
# <a name="ena-smartuc-connector"></a>ENA SmartUC-Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 11. März 2022</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ENA an Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | ENA SmartUC-Connector |
| ID | WA200003354 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | ENA |
| Website des Unternehmens | [https://www.ena.com](https://www.ena.com) |
| Nutzungsbedingungen der App | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| Kernfunktionen der App | Die App verbindet das ENA SmartUC-Produktset mit der Teams-App, sodass Endbenutzer ENA SmartUC-gestützte Telefonanrufe innerhalb Teams tätigen können. |
| Hauptsitz des Unternehmens | USA Amerikas |
| App-Infoseite | |
| Was ist die Hostingumgebung oder das Dienstmodell, die zum Ausführen Ihrer App verwendet wird? | Hybrid |
| Welche Hosting-Cloudanbieter verwendet die App? | Andere, Die Teile des Diensts von Metaswitch betrieben werden in Azure gehostet. Sie sollten auch Details dazu angeben, wie Ihre eigene Infrastruktur (z. B. EAS-Server) gehostet wird. |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ENA darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

| **Information** | **Response** |
|:----------------|:-------------|
| Verarbeitet die App oder die zugrunde liegende Infrastruktur Daten, die sich auf einen Microsoft-Kunden oder sein Gerät beziehen? | Ja |
| Welche Daten werden von Ihrer App verarbeitet? | Die folgende EUII/OII kann über den MCT-Proxy an die CommPortal JSON-API übertragen werden: IP-Adresse, Aufrufen der Telefonnummer des Benutzers, Kennwort, CommPortal-Authentifizierungstoken, CommPortal-Sitzungs-ID, Telefonnummer des Angerufenen beim Tätigen eines Anrufs, Die Domänen von E-Mail-Adressen. |
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
| Verwendet Ihre Umgebung herkömmlichen Schutz vor Schadsoftware oder Anwendungssteuerelemente? | TraditionalAntiMalware |
| Haben Sie einen etablierten Prozess zum Einrücken und Zurverfolgen von Sicherheitsrisiken? | Ja |
| Verfügen Sie über eine Richtlinie, die Ihre Service Level Agreement (SLA) für die Anwendung von Patches regelt? | Ja |
| Führen Sie Patchverwaltungsaktivitäten gemäß Ihren Patchingrichtlinien-SLAs durch? | Ja |
| Verfügt Ihre Umgebung über nicht unterstützte Betriebssysteme oder Software? | Nein |
| Führen Sie vierteljährliche Überprüfungen von Sicherheitsrisiken in Ihrer App und deren Unterstützung durch? | Ja |
| Haben Sie eine Firewall an Der Grenze des externen Netzwerks installiert? | Ja |
| Verfügen Sie über einen etablierten Änderungsverwaltungsprozess, der verwendet wird, um Änderungsanforderungen zu überprüfen und zu genehmigen, bevor sie in der Produktion bereitgestellt werden? | Ja |
| Überprüft und genehmigt eine zusätzliche Person alle Codeänderungsanforderungen, die vom ursprünglichen Entwickler an die Produktion gesendet werden? | Ja |
| Berücksichtigen sichere Codierungspraktiken allgemeine Sicherheitsrisikenklassen wie OWASP Top 10? | Nein |
| Mehrstufige Authentifizierung (MFA) aktiviert für: | CodeRepositories, DNSManagement |
| Haben Sie einen etablierten Prozess für die Bereitstellung, Änderung und Löschung von Mitarbeiterkonten? | Ja |
| Verfügen Sie über IdPS-Software (Intrusion Detection and Prevention), die am Rand der Netzwerkgrenze bereitgestellt wird, die Ihre App unterstützt? | Nein |
| Haben Sie die Ereignisprotokollierung für alle Systemkomponenten eingerichtet, die Ihre App unterstützen? | Ja |
| Werden alle Protokolle regelmäßig von menschlichen oder automatisierten Tools überprüft, um potenzielle Sicherheitsereignisse zu erkennen? | Nein |
| Wenn ein Sicherheitsereignis erkannt wird, werden Benachrichtigungen automatisch zur Triage an einen Mitarbeiter gesendet? | Nein |
| Haben Sie einen formalen Risikomanagementprozess für die Informationssicherheit eingerichtet? | Ja |
| Haben Sie einen formalen Prozess zur Reaktion auf Sicherheitsvorfälle dokumentiert und eingerichtet? | Ja |
| Melden Sie Verletzungen von App- oder Dienstdaten innerhalb von 72 Stunden nach Erkennung an Aufsichtsbehörden und personen, die von der Verletzung betroffen sind? | Ja |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| Entspricht die App dem Health Insurance Portability and Accounting Act (HIPAA)? | Nein |
| Entspricht die App der Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Nein |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 1)? | Nein |
| Entspricht die App den Steuerelementen der Dienstorganisation (SERVICE Organization Controls, SOC 2)? | Nein |
| Entspricht die App den Steuerelementen der Dienstorganisation (SOC 3)? | Nein |
| Führen Sie jährliche PCI DSS-Bewertungen für die App und ihre unterstützende Umgebung durch? | Nein |
| Ist die App International Organization for Standardization (ISO 27001) zertifiziert? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27018)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27017)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27002)? | Nein |
| Ist das Federal Risk and Authorization Management Program (FedRAMP) der App konform? | Nein |
| Entspricht die App dem Family Educational Rights and Privacy Act (FERPA)? | Nicht zutreffend |
| Entspricht die App dem Children es Online Privacy Protection Act (COPPA)? | Nicht zutreffend |
| Entspricht die App Sarbanes-Oxley Act (SOX)? | Nein |
| Entspricht die App NIST 800-171? | Nein |
| Wurde die App cloudsicherheitsallianz (CSA Star) zertifiziert? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Haben Sie DSGVO oder andere Datenschutz- oder Datenschutzanforderungen oder -pflichten (z. B. CCPA)? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Ist Ihre Anwendung in Microsoft Identity Platform (Azure AD) für einmaliges Anmelden, API-Zugriff usw. integriert? | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind? | Nein |
| Verwendet Ihre App die neueste Version von MSAL (Microsoft Authentication Library) oder Microsoft Identity Web für die Authentifizierung? | Ja |
| Welche Authentifizierungsbibliotheken werden verwendet, wenn Ihre App keine der oben genannten Bibliotheken verwendet? |  |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Unterstützt Ihre App die kontinuierliche Zugriffsauswertung (Continuous Access Evaluation, CAE) | Nein |
| Speichert Ihre App Anmeldeinformationen im Code? | Ja |
| Apps und Add-Ins für Microsoft 365 verwenden möglicherweise zusätzliche Microsoft-APIs außerhalb von Microsoft Graph. Verwendet Ihre App oder Ihr Add-In zusätzliche Microsoft-APIs? | Ja |

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

>|   **Graph Berechtigung**  | **Berechtigungstyp** |          **Justification**          | **Azure AD App-ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Kanals/Chats. Die App verwendet dies, um dem Benutzer eine Liste der Kanal-/Chatmitglieder zu präsentieren, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| Chat.ReadBasic | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Chats. Die App verwendet dies, um dem Benutzer eine Liste der Chatmitglieder zu präsentieren, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| People.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Teams. Die App verwendet dies, um dem Benutzer eine Liste der Teammitglieder zu präsentieren, die angerufen werden sollen. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| User.Read.All | Delegiert | Die Geschäftlichen und Mobiltelefonnummern der Benutzer. Dies ist erforderlich, damit Telefonanrufe an diese Nummern initiiert werden können. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| offline_access | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph-API Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity-Plattformanwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| openid | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph-API Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity-Plattformanwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| Profil | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph-API Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. Diese Zugriffsberechtigungen sind erforderlich, damit Microsoft Identity-Plattformanwendungen funktionieren. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |

>Diese Anwendung verfügt nicht über zusätzliche APIs.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

