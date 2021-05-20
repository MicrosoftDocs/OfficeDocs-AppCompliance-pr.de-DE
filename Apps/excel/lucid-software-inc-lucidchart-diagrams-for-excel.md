---
title: Anwendungsinformationen für Lucidchart-Diagramme für Excel von Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Lucidchart-Diagramme für Excel, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5481ed9ce5f8e589fe5ea8703fb48b53c5dab488
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548795"
---
# <a name="lucidchart-diagrams-for-excel"></a>Luidchartdiagramme für Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Lucid Software Inc an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Luidchartdiagramme für Excel |
| ID | WA104380194 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf mac, Excel 2013 oder höher auf Windows, Excel im Web |
| Partnerunternehmensname | Lucid Software Inc |
| URL der Partnerwebsite | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| URL der Datenschutzrichtlinie | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Lucid Software Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | delegierte | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen Es Lucidchart, ein openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto zu registrieren. Um die daten zu überprüfen, die von Microsoft stammen, stellen wir eine Anforderung, den öffentlichen Schlüssel zu erhalten, mit dem die Antwort signiert ist. Es werden keine weiteren Daten von Microsoft empfangen oder an Microsoft im Rahmen unseres SSO-Fluss gesendet. |  |
>| openid | delegierte | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen Es Lucidchart, ein openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto zu registrieren. Um die daten zu überprüfen, die von Microsoft stammen, stellen wir eine Anforderung, den öffentlichen Schlüssel zu erhalten, mit dem die Antwort signiert ist. Es werden keine weiteren Daten von Microsoft empfangen oder an Microsoft im Rahmen unseres SSO-Fluss gesendet. |  |
>| Profil | delegierte | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen Es Lucidchart, ein openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto zu registrieren. Um die daten zu überprüfen, die von Microsoft stammen, stellen wir eine Anforderung, den öffentlichen Schlüssel zu erhalten, mit dem die Antwort signiert ist. Es werden keine weiteren Daten von Microsoft empfangen oder an Microsoft im Rahmen unseres SSO-Fluss gesendet. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Wir verwenden das Office OneDrive javascript SDK aus, um die OneDrive dateisuche mithilfe von OneDrive.open() zu öffnen. Wir generieren keine Zugriffstoken und stellen keine Anforderungen an OneDrive APIs selbst; Das OneDrive Datei-Auswahl-SDK führt dies für uns aus. Es werden nur die Dateinamen angezeigt, die der Benutzer ausgibt. |  | Wenn der Benutzer eine Datei mit der OneDrive auswählt, speichern wir den Dateinamen. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart-Daten werden in AWS gespeichert. |  | Wir verwenden keine Microsoft-APIs. Wir verwenden openID, um grundlegende Benutzerdaten für die Ausführung von SSO zu erhalten. Wir verwenden ihre Dateiauswahl-API, aber dadurch haben wir keinen Zugriff auf die Dateien des Benutzers, die uns über die Auswahl übermittelt werden. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren E-Mail- und IP-Adressen aus Sicherheits- und Supportgründen. Der Zugriff auf Protokolle ist aufgezeichnete Protokolle sind in einem Drittanbietersystem tatsächlich &amp; unveränderlich. Für den Zugriff auf Protokolle ist MFA erforderlich.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Lucidchart-Daten werden in AWS gespeichert. Es wird im Ruhe- und Transitbereich verschlüsselt. Lucidchart verwendet die Regeln der geringsten Rechte und MFA.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

