---
title: Anwendungsinformationen für Salesforce nach salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Salesforce, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553706"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von salesforce.com Microsoft zur Verfügung gestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Salesforce |
| ID | WA104379334 |
| Office 365 unterstützten Clients | Outlook 2013 oder später Windows, Outlook 2016 oder später auf Mac, Outlook im Web |
| Name des Partnerunternehmens | salesforce.com |
| URL der Partner-Website | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL der Datenschutzrichtlinie | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von salesforce.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet Funktionen aus Office.js und EWS, um Inhalte und Anhänge über eine E-Mail zu kopieren, Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf der Kalenderseite verwendet, um Termine in Salesforce zu protokollieren. |  | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität, GetItem (.js und EWS) zu erhalten und zu setzen AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gekoppelten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) hinzuzufügen, um den Entwurfsordner zu erhalten .js. |  |
>| Exchange-Webdienste (Exchange Web Services, EWS) | Ja | Das Add-In verwendet Funktionen aus Office.js und EWS, um Inhalte und Anhänge über eine E-Mail zu kopieren, Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf der Kalenderseite verwendet, um Termine in Salesforce zu protokollieren. |  | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität, GetItem (.js und EWS) zu erhalten und zu setzen AdditionalProperties und den Inhalt der aktuellen E-Mail-Nachricht beim Speichern in Salesforce-Datensätzen, GetAttachment (EWS), um die Anlagen aus Exchange abzurufen und der gekoppelten Salesforce-E-Mail, UpdateItem (.js), GetFolder (.js) hinzuzufügen, um den Entwurfsordner zu erhalten .js. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Salesforce-Speicher wird im Security Guide unter https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

