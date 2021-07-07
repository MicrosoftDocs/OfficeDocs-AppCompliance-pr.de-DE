---
title: Anwendungsinformationen für Lucidchart von Lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Lucidchart, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 65a82c3e895af38dc719411c7729825acae2f9be
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281768"
---
# <a name="lucidchart"></a>Lucidchart

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7f905be6-3226-4a4c-9c54-ab1edce3c99c" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381935" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Lucid Software für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Lucidchart |
| ID | WA104381935 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Lucid Software |
| URL der Partnerwebsite | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://lucidchart.zendesk.com/](https://lucidchart.zendesk.com/) |
| URL der Datenschutzrichtlinie | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL der Nutzungsbedingungen | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Lucid Software dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidchart, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. |  |
>| openid | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidchart, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. |  |
>| Profil | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidchart, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um Organisationsdaten zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Wir verwenden das Office OneDrive Javascript SDK von, um die OneDrive Dateiauswahl mit OneDrive.open() zu öffnen. Wir generieren keine Zugriffstoken und stellen keine Anforderungen an die APIs von OneDrive; das OneDrive Dateiauswahl-SDK erledigt dies für uns. Es werden nur die Dateinamen angezeigt, die der Benutzer auswählt. |  | Wenn der Benutzer eine Datei mithilfe der OneDrive Dateiauswahl auswählt, wird der Dateiname gespeichert. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart-Daten werden in AWS gespeichert. |  | Wir verwenden keine Microsoft-APIs. Wir verwenden openID, um grundlegende Benutzerdaten zum Ausführen von SSO abzurufen. Wir verwenden die Dateiauswahl-API, aber dadurch erhalten wir keinen Zugriff auf die Dateien des Benutzers, die sie über die Auswahl an uns übermitteln. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren E-Mail- und IP-Adressen aus Sicherheits- und Supportgründen. Der gesamte Zugriff auf Protokolle ist &amp; aufgezeichnete Protokolle, die in einem Drittanbietersystem nicht geändert werden können. Der Zugriff auf Protokolle erfordert MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Lucidchart-Daten werden in AWS gespeichert. Er wird im Ruhezustand und während der Übertragung verschlüsselt. Lucidchart verwendet die Regeln der geringsten Rechte und der MFA.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

