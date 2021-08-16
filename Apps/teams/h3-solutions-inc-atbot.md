---
title: Anwendungsinformationen für AtBot von H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für AtBot, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d71404e66489ba3f1e81ca5f1a1a92c17b36f9e6
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/13/2021
ms.locfileid: "58239747"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von H3 Solutions, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | AtBot |
| ID | WA104381219 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | H3 Solutions, Inc. |
| URL der Partnerwebsite | [https://atbot.io](https://atbot.io) |
| URL der Seite mit Teams Anwendungsinformationen | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL der Datenschutzrichtlinie | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL der Nutzungsbedingungen | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von H3 Solutions, Inc. bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | Anwendung | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um die Sicherheitskürzung von Bot-Fähigkeiten zu ermöglichen. Auflisten von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden sollen | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| Directory.Read.All | Delegiert | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um die Sicherheitskürzung von Bot-Fähigkeiten zu ermöglichen. Auflisten von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden sollen | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| People.Read | Delegiert | Nein | Aufzählen von Personen in einer Aktion "Person abrufen" aus Flow.  Ermöglicht es dem Bot, Personen vom /People-Endpunkt in Microsoft Graph abzurufen. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| User.Read | Delegiert | Mandanten-ID, UPN | Ermöglicht uns den Zugriff auf die Mandanten-ID und den UPN des Benutzers&#8217;, damit wir die erstellten Flows/Logik-Apps mit den Benutzern verknüpfen können, die sie erstellt haben. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| email | Delegiert | E-Mail-Adressen werden verwendet, um den Support über unser Supportsystem zu kontaktieren. | Ermöglicht uns den Zugriff auf die E-Mail-Adresse des Benutzers. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| offline_access | Delegiert | Zugriffs-/Aktualisierungstoken. | Ermöglicht es uns, ein Aktualisierungstoken zu verwenden, um Benutzer angemeldet zu halten. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| openid | Delegiert | UPN, identifiziert den Benutzer innerhalb unseres Systems | Ermöglicht Benutzern die Anmeldung. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| profile | Delegiert | UPN | Zugriff auf den UPN des Benutzers. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Bot kann auf den UPN des Benutzers zugreifen, um Benutzer zu @mention oder Nachrichten an sie zu senden. | UPN | Wir müssen den UPN speichern, damit Benutzer auf das System zugreifen können. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Mandanten-ID, UPN. Wir verwenden Anwendungs-Insights und unsere Protokolle dauern 90 Tage, bevor sie automatisch archiviert werden. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Administratoren können Botkonfigurationen löschen, die AAD-Gruppennamen/-GUIDs enthalten können.
Nach dem Abbruch des Diensts werden alle UPNs aus der Lizenzierungsdatenbank entfernt.
Siehe "Azure Services" unter Data Residency.  Ein Großteil der kundenspezifischen Daten, die über die Verwendung von AtBot erstellt werden, werden im Mandanten des Kunden gespeichert, sodass Administratoren dieses Mandanten die volle Kontrolle über die daten dort haben.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von H3 Solutions, Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
