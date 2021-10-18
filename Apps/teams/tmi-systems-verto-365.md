---
title: Anwendungsinformationen für Verto 365 von TMI Systems
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Verto 365, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d2df916918905ba719980d2ee70dbefd4921998a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429663"
---
# <a name="verto-365"></a>Verto 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b27c082b-9d45-490a-b8bb-8dcda46c73f3" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003230" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von TMI-Systemen für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Verto 365 |
| ID | WA200003230 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | TMI-Systeme |
| URL der Partnerwebsite | [https://www.vertocloud.co.uk](https://www.vertocloud.co.uk) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.vertocloud.com](https://www.vertocloud.com) |
| URL der Datenschutzrichtlinie | [https://vertocloud.co.uk/privacy-policy/](https://vertocloud.co.uk/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://vertocloud.co.uk/terms-and-conditions/](https://vertocloud.co.uk/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von TMI Systems bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Allgemeine Benutzerinformationen, Vornamen, &amp; Nachnamen-E-Mail. Wird zum Erstellen eines Kontos verwendet. | Vorname, Nachname, E-Mail, OID. OID wird zum Erstellen eines Kontos in der Datenbank verwendet, um eine Anmeldung mit einem Verto-Konto zu verknüpfen. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| email | Delegiert | Allgemeine Benutzerinformationen, Vornamen, &amp; Nachnamen-E-Mail. Wird zum Erstellen eines Kontos verwendet. | Vorname, Nachname, E-Mail, OID. OID wird zum Erstellen eines Kontos in der Datenbank verwendet, um eine Anmeldung mit einem Verto-Konto zu verknüpfen. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| offline_access | Delegiert | Wird verwendet, um Aktualisierungstoken abzurufen und die Anmeldung beizubehalten | Nicht zutreffend | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| openid | Delegiert | Allgemeine Benutzerinformationen, Vornamen, &amp; Nachnamen-E-Mail. Wird zum Erstellen eines Kontos verwendet. | Vorname, Nachname, E-Mail, OID. OID wird zum Erstellen eines Kontos in der Datenbank verwendet, um eine Anmeldung mit einem Verto-Konto zu verknüpfen. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| Profil | Delegiert | Allgemeine Benutzerinformationen, Vornamen, &amp; Nachnamen-E-Mail. Wird zum Erstellen eines Kontos verwendet. | Vorname, Nachname, E-Mail, OID. OID wird zum Erstellen eines Kontos in der Datenbank verwendet, um eine Anmeldung mit einem Verto-Konto zu verknüpfen. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Organisationsname, Vorname, Nachname, Unternehmens-E-Mail-Adresse. Aufbewahrungsrichtlinien flexibel basierend auf internen Kundenrichtlinien, aber immer innerhalb der DSGVO.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Endbenutzerberechtigungen über zugriffssteuerungsliste. Administratoren können Daten entweder löschen oder ausblenden, das Überwachungsprotokoll kann von Endbenutzern überhaupt nicht geändert werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von TMI Systems darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
