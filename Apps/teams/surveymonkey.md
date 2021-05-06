---
title: Anwendungsinformationen für SurveyMonkey von SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SurveyMonkey, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9b4f40ab870844e403a1dc3c70a4535a3541190
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52248293"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SurveyMonkey an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SurveyMonkey |
| ID | WA104381088 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung, Connector |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | SurveyMonkey |
| URL der Partnerwebsite | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL Teams Anwendungsinfoseite | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL der Datenschutzrichtlinie | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von SurveyMonkey darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegierte | Nein | So stellen Sie eine Liste der Gruppen/Kanäle für die Freigabe einer Umfrage zur Verfügung |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Nur die MS-Benutzer-ID wird in SurveyMonkey gespeichert, um Antworten und Umfragen dem Teambenutzer zuzuordnen. |  | Für Teams verwenden wir das Microsoft Teams javascript SDK im Aufgabenmodul "Erstellen, Umfragen und Umfrageergebnisse" modal. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir rufen v3/conversations/{id}/pagedmembers auf, um zu überprüfen, ob die App einem Team hinzugefügt wurde, und rufen die Mitgliederanzahl ab. Es ist für die interne Nachverfolgung der Verwendung, wir sehen uns nur die Größe des Chatplans an, andere Informationen werden ignoriert. | Ja, die Größe des Chats wird gespeichert (eine einzelne ganze Zahl) |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII – Jedes Mal, wenn eine Umfrage eine Antwort erhält, wird ein Erfolgs-/Fehlerprotokoll erstellt, und wir versuchen, diese Antwort über den Connector an Teams zu senden. Dieses Protokoll enthält user_id, survey_id, integration_id (die in der Datenbank zum Suchen nach MS-Team-ID, MS-Benutzer-ID verwendet werden kann)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Unser primäres Rechenzentrum befindet sich in Las Vegas, NV, und unser sekundäres Rechenzentrum befindet sich in Santa Clara, CA. SurveyMonkey besitzt und betreibt alle Server und Infrastruktur an diesen Standorten. Wir haben auch die kanadische Datenresidenz für bestimmte SurveyMonkey-Enterprise in Kanada. Alle Daten werden im Ruhetag mit TDE mit AES256 verschlüsselt, und daten während der Übertragung werden mit TLS 1.2 verschlüsselt.

SurveyMonkey verwendet die zentrale Benutzerauthentifizierung, um die Identitäts- und Zugriffsverwaltung zu verwalten. Dieses System verwaltet die Authentifizierung und Autorisierung für alle Unternehmens- und Produktionsinfrastrukturen, Systeme und Dienste. Strikte Zugriffsrichtlinien werden vierteljährlich beibehalten und überprüft. Die Rezensionen umfassen u. a.: Benutzerzugriffslisten, Richtliniengruppen und Zugriffsüberprüfungen von Drittanbietern. Um auf unsere Produktionsumgebung zu zugreifen (d. h. um ein privilegiertes Konto zu erhalten), muss man eine Managergenehmigung erhalten, eine Reihe erforderlicher Schulungen abschließen und die Genehmigung von unserem Sicherheitsteam einsorgen. Zu diesem Zeitpunkt wird ein zusätzliches VPN-Konto bereitgestellt, das das &#8216;normale&#8217; von einem &#8216;privilegierten&#8217; unterscheidet.

Nur vom Unternehmen ausgestellte Geräte dürfen auf unser Produktionsnetzwerk zugreifen. Alle Standardeinstellungen des Drahtlosanbieters werden vor der Installation geändert, einschließlich, aber nicht beschränkt auf Standard-WLAN-Verschlüsselungsschlüssel, Kennwörter und SNMP-Communityzeichenfolgen. 2FA und VPN sind dazu remote erforderlich. Wir verfügen über ein separates WLAN-Netzwerk für den Gastzugriff in unseren Unternehmensbüros.

Alle Dienste, Protokolle und zulässigen Ports müssen über eine dokumentierte geschäftliche Begründung und Genehmigung verfügen, einschließlich der Verwendung von Sicherheitsfeatures, die für diese protokolle implementiert werden, die als unsicher gelten. Router und Firewalls sind so konfiguriert, dass die IP-Offenlegung auf nicht autorisierte oder unbeabsichtigte Parteien begrenzt wird und der eingehende Internetzugriff auf IP-Adressen innerhalb der DMZ-Firewall begrenzt wird, und Routerregeln werden mindestens alle sechs Monate überprüft.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

