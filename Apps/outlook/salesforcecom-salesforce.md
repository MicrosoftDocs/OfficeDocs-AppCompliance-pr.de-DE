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
ms.openlocfilehash: 749e4cf95c8eefb650f6fd0f8ceb59721d7efcc8
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413527"
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

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gepaarten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) zum Abrufen des Entwurfsordners hinzuzufügen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gepaarten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) zum Abrufen des Entwurfsordners hinzuzufügen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. |
>| Exchange-Webdienste (Exchange Web Services, EWS) | Ja | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen von Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gepaarten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) zum Abrufen des Entwurfsordners hinzuzufügen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js und EWS), um AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen abzurufen und festzulegen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gepaarten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) zum Abrufen des Entwurfsordners hinzuzufügen,  CreateItem (.js), das zum Erstellen eines Nachrichtenentwurfs verwendet wird. |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

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

