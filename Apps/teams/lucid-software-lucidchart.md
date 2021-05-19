---
title: Anwendungsinformationen für Lucidchart von Lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Lucidchart, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cdfec0551da7278ac92c3e24caa2664a26a89bea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552966"
---
# <a name="lucidchart"></a>Lucidchart

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/7f905be6-3226-4a4c-9c54-ab1edce3c99c" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381935" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Lucid Software Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Lucidchart |
| ID | WA104381935 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Lucid Software |
| URL der Partner-Website | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL Teams Anwendungsinfoseite | [https://lucidchart.zendesk.com/](https://lucidchart.zendesk.com/) |
| URL der Datenschutzrichtlinie | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL der Nutzungsbedingungen | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Lucid Software darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen es Lucidchart, ein Openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für ihn zu registrieren. Um die daten zu überprüfen, die von Microsoft zurückstammen, stellen wir eine Anforderung, um den öffentlichen Schlüssel zu erhalten, mit dem ihre Antwort signiert ist. Es werden keine anderen Daten von Microsoft empfangen oder im Rahmen unseres SSO-Flusses an Microsoft gesendet. |  |
>| openid | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen es Lucidchart, ein Openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für ihn zu registrieren. Um die daten zu überprüfen, die von Microsoft zurückstammen, stellen wir eine Anforderung, um den öffentlichen Schlüssel zu erhalten, mit dem ihre Antwort signiert ist. Es werden keine anderen Daten von Microsoft empfangen oder im Rahmen unseres SSO-Flusses an Microsoft gesendet. |  |
>| Profil | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, Openid- und Profilberechtigungen ermöglichen es Lucidchart, ein Openid-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidchart-Konto für ihn zu registrieren. Um die daten zu überprüfen, die von Microsoft zurückstammen, stellen wir eine Anforderung, um den öffentlichen Schlüssel zu erhalten, mit dem ihre Antwort signiert ist. Es werden keine anderen Daten von Microsoft empfangen oder im Rahmen unseres SSO-Flusses an Microsoft gesendet. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Wir verwenden das Office OneDrive Javascript SDK aus, um die OneDrive Dateiauswahl mit OneDrive.open() zu öffnen. Wir generieren keine Zugriffstoken und stellen keine Anfragen an die APIs von OneDrive selbst; die OneDrive Dateiauswahl SDK tut dies für uns. Wir sehen nur die Dateinamen, die der Benutzer auswählt. |  | Wenn der Benutzer eine Datei mit der OneDrive Dateiauswahl auswählt, speichern wir den Dateinamen. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart-Daten werden in AWS gespeichert. |  | Wir verwenden keine Microsoft-APIs. Wir verwenden openID, um grundlegende Benutzerdaten für die Ausführung von SSO zu erhalten. Wir verwenden ihre Dateiauswahl-API, aber das gibt uns keinen Zugriff auf die Dateien des Benutzers, außer denen, die sie uns über die Auswahl übermitteln. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren E-Mail- und IP-Adressen aus Sicherheits- und Supportgründen. Der gesamte Zugriff auf Protokolle ist in &amp; einem System eines Drittanbieters nicht veränderbar. Für den Zugriff auf Protokolle ist MFA erforderlich.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Lucidchart-Daten werden in AWS gespeichert. Es ist in Ruhe und während der Durchreise verschlüsselt. Lucidchart verwendet die Regeln der geringsten Berechtigungen und MFA.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

