---
title: Anwendungsinformationen für Asana von Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Asana, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6c18bb20cdf753b1a5d998b3d7b7144f950f00c0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553406"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 2. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Asana Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Asana |
| ID | WA200001727 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Asana |
| URL der Partner-Website | [https://asana.com/?noredirect&amp;utm_source=asana_inproduct &amp; ut...](https://asana.com/?noredirect&amp;utm_source=asana_inproduct&amp;utm_medium=organic_inproduct&amp;utm_campaign=msft_teams_launch) |
| URL der Datenschutzrichtlinie | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL der Nutzungsbedingungen | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Asana darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Das Add-In überträgt grundlegende E-Mail-Informationen (Absender, Empfänger, Betreff, Körper) und Anhänge an Asana, wenn der Benutzer dies verlangt. |  | E-Mail – Liest derzeit geöffnete E-Mails, wenn sie in einem Aufgabenbereich angezeigt werden. - Liest derzeit geöffnete E-Mail-Anhänge, um sie in Asana-Aufgaben hochzuladen. - Dies bietet Benutzern die Möglichkeit, schnell Aufgaben in Asana mit Informationen aus E-Mails zu machen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Unsere Anwendung protokolliert nur Informationen zu Asana-Daten. Das einzige Mal, wenn wir etwas im Zusammenhang mit Outlook Benutzerinformationen protokollieren, ist, wenn der Benutzer explizit eine E-Mail anhängt oder eine Anlage an Asana hochlädt, und selbst dann protokollieren wir den Inhalt nicht. Kurzfristige Protokolle existieren auf Servern, die einige Benutzerdaten enthalten können, aber sie sind kurzlebig und auf Zeiträume von weniger als 72 Stunden begrenzt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Enterprise Kunden haben die Verschlüsselung im Ruhezustand mit AES-256 garantiert. Die Daten werden auf Amazon Web Services gespeichert, und AWS verwaltet die Verschlüsselungsschlüssel über ihr Key Management-System. Wir haben 2FA für alle Admins. Der Zugang erfolgt nach dem Prinzip der geringsten Privilegien.
Ihre Asana-Organisationsadministratoren haben die Möglichkeit, SAML-, SCIM-, Dienstkonten einzurichten und eine übergreifende Ansicht der Daten zu haben, die in das Tool eingefügt werden. Administratoren können einen vollständigen Organisationsexport über die Admin-Konsole anfordern und bei Bedarf eine Überwachung überwachen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

