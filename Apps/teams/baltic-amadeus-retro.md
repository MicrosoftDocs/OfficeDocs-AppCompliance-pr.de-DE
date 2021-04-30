---
title: Anwendungsinformationen für "Retro" von "Baltic"-A0
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: 'Alle verfügbaren Sicherheits- und Complianceinformationen für Retro, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security Informationen zum #A0 sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.'
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 35a2849b5a9db58f3bda375b5fde1f2b39204780
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095517"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Baltic Amadeus an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Retro |
| ID | WA200001892 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Baltic Amadeus |
| URL der Partnerwebsite | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL der Datenschutzrichtlinie | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL der Nutzungsbedingungen | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Baltic Amadeus bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Die App "Retro" verfügt über eine eigene Web-API, die nicht als Microsoft-Dienst betrachtet wird. Wie bereits erwähnt, werden E-Mail und Fullname zur Identifizierung und zur entsprechenden Inhaltsanzeige gespeichert. Diese Daten werden an keine andere Stelle gesendet. Darüber hinaus verfügt "Retro" über eine optionale Funktion zum Exportieren von Sprintdaten in den Atlassian-Zusammenflussbereich. Dazu muss der Benutzer seinen Benutzernamen und das Kennwort für den Zusammenfluss eingeben. Diese Daten werden nur verwendet, um authentifizierte Anforderungen an die Confluence-API im Namen des Benutzers zu stellen und werden weder gespeichert noch an einem beliebigen Ort protokolliert. |  | Retro verfügt über eine eigene Web-API, die auch in azure registriert ist. Um sie verwenden zu können, muss der Benutzer über die Microsoft Identity Platform authentifiziert werden. Der Benutzer muss authentifiziert werden, damit die App "Retro" benutzerspezifische Inhalte servern kann |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot zugrifft auf den Dienstplan, um zu überprüfen, welches Mitglied dem Team beigetreten ist oder das Team verlassen hat. Auf dieser Grundlage wird dieser Benutzer entweder aus dem Projekt hinzugefügt oder deaktiviert, sodass der Benutzer nicht mehr in der Liste der Sprintteilnehmer angezeigt wird. | E-Mail und FullName sind miteinander verknüpft und werden in der Datenbank gespeichert. E-Mails werden zur Benutzeridentifizierung verwendet, um den entsprechenden Inhalt für den angemeldeten Benutzer anzuzeigen. FullName wird zum Anzeigen von Puproses verwendet, damit andere Benutzer wissen können, für wen sie Feedback auswerten oder schreiben.  |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein. Der einzige Prozess, der Telemetrie/Protokolle in der App "Retro" generiert, ist die Fehlerprotokollierung. Fehlerprotokolle enthalten keine EUII oder OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten werden in der azure sql server-Datenbank gespeichert. Sie wird über die App "Retro" und den "Retro-Bot" gespeichert.
Standardmäßig ist die transparente Datenverschlüsselung für azure sql database aktiviert.
Die Datenbank ist hinter der Standardauthentifizierung gesperrt.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

