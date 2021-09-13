---
title: Anwendungsinformationen für Das StarLeaf-Add-In für Outlook von StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für das StarLeaf-Add-In für Outlook, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66f31eb44942e20b4db10d5e718eb67e3e50b03e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283373"
---
# <a name="starleaf-add-in-for-outlook"></a>StarLeaf-Add-In für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von StarLeaf für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | StarLeaf-Add-In für Outlook |
| ID | WA104381343 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher für Mac Outlook im Web |
| Name des Partnerunternehmens | StarLeaf |
| URL der Partnerwebsite | [https://www.starleaf.com](https://www.starleaf.com) |
| URL der Datenschutzrichtlinie | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| URL der Nutzungsbedingungen | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von StarLeaf zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Anwendung | wir speichern die iCalUId von Besprechungen, Uhrzeit/Datum der Besprechung, E-Mail-Adressen der Teilnehmer und eine Single-Value-Extended-Property, die wir mithilfe der benutzerdefinierten Eigenschaftenschnittstelle Office.js lesen und in die Besprechung schreiben. Die iCalUId wird verwendet, um die Besprechung in einem Outlook-Kalender eines Benutzers&#8217;mit der Videobesprechung in unserem Dienst zu korrelieren. Die Uhrzeit/das Datum und die Teilnehmer werden verwendet, um den richtigen Personen in unserem Dienst zur richtigen Zeit eine Videobesprechung bereitzustellen. SVEP wird mit unserem O365-Add-In verwendet, um Benutzern eine Benutzeroberfläche zum Festlegen von Details zur Videobesprechung in unserem Dienst bereitzustellen, z. B. Aufzeichnung. | verwendet, um Webhook-Benachrichtigungen zu abonnieren, um Benutzeränderungen an Ereignissen in ihren Kalendern nachzuverfolgen und unseren Dienst zu aktualisieren, um ihn konsistent zu halten. Es wird auch verwendet, um Ereignisse in ihrem Kalender zu erstellen, wenn ein Benutzer mit unserer Teams-App interagiert und eine Besprechung für unseren Dienst plant. | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |
>| User.Read | Anwendung | Wir speichern das oauth-Aktualisierungstoken, um sich anmelden zu können. Wir speichern die Benutzerprofil-ID, um zukünftige OAuth-Versuche dieses Benutzers vergleichen zu können, und stellen sicher, dass wir ihre Details nicht zweimal speichern&#8217;.  | Ermöglichen Sie Benutzern, sich bei der App anzumelden, und ermöglicht es unserer App, die E-Mail-Adresse des Benutzers&#8217;abzurufen, um seine Anmeldung mit einem Konto bei unserem Dienst zu korrelieren.  | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Wenn Probleme mit dem technischen Support auftreten, können organisatorische Daten zur Fallverwaltung an SalesForce übertragen werden. Wenn der Benutzer die PSTN-Einwahlfunktion verwendet, wird der Anruf durch Twilio, Plivo oder Voxbone fließen. |  | Nicht zutreffend |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja. Zu den Protokollen gehören Benutzernamen, IP-Adressen, Anrufdetaildatensätze, Informationen zur Verbindungsqualität (Paketverlust, Bitrate), Gerätetyp, Anruffortschritt. Die Informationen stehen dem technischen Supportteam und leitenden Entwicklern zur Diagnose von Dienstproblemen zur Verfügung. Die Daten werden nach 90 Tagen anonymisiert. Steuerelemente zum Schutz dieser Daten werden gemäß unserer ISO/IEC 27001-Zertifizierung geprüft.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten werden auf StarLeaf&#8217;eigenen Protokollservern im Datencenter gespeichert, in dem sich der Benutzer&#8217;Konto befindet, und auf einem oder mehreren Datenauftragsverarbeitern innerhalb derselben Gerichtsbarkeit gesichert. Der Zugriff auf die Daten erfolgt über ein einzelnes Benutzerkonto mithilfe von benutzerbezogenen Kennwörtern, die überprüft werden. Die Dienstbenutzerkonten von StarLeaf&#8217;werden automatisch anhand der HR-Systeme und der Active Directory-Gruppen des Unternehmens überwacht, um das Sicherheits- und Complianceteam zu benachrichtigen, wenn Anomalien gefunden werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

