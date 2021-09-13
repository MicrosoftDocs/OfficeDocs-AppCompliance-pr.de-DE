---
title: Anwendungsinformationen für Go1 by Go1
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Go1, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d6fa3c9d0ecf710724379da869fba4b0cec23f6a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281528"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Go1 an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Go1 |
| ID | WA200001484 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Go1 |
| URL der Partnerwebsite | [https://www.go1.com/user/login](https://www.go1.com/user/login) |
| URL der Datenschutzrichtlinie | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Go1 dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | Anwendung | App speichert keine Dateidaten | ermöglicht Benutzern das Hochladen und Freigeben von Dateien aus OneDrive | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |
>| Group.ReadWrite.All | Anwendung | Teams und Kanalname und eindeutige IDs zur Unterstützung der App, die die Lernumgebung verwaltet | ermöglicht der App, Teams und Kanäle dynamisch einzurichten, um strukturiertes Lernen in Teams Umgebung zu unterstützen. | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |
>| User.Read.All | Anwendung | Benutzername und E-Mail und UPN gespeichert, um direkte persönliche Erfahrung zu ermöglichen | ermöglicht die Verwendung zum Signieren und Unterstützen der Freigabe von Lernressourcen zwischen Teammitgliedern | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Der Vor- und Nachname der Benutzer kann bei der Wiedergabe von Kursinhalten mit den Inhaltsanbietern von GO1 geteilt werden. Dies wird nur freigegeben, wenn der Inhaltsanbieter eine personalisierte Lernerfahrung bereitstellen muss. |  | Nicht zutreffend |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>GO1 verhindert die Speicherung von persönlichen oder organisationsbezogenen Informationen. Ausführliche Anwendungsprotokolle, in denen diese Daten gespeichert werden, werden innerhalb von 90 Werktagen nach der Erstellung gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>2FA ist für alle Mitarbeitersysteme erforderlich. GO1-Systemzugriff verwaltet nach Rolle. Nur Rollen, die Zugriff benötigen, um ihre Aufgaben auszuführen, erhalten Zugriff auf Produktionssysteme. Interne Richtlinien erfordern, dass Daten während der Übertragung und im Ruhezustand immer verschlüsselt werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

