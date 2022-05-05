---
title: Anwendungsinformationen für Saberr von Saberr
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 02/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Saberr, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a41fb58d14186cea217bc23e09061233f87c21d8
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226149"
---
# <a name="saberr"></a>Saberr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 11. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3a07709-eb0e-421c-8609-b61b0600e645" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001501" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Saberr an Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Saberr |
| ID | WA200001501 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | Saberr |
| URL der Partnerwebsite | [https://www.saberr.com](https://www.saberr.com) |
| URL der Teams Anwendungsinformationsseite | [https://help.saberr.com/en/articles/3854472-use-coachbot-in...](https://help.saberr.com/en/articles/3854472-use-coachbot-in-microsoft-teams-to-get-notifications-and-quick-actions) |
| URL der Datenschutzrichtlinie | [https://help.saberr.com/en/articles/3853094-privacy-for-use...](https://help.saberr.com/en/articles/3853094-privacy-for-users-of-coachbot-s-microsoft-teams-or-slack-integrations) |
| URL der Nutzungsbedingungen | [https://help.saberr.com/en/articles/3853596-terms-and-condi...](https://help.saberr.com/en/articles/3853596-terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Saberr darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | E-Mail, Vorname und Nachname. Wird für die Kontoerstellung in unserer API verwendet. | E-Mail, Vorname und Nachname. Wird für die Kontoerstellung in unserer API verwendet. | [9de91aee-708c-4d9f-958b-109fdb79d993](/microsoft-365-app-certification/azure/9de91aee-708c-4d9f-958b-109fdb79d993) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise andere Microsoft-APIs als Microsoft Graph, um Organisationsinformationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph, die diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für das Sammeln von OII?** | **Ist OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft BOT-API | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII wird übertragen an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Slack, Pipedrive, Google, Mailchimp, Intercom, Cronofy | Firmenname, Benutzername, E-Mail-Adresse des Benutzers | Benutzer müssen mit ihrer Organisation in Verbindung gebracht werden, um Features wie Besprechungen verwenden zu können. Wir übertragen nur die EUII/OII, die erforderlich sind, um diese In-App-Organisationen einzurichten und verträgen + Unterstützung mit ihnen zu führen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Endbenutzer-identifizierbare Informationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wurde. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Ist EUII in Datenbank(en) gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir benötigen E-Mail, Vorname und Nachname für die Kontoerstellung in unserer API | E-Mail, Vorname, Nachname | Erforderlich für die Kontoerstellung in unserer API |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Keine OII oder EUII erscheinen in den Anwendungen Telemetrie oder Protokolle.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir legen Aufbewahrungsrichtlinien in allen Partnersystemen fest und erzwingen die maximal verfügbaren Sicherheitssetups (z. B. 2FA).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36430" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Saberr darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
