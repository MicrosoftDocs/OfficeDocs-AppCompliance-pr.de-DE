---
title: Anwendungsinformationen für QuickMinutes von QuickMinutes
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/18/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für QuickMinutes, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 462cbb7aa74e6a1f4718554efdfc0e482a832b44
ms.sourcegitcommit: 21d1c42a8e6d9f94b9c8f279bbe37f649ebd4e10
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/19/2022
ms.locfileid: "66852694"
---
# <a name="quickminutes"></a>QuickMinutes

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 9. Juni 2022</p>

* <a href="https://teams.microsoft.com/l/app/5f60fe53-d441-4320-8c26-13fdaee9b58a" target="_blank">Im Teams Store anzeigen</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004414" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von QuickMinutes an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | QuickMinutes |
| ID | WA200004414 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | QuickMinutes |
| Website des Unternehmens | [https://quickminutes.com](https://quickminutes.com) |
| Nutzungsbedingungen der App | [https://quickminutes.com/privacy#/terms_of_service](https://quickminutes.com/privacy#/terms_of_service) |
| Kernfunktionen der App | Optimieren Sie Ihre Online-Workflows für Besprechungen mit unserem intelligenten digitalen Assistenten. |
| Hauptsitz des Unternehmens | Irland |
| App-Infoseite | [https://support.quickminutes.com/portal/en-gb/kb/articles/m...](https://support.quickminutes.com/portal/en-gb/kb/articles/microsoft-teams-integration-22-4-2020-1) |
| Was ist die Hostingumgebung oder das Dienstmodell, die zum Ausführen Ihrer App verwendet wird? | Iaas |
| Welche Hosting-Cloudanbieter verwendet die App? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von QuickMinutes darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Verarbeitet die App oder die zugrunde liegende Infrastruktur Daten, die sich auf einen Microsoft-Kunden oder sein Gerät beziehen? | Ja |
| Welche Daten werden von Ihrer App verarbeitet? | Wir verwenden die Benutzerprofildaten, um die Benutzerinformationen in der QuickMinutes DB aufzufüllen, wenn der Benutzer ein neues Konto bei QuickMinutes mitHilfe von Microsoft SSO registriert. QuickMinutes ruft die Kalenderdaten des Benutzers ab, um die Ereignisse in der QuickMinutes-Benutzeroberfläche anzuzeigen. Wir speichern diese Informationen nicht in der QuickMinutes DB, wir rufen nur die Informationen aus Graph-API ab und zeigen sie dem Benutzer an.  |
| Unterstützt die App TLS 1.1 oder höher? | Ja |
| Speichert die App oder die zugrunde liegende Infrastruktur Microsoft-Kundendaten? | Ja |
| Welche Daten werden in Ihren Datenbanken gespeichert? | Benutzerprofilinformationen, z. B. Vorname, Nachname, Email und Profilbild. Außerdem speichern wir Benutzer MS-Zugriffs- und Aktualisierungstoken. |
| Wenn zugrunde liegende Infrastrukturprozesse oder Microsoft-Kundendaten gespeichert werden, wo werden diese Daten geografisch gespeichert? | Irland |
| Haben Sie einen etablierten Datenbesorgungs- und Entsorgungsprozess? | Ja |
| Wie lange werden Die Daten nach der Kontoentsendung aufbewahrt? | Nicht beibehalten |
| Haben Sie einen etablierten Datenzugriffsverwaltungsprozess? | Ja |
| Übertragen Sie Kundendaten oder Kundeninhalte an Dritte oder Unterauftragsverarbeiter? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Führen Sie jährliche Penetrationstests für die App durch? | Nein |
| Verfügt die App über einen dokumentierten Notfallwiederherstellungsplan, einschließlich einer Sicherungs- und Wiederherstellungsstrategie? | Ja |
| Verwendet Ihre Umgebung herkömmlichen Schutz vor Schadsoftware oder Anwendungssteuerelemente? | TraditionalAntiMalware, ApplicationControls |
| Haben Sie einen etablierten Prozess zum Einrücken und Zurverfolgen von Sicherheitsrisiken? | Nein |
| Verfügen Sie über eine Richtlinie, die Ihre Service Level Agreement (SLA) für die Anwendung von Patches regelt? | Ja |
| Führen Sie Patchverwaltungsaktivitäten gemäß Ihren Patchingrichtlinien-SLAs durch? | Ja |
| Verfügt Ihre Umgebung über nicht unterstützte Betriebssysteme oder Software? | Nein |
| Führen Sie vierteljährliche Überprüfungen von Sicherheitsrisiken in Ihrer App und deren Unterstützung durch? | Nein |
| Haben Sie eine Firewall an Der Grenze des externen Netzwerks installiert? | Ja |
| Verfügen Sie über einen etablierten Änderungsverwaltungsprozess, der verwendet wird, um Änderungsanforderungen zu überprüfen und zu genehmigen, bevor sie in der Produktion bereitgestellt werden? | Ja |
| Überprüft und genehmigt eine zusätzliche Person alle Codeänderungsanforderungen, die vom ursprünglichen Entwickler an die Produktion gesendet werden? | Ja |
| Berücksichtigen sichere Codierungspraktiken allgemeine Sicherheitsrisikenklassen wie OWASP Top 10? | Ja |
| Mehrstufige Authentifizierung (MFA) aktiviert für: | DNSManagement, Anmeldeinformationen, CodeRepositories |
| Haben Sie einen etablierten Prozess für die Bereitstellung, Änderung und Löschung von Mitarbeiterkonten? | Ja |
| Verfügen Sie über IdPS-Software (Intrusion Detection and Prevention), die am Rand der Netzwerkgrenze bereitgestellt wird, die Ihre App unterstützt? | Ja |
| Haben Sie die Ereignisprotokollierung für alle Systemkomponenten eingerichtet, die Ihre App unterstützen? | Ja |
| Werden alle Protokolle regelmäßig von menschlichen oder automatisierten Tools überprüft, um potenzielle Sicherheitsereignisse zu erkennen? | Nein |
| Wenn ein Sicherheitsereignis erkannt wird, werden Benachrichtigungen automatisch zur Triage an einen Mitarbeiter gesendet? | Nein |
| Haben Sie einen formalen Risikomanagementprozess für die Informationssicherheit eingerichtet? | Nein |
| Haben Sie einen formalen Prozess zur Reaktion auf Sicherheitsvorfälle dokumentiert und eingerichtet? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Antwort** |
|:----------------|:-------------|
| Entspricht die App dem Health Insurance Portability and Accounting Act (HIPAA)? | Nicht zutreffend |
| Entspricht die App der Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Nicht zutreffend |
| Entspricht die App den Dienstorganisationssteuerelementen (SOC 1)? | Nicht zutreffend |
| Entspricht die App den Steuerelementen der Dienstorganisation (SERVICE Organization Controls, SOC 2)? | Nein |
| Entspricht die App den Steuerelementen der Dienstorganisation (SOC 3)? | Nein |
| Führen Sie jährliche PCI DSS-Bewertungen für die App und ihre unterstützende Umgebung durch? | Nicht zutreffend |
| Ist die App International Organization for Standardization (ISO 27001) zertifiziert? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27018)? | Nicht zutreffend |
| Entspricht die App der International Organization for Standardization (ISO 27017)? | Nein |
| Entspricht die App der International Organization for Standardization (ISO 27002)? | Nein |
| Ist das Federal Risk and Authorization Management Program (FedRAMP) der App konform? | Nein |
| Entspricht die App dem Family Educational Rights and Privacy Act (FERPA)? | Nein |
| Entspricht die App dem Children es Online Privacy Protection Act (COPPA)? | Nein |
| Entspricht die App Sarbanes-Oxley Act (SOX)? | Nicht zutreffend |
| Entspricht die App NIST 800-171? | Nicht zutreffend |
| Wurde die App cloudsicherheitsallianz (CSA Star) zertifiziert? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Antwort** |
|:----------------|:-------------|
| Haben Sie DSGVO oder andere Datenschutz- oder Datenschutzanforderungen oder -pflichten (z. B. CCPA)? | Ja |
| Verfügt die App über einen externen Datenschutzhinweis, der beschreibt, wie Kundendaten gesammelt, verwendet, freigegeben und gespeichert werden? | Ja |
| URL der Datenschutzrichtlinie | https://quickminutes.com/privacy#/privacy_policy |
| Führt die App automatisierte Entscheidungsfindung durch, einschließlich Profilerstellung, die rechtliche Auswirkungen oder ähnliche Auswirkungen haben könnte? | Nein |
| Verarbeitet die App Kundendaten zu einem sekundären Zweck, der nicht in der Datenschutzerklärung beschrieben ist (z. B. Marketing, Analysen)? | Nein |
| Verarbeiten Sie spezielle Kategorien vertraulicher Daten (z. B. rassische oder ethnische Herkunft, politische Meinung, religiöse oder philosophische Überzeugungen, genetische oder biometrische Daten, Gesundheitsdaten) oder Kategorien von Daten, die Benachrichtigungsgesetzen unterliegen? | Nein |
| Sammelt oder verarbeitet die App Daten von Minderjährigen (d. h. Personen unter 16 Jahren)? | Nein |
| Verfügt die App über die Möglichkeit, die personenbezogenen Daten einer Person auf Anfrage zu löschen? | Ja |
| Verfügt die App über Funktionen, um die Verarbeitung der personenbezogenen Daten einer Person auf Anfrage einzuschränken oder einzuschränken? | Nein |
| Bietet die App Einzelpersonen die Möglichkeit, ihre personenbezogenen Daten zu korrigieren oder zu aktualisieren? | Ja |
| Werden regelmäßige Datenschutz- und Datenschutzüberprüfungen (z. B. Datenschutz-Folgenabschätzungen oder Datenschutzrisikobewertungen) durchgeführt, um Risiken im Zusammenhang mit der Verarbeitung personenbezogener Daten für die App zu identifizieren? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Antwort** |
|:----------------|:-------------|
| Ist Ihre Anwendung in Microsoft Identity Platform (Azure AD) für einmaliges Anmelden, API-Zugriff usw. integriert? | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind? | Ja |
| Verwendet Ihre App die neueste Version von MSAL (Microsoft Authentication Library) oder Microsoft Identity Web für die Authentifizierung? | Nicht zutreffend |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Unterstützt Ihre App die kontinuierliche Zugriffsauswertung (Continuous Access Evaluation, CAE) | Nein |
| Speichert Ihre App Anmeldeinformationen im Code? | Nein |
| Apps und Add-Ins für Microsoft 365 verwenden möglicherweise zusätzliche Microsoft-APIs außerhalb von Microsoft Graph. Verwendet Ihre App oder Ihr Add-In zusätzliche Microsoft-APIs? | Nein |

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

>|   **Graph-Berechtigung**  | **Berechtigungstyp** |          **Justification**          | **Azure AD-App-ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Der Kalenderbereich wird von QuickMinutes zum Lesen/Schreiben von QuickMinutes-Besprechungen im Microsoft-Kalender des Benutzers verwendet. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| People.Read | Delegiert | Der Personenbereich wird von QuickMinutes verwendet, um die Kontakte von Microsoft-Benutzern auflisten, wenn sie Benutzer zur QuickMinutes-Organisation oder -Gruppe hinzufügen. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| email | Delegiert | Der E-Mail-Bereich wird verwendet, um QuickMinutes Zugriff auf die primäre E-Mail-Adresse des Benutzers in Form des E-Mail-Anspruchs zu gewähren. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| openid | Delegiert | Der OpenID-Bereich wird von QuickMinutes am Microsoft Identity Platform Tokenendpunkt verwendet, um ID-Token abzurufen. Auf diese Weise kann QuickMinutes die Token verwenden, um im Namen der Benutzer auf die Graph-API zuzugreifen. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| Profil | Delegiert | Der Profilbereich wird von QuickMinutes verwendet, um auf das Benutzerprofil zuzugreifen, wenn wir sie über Microsoft SSO registrieren und ihr QuickMinutes-Konto erstellen. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |

>Diese Anwendung verfügt nicht über zusätzliche APIs.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

