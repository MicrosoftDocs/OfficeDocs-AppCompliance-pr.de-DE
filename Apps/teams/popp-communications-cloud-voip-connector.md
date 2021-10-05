---
title: Anwendungsinformationen für POP Cloud VoIP Connector von POP Communications
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für DEN POP-Cloud-VoIP-Connector, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9f64b18c26d3fd38e4272171e7a90f493e76de5f
ms.sourcegitcommit: 11288ac2cbae57aaa7820be0d9fb87c631805b7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/05/2021
ms.locfileid: "60112282"
---
# <a name="popp-cloud-voip-connector"></a>POP Cloud VoIP Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 20, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von DER POP-Kommunikation an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | POP Cloud VoIP Connector |
| ID | WA200003306 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | POP-Kommunikation |
| URL der Partnerwebsite | [https://popp.com](https://popp.com) |
| URL der Datenschutzrichtlinie | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von DER POP-Kommunikation darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Kanals. Die App verwendet dies, um dem Benutzer eine Liste der Kanalmitglieder anzuzeigen, die aufgerufen werden sollen. | Metaswitch speichert diese Daten nicht. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | Delegiert |  Welche Daten werden gesammelt oder verwendet? Fügen Sie eine Begründung für die Erfassung oder Verwendung der Daten hinzu. Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Chats. Die App verwendet dies, um dem Benutzer eine Liste der Chatmitglieder zu präsentieren, die angerufen werden sollen. | Metaswitch speichert diese Daten nicht. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | Delegiert | Benutzer-IDs und Anzeigenamen von Mitgliedern des aktuellen Teams. Die App verwendet dies, um dem Benutzer eine Liste der Teammitglieder anzuzeigen, die angerufen werden sollen. | Metaswitch speichert diese Daten nicht. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | Delegiert |  Welche Daten werden gesammelt oder verwendet? Fügen Sie eine Begründung für die Erfassung oder Verwendung der Daten hinzu. Die Geschäftlichen und Mobiltelefonnummern der Benutzer. Dies ist erforderlich, damit Anrufe zu diesen Nummern initiiert werden können. |   Metaswitch speichert diese Daten nicht | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | Delegiert | Ein Autorisierungstoken für den Benutzer, das die App für den Zugriff auf die anderen Graph API-Endpunkte autorisiert, die in ihrem Namen aufgeführt sind. | Metaswitch speichert diese Daten nicht. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs außer Microsoft Graph verwenden, um organisationsbezogene Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Identity Platform | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Metaswitch-Netzwerke und POP-Kommunikation | Die folgende OII wird auf den gehosteten MCT-Bot-Server übertragen: Der Inhalt des Azure AD-Mandanten-ID-Team-IDs-Kanals/Chat-IDs Nachrichteninhalte werden ebenfalls übertragen, was möglicherweise OII umfassen kann. Die folgenden OII können an die CommPortal JSON-API übertragen werden: Telefon Anzahl von Benutzern in einer Geschäftsgruppe Die Domänen der E-Mail-Adressen Benutzer-IP-Adressen | Fügen Sie eine Begründung dafür hinzu, warum Sie OII übertragen müssen. Der Hauptzweck der App&#8217;ist die Erleichterung von Telefonanrufen. Wenn ein Benutzer versucht, einen Telefonanruf zu tätigen, müssen diese Informationen bereitgestellt werden, um sich bei ihrem CommPortal-Konto anzumelden und den Anruf mit dem richtigen Benutzer zu korrelieren.  Das OII, das auf den gehosteten MCT-Bot-Server übertragen wird, ist in die Bot Framework-API integriert, die zur Integration in Teams verwendet wird und nicht vermieden werden kann. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Hauptzweck der App&#8217;ist die Erleichterung von Telefonanrufen. Wenn ein Benutzer versucht, einen Telefonanruf zu tätigen, muss EUII für alle Parteien des Anrufs bereitgestellt werden, um den Anruf zwischen den richtigen Telefoniebenutzern herzustellen. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Metaswitch und POPP speichern die Daten nicht länger als die sofortige Notwendigkeit, die MCT-Webseiten aus commPortal Web zu laden. Die Daten werden nicht aufbewahrt und sofort entfernt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von DER POP-Kommunikation darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Nein |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Richtlinien für bedingten Zugriff, soweit diese Unterstützung automatisch von der msal-Bibliothek bereitgestellt wird, die für die Authentifizierung verwendet wird.  |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Nein |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
