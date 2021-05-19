---
title: Anwendungsinformationen für InStation von Entwicklern Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für InStation, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552246"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 6. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Entwickler Invillia Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | InStation |
| ID | WA200001701 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Developers Invillia |
| URL der Partner-Website | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL der Datenschutzrichtlinie | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL der Nutzungsbedingungen | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Entwickler invillia darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | Delegiert | Filialen: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | Filialen: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | Delegiert | Filialen: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | Filialen: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | Delegiert | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | Aktivität und Avaliability. Ermöglicht der App, den Benutzerstatus zu erfassen; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | Delegiert | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden, | Aktivität und Avaliability. Ermöglicht der App, den Benutzerstatus zu erfassen; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | Delegiert | Speichert: id, Mail, Anzeigename, Nachname und Bild. Ermöglicht der App die Suche nach Benutzerdaten; | Speichert: id, Mail, Anzeigename, Nachname und Bild. Ermöglicht der App die Suche nach Benutzerdaten; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | Delegiert | Speichert: id, Mail, Anzeigename, Nachname und Bild. Ermöglicht der App die Suche nach Benutzerdaten; | Speichert: id, Mail, Anzeigename, Nachname und Bild. Ermöglicht der App die Suche nach Benutzerdaten; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | Delegiert | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;beim ersten Login zu erfassen | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;beim ersten Login zu erfassen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | Delegiert | Stores: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen | Stores: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | Delegiert | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Profil | Delegiert | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;bei der ersten Anmeldung zu erfassen. | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;bei der ersten Anmeldung zu erfassen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern nur Benutzernutzungsprotokolle in unserer Anwendung.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern nur Benutzernutzungsprotokolle in unserer Anwendung. Nichts Vertrauliches, das keine Verschlüsselung erfordert und nur unsere spezifischen Administratoren haben Zugriff auf diese Daten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

