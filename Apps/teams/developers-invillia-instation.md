---
title: Anwendungsinformationen für InStation von Entwicklern Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für InStation, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Developers Invillia an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | InStation |
| ID | WA200001701 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Developers Invillia |
| URL der Partnerwebsite | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL der Datenschutzrichtlinie | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL der Nutzungsbedingungen | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Developers Invillia darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | delegierte | stores: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | stores: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | delegierte | stores: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | stores: id, join_url, join_web_url und chat_id. Ermöglicht der App das Erstellen von Besprechungen | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | delegierte | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | Aktivität und Vergeltung. Ermöglicht der App, den Benutzerstatus zu erfassen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | delegierte | Ermöglicht der App, sich bei ihrem ersten Schritt bei der Organisation anzumelden. | Aktivität und Vergeltung. Ermöglicht der App, den Benutzerstatus zu erfassen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | delegierte | stores: id, mail, display name, surname and picture. Ermöglicht der App, nach Benutzerdaten zu suchen. | stores: id, mail, display name, surname and picture. Ermöglicht der App, nach Benutzerdaten zu suchen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | delegierte | stores: id, mail, display name, surname and picture. Ermöglicht der App, nach Benutzerdaten zu suchen. | stores: id, mail, display name, surname and picture. Ermöglicht der App, nach Benutzerdaten zu suchen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | delegierte | Ermöglicht der App, die grundlegenden Informationen&#180;Administratorinformationen bei der ersten Anmeldung zu erfassen. | Ermöglicht der App, die grundlegenden Informationen&#180;Administratorinformationen bei der ersten Anmeldung zu erfassen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | delegierte | Stores: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen. | Stores: Token und Aktualisierungstoken. Ermöglicht der App, eine Aktualisierung des MS-Tokens durchzuführen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | delegierte | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | Ermöglicht der App, sich im ersten Schritt bei der Organisation anzumelden | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Profil | delegierte | Ermöglicht der App, die grundlegenden Informationen&#180;Administratorinformationen bei der ersten Anmeldung zu erfassen. | Ermöglicht der App, die grundlegenden Informationen&#180;Administratorinformationen bei der ersten Anmeldung zu erfassen. | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern nur Benutzerverwendungsprotokolle in unserer Anwendung.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern nur Benutzerverwendungsprotokolle in unserer Anwendung. Nichts vertrauliches, das keine Verschlüsselung erfordert, und nur unsere spezifischen Administratoren haben Zugriff auf diese Daten.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

