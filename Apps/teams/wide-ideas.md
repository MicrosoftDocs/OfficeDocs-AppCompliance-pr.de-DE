---
title: Application Information for Wide Ideas by Wide Ideas
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für wide Ideas, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1e73a7aebbaaffa12572717f7a4a9968fd5667f7
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528061"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von "Wide Ideas" für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wide Ideas |
| ID | WA200000819 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Wide Ideas |
| URL der Partnerwebsite | [https://getwideideas.com](https://getwideideas.com) |
| URL der Datenschutzrichtlinie | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von "Wide Ideas" bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | Anwendung | Wir speichern die Gruppen-ID und welche Benutzer zu welchen Gruppen gehören | Ermöglicht der App, Daten im Verzeichnis unserer Kundenorganisation zu lesen, z. B. Benutzer und Gruppen.  | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| Group.ReadWrite.All | Anwendung | Wir speichern die Kanal-ID, die der Gruppe zugeordnet ist. | Ermöglicht benutzern das Erstellen von Teams, Kanälen und Registerkarten innerhalb Microsoft Teams über das Kundenportal. Dadurch können Benutzer auch vorhandene Teams in Microsoft Teams im Kundenportal synchronisieren. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| User.Read | Delegiert | Wir speichern &amp; Namens-E-Mail | Ermöglicht Benutzern, sich anzumelden und In ihrem Namen Zugriff auf Microsoft Graph zu gewähren. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet-E-Mail, die für E-Mail-Benachrichtigungen verwendet wird. |  | Nicht zutreffend |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Um Benutzer in unserem Back-End zu erstellen und Berechtigungen für den Zugriff auf mit dem Team verknüpfte Inhalte zu erteilen. | Wir speichern: Name - So zeigen Sie den Namen des Benutzers an, E-Mail-Adresse - Um den Benutzer zu identifizieren |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern nur die IP-Nummer in unseren Protokollen. 

Die Organisation kann eine Anforderung an uns als Lieferant senden, wenn daten gelöscht werden sollen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Datenspeicherung: Alle Kundendaten werden in Microsoft Azure-Diensten gespeichert. Benutzer müssen über Azure AD 2-Faktor authentifiziert werden. Rollenbasierter Zugriff (Role Based Access, RBAC) ist vorhanden. Der gesamte Zugriff auf Microsoft Azure erfolgt ausschließlich über verschlüsselte Verbindungen. Alle ruhenden Daten werden verschlüsselt. Alle Dienste sind am besten durch das Azure Security Center geschützt. 

Wir verfügen auch über eine Zugriffsrichtlinie gemäß dem Prinzip der geringsten Rechte. 


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

