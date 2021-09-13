---
title: Anwendungsinformationen für Studi.ly von inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Studi.ly, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security Informationen zum App-Katalog und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d682e758d9632a2c3ac19296dda7083dc8379689
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283682"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von inLogic-Office Store an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Studi.ly |
| ID | WA200001668 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | inLogic-Office Store |
| URL der Partnerwebsite | [https://www.inlogic.dk](https://www.inlogic.dk) |
| URL der Datenschutzrichtlinie | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| URL der Nutzungsbedingungen | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von inLogic-Office Store darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Schreiben eines Verzeichnisses in die Gruppen für Aufgaben und Materialien. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Schreiben eines Verzeichnisses in die Gruppen für Aufgaben und Materialien. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, funktioniert unsere Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members and Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members and Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen Sie Education Classes, School, Members and Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Mit dieser Berechtigung konnte die App verschiedene Claender-Ereignisse für Gruppen des Mandanten abrufen.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | Beide | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Mit dieser Berechtigung konnte die App verschiedene Claender-Ereignisse für Gruppen des Mandanten abrufen.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | Anwendung |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | Beide | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen von Benutzerinformationen | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder sowie Begriffsinformationen aus der Bildungs-API in unserer API, und wir benötigen sie, denn wenn wir sie jedes Mal aus der Graph-API abrufen, wird die Anwendung langsam. Wir synchronisieren es für ein zeitbasiertes Ereignis von der Bildungs-API mit unserer Datenbank. | Lesen von Benutzerinformationen | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Solche Daten werden nicht in den Protokollen angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Sie wird in der Azure Cosmos-Datenbank gespeichert, und alle Verschlüsselungen und Speicher, die standardmäßig mit kosmos-Datenbank verfügbar sind, gelten für diese Anwendung.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

