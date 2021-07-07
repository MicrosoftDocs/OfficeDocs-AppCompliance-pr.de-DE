---
title: Anwendungsinformationen für SmartWork von SmartWork von Intumit
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SmartWork, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f6ed1a9278713153be2ef14d61ad56453ee03fa3
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283199"
---
# <a name="smartwork"></a>SmartWork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 31. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/a938ae1e-a791-4751-9e6a-178c991fa0fa" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001149" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SmartWork von Intumit für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SmartWork |
| ID | WA200001149 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SmartWork of Intumit |
| URL der Partnerwebsite | [https://www.intumit.com/english/](https://www.intumit.com/english/) |
| URL der Datenschutzrichtlinie | [https://www.intumit.com/privacy.html](https://www.intumit.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.intumit.com/english/TermsOfUse.html](https://www.intumit.com/english/TermsOfUse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SmartWork of Intumit darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Verwenden von userPrincipalName zum Identifizieren, ob die E-Mails des Benutzers von gültigem AAD stammen oder nicht | Anmelden und Benutzerprofil lesen | a938ae1e-a791-4751-9e6a-178c991fa0fa |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Verwenden, um die E-Mails des Benutzers zu identifizieren, ob sie von gültigem AAD stammen oder nicht | Die E-Mail-Liste des gespeicherten Benutzers, um zu identifizieren, ob der Benutzer von gültigem AAD stammt oder nicht |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein. Während der Unterhaltung verwenden wir den Sitzungsmodus, um dies zu steuern. Verwenden Sie die ID, die dem Element in der Db entspricht, und greifen Sie dann auf die Daten zu. Wir protokollieren nicht ausdrücklich die Benutzerinformationen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nur Sie haben ein gültiges AAD-Konto, das auf die Anwendung zugreifen kann.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35852' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35852" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

