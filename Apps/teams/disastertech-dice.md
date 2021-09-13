---
title: Anwendungsinformationen für DisasterTech DICE von DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für DisasterTech DICE, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8eec2ad9c7047a33dae446943c3ab2d934cc78c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283067"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von DisasterTech für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | DisasterTech |
| URL der Partnerwebsite | [https://www.disastertech.com](https://www.disastertech.com) |
| URL der Datenschutzrichtlinie | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von DisasterTech bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | E-Mail-Adresse des Benutzers, die zum Einrichten von Zugriffsrechten gespeichert ist, sowie Benutzername, um Benutzer anhand des Namens zu identifizieren | Ermöglicht es dem Benutzer, sich anzumelden, und gewährt app-Zugriff auf den UPN, um die automatische Anmeldung sowie Teams Anmeldung zu aktivieren, auch um Benutzernamen und E-Mail-Adressen einzurichten. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| email | Delegiert | Keine | Erforderlich für Teams einzelnen Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| offline_access | Delegiert | Keine | Erforderlich für Teams einzelnen Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| openid | Delegiert | Keine | Erforderlich für Teams einzelnen Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| Profil | Delegiert | Keine | Erforderlich für Teams einmaliges Anmelden. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern den Benutzernamen, Vornamen und Nachnamen in einer von Azure gehosteten PostgreSQL-Datenbank, damit Benutzer in der Anwendung zusammenarbeiten können. Die Steuerelemente sind, dass nur Mitarbeiter von Disaster Tech direkten Zugriff auf die Datenbank haben. Wenn ein Benutzer aus der Anwendung entfernt wird, werden die Informationen archiviert. Die Benutzer behalten das Recht, ihre personenbezogenen Daten jederzeit aus dem System zu entfernen. Das Entfernen solcher Informationen würde jedoch auch deren Verwendung der Anwendung verbieten.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungsdaten werden in einer PostgreSQL-Datenbank in Azure gespeichert, die im Ruhezustand verschlüsselt ist. Kein Benutzer hat direkten Zugriff auf die Datenbank oder die Back-End-API. Alle API-Aufrufe sind durch ein Active Directory-Zugriffstoken geschützt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

