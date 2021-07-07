---
title: Anwendungsinformationen für Poppop von Tarverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Tarverpop, die Zugehörigen Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security Informationen zum App-Katalog sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c6be013237c6368624687f7eb297a7149c28a548
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281347"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ApplePop für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Cloverpop |
| ID | WA200001803 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cloverpop |
| URL der Partnerwebsite | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| URL der Datenschutzrichtlinie | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Tarverpop bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Speichern Sie Benutzerdaten wie folgt. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit diesen interagieren, verknüpfen wir diese Daten mit dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen. Daher werden Anzeigeinformationen gespeichert, z. B. der Benutzer&#8217;Avatar. | ermöglicht dem Benutzer die Anmeldung und ermöglicht app-Zugriff auf den UPN, um die automatische Anmeldung&#8221; zu ermöglichen – E-Mail, Name, oid, tid, givenName, Nachname, Familienname, Benutzer-Avatar(Foto), Organisation DisplayName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | Delegiert | Store Benutzerdaten gefällt. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit diesen interagieren, verknüpfen wir diese Daten mit dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen. Daher werden Anzeigeinformationen gespeichert, z. B. der Benutzer&#8217;Avatar. | Um &#8220;sie zu implementieren, melden Sie sich mit Teams&#8221; in unserer Web-App an. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| Profil | Delegiert | Store Benutzerdaten gefällt. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit diesen interagieren, verknüpfen wir diese Daten mit dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen. Daher werden Anzeigeinformationen gespeichert, z. B. der Benutzer&#8217;Avatar. | Um &#8220;sie zu implementieren, melden Sie sich mit Teams&#8221; in unserer Web-App an. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir greifen auf die Daten des Vor-/Nach-/Anzeigenamens zu, um genau anzuzeigen, welche Aktionen von bestimmten Benutzern im Zusammenhang mit einer Entscheidung ausgeführt wurden. Wir verwenden die E-Mail-Adresse als eindeutigen Bezeichner für jeden Benutzer in unserer Datenbank, da jeder Benutzer mehreren Organisationen angehören kann. Wir greifen nur auf diese Daten zu, wenn sie mit unserer App interagieren, z. B. wenn sie auf eine Umfrage antworten. | Wir speichern die Daten des Vor-/Nach-/Anzeigenamens, um genau anzuzeigen, welche Aktionen von bestimmten Benutzern im Zusammenhang mit einer Entscheidung ausgeführt wurden.  Wir speichern die E-Mail-Adresse, da wir sie als eindeutigen Bezeichner für jeden Benutzer in unserer Datenbank verwenden, da jeder Benutzer mehreren Organisationen angehören kann. Wir speichern diese Daten nur, wenn sie mit unserer App interagieren, z. B. wenn sie auf eine Umfrage antworten. Unsere Entscheidungsdaten sollten ein Aufzeichnungssystem für Entscheidungen sein, daher ist es wichtig, dass wir die Daten speichern, um zu bestimmen, wie jeder Benutzer, der an einer Entscheidung beteiligt war, zu dieser Entscheidung beigetragen hat. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja.
Die Team-ID wird in unseren Protokollen angezeigt, wenn unsere App in einem Team interagiert.
Wir haben eingeschränkten Zugriff auf unsere Produktionsprotokolle für unsere drei Inserenten, die alle in den USA ansässig sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Computersverpop-App wurde mit Ruby on Rails erstellt und wird auf der Heroku PaaS (Platform as a Service) gehostet, die AWS für ihre Cloudinfrastruktur nutzt. Heroku und AWS verfügen beide über SOC-Berichte, auf die zugegriffen werden kann. Unsere App verwendet PostgreSQL für den verschlüsselten Ruhedatenspeicher und ist eine mehrinstanzenfähige Umgebung.
 
Für den gesamten Code wurden automatisierte Tests geschrieben, die die Sicherheit des Datenzugriffs abdeckt. Jeder Build durchläuft einen strengen Codeüberprüfungsprozess für Die Sicherheit und einen manuellen QA-Testprozess, der auch Überprüfungen der Benutzerauthentifizierung und des Datenzugriffs über verfügbare Benutzeraktionen umfasst. Es besteht eine klare Trennung zwischen unserer Produktionsumgebung und allen anderen Umgebungen, z. B. Entwicklung und Tests.
 
Nur ausgewählte Mitarbeiter haben Zugriff auf die Produktionsumgebung und Datenbank: Unternehmensmitarbeiter und eine kleine Handvoll von überprüften Mitarbeitern, die Hintergrundprüfungen unterzogen wurden und eine quantifizierte Notwendigkeit haben (z. B. Kundensupport).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

