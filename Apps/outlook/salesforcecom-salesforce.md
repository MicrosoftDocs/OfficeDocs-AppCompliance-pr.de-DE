---
title: Anwendungsinformationen für Salesforce nach salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Salesforce, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b15f111d61d974a71eade2e5a3322ea3ee3431ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429743"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von salesforce.com an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Salesforce |
| ID | WA104379334 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher für Mac Outlook im Web |
| Name des Partnerunternehmens | salesforce.com |
| URL der Partnerwebsite | [https://www.salesforce.com](https://www.salesforce.com) |
| URL der Datenschutzrichtlinie | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL der Nutzungsbedingungen | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von salesforce.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer beschlossen hat, sich bei Salesforce anzumelden. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer beschlossen hat, sich bei Salesforce anzumelden. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und zur gepaarten Salesforce-E-Mail hinzuzufügen, UpdateItem (.js), GetFolder (.js), um den Entwurfsordner abzurufen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und zur gepaarten Salesforce-E-Mail hinzuzufügen, UpdateItem (.js), GetFolder (.js), um den Entwurfsordner abzurufen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. |
>| Exchange-Webdienste (Exchange Web Services, EWS) | Ja | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer beschlossen hat, sich bei Salesforce anzumelden. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer beschlossen hat, sich bei Salesforce anzumelden. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und zur gepaarten Salesforce-E-Mail hinzuzufügen, UpdateItem (.js), GetFolder (.js), um den Entwurfsordner abzurufen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und zur gepaarten Salesforce-E-Mail hinzuzufügen, UpdateItem (.js), GetFolder (.js), um den Entwurfsordner abzurufen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. |

#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Salesforce-Speicher wird im Sicherheitshandbuch unter https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von salesforce.com darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
