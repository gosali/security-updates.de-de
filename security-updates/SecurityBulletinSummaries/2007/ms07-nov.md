---
TOCTitle: 'MS07-NOV'
Title: Microsoft Security Bulletin Summary für November 2007
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61225052
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms07-nov(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für November 2007
=====================================================

Veröffentlicht: Dienstag, 13. November 2007

**Version:** 1.0

In diesem Bulletin Summary sind die im November 2007 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für November 2007 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 8. November 2007 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx)

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 14. November 2007 um 11:00 Uhr pazifischer Zeit (USA & Kanada) führt Microsoft einen englischsprachigen Webcast durch, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im November.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Summarys und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

Die Security Bulletins für diesen Monat, nach Schweregrad geordnet:

Kritisch (1)
------------

| Kennung des Bulletins                      | Microsoft Security Bulletin MS07-061                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                    | [**Sicherheitsanfälligkeit bei der URI-Verarbeitung in Windows kann Remotecodeausführung ermöglichen (943460)**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-061.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Kurzzusammenfassung**                    | Dieses Update behebt eine öffentlich gemeldete Sicherheitsanfälligkeit. Es liegt eine Sicherheitsanfälligkeit bezüglich Remotecodeausführung vor, die durch die Art und Weise der Verarbeitung speziell gestalteter URIs, die der Windows Shell übergeben werden, verursacht wird. Wenn Windows Shell diese URIs nicht ausreichend überprüft hat, kann ein Angreifer diese Sicherheitsanfälligkeit ausnutzen und beliebigen Code ausführen. Microsoft hat nur auf Systemen, auf denen Internet Explorer 7 ausgeführt wird, Möglichkeiten zum Ausnutzen dieser Sicherheitsanfälligkeit identifiziert. Allerdings liegt die Sicherheitsanfälligkeit in der Windows-Datei Shell32.dll vor, die in allen unterstützten Editionen von Windows XP und Windows Server 2003 enthalten ist. |
| **Bewertung des maximalen Schweregrads**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Auswirkung der Sicherheitsanfälligkeit** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Erkennung**                              | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Betroffene Software**                    | **Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

Hoch (1)
--------

| Kennung des Bulletins                      | Microsoft Security Bulletin MS07-062                                                                                                                                                                                                                                                                                                                                            |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                    | [**Sicherheitsanfälligkeit in DNS kann Spoofing ermöglichen (941672)**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-062.mspx)                                                                                                                                                                                                                            |
| **Kurzzusammenfassung**                    | Dieses wichtige Sicherheitsupdate behebt eine von einem Privatanwender gemeldete Sicherheitsanfälligkeit. Diese Sicherheitsanfälligkeit bezüglich Spoofing liegt auf Windows DNS-Servern vor und kann einem Angreifer ermöglichen, speziell gestaltete Antworten auf DNS-Anforderungen zu senden und dadurch Internetverkehr von legitimen Orten vorzutäuschen oder umzuleiten. |
| **Bewertung des maximalen Schweregrads**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                 |
| **Auswirkung der Sicherheitsanfälligkeit** | Spoofing                                                                                                                                                                                                                                                                                                                                                                        |
| **Erkennung**                              | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart, mit Ausnahme von bestimmten Situationen.                                                                                                                                                                                                 |
| **Betroffene Software**                    | **Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                          |

Betroffene Software und Downloadadressen
----------------------------------------

**Wie verwende ich diese Tabelle?**  

In dieser Tabelle finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Sie sollten jedes aufgeführte Softwareprogramm und jede Komponente überprüfen, um zu sehen, ob Sicherheitsupdates erforderlich sind. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Auswirkung der Sicherheitsanfälligkeit aufgelistet und mit einem Softwareupdate verlinkt.

**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Prüfen Sie für jede aufgeführte Kennung der Bulletins die gesamte Spalte, um basierend auf den in Ihrem System installierten Programmen und Komponenten alle Updates zu finden, die Sie installieren müssen.

**Betroffene Software und Downloadadressen**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Details        
</th>
<th style="border:1px solid black;" >
Details        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS07-061**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-061.mspx)
</td>
<td style="border:1px solid black;">
[**MS07-062**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-062.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows-Betriebssystem:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104)
</td>
<td style="border:1px solid black;">

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Security Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind auch über [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) und [Office Update](http://office.microsoft.com/de-de/downloads/default.aspx) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „sicherheitsupdate“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Microsoft Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Anleitungen zur Erkennung und Bereitstellung**

Zu den Sicherheitsupdates dieses Monats stellt Microsoft Anleitungen zur Erkennung und Bereitstellung zur Verfügung: Diese Anleitungen geben auch IT-Profis Informationen zum Einsatz der verschiedenen Tools und zur Bereitstellung des Sicherheitsupdates. Behandelt werden u. a. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) und das Erweiterte Sicherheitsupdate-Inventurprogramm (ESUIT). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

Mit dem Microsoft Baseline Security Analyzer können Sie als Administrator Systeme sowohl lokal als auch remote auf fehlende Sicherheitspatches und fehlerhafte Konfigurationen überprüfen. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Hinweis:** Nach dem 9. Oktober 2007 wird die von MBSA 1.2.1 verwendete Datei MSSecure.XML nicht mehr aktualisiert. Nach diesem Datum werden keine neuen Sicherheitsupdates für die von MBSA 1.2.1 verwendete Datei MSSecure.XML erstellt und keine neuen Versionen des Enterprise Scan Tools veröffentlicht. Dies betrifft nicht das Sicherheitsupdate-Inventurprogramm (SUIT) oder das Erweiterte Sicherheitsupdate-Inventurprogramm (ESUIT) für SMS 2.0 und SMS 2003. Weitere Informationen finden Sie unter [Microsoft Baseline Security Analyzer.](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx)

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie auf der Website [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch die Website [Software Updates Service Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2/downloads/featurepacks/suspack/default.mspx) besuchen, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/smserver/default.mspx).

**Hinweis:** SMS nutzt Microsoft Baseline Security Analyzer und das Microsoft Office Detection Tool, um eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates bereitzustellen. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2003/downloads/featurepacks/adminpack.mspx) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

### Weitere Informationen:

#### Windows-Tool zum Entfernen bösartiger Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Für diesen Monat:

-   Microsoft hat drei **nicht sicherheitsrelevante** Updates mit hoher Priorität auf Microsoft Update (MU) und Windows Server Update Services (WSUS) veröffentlicht.
-   Microsoft hat keine **nicht sicherheitsrelevanten** Updates mit hoher Priorität für Windows auf Windows-Update (WU) veröffentlicht.

Diese Informationen gelten **nur** für wichtige, **nicht sicherheitsrelevante** Updates auf Microsoft Update, Windows Update und Windows Server Update Services, die an demselben Tag wie das Security Bulletin Summary veröffentlicht wurden. Es werden **keine** Informationen zu **nicht sicherheitsrelevanten** Updates bereitgestellt, die an anderen Tagen veröffentlicht werden.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Security Guidance für Patchverwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar Sie können am einfachsten durch eine Suche nach dem Begriff „sicherheitsupdate“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community:**

Auf der Website [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) erfahren Sie, wie Sie die Sicherheit erhöhen und die IT-Infrastruktur optimieren können. Sie haben zudem die Möglichkeit sich mit anderen IT-Fachleuten über Sicherheitsthemen auszutauschen.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Jesper Johansson für die Zusammenarbeit mit uns an einem in MS07-061 beschriebenen Problem.
-   Carsten H. Eiram von [Secunia](http://corporate.secunia.com/) für die Zusammenarbeit mit uns an einem in MS07-061 beschriebenen Problem.
-   Aviv Raff von [Finjan](http://www.finjan.com/) für die Zusammenarbeit mit uns an einem in MS07-061 beschriebenen Problem.
-   Petko Petkov von [GNUCITIZEN](http://www.gnucitizen.org/) für die Zusammenarbeit mit uns an einem in MS07-061 beschriebenen Problem.
-   Alla Berzroutchko von [Scanit](http://www.scanit.be/) für den Hinweis auf ein in MS07-062 beschriebenes Problem.
-   Amit Klein von [Trusteer](http://www.trusteer.com/) für den Hinweis auf ein in MS07-062 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über die [Microsoft Support Services](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos.
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (13. November 2007): Bulletin Summary veröffentlicht.

*Built at 2014-04-18T01:50:00Z-07:00*
