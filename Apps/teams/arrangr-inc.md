---
title: Anwendungsinformationen für Arrangr von Arrangr, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Arrangr, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a79f5d727ae54489bf5623d41c2bf77c32f4be81
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410419"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Arrangr, Inc. für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Arrangr |
| ID | WA200002975 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Arrangr, Inc. |
| URL der Partnerwebsite | [https://arrangr.com](https://arrangr.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| URL der Datenschutzrichtlinie | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| URL der Nutzungsbedingungen | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Arrangr, Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Wir erfassen Namen der Kalender von Benutzern und Details zu ihren Kalenderereignissen, um die Planung von Besprechungen zu vereinfachen. | Wir speichern die Namen aller Kalender, die sie verbunden haben, damit sie sehen und ändern können, welche Kalender sie verbunden haben. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | Delegiert | Sammeln Sie eine Liste der Kanäle, die den Benutzern zur Verfügung stehen, damit wir ihnen eine Liste ihrer Kanäle anzeigen können, in die sie einen auswählen können, in den eine Arrangr-Einladung geteilt werden soll. | Wir speichern keine Informationen auf den Kanälen des Benutzers. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | Delegiert | Diese Berechtigung wird verwendet, um Arrangr-Einladungen im Namen des Benutzers an Teamkanäle zu senden. Es wird nicht zum Sammeln von Daten verwendet. | Es werden keine Daten gespeichert, die mit dieser Berechtigung gesammelt werden. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | Delegiert | Diese Berechtigung wird verwendet, um Arrangr-Einladungen in einen Teams Chat im Namen des Benutzers zu senden. Diese Berechtigung wird nicht zum Sammeln von Daten verwendet. | Es werden keine Daten gespeichert, die mit dieser Berechtigung gesammelt werden. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | Delegiert | Diese Berechtigung wird verwendet, um Arrangr-Einladungen in 1:1- und Gruppenchats im Namen des Benutzers zu senden. Es wird nicht zum Sammeln von Daten verwendet. | Es werden keine Daten gespeichert, die mit dieser Berechtigung gesammelt werden. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | Delegiert | Arrangr sammelt Microsoft Teams Besprechungslinks, um diese mit dieser Berechtigung zu generieren. Wir generieren Teams Besprechungen im Namen des Benutzers, damit sie Teams Anrufe auf Arrangr organisieren können. | Wir speichern die Besprechungslinks, damit sie für die entsprechenden Parteien freigegeben werden können, um an der Besprechung teilzunehmen. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | Delegiert | Wir erfassen Namen und E-Mails von Personen, die für den Benutzer relevant sind. Auf diese Weise können wir dem Benutzer die Auswahl als Empfänger von Arrangr-Einladungen erleichtern. | Wenn der Benutzer einen Empfänger auswählt, der über diese API angeboten wird, speichern wir den Namen und die E-Mail des Empfängers, um die Besprechung durchzuführen und es dem Benutzer zu erleichtern, ihn in Zukunft erneut als Empfänger auszuwählen. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | Delegiert | Wir erfassen die Namen der Teams des Benutzers, sodass er auswählen kann, in welchem Teams er eine Verbindung mit Arrangr herstellen möchte und in welches Team er eine Arrangr-Einladung teilen möchte. | Arrangr speichert die Namen von Teams der Benutzer eine Verknüpfung mit Arrangr ausgewählt hat, sodass wir diese Teams in ihren Einstellungen anzeigen und sie aus diesen Teams auswählen können, wenn sie entscheiden, wo eine Arrangr-Einladung freigegeben werden soll. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | Delegiert | Wir lesen, ob unsere App im Teams Konto des Benutzers installiert wurde, damit wir sie fragen können, ob sie unsere App installieren möchten, und dass wir sie für sie installieren können. | Wir speichern keine Daten, die über diese Berechtigung gesammelt werden. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Profil | Delegiert | Name und E-Mail-Adresse | Name und E-Mail-Adresse, um dem Benutzer anzuzeigen, welches Konto er mit unserem Dienst verbunden hat. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | Ja | Name, E-Mail, Kalendernamen, Kalenderereignisinformationen | Wir erfassen diese Informationen, damit Benutzer ihren Kalender mit Arrangr verbinden können, um die Planung von Besprechungen zu vereinfachen. | Name, E-Mail, Kalendernamen | Wir speichern diese Informationen, damit wir den Benutzern zeigen können, welche Konten und Kalender sie mit unserem Dienst verbunden haben. |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | Google Cloud speichert alle Benutzerdaten, Benutzernamen und E-Mails werden mit SendGrid geteilt, um E-Mails an Benutzer zu senden, stripe erhält Benutzernamen, E-Mails und Zahlungsinformationen für die Verarbeitung von Zahlungen. Quaderno erhält Benutzernamen, E-Mails und geografische Informationen, um die Einhaltung der Umsatzsteuer zu unterstützen. | Google Cloud wird zum Speichern von Daten benötigt, um Benutzer zu speichern und die Informationen bereitzustellen, die sie in Arrangr gespeichert haben. Um E-Mails an unsere Nutzungen zu senden, müssen wir deren E-Mail-Adressen an SendGrid senden. Um Zahlungen zu sammeln, müssen wir ihre Zahlungsinformationen in Stripe verarbeiten, aber wir speichern ihre Zahlungsinformationen nicht auf unseren eigenen Servern. Quaderno ist erforderlich, um die Mehrwertsteuer zu berechnen und sicherzustellen, dass wir die Bestimmungen der Mehrwertsteuer einhalten. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Benutzer verwenden unsere Messaging-Erweiterung, um Besprechungen mit anderen zu planen. Wir müssen dem Benutzer das Konto anzeigen, bei dem er angemeldet ist, und wir müssen in der Lage sein, die einladung, die er sendet, dem richtigen Arrangr-Benutzer zuzuordnen. | Benutzernamen, E-Mails und Kommunikationsinformationen. | Diese Informationen sind erforderlich, um Besprechungen zwischen mehreren Parteien zu koordinieren und die Details für die Verbindung und die Person, mit der sie sich treffen, zu teilen. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir steuern die im Google Cloud Datastore gespeicherten Daten über deren API und können alle benötigten Daten löschen. Unsere Benutzer können die Entfernung ihrer Konten und die Löschung ihrer Daten anfordern.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Arrangr, Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

