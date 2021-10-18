---
title: Anwendungsinformationen für genehmigte Kontaktkalender nach genehmigtem Kontakt
ms.author: elmalova
author: elenamalova
ms.date: 05/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für genehmigte Kontaktkalender, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6bf401411f26e95a952e75256bc46b8f28efed53
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428157"
---
# <a name="approved-contact-calendars"></a>Genehmigte Kontaktkalender

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 10, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von einem genehmigten Kontakt an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Genehmigte Kontaktkalender |
| ID | WA104380294 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher für Mac Outlook im Web |
| Name des Partnerunternehmens | Approved Contact |
| URL der Partnerwebsite | [https://www.approvedcontact.com](https://www.approvedcontact.com) |
| URL der Datenschutzrichtlinie | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| URL der Nutzungsbedingungen | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von genehmigten Kontakten darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Für den Kalender-BOT speichern wir Frei/Gebucht-Zeit für Benutzer, um freie Zeiten für mehrere Personen zu finden.  | Wir lesen und vergleichen Frei/Gebucht-Zeit und planen Besprechungen. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| Contacts.Read | Delegiert | Ja, wir speichern Kontaktinformationen. | Importieren und Synchronisieren von Kontakten. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.Read | Delegiert | Ja | Grundlegende Profilinformationen. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.ReadBasic.All | Delegiert | Nein | Wird zum Anzeigen von Profilen von Kollegen, zum Vergleichen von freien Zeiten und zum Planen von Konferenzräumen verwendet. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| offline_access | Delegiert | Ja, Frei/Gebucht-Zeiten für Offlinebenutzer. | Rufen Sie Graph auf, wenn der Benutzer unsere Website nicht aktiv verwendet. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| openid | Delegiert | Nein | Office 365 SSO. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir protokollieren E-Mail-Adressen zum Verbinden von Lizenzkäufen mit Commercial Appsource. Wir bieten die Möglichkeit, diese Informationen aus unseren Protokollen zu löschen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nur Entwickler haben Zugriff auf unsere Protokolle. Wir erzwingen 2FA für den Zugriff auf alle Entwicklungsplattformen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden vom genehmigten Kontakt bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
