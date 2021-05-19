---
title: Anwendungsinformationen für breite Ideen durch breite Ideen
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Wide Ideas, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f1fc5d97736ba587595ef6c742b14ce75c0b1863
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550895"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. Juni 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Wide Ideas an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wide Ideas |
| ID | WA200000819 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Wide Ideas |
| URL der Partner-Website | [https://getwideideas.com](https://getwideideas.com) |
| URL der Datenschutzrichtlinie | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Wide Ideas bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Anwendung | Wir speichern Gruppen-ID und welche Benutzer zu welchen Gruppen gehören | Ermöglicht der App das Lesen von Daten im Verzeichnis unserer Kundenorganisation, z. B. Benutzer und Gruppen.  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | Anwendung | Wir speichern die Kanal-ID, die der Gruppe zugeordnet ist. | Ermöglicht es Dem Benutzer, Teams, Kanäle und Registerkarten innerhalb Microsoft Teams über das Kundenportal zu erstellen. Dadurch können Benutzer auch vorhandene Teams in Microsoft Teams mit dem Kundenportal synchronisieren. | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | Delegiert | Wir speichern &amp; Namens-E-Mail | Ermöglicht Benutzern die Anmeldung und den Zugriff auf Microsoft-Graph in ihrem Namen | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Mailjet Email, das für E-Mail-Benachrichtigungen verwendet wird. |  | Nicht zutreffend |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Um Benutzer in unserem Backend zu erstellen und Berechtigungen für den Zugriff auf Inhalte zu erteilen, die mit dem Team verknüpft sind. | Wir speichern: Name - So wird der Name des Benutzers angezeigt, E-Mail-Adresse - So identifizieren Sie den Benutzer |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern nur die IP-Nummer in unseren Protokollen. 

Die Organisation kann uns als Lieferanten eine Anfrage senden, wenn sie datenlöschung enden möchte.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Datenspeicherung: Alle Kundendaten werden in Microsoft Azure-Diensten gespeichert. Benutzer müssen über Azure AD authentifiziert werden. Rollenbasierter Zugriff (RBAC) ist vorhanden. Der gesamte Zugriff auf Microsoft Azure erfolgt ausschließlich über verschlüsselte Verbindungen. Alle Daten werden im Ruhezustand verschlüsselt. Alle Dienste sind durch die bewährte Methode des Azure Security Center geschützt. 

Wir haben auch eine Zugangsrichtlinie nach dem Prinzip der geringsten Privilegien. 


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

