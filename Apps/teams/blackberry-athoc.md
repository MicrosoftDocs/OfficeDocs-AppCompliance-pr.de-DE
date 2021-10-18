---
title: Anwendungsinformationen für BlackBerry AtHoc von BlackBerry
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für BlackBerry AtHoc, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 60183f04c8f82a7e2c365bb26ee73db7a787147a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428358"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. Juni 2021</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von BlackBerry für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | BlackBerry AtHoc |
| ID | WA200003065 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | BlackBerry |
| URL der Partnerwebsite | [https://www.blackberry.com](https://www.blackberry.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| URL der Datenschutzrichtlinie | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von BlackBerry darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Profil | Delegiert | Wir greifen auf die grundlegenden Details des Benutzers&#8217;zu, z. B. den Prinzipalnamen und den Link zum allgemeinen Kanal von Teams (für den der angemeldete Benutzer autorisiert ist), um die Benachrichtigungskarte an die Teams zu senden. | Wir&#8217;die Benutzerdaten nicht in der Datenbank, sondern im Bot-Speicher speichern. Wir speichern den Prinzipalnamen des angemeldeten Benutzers, AAD Token, BlackBerry AtHoc-Token, BlackBerry AtHoc Server-Einstellung/-Konfiguration im Bot-Speicher. Benötigen Sie die Informationen zum Senden von API-Anforderungen an die Microsoft Graph-API und unseren BlackBerry AtHoc-Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>–

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von BlackBerry bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
