---
title: Anwendungsinformationen für Lucidspark von Lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Lucidspark, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e79bed420b3081ae31a0abda25299610eeb1bc5f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282461"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Lucid Software für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Lucidspark |
| ID | WA200002583 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Lucid Software |
| URL der Partnerwebsite | [https://lucid.co](https://lucid.co) |
| URL der Seite mit Teams Anwendungsinformationen | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| URL der Datenschutzrichtlinie | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL der Nutzungsbedingungen | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Lucid Software dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidspark, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidspark-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidspark, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidspark-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| Profil | Delegiert | Name und E-Mail-Adresse. | Die E-Mail-, OpenID- und Profilberechtigungen ermöglichen Lucidspark, ein OpenID-Token für einen Benutzer zu generieren und genügend grundlegende Informationen über den Benutzer zu erhalten, um bei Bedarf ein Lucidspark-Konto für diesen zu registrieren. Um die von Microsoft zurückgegebenen Daten zu überprüfen, stellen wir eine Anforderung zum Abrufen des öffentlichen Schlüssels, mit dem ihre Antwort signiert ist. Im Rahmen unseres SSO-Flusses werden keine anderen Daten von Microsoft empfangen oder an Microsoft gesendet. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Lucidspark- und Lucidchart-Daten werden in AWS und Demflake gespeichert. | Organisationsname, Kontaktinformationen und Lizenzebene | Wir verwenden keine Microsoft-APIs. Wir verwenden openID, um grundlegende Benutzerdaten zum Ausführen von SSO abzurufen. Wir verwenden die Dateiauswahl-API, aber dadurch erhalten wir keinen Zugriff auf die Dateien des Benutzers, außer auf die Dateien, die sie über die Auswahl an uns übermitteln. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren E-Mail- und IP-Adressen aus Sicherheits- und Supportgründen. Der gesamte Zugriff auf Protokolle erfolgt über aufgezeichnete &amp; Protokolle, die in einem Drittanbietersystem nicht geändert werden können. Der Zugriff auf Protokolle erfordert MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Lucidspark- und Lucidchart-Daten werden in AWS gespeichert. Er wird im Ruhezustand und während der Übertragung verschlüsselt. Lucid verwendet die Regeln der geringsten Rechte und der MFA.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Lucid Software darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
