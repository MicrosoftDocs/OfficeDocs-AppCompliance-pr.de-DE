---
title: Anwendungsinformationen für Cloverpop von Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Cloverpop, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553226"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Cloverpop Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Cloverpop |
| ID | WA200001803 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cloverpop |
| URL der Partner-Website | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL der Datenschutzrichtlinie | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Cloverpop darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Benutzerdaten wie speichern. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organisationsanzeigename, Auch speichern wir auf unserer Seite Teams/Kanäle Namen, IDs, Teammitglieder. Wenn Benutzer Entscheidungen erstellen und mit ihnen interagieren, verknüpfen wir diese Daten dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer menschenfreundlichen UX anzeigen und speichern daher Anzeigeinformationen, z.B. den Benutzer&#8217;Avatar. | ermöglicht es dem Benutzer, sich anzumelden und gewährt App-Zugriff auf seinen UPN, um eine automatische Anmeldung&#8221; - E-Mail, Name, Oid, Tid, Vorname, Nachname, FamilyName, Benutzer-Avatar(Foto), Organisationsanzeigename zu aktivieren | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | Delegiert | Store Benutzerdaten wie. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organisationsanzeigename, Auch speichern wir auf unserer Seite Teams/Kanäle Namen, IDs, Teammitglieder. Wenn Benutzer Entscheidungen erstellen und mit ihnen interagieren, verknüpfen wir diese Daten dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer menschenfreundlichen UX anzeigen und speichern daher Anzeigeinformationen, z.B. den Benutzer&#8217;Avatar. | So implementieren Sie &#8220;melden Sie sich mit Teams&#8221; in unserer Web-App an. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| Profil | Delegiert | Store Benutzerdaten wie. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organisationsanzeigename, Auch speichern wir auf unserer Seite Teams/Kanäle Namen, IDs, Teammitglieder. Wenn Benutzer Entscheidungen erstellen und mit ihnen interagieren, verknüpfen wir diese Daten dem Benutzer, dem Team und der Organisation, die sie erstellt haben. Wir müssen diesen Besitz auch in einer menschenfreundlichen UX anzeigen und speichern daher Anzeigeinformationen, z.B. den Benutzer&#8217;Avatar. | So implementieren Sie &#8220;melden Sie sich mit Teams&#8221; in unserer Web-App an. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir greifen auf die ersten/letzten/Anzeigenamendaten zu, um genau anzuzeigen, welche Aktionen bestimmte Benutzer im Zusammenhang mit einer Entscheidung ergriffen haben. Wir verwenden die E-Mail-Adresse als eindeutige Kennung für jeden Benutzer in unserer db, da wir jedem Benutzer erlauben, mehreren Organisationen anzugehören. Wir greifen nur auf diese Daten zu, wenn sie mit unserer App interagieren, z.B. wenn sie auf eine Umfrage antworten. | Wir speichern die ersten/letzten/Anzeigenamendaten, um genau anzuzeigen, welche Aktionen bestimmte Benutzer im Zusammenhang mit einer Entscheidung ergriffen haben.  Wir speichern die E-Mail-Adresse, da wir sie als eindeutige Kennung für jeden Benutzer in unserer db verwenden, da wir jedem Benutzer erlauben, mehreren Organisationen anzugehören. Wir speichern diese Daten nur, wenn sie mit unserer App interagieren, z.B. wenn sie auf eine Umfrage antworten. Unsere Entscheidungsdaten sollen ein System von Datensätzen für Entscheidungen sein, daher ist es wichtig, dass wir die Daten speichern, um zu ermitteln, wie jeder Benutzer, der an einer Entscheidung beteiligt war, zu dieser Entscheidung beigetragen hat. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja.
Die Team-ID wird in unseren Protokollen angezeigt, wenn unsere App in einem Team interagiert wird.
Wir haben begrenzten Zugang zu unseren Produktionsprotokollen für unsere drei Gründer, die alle in den USA ansässig sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Cloverpop-App wurde mit Ruby on Rails erstellt und auf der Heroku PaaS (Plattform als Service) gehostet, die AWS für ihre Cloud-Infrastruktur nutzt. Heroku und AWS verfügen beide über SOC-Berichte, auf die zugegriffen werden kann. Unsere App verwendet PostgreSQL für die verschlüsselte Datenspeicherung im Ruhezustand und ist eine mehrinstanzenfähige Umgebung.
 
Unser gesamter Code enthält automatisierte Tests, die für ihn geschrieben wurden und die Datenzugriffssicherheit abdecken. Jeder Build wird einem strengen Codeüberprüfungsprozess auf Sicherheit und einem manuellen QS-Testprozess unterzogen, der auch Überprüfungen auf Benutzerauthentifizierung und Datenzugriff durch verfügbare Benutzeraktionen umfasst. Es gibt eine klare Trennung zwischen unserer Produktionsumgebung und allen anderen Umgebungen, wie Z. B. Entwicklung und Tests.
 
Nur ausgewählte Mitarbeiter haben Zugriff auf die Produktionsumgebung und Datenbank: Firmengründer und eine kleine Handvoll geprüfter Mitarbeiter, die Hintergrundprüfungen unterzogen wurden und einen quantifizierten Bedarf haben (z. B. Kundenbetreuung).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

