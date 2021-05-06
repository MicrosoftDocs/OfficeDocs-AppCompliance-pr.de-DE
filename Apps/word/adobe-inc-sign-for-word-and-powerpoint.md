---
title: Anwendungsinformationen für Adobe Sign for Word und PowerPoint von Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Adobe Sign for Word und PowerPoint, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cdb2750d21967d83ad40710a5b6888f11ca945e1
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251594"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign for Word und PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Adobe Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign for Word und PowerPoint |
| ID | WA104381155 |
| Office 365 unterstützten Clients | Word 2016 oder höher auf mac, PowerPoint 2013 Service Pack 1 oder höher auf Windows, Word 2013 Service Pack 1 oder höher auf Windows, Word im Web, PowerPoint im Web, PowerPoint 2016 oder höher auf dem Mac |
| Partnerunternehmensname | Adobe Inc. |
| URL der Partnerwebsite | [https://www.adobe.com/](https://www.adobe.com/) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL der Nutzungsbedingungen | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Adobe Inc. bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Anwendung | Wir benötigen Daten aus der E-Mail, um den Adobe Sign History and Audit Trail-Bericht jeder Transaktion herausziehen zu können. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | So füllen Sie das angefügte Dokument, absender- und empfänger-E-Mails und Nachrichteninhalte aus E-Mails an Adobe unter, um sie zur Signatur zu senden. Dadurch wird dem Benutzer Zeit zum erneuten Einschreiben dieser Felder in Adobe Sign erspart. Nachdem ein Vertrag unterzeichnet wurde, verfassen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail sendet, um seine Empfänger über die Transaktion zu informieren. |  |
>| People.Read | delegierte |  | Zum automatischen Ausfüllen der E-Mail-Adresse in der Funktion Signatur senden müssen Benutzer nicht die gesamten E-Mails eingeben, indem Sie einige Anfangsbuchstaben &quot; &quot; eingeben. |  |
>| User.Read | delegierte |  | So lesen Sie das Profil des Benutzers, und passen Sie ihr Profil (im Wesentlichen ihre E-Mails) unserer Datenbank an, damit sie Adobe Sign verwenden können. |  |
>| offline_access | delegierte |  | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem Fenster zum Senden von Signaturen befindet und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, wenn &quot; der Benutzer aktiv &quot; ist. |  |
>| openid | delegierte | E-Mail ist der eindeutige Bezeichner für Benutzer in Adobe Sign. Wir speichern E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnungen können.  | So melden Sie sich an, um ihre Zustimmung für die Verwendung der Adobe Sign-App sicherzustellen. |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite Document | Kann Ihr Dokument lesen und änderungen vornehmen |
>| Senden von Daten | Kann Daten über das Internet senden |

#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Keine. Wir protokollieren keine EUII oder OII in Telemetrie- oder Protokollen. Der Prozess ist unsere eigenen Sicherheitsüberprüfungen, die bestätigen, dass wir dies nicht tun.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In unserem System gibt es keine Interaktion von Kundenadministratoren für Microsoft Teams Anwendung.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

