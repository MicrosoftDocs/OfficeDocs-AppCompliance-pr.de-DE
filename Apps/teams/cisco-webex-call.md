---
title: Anwendungsinformationen für Webex-Anruf von Cisco
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Webex Call, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e4addbd6b3ad932c9c987f57cca03c1e6e77cfcd
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281348"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 4. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Cisco für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Webex Call |
| ID | WA200001495 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cisco |
| URL der Partnerwebsite | [https://www.cisco.com](https://www.cisco.com) |
| URL der Datenschutzrichtlinie | [https://www.cisco.com/c/en/us/about/legal/privacy.html](https://www.cisco.com/c/en/us/about/legal/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Cisco bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.Read | Delegiert | Chatmitglieder abrufen, um das andere Mitglied in einem privaten Chat mit Cisco WebEx anzurufen | Die App speichert keine Daten in ihren Datenbanken. | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| Contacts.Read | Delegiert | Abrufen von Benutzerkontakten, damit Benutzer Kontakte mit Cisco WebEx anrufen können | Die App speichert keine Daten in ihren Datenbanken. | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.Read | Delegiert | Benutzer-E-Mails abrufen, Telefone, damit sie Cisco WebEx starten können, um E-Mails oder Telefone anzurufen | Die App speichert keine Daten in ihren Datenbanken. | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadBasic.All | Delegiert | Benutzer-E-Mails abrufen, Telefone, damit sie Cisco WebEx starten können, um E-Mails oder Telefone anzurufen | Die App speichert keine Daten in ihren Datenbanken. | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadWrite | Delegiert | Diese Berechtigung besteht darin, Schnellwahlinformationen in der Benutzererweiterung zu speichern. | Die App speichert keine Daten in ihren Datenbanken.  | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Diese Nachrichtenerweiterung würde die E-Mails/Telefone von Chatmitgliedern lesen, damit der Benutzer sie mit Cisco WebEx anrufen kann. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Diese App speicherte keine Benutzerdaten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Cisco darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
