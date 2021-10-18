---
title: Anwendungsinformationen für CodeTwo-E-Mail-Signaturen für Office 365 von CodeTwo
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CodeTwo-E-Mail-Signaturen für Office 365, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3b6ab4d89a64aaec64dbb731a213fd203876476c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428177"
---
# <a name="codetwo-email-signatures-for-office-365"></a>CodeTwo-E-Mail-Signaturen für Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von CodeTwo für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CodeTwo-E-Mail-Signaturen für Office 365 |
| ID | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| Name des Partnerunternehmens | CodeTwo |
| URL der Partnerwebsite | [https://www.codetwo.com](https://www.codetwo.com) |
| URL der Datenschutzrichtlinie | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| URL der Nutzungsbedingungen | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von CodeTwo darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Ermöglicht Benutzern, sich bei der App anzumelden, und ermöglicht der App, das Profil der angemeldeten Benutzer zu lesen. Außerdem kann die App grundlegende Organisationsinformationen von angemeldeten Benutzern lesen. | Es werden keine Daten gespeichert. | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | Delegiert | Damit können Benutzer sich bei der App anmelden, und die App kann das Profil von angemeldeten Benutzern lesen. Die App kann auch grundlegende Unternehmensinformationen von angemeldeten Benutzern lesen. | Es werden keine Daten gespeichert. | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | Delegiert | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | Es werden keine Daten gespeichert. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | Beide | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation&#8217;zu lesen, z. B. Benutzer, Gruppen und Apps. | Es werden keine Daten gespeichert. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | Delegiert | Ermöglicht der App, einen grundlegenden Satz von Profileigenschaften anderer Benutzer in Ihrer Organisation im Namen des angemeldeten Benutzers zu lesen. Dazu gehören Anzeigename, Vor- und Nachname, E-Mail-Adresse und Foto. Informationen werden verwendet, um E-Mail-Signaturen für Benutzer automatisch zu personalisieren. | Es werden keine Daten gespeichert. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | Delegiert | Allows users to sign-in to the app, and allows the app to read the profile of signed-in users. Außerdem kann die App grundlegende Unternehmensinformationen von angemeldeten Benutzern lesen. Wird verwendet, um den Benutzer beim CodeTwo-Dienst zu registrieren. | Es werden keine Daten gespeichert. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| email | Delegiert | Ermöglicht der App, die primäre E-Mail-Adresse Ihrer Benutzer zu lesen. Wird verwendet, um den Benutzer beim CodeTwo-Dienst zu registrieren. | Es werden keine Daten gespeichert. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | Delegiert | Ermöglicht der App, die Daten anzuzeigen und zu aktualisieren, auf die Sie zugriffen, auch wenn Benutzer die App derzeit nicht verwenden. Dadurch wird der App keine zusätzlichen Berechtigungen erteilt. | Es werden keine Daten gespeichert. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| openid | Delegiert | Damit können Benutzer sich mit Ihren Geschäfts- oder Schulkonten bei der App anmelden, und die App kann grundlegende Benutzerprofilinformationen lesen. Wird verwendet, um den Benutzer beim CodeTwo-Dienst zu registrieren. | Es werden keine Daten gespeichert. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| Profil | Delegiert | Ermöglicht der App, das grundlegende Profil Ihrer Benutzer (Name, Bild, Benutzername) anzuzeigen. Wird verwendet, um den Benutzer beim CodeTwo-Dienst zu registrieren. | Es werden keine Daten gespeichert. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Kunden können über den CodeTwo Admin Panel auf ihre Kontaktdaten und Diensteinstellungen zugreifen und diese &amp; berichtigen. Sie können sich auch über ein dediziertes Formular an das CodeTwo Information Security-Team wenden ( https://www.codetwo.com/form/security-officer/) um eines der in den Geschäftsbedingungen und -datenschutzbestimmungen von CodeTwo beschriebenen Rechte ( https://www.codetwo.com/regulations/privacy) d. h.: Zugriff auf Daten, Berichtigung von Daten, Löschung und Einschränkung der Verarbeitung, Widerruf der Zustimmung und das Recht auf Widerruf der Verarbeitung) zu ausüben.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von CodeTwo darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
