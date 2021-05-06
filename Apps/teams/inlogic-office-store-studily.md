---
title: Anwendungsinformationen für Studi.ly von inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Studi.ly, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e01185ce576f7326ddde227949c1dbbe1dfff583
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251354"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von inLogic-Office Store an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Studi.ly |
| ID | WA200001668 |
| Funktionen | Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | inLogic-Office Store |
| URL der Partnerwebsite | [https://www.studi.ly](https://www.studi.ly) |
| URL der Datenschutzrichtlinie | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL der Nutzungsbedingungen | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von inLogic-Office Store darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Schreiben Sie Verzeichnis in die Gruppen für Zuordnungen und Materialien. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Schreiben Sie Verzeichnis in die Gruppen für Zuordnungen und Materialien. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members und Terms.Get all classes and schools of a tenant for synchronization into app database. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members und Terms.Get all classes and schools of a tenant for synchronization into app database. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members und Terms.Get all classes and schools of a tenant for synchronization into app database. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | ReadWrite Files from One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Mit dieser Berechtigung konnte die App unterschiedliche Claenderereignisse für Gruppen des Mandanten erhalten.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | both | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Mit dieser Berechtigung konnte die App unterschiedliche Claenderereignisse für Gruppen des Mandanten erhalten.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | Anwendung |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | both | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | ReadWrite Files from One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen von Benutzerinformationen | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | delegierte | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, da wir sie jedes Mal aus der Graph-API abrufen, die unsere Anwendung langsam arbeitet. Wir synchronisieren sie auf einem zeitbasierten Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen von Benutzerinformationen | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Solche Daten werden nicht in den Protokollen angezeigt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Es wird in der Azure Cosmos-Datenbank gespeichert, und alle Verschlüsselungen und Speicher, die standardmäßig mit der Cosmos-Datenbank verfügbar sind, gelten für diese Anwendung.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

