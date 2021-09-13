---
title: Microsoft 365 Compliance-Programm
author: LGerrard
ms.author: Legerrar
description: Programmeinführung und -Übersicht
keywords: Microsoft 365 m365-App Herausgebernachweis-Zertifizierung
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: c644414281f46696ff49f3b9eb1341f02e96f0ba
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283088"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 Compliance-Programm

Das Microsoft 365 App-Compliance-Programm ist ein dreistufiger Ansatz für App-Sicherheit und -Compliance. Jede Stufe baut auf der nächsten auf – und bieten ein mehrschichtiges Programm, um den Benutzern die Sicherheit zu geben, die sie bei der Verwendung von Apps im Microsoft 365-Ökosystem benötigen. Derzeit sind alle Stufen des Programms freiwillig und werden nach Ermessen der App-Entwickler abgeschlossen. 

Unser Leitbild: Microsoft-Kunden haben volles Vertrauen in die Anwendungen, mit denen ihre Organisationen arbeiten.

  ![3-stufiger Ansatz zur App-Compliance](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Herausgeberüberprüfung

Die [Herausgeberüberprüfung](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) hilft Administratoren und Anwendern, die Authentizität von App-Entwicklern zu verstehen, die sich in die Microsoft-Identitätsplattform integrieren. Wenn eine App als „vom Herausgeber überprüft“ gekennzeichnet ist, bedeutet dies, dass der Herausgeber seine Identität mithilfe eines Microsoft Partner Network-Kontos überprüft hat, das den Überprüfungsprozess abgeschlossen und dieses MPN-Konto mit seiner Anwendungsregistrierung verknüpft hat.
Die Herausgeberüberprüfung gilt für Apps, die folgende Bedingungen erfüllen:  
- Verwenden von OAuth 2.0 und OpenID Connect, um Benutzer anzumelden und den Zugriff auf Daten mithilfe dienstseitiger APIs wie Microsoft Graph anzufordern. 
- Registriert in Azure AD als Mehrfachmandant.  

> [!IMPORTANT]
> Die Herausgeberüberprüfung hindert einen App-Entwickler nicht daran, den Herausgebernachweis oder die Microsoft 365-Zertifizierung zu starten oder abzuschließen. Wenn dies auf die App nicht zutrifft, kann die Überprüfung übersprungen und der Nachweis gestartet werden.

## <a name="publisher-attestation"></a>Herausgebernachweis

Der [Herausgebernachweis](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) ist der Ort, an dem Entwickler allgemeine Informationen, Informationen zur Datenverarbeitung sowie Sicherheits- und Compliance-Informationen zu ihrem App-Dienst freigeben. Dies reduziert die Notwendigkeit für IT-Administratoren, direkt mit App-Herausgebern zusammenzuarbeiten. Alle Informationen, die für eine informierte Entscheidung erforderlich sind, können für alle Apps, welche den Herausgebernachweis abgeschlossen haben, an einem Ort und in einem einheitlichen Format gefunden werden. Das Ziel ist es, den Prozess der App-Einführung zu vereinfachen und zu beschleunigen und gleichzeitig sicherzustellen, dass die Apps, welche die Kunden in ihren Mandanten verwenden, ihren Unternehmensstandards entsprechen.

Der Herausgebernachweis gilt für WebApps und alle Apps, die in die folgenden Microsoft-Produkte integriert sind:
-   Microsoft Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft überprüft die angegebenen Informationen nicht. Der Entwickler bestätigt alleine die Richtigkeit, Genauigkeit und Integrität der Nachweisdokumentation und der entsprechenden App-Leistungsdaten. 

## <a name="microsoft-365-certification"></a>Microsoft 365-Zertifizierung
Die [Microsoft 365-Zertifizierung](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) bietet Unternehmen die Gewissheit und das Vertrauen, dass Daten und Privatsphäre bei der Verwendung von Microsoft Teams-Apps angemessen gesichert und geschützt sind. Die Zertifizierung bestätigt, dass eine App-Lösung mit Microsoft-Technologien kompatibel ist, den bewährten Methoden für Cloud App Security entspricht und von Microsoft unterstützt wird. Während diesem Prozess arbeiten die App-Entwickler mit einem externen Prüfer zusammen, um die Sicherheits- und Compliance-Standards des Unternehmens zu validieren. Microsoft 365-Zertifizierung gilt für dieselben Apps, die für den Herausgebernachweis qualifiziert sind. 


