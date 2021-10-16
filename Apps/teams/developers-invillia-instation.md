---
title: Anwendungsinformationen für InStation von Entwickler Invillia
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für InStation, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 33ef3024f1b0e9b70cb6445e28c71ee1f6de22be
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411773"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Developers Invillia an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | InStation |
| ID | WA200001701 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Developers Invillia |
| URL der Partnerwebsite | [https://invillia.com/](https://invillia.com/) |
| URL der Datenschutzrichtlinie | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL der Nutzungsbedingungen | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Developers Invillia darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.Read.All | Delegiert | Speicher: ID, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | Speicher: ID, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| OnlineMeetings.ReadWrite.All | Delegiert | Speicher: ID, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | Speicher: ID, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read | Delegiert | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden. | Aktivität und Haftung. Ermöglicht der App, den Benutzerstatus zu erfassen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read.All | Delegiert | Ermöglicht der App, sich bei ihrem ersten Schritt bei der Organisation anzumelden. | Aktivität und Haftung. Ermöglicht der App, den Benutzerstatus zu erfassen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read | Delegiert | Speicher: ID, E-Mail, Anzeigename, Nachname und Bild. Ermöglicht der App, nach Benutzerdaten zu suchen. | Speicher: ID, E-Mail, Anzeigename, Nachname und Bild. Ermöglicht der App, nach Benutzerdaten zu suchen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read.All | Delegiert | Speicher: ID, E-Mail, Anzeigename, Nachname und Bild. Ermöglicht der App, nach Benutzerdaten zu suchen. | Speicher: ID, E-Mail, Anzeigename, Nachname und Bild. Ermöglicht der App, nach Benutzerdaten zu suchen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| email | Delegiert | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;bei der ersten Anmeldung zu erfassen. | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;bei der ersten Anmeldung zu erfassen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| offline_access | Delegiert | speichert: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen. | speichert: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| openid | Delegiert | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden. | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Profil | Delegiert | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;beim ersten Anmelden zu erfassen. | Ermöglicht der App, die grundlegenden Informationen des Administrators&#180;beim ersten Anmelden zu erfassen. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern nur Benutzernutzungsprotokolle in unserer Anwendung.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern nur Benutzernutzungsprotokolle in unserer Anwendung. Nichts Vertrauliches, das keine Verschlüsselung erfordert, und nur unsere spezifischen Administratoren haben Zugriff auf diese Daten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


