---
title: Anwendungsinformationen für Myfone von Flexfone
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Myfone, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37967a116553b7c7b83b1809c9b23a56822be5ed
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282818"
---
# <a name="myfone"></a>Myfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5f447fa4-da1f-4651-a0da-d2488a404c19" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000716" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Flexfone für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Myfone |
| ID | WA200000716 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Flexfone |
| URL der Partnerwebsite | [https://flexfone.dk](https://flexfone.dk) |
| URL der Seite mit Teams Anwendungsinformationen | [https://faq.flexfone.dk/da](https://faq.flexfone.dk/da) |
| URL der Datenschutzrichtlinie | [https://flexfone.dk/privatlivs-og-cookiepolitik](https://flexfone.dk/privatlivs-og-cookiepolitik) |
| URL der Nutzungsbedingungen | [https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf](https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Flexfone darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Kalender werden verwendet, damit Benutzer kollegen ihre Kalandar anzeigen und Besprechungen zum Einrichten ihrer Telefonie verwenden können. | Kalender werden verwendet, damit Benutzer kollegen ihre Kalandar anzeigen und Besprechungen zum Einrichten ihrer Telefonie verwenden können. | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| Contacts.Read | Delegiert | Die Kontakte der Benutzer können gespeichert werden, wenn sie sie in der App anzeigen möchten, um die Auswahl von Kontakten zu vereinfachen. | Die Kontakte der Benutzer können gespeichert werden, wenn sie sie in der App anzeigen möchten, um die Auswahl von Kontakten zu vereinfachen. | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | Delegiert | Benutzer, die in dieser Anwendung gelesen werden, werden zu Identifizierungszwecken verwendet. | Benutzer, die in dieser Anwendung gelesen werden, werden zu Identifizierungszwecken verwendet. | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | Delegiert | Wir speichern die Daten nicht. Die Anwendung wird einfach zu Authentifizierungszwecken verwendet. | Wir speichern die Daten nicht. Die Anwendung wird einfach zu Authentifizierungszwecken verwendet. | [f0199b83-0ca3-4b41-a23b-d9b234484438](https://docs.microsoft.com/microsoft-365-app-certification/azure/f0199b83-0ca3-4b41-a23b-d9b234484438) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS. AccessAsUser.All | Ja | Firmenname, Mitarbeiternamen und Telefonnummern | Anzeigen der Daten für die Benutzer in der App und deren Verwendung | Firmenname, Mitarbeiternamen und Telefonnummern | Anzeigen der Daten für die Benutzer in der App und deren Verwendung |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Ribbon Communications, Voxbone, team.blue, Fakturaservice.dk A/S, Flexible | Firmenname, Mitarbeiternamen und Telefonnummern | Das Menüband stellt unseren Teams SBC bereit. Voxbone wird für internationale Nummern verwendet, jedoch nur, wenn Sie diese haben. team.blue ist unser Hostinganbieter. FakturaService.dk A/S wird für die Abrechnung verwendet. Flexibles Wird für die Protokollierung verwendet |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Jeder Benutzer ist ein Mitarbeiter eines Unternehmens, das unsere Dienste nutzt. Sie verfügen über einen Administrator, der Daten löschen und bearbeiten kann. DpAs sind ebenfalls vorhanden, bevor Endbenutzer Zugriff erhalten

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

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

Diese Informationen wurden von Flexfone darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
