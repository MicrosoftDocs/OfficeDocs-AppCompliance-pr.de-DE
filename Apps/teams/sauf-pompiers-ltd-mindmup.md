---
title: Anwendungsinformationen für MindMup von Sauf Pomiers Ltd
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für MindMup, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0bf09c9e6a144fb4415879577af4debcc5fc6713
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283059"
---
# <a name="mindmup"></a>MindMup

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001759" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Sauf Holdingiers Ltd an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | MindMup |
| ID | WA200001759 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Sauf Pompiers Ltd |
| URL der Partnerwebsite | [https://www.mindmup.com](https://www.mindmup.com) |
| URL der Datenschutzrichtlinie | [https://www.mindmup.com/resources/privacy_policy.html](https://www.mindmup.com/resources/privacy_policy.html) |
| URL der Nutzungsbedingungen | [https://www.mindmup.com/resources/terms_mindmup.html](https://www.mindmup.com/resources/terms_mindmup.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Sauf Holdingiers Ltd zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS-Speichersysteme, die verwendet werden, um grundlegende Benutzerprofilinformationen zu speichern, um die Freigabe von Dokumenten und den sicheren Zugriff auf Benutzerdokumente auf MindMup zu unterstützen |  | Nicht zutreffend |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Der Sicherheitszugriff protokolliert die Benutzer-ID, die Office 365-Mandanten-ID und Zugriffszeitstempel. Sie werden beibehalten, um Betrug und Missbrauch zu verhindern.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Benutzerdokumente werden in AWS (us-east-1) gespeichert, bei der Übertragung verschlüsselt und im Ruhezustand verschlüsselt. Die Daten sind für die Benutzer verfügbar, die die Dokumente erstellt haben, und für alle Benutzer, für die der Besitzer das Dokument explizit freigegeben hat.

Der gesamte Operator-/Administratorzugriff ist durch 2FA geschützt.

Der Benutzer- und Clientadministratorzugriff erfolgt über die integrierte Authentifizierung von Microsoft/Azure AD, wobei 2FA-Optionen direkt über SSO verfügbar sind.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

