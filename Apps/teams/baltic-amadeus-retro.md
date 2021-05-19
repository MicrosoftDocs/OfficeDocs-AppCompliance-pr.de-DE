---
title: Anwendungsinformationen für Retro von Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Retro, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553456"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Baltic Amadeus an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Retro |
| ID | WA200001892 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Baltic Amadeus |
| URL der Partner-Website | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL der Datenschutzrichtlinie | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL der Nutzungsbedingungen | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Baltic Amadeus darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Retro-App verfügt über eine eigene Web-API, die nicht als Microsoft-Dienst betrachtet wird. Wie bereits erwähnt, speichert es E-Mail und Fullname zur Identifizierung und entsprechenden InhaltsanzeigeZwecke. Diese Daten werden nirgendwo anders gesendet. Darüber hinaus verfügt Retro über eine optionale Funktionalität zum Exportieren von Sprintdaten in den Atlassian-Konfluenzraum. Dazu muss der Nutzer seinen Confluence-Benutzernamen und sein Passwort eingeben. Diese Daten werden nur verwendet, um authentifizierte Anforderungen an confluence api im Namen des Benutzers zu stellen und werden nirgendwo gespeichert oder protokolliert. |  | Retro verfügt über eine eigene Web-API, die ebenfalls in azure registriert ist. Um sie verwenden zu können, muss der Benutzer über die Microsoft Identity Platform authentifiziert werden. Der Benutzer muss authentifiziert werden, damit die Retro-App benutzerspezifische Inhalte serverservern kann |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot greift auf den Dienstplan zu, um zu überprüfen, welches Mitglied dem Team beigetreten ist oder es verlassen hat. Auf dieser Grundlage wird dieser Benutzer aus dem Projekt entweder hinzugefügt oder deaktiviert, sodass der Benutzer nicht mehr in der Liste der Sprintteilnehmer angezeigt wird. | E-Mail und FullName sind miteinander verknüpft und werden in der Datenbank gespeichert. E-Mail wird zur Benutzeridentifikation verwendet, um dem angemeldeten Benutzer den entsprechenden Inhalt anzuzeigen. FullName wird zum Anzeigen von Puproses verwendet, damit andere Benutzer wissen können, für wen sie feedbackieren oder Feedback schreiben.  |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Nein. Der einzige Prozess, der Telemetriedaten/Protokolle in der Retro-App generiert, ist die Fehlerprotokollierung. Fehlerprotokolle enthalten keine EUII oder OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten werden in der azure sql Server-Datenbank gespeichert. Es wird über Retro App und Retro Bot gespeichert.
Standardmäßig ist für die azure sql-Datenbank eine transparente Datenverschlüsselung aktiviert.
Die Datenbank ist hinter der Standardauthentifizierung gesperrt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

