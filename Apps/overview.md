---
title: Microsoft 365 Compliance-Programm
author: LGerrard
ms.author: Legerrar
description: Programmeinführung und -Übersicht
keywords: Microsoft 365 m365-App Herausgebernachweis-Zertifizierung
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: e36bee4289de320d264a8a5e55c7bc20a4ea803b
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545767"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 Compliance-Programm

Das Microsoft 365 App Compliance-Programm ist ein zweistufiger Ansatz für App-Sicherheit und -Compliance. Er umfasst Publisher-Überprüfung und die Microsoft 365-Zertifizierung. Jede Stufe baut auf der nächsten auf – und bieten ein mehrschichtiges Programm, um den Benutzern die Sicherheit zu geben, die sie bei der Verwendung von Apps im Microsoft 365-Ökosystem benötigen.  

Unsere Mission: Microsoft-Kunden eine Möglichkeit geben, den Anwendungen, mit denen ihre Organisationen arbeiten, vollständig zu vertrauen.

![2-stufiger Ansatz zur App-Compliance](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>Herausgeberüberprüfung

Die [Herausgeberüberprüfung](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) hilft Administratoren und Anwendern, die Authentizität von App-Entwicklern zu verstehen, die sich in die Microsoft-Identitätsplattform integrieren. Wenn eine App als „vom Herausgeber überprüft“ gekennzeichnet ist, bedeutet dies, dass der Herausgeber seine Identität mithilfe eines Microsoft Partner Network-Kontos überprüft hat, das den Überprüfungsprozess abgeschlossen und dieses MPN-Konto mit seiner Anwendungsregistrierung verknüpft hat.
Die Herausgeberüberprüfung gilt für Apps, die folgende Bedingungen erfüllen:  
- Verwenden von OAuth 2.0 und OpenID Connect, um Benutzer anzumelden und den Zugriff auf Daten mithilfe dienstseitiger APIs wie Microsoft Graph anzufordern. 
- Registriert in Azure AD als Mehrfachmandant.  

> [!IMPORTANT]
> Die Herausgeberüberprüfung hindert einen App-Entwickler nicht daran, den Herausgebernachweis oder die Microsoft 365-Zertifizierung zu starten oder abzuschließen. Wenn dies auf die App nicht zutrifft, kann die Überprüfung übersprungen und der Nachweis gestartet werden.

## <a name="microsoft-365-certification"></a>Microsoft 365-Zertifizierung
Der Microsoft 365-Zertifizierungsprozess besteht aus zwei Phasen: **Nachweis** und **Zertifizierung**.
1.  Der **Nachweis** umfasst das Ausfüllen eines Fragebogens zu den Sicherheits-, Datenverarbeitungs- und Complianceattributen einer App, die für Kunden am wichtigsten sind. Alle Informationen werden dann an einem zentralen Ort und in einem konsistenten, leicht lesbaren Format veröffentlicht. Das Ziel besteht darin, den Prozess der App-Einführung zu beschleunigen und gleichzeitig sicherzustellen, dass die von Kunden in ihren Mandanten verwendeten Apps ihren Unternehmensstandards entsprechen.
1.  Die **Zertifizierung** umfasst eine sorgfältige Prüfung einer App anhand einer Reihe von Kontrollen, die aus führenden Branchen-Standardframeworks abgeleitet sind. ISVs werden aufgefordert, Nachweise zu liefern, um zu beweisen, dass sie die einzelnen Kontrollen erfüllen, bevor sie eine Zertifizierung erhalten. Das Ziel besteht darin, Kunden die Sicherheit zu geben, dass sie der App vertrauen können, dass Apps, die eine Microsoft 365-Zertifizierung erhalten haben, starke Sicherheits- und Compliancepraktiken bieten, um ihre Datensicherheit und den Datenschutz zu gewährleisten.


Die Microsoft 365-Zertifizierung gilt für WebApps und alle Apps, die in die folgenden Microsoft-Produkte integriert sind:
-   Microsoft Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

### <a name="get-started"></a>Erste Schritte
- [So schließen Sie die Publisher-Überprüfung ab](https://docs.microsoft.com/en-us/azure/active-directory/develop/mark-app-as-publisher-verified)
- [So schließen Sie die Microsoft 365-Zertifizierung ab](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification)

