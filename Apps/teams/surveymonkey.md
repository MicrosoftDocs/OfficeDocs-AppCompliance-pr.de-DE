---
title: Anwendungsinformationen für SurveyMonkey von SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SurveyMonkey, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f4898e476e0848ba728d07d0d851fc09f239aecf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282362"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SurveyMonkey für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SurveyMonkey |
| ID | WA104381088 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SurveyMonkey |
| URL der Partnerwebsite | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL der Datenschutzrichtlinie | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SurveyMonkey bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | Delegiert | Nein | So stellen Sie eine Liste von Gruppen/Kanälen bereit, mit denen eine Umfrage geteilt werden kann | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| In SurveyMonkey wird nur die MS-Benutzer-ID gespeichert, um Antworten und Umfragen dem Teambenutzer zuzuordnen. |  | Für Teams verwenden wir das Microsoft Teams Javascript SDK im Aufgabenmodul "Erstellen", "Umfrage" und "Umfrageergebnisse" modal. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir rufen v3/conversations/{id}/pagedmembers auf, um zu überprüfen, ob die App einem Team hinzugefügt wird, und die Mitgliederanzahl abzurufen. Es ist für die interne Nachverfolgung der Nutzung, wir betrachten nur die Größe der Chatliste, andere Informationen werden ignoriert. | Ja, die Größe des Chats wird gespeichert (eine einzelne ganze Zahl) |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII – Ein Erfolg-/Fehlerprotokoll wird erstellt, sobald eine Umfrage eine Antwort erhält, und wir versuchen, diese Antwort über den Connector an Teams zu senden. Dieses Protokoll enthält user_id, survey_id, integration_id (die in der Datenbank zum Nachschlagen der MS-Team-ID, MS-Benutzer-ID verwendet werden können)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Unser primäres Rechenzentrum befindet sich in Las Vegas, NV, und unser sekundäres Rechenzentrum befindet sich in Dersassem, Ca. SurveyMonkey besitzt und betreibt alle Server und Infrastruktur an diesen Standorten. Wir haben auch eine kanadische Datenaufbewahrung für bestimmte SurveyMonkey-Enterprise Kunden in Kanada zur Verfügung. Alle ruhenden Daten werden mithilfe von TDE mit AES256 verschlüsselt, und daten während der Übertragung werden mit TLS 1.2 verschlüsselt.

SurveyMonkey verwendet die zentrale Benutzerauthentifizierung, um die Identitäts- und Zugriffsverwaltung aufrechtzuerhalten. Dieses System verwaltet die gesamte Authentifizierung und Autorisierung für alle Unternehmens- und Produktionsinfrastrukturen, Systeme und Dienste. Strenge Zugriffsrichtlinien werden vierteljährlich beibehalten und überprüft. Die Überprüfungen umfassen unter anderem: Benutzerzugriffslisten, Richtliniengruppen und Zugriffsüberprüfungen von Drittanbietern. Um auf unsere Produktionsumgebung zuzugreifen (d. h. um ein privilegiertes Konto zu erhalten), muss man die Genehmigung des Vorgesetzten einholen, eine Reihe erforderlicher Schulungen durchführen und die Genehmigung von unserem Sicherheitsteam einholen. Zu diesem Zeitpunkt wird ein zusätzliches VPN-Konto bereitgestellt, das das &#8216;normale&#8217; konto von einem konto mit &#8216;privilegierten&#8217; unterscheidet.

Nur vom Unternehmen ausgestellte Geräte dürfen auf unser Produktionsnetzwerk zugreifen. Alle Standardeinstellungen des Anbieters für drahtlose Verbindungen werden vor der Installation geändert, einschließlich, aber nicht beschränkt auf standardmäßige drahtlose Verschlüsselungsschlüssel, Kennwörter und SNMP-Communityzeichenfolgen. 2FA und VPN sind erforderlich, um dies remote zu tun. Wir verfügen über ein separates WLAN-Netzwerk für den Gastzugriff in unseren Unternehmensstandorten.

Alle Dienste, Protokolle und zulässigen Ports müssen über eine dokumentierte geschäftliche Begründung und Genehmigung verfügen, einschließlich der Verwendung von Sicherheitsfeatures, die für diese Protokolle implementiert wurden, die als unsicher eingestuft werden. Router und Firewalls sind so konfiguriert, dass die IP-Offenlegung an nicht autorisierte oder unbeabsichtigte Parteien beschränkt wird und der eingehende Internetzugriff auf IP-Adressen innerhalb der DMZ-Firewall begrenzt wird, und Router-Regelsätze werden mindestens alle sechs Monate überprüft.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

