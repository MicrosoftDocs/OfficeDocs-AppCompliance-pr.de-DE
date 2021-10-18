---
title: Anwendungsinformationen für AVA von AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für AVA, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e5b53fbbc4c65c709324611a9ac645b045e4eaa7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430003"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von AvePoint, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | AVA |
| ID | WA104381883 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | AvePoint, Inc. |
| URL der Partnerwebsite | [https://www.avepoint.com/](https://www.avepoint.com/) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL der Datenschutzrichtlinie | [https://www.avepoint.com/company/privacy-policy/](https://www.avepoint.com/company/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von AvePoint, Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite.Shared | Delegiert | Keine | Durchsuchen der E-Mails des Benutzers und Verschieben der E-Mail in den angegebenen Ordner | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.Read | Delegiert |  Zugriffstoken des Benutzers – wird zum Suchen und Wiederherstellen von Benutzerdaten verwendet | Ermöglicht dem Benutzer, sich anzumelden und das Zugriffstoken an die App zu übergeben. | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.ReadWrite | Delegiert | DisplayName, UserPrincipalName, JobTitle, Organization, Country, MySiteUrl – Aufzeichnen der grundlegenden Informationen des Benutzers, der die App verwendet hat | Abrufen der grundlegenden Profilinformationen des Benutzers | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint-REST-APIs | Ja | Durchsuchen Sie die Datei in der Wiederverwendung der persönlichen Website des Benutzers, und stellen Sie diese Dateien wieder her. Erfordert die Berechtigung "AllSites.Manage". |  | Keine |  |

#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, die E-Mail- und Mandanten-ID des Benutzers wird in Protokollen angezeigt. Die Protokolle werden an einem sicheren Ort gespeichert, und nur autorisiertes Personal kann während der Problembehandlung auf sie zugreifen. Die Protokolle werden nach 60 Tagen zu Sicherheitsüberwachungszwecken archiviert und nach einem Jahr gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten der Anwendung werden in Azure SQL-Datenbank und Azure Storage gespeichert. Azure SQL und Azure Storage Verschlüsselung sind aktiviert.
Nur autorisierte Administratoren können auf die Daten zugreifen. MFA ist erforderlich, damit sich die Administratoren anmelden können. Die Vorgänge werden überwacht. Ip-Whitelisting wird auch verwendet, um den Zugriff auf die Daten einzuschränken.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

