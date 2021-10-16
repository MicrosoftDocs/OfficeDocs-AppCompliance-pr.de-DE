---
title: Application Information for Wide Ideas by Wide Ideas
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für wide Ideas, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 075136dcf0c7e03d3f70461490f1b8c181478c43
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414371"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. August 2021</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von "Wide Ideas" für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wide Ideas |
| ID | WA200000819 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Wide Ideas |
| URL der Partnerwebsite | [https://getwideideas.com](https://getwideideas.com) |
| URL der Datenschutzrichtlinie | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von "Wide Ideas" bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | Delegiert | So erstellen Sie einen Kanal in einem Team.  | Wir speichern die Kanal-ID für die erstellte Abfrage.  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Directory.Read.All | Delegiert | Wir verwenden dies zum Auflisten von Benutzern aus dem Kundenverzeichnis  | Nicht zutreffend | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Group.Read.All | Delegiert | Wir verwenden dies, um Teams aus Microsoft Teams zu lesen und zu synchronisieren. | Wir speichern die Gruppen-ID des Teams und die Mitglieder des Teams.  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsAppInstallation.ReadWriteForTeam | Delegiert | Dies wird verwendet, um die App automatisch in Teams zu installieren.  | Wir speichern Informationen darüber, in welchem Team die App installiert ist. | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsTab.Create | Delegiert | Wir verwenden dies, um Anwendungsregisterkarten (Abfrage-/Suchideen) automatisch in Kanälen zu erstellen, die von Wide Ideas erstellt wurden. | Nicht zutreffend | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| User.Read | Delegiert | Wird verwendet, um Benutzer über SSO zu authentifizieren und Benutzerdaten zu synchronisieren | Wir speichern Name, E-Mail und Benutzer-ID.  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet-E-Mail, die für E-Mail-Benachrichtigungen verwendet wird. | email address | So können Sie E-Mail-Benachrichtigungen über Aktivitäten senden  |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Um Benutzer in unserem Back-End zu erstellen und Berechtigungen für den Zugriff auf mit dem Team verknüpfte Inhalte zu erteilen. | Wir speichern: Name - So zeigen Sie den Namen des Benutzers an, E-Mail-Adresse - Um den Benutzer zu identifizieren | Um die Berechtigung für Inhalte in unserem Back-End zu verwalten |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern Namen, E-Mail- und IP-Nummer in unseren Protokollen. Die Organisation kann eine Anforderung an uns als Lieferant senden, wenn daten gelöscht werden sollen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Datenspeicherung: Alle Kundendaten werden in Microsoft Azure Diensten gespeichert. Benutzer müssen über Azure AD 2-Faktor authentifiziert werden. Rollenbasierter Zugriff (Role Based Access, RBAC) ist vorhanden. Der gesamte Zugriff auf Microsoft Azure erfolgt ausschließlich über verschlüsselte Verbindungen. Alle ruhenden Daten werden verschlüsselt. Alle Dienste sind am besten durch das Azure Security Center geschützt. 

Wir verfügen auch über eine Zugriffsrichtlinie gemäß dem Prinzip der geringsten Rechte. 


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von umfassenden Ideen dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | MFA |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

