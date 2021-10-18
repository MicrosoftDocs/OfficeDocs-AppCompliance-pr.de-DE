---
title: Anwendungsinformationen für SuperBeings von Haptivity Technologies Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SuperBeings, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d16100c156419c55e199268168cfb9d667e00802
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430474"
---
# <a name="superbeings"></a>SuperBeings

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/1e7931be-a76f-4b12-b1b3-8914c7860aec" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003246" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Haptivity Technologies Pvt Ltd an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SuperBeings |
| ID | WA200003246 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Haptivity Technologies Pvt Ltd |
| URL der Partnerwebsite | [https://www.superbeings.ai](https://www.superbeings.ai) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.superbeings.ai](https://www.superbeings.ai) |
| URL der Datenschutzrichtlinie | [https://www.superbeings.ai/policy](https://www.superbeings.ai/policy) |
| URL der Nutzungsbedingungen | [https://www.superbeings.ai/terms-of-use](https://www.superbeings.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Haptivity Technologies Pvt Ltd darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://api.botframework.com/.default | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.sendinblue.com | Es wird keine OII übertragen, nur E-Mails und Benutzernamen werden für E-Mail-Dienste übertragen. | Siehe antwort oben. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Organisationen, die sich registrieren, um unseren Dienst zu verwenden, teilen E-Mails von Mitarbeitern mit uns. Wir versuchen, E-Mails vom Bot abzurufen, um die richtigen Informationen für einen Benutzer zu synchronisieren und den Benutzer besser zu bedienen. | E-Mails | Wir verwenden die E-Mail-ID, um Daten aus verschiedenen Diensten zu synchronisieren. Das gleiche gilt auch für unseren Teams-Bot. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Organisationsname und E-Mail-IDs/Name der Mitarbeiter konnten in Protokollen gefunden werden. Protokolle werden für einen Monat aufbewahrt, nach dem sie gelöscht werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle unsere Partner sind DSGVO-konform. Daher können wir das Löschen/Archivieren und die Datenaufbewahrung für alle Systeme anfordern, die SuperBeings verwendet oder mit denen superBeings interagiert.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Haptivity Technologies Pvt Ltd darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
