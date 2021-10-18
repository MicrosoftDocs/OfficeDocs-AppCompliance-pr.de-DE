---
title: Anwendungsinformationen für Diete von Baltisch (Baltisch)
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Denz, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 044866a2d32323ea0c63243aebcba429e165e224
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429993"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Der Baltisch für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Retro |
| ID | WA200001892 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Baltic Amadeus |
| URL der Partnerwebsite | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL der Datenschutzrichtlinie | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL der Nutzungsbedingungen | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Der baltisch-baltisch-benutzerdefinierten Abteilung bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Die Webanwendung verfügt über eine eigene Web-API, die nicht als Microsoft-Dienst betrachtet wird. Wie bereits erwähnt, werden E-Mail und Fullname zur Identifizierung und zu geeigneten Inhaltsanzeigezwecken gespeichert. Diese Daten werden an keiner anderen Stelle gesendet. Darüber hinaus verfügt Einer über eine optionale Funktionalität zum Exportieren von Sprintdaten in den Atlassian-Zusammenflussbereich. Dazu muss der Benutzer den Zugehörigen Benutzernamen und das Kennwort eingeben. Diese Daten werden nur verwendet, um authentifizierte Anforderungen an die Confluence-API im Namen des Benutzers zu senden, und sie werden nicht gespeichert oder an einer beliebigen Stelle protokolliert. |  | Der Besitzer verfügt über eine eigene Web-API, die auch in Azure registriert ist. Um sie verwenden zu können, muss der Benutzer über die Microsoft Identity Platform authentifiziert werden. Der Benutzer muss authentifiziert werden, damit die App benutzerspezifische Inhalte servern kann. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot greift auf die Liste zu, um zu überprüfen, welches Mitglied dem Team beigetreten ist oder dieses verlassen hat. Basierend darauf wird dieser Benutzer entweder aus dem Projekt hinzugefügt oder deaktiviert, sodass der Benutzer nicht mehr in der Liste der Sprintteilnehmer angezeigt wird. | E-Mails und FullName sind miteinander verknüpft und werden in der Datenbank gespeichert. E-Mails werden für die Benutzeridentifikation verwendet, um geeignete Inhalte für den angemeldeten Benutzer anzuzeigen. FullName wird zum Anzeigen von Bestätigungen verwendet, damit andere Benutzer wissen können, für wen sie Feedback auswerten oder schreiben.  |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein. Der einzige Prozess, der Telemetrie/Protokolle in Der App generiert, ist die Fehlerprotokollierung. Fehlerprotokolle enthalten keine EUII oder OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten werden in der Azure SQL Server-Datenbank gespeichert. Sie wird über die App Und Denk bot gespeichert.
Standardmäßig ist in der Azure SQL-Datenbank die transparente Datenverschlüsselung aktiviert.
Die Datenbank ist hinter der Standardauthentifizierung gesperrt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

