---
title: Anwendungsinformationen für researcHR von KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für researcHR, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b57d492945766c8d65417cf2f1d642ea4ecb8aae
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873925"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von KBE&#26666;&#24335;&#20250;&#31038; für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | researcHR |
| ID | WA200002557 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | KBE&#26666;&#24335;&#20250;&#31038; |
| URL der Partnerwebsite | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL der Seite mit Teams Anwendungsinformationen | [https://app.researchr.work](https://app.researchr.work) |
| URL der Datenschutzrichtlinie | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL der Nutzungsbedingungen | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von KBE&#26666;&#24335;&#20250;&#31038; darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | Anwendung | Wir verwenden diesen Bereich, um es unserem Bot zu ermöglichen, einen neuen Kanal auf dem Teams-Client zu erstellen. Siehe: https://docs.microsoft.com/en-us/graph/api/channel-post | Wir speichern diese Daten nicht in unserer Datenbank. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | Anwendung | Wir verwenden diesen Bereich, um die Kanal-IDs und Namen abzurufen, um diese Daten auf unserer Website anzuzeigen. Siehe: https://docs.microsoft.com/en-us/graph/api/channel-list | Wir speichern diese Daten nicht in unserer Datenbank. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | Anwendung | Wir verwenden diesen Bereich, um die Kanal-IDs und Namen abzurufen, um diese Daten auf unserer Website anzuzeigen. Siehe: https://docs.microsoft.com/en-us/graph/api/channel-list | Wir speichern diese Daten nicht in unserer Datenbank. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | Anwendung | Wir verwenden diesen Bereich, um die Mitglieder des Teams abzurufen, damit Benutzer ihre Teammitglieder auf unserer Website sehen können. Siehe: https://docs.microsoft.com/en-us/graph/api/group-list-members | Wir speichern diese Daten nicht in der Out-Datenbank. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | Anwendung | Wir verwenden diesen Bereich, um die verbundenen Kanäle des Benutzers abzurufen, damit die Benutzer ihre beigetretenen Teams auf unserer Website sehen können. Siehe: https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | Wir speichern diese Daten nicht in unserer Datenbank. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | Delegiert | Wir verwenden diesen Bereich, um die OAuth-Anmeldung zu aktivieren und die AAD-ID, das Zugriffstoken und das Aktualisierungstoken des Benutzers zu erfassen. Siehe: https://docs.microsoft.com/en-us/graph/auth-v2-user | Wir speichern die AAD-ID, das Zugriffstoken und das Aktualisierungstoken des Benutzers in unserer Datenbank, damit sich der Benutzer mit OAuth bei unserer Website anmelden kann. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | Delegiert | Wir verwenden diesen Bereich, um das Aktualisierungstoken abzurufen, damit das Zugriffstoken der authentifizierten Benutzer ohne Benutzerinteraktionen aktualisiert werden kann. Siehe: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Wir speichern das Aktualisierungstoken in unserer Datenbank, damit wir das Zugriffstoken ohne Benutzerinteraktionen aktualisieren können. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten in der Datenbank werden verschlüsselt. Sicherungen von Datenbankdaten werden gemäß unserer internen Betriebsrichtlinie für einen bestimmten Zeitraum durchgeführt und gespeichert. Für den Fall, dass ein Benutzer diesen Dienst bricht, löschen wir die Benutzerinformationen des Benutzers unverzüglich, es sei denn, dies ist erforderlich, um die gesetzlich festgelegten Speicherverpflichtungen zu erfüllen. Hier sind die Details. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von KBE&#26666;&#24335;&#20250;&#31038; darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
