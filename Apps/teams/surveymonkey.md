---
title: Anwendungsinformationen für SurveyMonkey von SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für SurveyMonkey, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552726"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die SurveyMonkey Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SurveyMonkey |
| ID | WA104381088 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SurveyMonkey |
| URL der Partner-Website | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL Teams Anwendungsinfoseite | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL der Datenschutzrichtlinie | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von SurveyMonkey darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegiert | Nein | So stellen Sie eine Liste von Gruppen/Kanälen bereit, mit der sie eine Umfrage gemeinsam nutzen können |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Nur MS-Benutzer-ID wird in SurveyMonkey gespeichert, um Antworten und Umfragen mit dem Teambenutzer zu verknüpfen. |  | Für Teams verwenden wir das Microsoft Teams Javascript SDK im Aufgabenmodul "Erstellungs-, Umfrage- und Umfrageergebnisse" modal. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir rufen v3/conversations/-id/paged-Mitglieder an, um zu überprüfen, ob die App einem Team hinzugefügt wird, und die Mitgliederanzahl abzurufen. Es ist für die interne Verfolgung der Nutzung, wir schauen nur auf die Größe der Chat-Liste, andere Informationen werden ignoriert. | Ja, die Größe des Chats wird gespeichert (eine einzelne ganze Zahl) |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>EUII - Ein Erfolgs-/Fail-Protokoll wird erstellt, wenn eine Umfrage eine Antwort erhält, und wir versuchen, diese Antwort über den Connector an Teams zu senden, dieses Protokoll enthält user_id, survey_id, integration_id (die in der Datenbank verwendet werden können, um MS Team ID, MS-Benutzer-ID zu suchen)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Unser primäres Rechenzentrum befindet sich in Las Vegas, NV und unser sekundäres Rechenzentrum befindet sich in Santa Clara, CA. SurveyMonkey besitzt und betreibt alle Server und Infrastrukturen an diesen Standorten. Wir haben auch kanadische Datenresidenz für bestimmte SurveyMonkey Enterprise Kunden in Kanada verfügbar. Alle Daten werden im Ruhezustand mit TDE mit AES256 verschlüsselt und die Daten während der Übertragung werden mit TLS 1.2 verschlüsselt.

SurveyMonkey verwendet die zentrale Benutzerauthentifizierung, um die Identitäts- und Zugriffsverwaltung aufrechtzuerhalten. Dieses System verwaltet die gesamte Authentifizierung und Autorisierung für alle Unternehmen und Produktionsinfrastrukturen, Systeme und Dienste. Strenge Zugangsrichtlinien werden vierteljährlich beibehalten und überprüft. Die Bewertungen umfassen, sind aber nicht beschränkt auf: Benutzerzugriffslisten, Richtliniengruppen und Zugriffsüberprüfungen von Drittanbietern. Um auf unsere Produktionsumgebung zuzugreifen (d. h. um ein privilegiertes Konto zu erhalten), muss man die Genehmigung des Managers einholen, eine Reihe von erforderlichen Schulungen absolvieren und die Genehmigung unseres Sicherheitsteams einholen. Zu diesem Zeitpunkt wird ein zusätzliches VPN-Konto bereitgestellt, das die &#8216;normalen&#8217; Kontos von einem &#8216;privilegierten&#8217;-Konto unterscheidet.

Nur von Unternehmen ausgegebene Geräte dürfen auf unser Produktionsnetzwerk zugreifen. Alle Standardeinstellungen des drahtlosen Herstellers werden vor der Installation geändert, einschließlich, aber nicht beschränkt auf standarddrahtlose Verschlüsselungsschlüssel, Kennwörter und SNMP-Community-Zeichenfolgen. 2FA und VPN sind erforderlich, um dies aus der Ferne zu tun. Wir haben ein separates WLAN-Netzwerk für den Zugang zu Gästen in unseren Firmenbüros.

Alle Dienste, Protokolle und zulässigen Ports müssen über eine dokumentierte geschäftliche Begründung und -genehmigung verfügen, einschließlich der Verwendung von Sicherheitsfeatures, die für die Protokolle implementiert sind, die als unsicher gelten. Router und Firewalls sind so konfiguriert, dass die IP-Offenlegung auf nicht autorisierte oder unbeabsichtigte Parteien beschränkt und der eingehende Internetzugriff auf IP-Adressen innerhalb der DMZ-Firewall beschränkt wird und Router-Regelsätze mindestens alle sechs Monate überprüft werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

