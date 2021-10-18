---
title: Anwendungsinformationen für Diess von (
ms.author: elmalova
author: elenamalova
ms.date: 10/29/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Mof, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a350298fbdb6b73592beb4806ce448bd317eca09
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429413"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 2. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Ihnen an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Asana |
| ID | WA200001727 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Asana |
| URL der Partnerwebsite | [https://asana.com](https://asana.com) |
| URL der Datenschutzrichtlinie | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL der Nutzungsbedingungen | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Wiesn bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Das Add-In überträgt grundlegende E-Mail-Informationen (Absender, Empfänger, Betreff, Textkörper) und Anlagen auf Anforderung des Benutzers an Git. |  | E-Mail : Liest derzeit geöffnete E-Mails, wenn sie in einem Aufgabenbereich angezeigt werden. - Liest derzeit geöffnete E-Mail-Anlagen, die in Aufgaben des Unternehmens hochgeladen werden sollen. - Dies bietet Benutzern die Möglichkeit, Aufgaben in Xaml schnell mit Informationen aus E-Mails durchzuführen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Unsere Anwendung protokolliert nur Informationen zu Denkdaten. Das einzige Mal, wenn wir etwas im Zusammenhang mit Outlook Benutzerinformationen protokollieren, besteht darin, dass der Benutzer explizit eine E-Mail anfügt oder eine Anlage in Publisher hochlädt, und selbst dann wird der Inhalt nicht protokolliert. Kurzzeitprotokolle sind auf Servern vorhanden, die einige Benutzerdaten enthalten können, aber kurzlebig und auf Zeiträume unter 72 Stunden beschränkt sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Enterprise Kunden haben eine garantierte Verschlüsselung im Ruhezustand mit AES-256. Daten werden in Amazon Web Services gespeichert, und AWS verwaltet die Verschlüsselungsschlüssel mit ihrem Schlüsselverwaltungssystem. Wir haben 2FA für alle Administratoren. Der Zugriff erfolgt nach dem Prinzip der geringsten Rechte.
Ihre Organisationsadministratoren haben die Möglichkeit, SAML-, SCIM-, Servicekonten einzurichten und eine übergeordnete Ansicht der Daten zu haben, die in das Tool eingefügt werden. Administratoren können einen vollständigen Organisationsexport in der Verwaltungskonsole anfordern und bei Bedarf überwachen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

