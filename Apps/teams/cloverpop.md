---
title: Anwendungsinformationen für "Cloverpop" von "Cloverpop"
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Cloverpop, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1f7ee0c5a92757d03291de890ebfde05ed55a7db
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252695"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Cloverpop für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Cloverpop |
| ID | WA200001803 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Cloverpop |
| URL der Partnerwebsite | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL der Datenschutzrichtlinie | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Cloverpop darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | speichern Sie Benutzerdaten wie. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit entscheidungen interagieren, ordnen wir diese Daten dem Benutzer, dem Team und der Organisation zu, von dem sie erstellt wurden. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen, daher speichern wir Anzeigeinformationen, z. B. den&#8217;Avatar. | ermöglicht es dem Benutzer, sich anzumelden und der App Zugriff auf seinen UPN zu geben, um die automatische Anmeldung&#8221; zu aktivieren – E-Mail, Name, oid, tid, givenName, Surname, familyName, User avatar(photo), Organization displayName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | delegierte | Store benutzerdaten wie. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit entscheidungen interagieren, ordnen wir diese Daten dem Benutzer, dem Team und der Organisation zu, von dem sie erstellt wurden. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen, daher speichern wir Anzeigeinformationen, z. B. den&#8217;Avatar. | Zum Implementieren &#8220;sich mit Teams&#8221; in unserer Web-App anmelden. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| Profil | delegierte | Store benutzerdaten wie. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Wenn Benutzer Entscheidungen erstellen und mit entscheidungen interagieren, ordnen wir diese Daten dem Benutzer, dem Team und der Organisation zu, von dem sie erstellt wurden. Wir müssen diesen Besitz auch in einer benutzerfreundlichen UX anzeigen, daher speichern wir Anzeigeinformationen, z. B. den&#8217;Avatar. | Zum Implementieren &#8220;sich mit Teams&#8221; in unserer Web-App anmelden. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir greifen auf die Daten des Ersten/Nach-/Anzeigenamens zu, um genau zu zeigen, welche Aktionen von bestimmten Benutzern im Zusammenhang mit einer Entscheidung ergriffen wurden. Wir verwenden die E-Mail-Adresse als eindeutige ID für jeden Benutzer in unserer db, da wir jedem Benutzer erlauben, mehreren Organisationen zu angehören. Wir greifen nur auf diese Daten zu, wenn sie mit unserer App interagieren, z. B. wenn sie auf eine Umfrage antworten. | Wir speichern die Daten des Ersten/Nach-/Anzeigenamens, um genau zu zeigen, welche Aktionen von bestimmten Benutzern im Zusammenhang mit einer Entscheidung ergriffen wurden.  Wir speichern die E-Mail-Adresse, da wir sie als eindeutige ID für jeden Benutzer in unserer db verwenden, da jeder Benutzer mehreren Organisationen angehören kann. Wir speichern diese Daten nur, wenn sie mit unserer App interagieren, z. B. wenn sie auf eine Umfrage antworten. Unsere Entscheidungsdaten sollen ein Datensatzsystem für Entscheidungen sein, daher ist es wichtig, dass wir die Daten speichern, um zu ermitteln, wie jeder Benutzer an einer Entscheidung beteiligt ist, die zu dieser Entscheidung beigetragen hat. |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja.
Die Team-ID wird in unseren Protokollen angezeigt, wenn unsere App in einem Team interagiert wird.
Wir haben nur eingeschränkten Zugriff auf unsere Produktionsprotokolle für unsere drei Gründer, die alle in den USA ansässig sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die App "Cloverpop" wird mithilfe von Ruby on Rails erstellt und auf der Heroku PaaS (Plattform als Dienst) gehostet, die AWS für die Cloudinfrastruktur verwendet. Heroku und AWS verfügen beide über SOC-Berichte, auf die zugegriffen werden kann. Unsere App verwendet PostgreSQL für verschlüsselte Ruhedatenspeicherung und ist eine Mehr-Mandanten-Umgebung.
 
Der gesamte Code verfügt über automatisierte Tests, die für die Datenzugriffssicherheit geschrieben wurden. Jeder Build unterliegt einem strengen Codeüberprüfungsprozess für Die Sicherheit und einem manuellen Qaida-Testprozess, der auch Überprüfungen auf Benutzerauthentifizierung und Datenzugriff über verfügbare Benutzeraktionen umfasst. Es besteht eine klare Trennung zwischen unserer Produktionsumgebung und allen anderen Umgebungen, z. B. Entwicklung und Tests.
 
Nur ausgewählte Mitarbeiter haben Zugriff auf die Produktionsumgebung und Datenbank: Unternehmensgründer und eine kleine Handvoll geprüfter Mitarbeiter, die Hintergrundprüfungen durchgeführt haben und einen quantifizierten Bedarf (z. B. Kundensupport) haben.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

