---
title: Application Information for Tour by Tour
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Centers, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 61f53fe653ebce1a833005082c8254392e61b2c1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411600"
---
# <a name="lucca"></a>Lucca

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/53628f6a-ac66-4fde-8945-d639c8da4c0d" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001650" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Ihnen an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Lucca |
| ID | WA200001650 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Lucca |
| URL der Partnerwebsite | [https://www.lucca.fr](https://www.lucca.fr) |
| URL der Datenschutzrichtlinie | [https://www.lucca.fr/privacy-policy](https://www.lucca.fr/privacy-policy) |
| URL der Nutzungsbedingungen | [https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/Ter...](https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/TermsAndConditions.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Weitere bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | Delegiert | Es werden keine Daten gesammelt. Wir haben diese zum Filtern der Anzeigeplanung verwendet. Nur die Benutzer, die sich im Kanal befinden, haben ihre Planung angezeigt | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Chat.ReadWrite | Anwendung | Es werden keine Daten gesammelt oder verwendet. Die App poste nur eine Nachricht, die Abwesenheiten des Tages enthält | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Group.Read.All | Anwendung | Wir erfassen die GroupId, um zu wissen, in welcher Gruppe die App die Nachricht mit den Abwesenheiten senden soll.  | Wir speichern nur die GroupId, um die Konfiguration zu speichern, die der Benutzer vorgenommen hat. Damit können wir wissen, in welcher Gruppe die Nachricht gesendet werden soll. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read | Delegiert | Wird zum Anmelden von Benutzern verwendet | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read.All | Anwendung | Wird zum Lesen von Benutzerprofilen verwendet | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| email | Delegiert | Wird verwendet, um Benutzer-E-Mails auf der Registerkarte "App" anzuzeigen. | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| openid | Delegiert | Wird zum Anmelden des Benutzers verwendet | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Profil | Delegiert | Wird zum Anzeigen des Benutzerprofils auf der Registerkarte "App" verwendet | Es werden keine Daten gespeichert. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Endbenutzerrichtlinie

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Erfahren bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

