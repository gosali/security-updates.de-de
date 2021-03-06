---
TOCTitle: 'MS09-AUG'
Title: Microsoft Security Bulletin Summary für August 2009
ms:assetid: 'ms09-aug'
ms:contentKeyID: 61225068
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms09-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für August 2009
===================================================

Veröffentlicht: Dienstag, 11. August 2009 | Aktualisiert: Dienstag, 27. Oktober 2009

**Version:** 4.0

In diesem Bulletin Summary sind die im August 2009 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für August 2009 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 6. August 2009 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 12. August 2009 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im August.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

Kurzzusammenfassungen
---------------------

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software und Downloadadressen**.

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Kennung des Bulletins</th>
<th style="border:1px solid black;" >Titel des Bulletins und Kurzzusammenfassung</th>
<th style="border:1px solid black;" >Bewertung des maximalen Schweregrads und Sicherheitsauswirkung</th>
<th style="border:1px solid black;" >Neustartanforderung:</th>
<th style="border:1px solid black;" >Betroffene Software</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Office Web Components können Remotecodeausführung ermöglichen (957638)</strong><br />
<br />
Dieses Sicherheitsupdate behebt mehrere vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office Web Components, die Remotecodeausführung ermöglichen können, wenn ein Benutzer eine speziell gestaltete Webseite anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Visual Studio, Microsoft ISA Server, Microsoft BizTalk Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157861">MS09-044</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Remotedesktopverbindung können Remotecodeausführung ermöglichen (970927)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft-Remotedesktopverbindung. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Angreifer einen Benutzer von Terminaldiensten erfolgreich dazu verleitet, eine Verbindung zu einem schädlichen RDP-Server herzustellen, oder wenn ein Benutzer eine speziell gestaltete Website besucht, die diese Sicherheitsanfälligkeit ausnutzt. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows, Remotedesktopverbindungs-Client für Mac</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155974">MS09-039</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in WINS können Remotecodeausführung ermöglichen (969883)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten im Windows Internet Name Service (WINS). Jede der beiden Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer auf einem betroffenen System, das den WINS-Dienst ausführt, ein speziell gestaltetes WINS-Replikationspaket empfängt. Standardmäßig ist WINS bei keiner Version der betroffenen Betriebssysteme installiert. Nur Benutzer, die diese Komponente manuell installieren, sind von diesem Problem betroffen.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155975">MS09-038</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten bei der Verarbeitung von Windows Media-Dateien können Remotecodeausführung ermöglichen (971557)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in der Verarbeitung von Windows Media-Dateien. Jede dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete AVI-Datei öffnet. Wenn ein Benutzer mit administrativen Benutzerrechten angemeldet ist, kann ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908)</strong><br />
<br />
Dieses Sicherheitsupdate behebt mehrere vertraulich gemeldete Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL). Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer speziell gestaltete Komponenten oder Steuerelemente lädt, die auf einer schädlichen Website gehostet werden. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155977">MS09-041</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im Arbeitsstationsdienst kann Erhöhung von Berechtigungen ermöglichen (971657)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Windows-Arbeitsstationsdienst. Die Sicherheitsanfälligkeit kann eine Erhöhung von Berechtigungen ermöglichen, wenn ein Angreifer eine speziell gestaltete RPC-Nachricht erstellt und an ein betroffenes System sendet. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann beliebigen Code ausführen und vollständige Kontrolle über das betroffene System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Ein Angreifer muss über gültige Anmeldeinformationen für ein betroffenes System verfügen, um diese Sicherheitsanfälligkeit ausnutzen zu können. Die Sicherheitsanfälligkeit kann nicht von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155979">MS09-040</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit beim Message Queuing kann Erhöhung von Berechtigungen ermöglichen (971032)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Windows Message Queuing-Dienst (MSMQ). Die Sicherheitsanfälligkeit kann eine Erhöhung von Berechtigungen ermöglichen, wenn ein Benutzer eine speziell gestaltete Anforderung an einen betroffenen MSMQ-Dienst erhalten hat. Standardmäßig wird die Komponente Message Queuing nicht unter betroffenen Betriebssystemversionen installiert und kann nur von einem Benutzer mit Administratorberechtigungen aktiviert werden. Nur Kunden, die die Message Queuing-Komponente manuell installieren, können für dieses Problem anfällig sein.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157296">MS09-036</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in ASP.NET in Microsoft Windows kann Denial-of-Service ermöglichen (970957)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit bezüglich Denial-of-Service in der Microsoft .NET Framework-Komponente in Microsoft Windows. Diese Sicherheitsanfälligkeit kann nur ausgenutzt werden, wenn Internet Information Services (IIS) 7.0 installiert und ASP.NET so konfiguriert ist, dass auf den betroffenen Versionen von Microsoft Windows der integrierte Modus verwendet wird. Ein Angreifer könnte speziell gestaltete anonyme HTTP-Anforderungen erstellen, die dazu führen können, dass der betroffene Webserver erst wieder reagieren kann, wenn der zugeordnete Anwendungspool neu gestartet wird. Benutzer, die IIS-7.0-Anwendungspools im klassischen Modus ausführen, sind von dieser Sicherheitsanfälligkeit nicht betroffen.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Kein Neustart erforderlich.</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157140">MS09-042</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Telnet kann Remotecodeausführung ermöglichen (960859)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich gemeldete Sicherheitsanfälligkeit im Microsoft Telnet-Dienst. Die Sicherheitsanfälligkeit kann einem Angreifer ermöglichen, Anmeldeinformationen zu erhalten und sich damit bei betroffenen Systemen anzumelden. Der Angreifer erlangt dann auf einem System Benutzerrechte, die mit denen des angemeldeten Benutzers identisch sind. Dieses Szenario kann letzten Endes zu Remotecodeausführung auf betroffenen Systemen führen. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und CVE-ID geordnet.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Kennung des Bulletins                                     | Titel des Bulletins                                                                                                       | CVE-ID                                                                           | Ausnutzbarkeitsindex – Bewertung                                                                                     | Wichtige Hinweise                                                                                                                                                                                                                                                                                               |  
|-----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-036](http://go.microsoft.com/fwlink/?linkid=157296) | Sicherheitsanfälligkeit in ASP.NET in Microsoft Windows kann Denial-of-Service ermöglichen (970957)                       | [CVE-2009-1536](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Ein Denial-of-Service-Tool ist wahrscheinlich. Funktionierender Angreifercode für Remotecodeausführung ist jedoch unwahrscheinlich.                                                                                                                                                                             |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908) | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | **Diese Sicherheitsanfälligkeit wird derzeit in der Internetumgebung ausgenutzt.**                                                                                                                                                                                                                              |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908) | [CVE-2008-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908) | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | Keine                                                                                                                | (Diese Sicherheitsanfälligkeit wurde bereits im Ausnutzbarkeitsindex im [Bulletin Summary von Juli](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms09-jul.mspx) bewertet. Diese Sicherheitsanfälligkeit wurde erstmalig in [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) behoben.) |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908) | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Keine                                                                                                                | (Diese Sicherheitsanfälligkeit wurde bereits im Ausnutzbarkeitsindex im [Bulletin Summary von Juli](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms09-jul.mspx) bewertet. Diese Sicherheitsanfälligkeit wurde erstmalig in [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) behoben.) |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Sicherheitsanfälligkeiten in der Microsoft Active Template Library (ATL) können Remotecodeausführung ermöglichen (973908) | [CVE-2009-2494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-038](http://go.microsoft.com/fwlink/?linkid=155975) | Sicherheitsanfälligkeiten bei der Verarbeitung von Windows Media-Dateien können Remotecodeausführung ermöglichen (971557) | [CVE-2009-1545](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545) | [**2**  –](http://technet.microsoft.com/en-us/security/cc998259.aspx) Inkonsistenter Angreifercode wahrscheinlich    | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-038](http://go.microsoft.com/fwlink/?linkid=155975) | Sicherheitsanfälligkeiten bei der Verarbeitung von Windows Media-Dateien können Remotecodeausführung ermöglichen (971557) | [CVE-2009-1546](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546) | [**2**  –](http://technet.microsoft.com/en-us/security/cc998259.aspx) Inkonsistenter Angreifercode wahrscheinlich    | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-039](http://go.microsoft.com/fwlink/?linkid=155974) | Sicherheitsanfälligkeiten in WINS können Remotecodeausführung ermöglichen (969883)                                        | [CVE-2009-1923](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-039](http://go.microsoft.com/fwlink/?linkid=155974) | Sicherheitsanfälligkeiten in WINS können Remotecodeausführung ermöglichen (969883)                                        | [CVE-2009-1924](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924) | [**2**  –](http://technet.microsoft.com/en-us/security/cc998259.aspx) Inkonsistenter Angreifercode wahrscheinlich    | Ausnutzung eines Windows 2000-Ziels ist wahrscheinlich erfolgreicher.                                                                                                                                                                                                                                           |  
| [MS09-040](http://go.microsoft.com/fwlink/?linkid=155979) | Sicherheitsanfälligkeit beim Message Queuing kann Erhöhung von Berechtigungen ermöglichen (971032)                        | [CVE-2009-1922](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Ein Remoteangriff mit dieser Sicherheitsanfälligkeit ist nicht möglich.                                                                                                                                                                                                                                         |  
| [MS09-041](http://go.microsoft.com/fwlink/?linkid=155977) | Sicherheitsanfälligkeit im Arbeitsstationsdienst kann Erhöhung von Berechtigungen ermöglichen (971657)                    | [CVE-2009-1544](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Ein Angreifer muss sich authentifizieren, um diese Sicherheitsanfälligkeit auszunutzen.                                                                                                                                                                                                                         |  
| [MS09-042](http://go.microsoft.com/fwlink/?linkid=157140) | Sicherheitsanfälligkeit in Telnet kann Remotecodeausführung ermöglichen (960859)                                          | [CVE-2009-1930](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Diese Sicherheitsanfälligkeit ähnelt früheren Sicherheitsanfälligkeiten bezüglich der Reflektion von NTLM-Anmeldeinformationen, für die bereits Angreifercode vorhanden ist.                                                                                                                                    |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Sicherheitsanfälligkeiten in Microsoft Office Web Components können Remotecodeausführung ermöglichen (957638)             | [CVE-2009-0562](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Sicherheitsanfälligkeiten in Microsoft Office Web Components können Remotecodeausführung ermöglichen (957638)             | [CVE-2009-1136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Für diese Sicherheitsanfälligkeit wurde Angreifercode veröffentlicht.                                                                                                                                                                                                                                           |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Sicherheitsanfälligkeiten in Microsoft Office Web Components können Remotecodeausführung ermöglichen (957638)             | [CVE-2009-1534](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Sicherheitsanfälligkeiten in Microsoft Office Web Components können Remotecodeausführung ermöglichen (957638)             | [CVE-2009-2496](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-044](http://go.microsoft.com/fwlink/?linkid=157861) | Sicherheitsanfälligkeiten in Remotedesktopverbindung können Remotecodeausführung ermöglichen (970927)                     | [CVE-2009-1133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133) | [**2**  –](http://technet.microsoft.com/en-us/security/cc998259.aspx) Inkonsistenter Angreifercode wahrscheinlich    | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-044](http://go.microsoft.com/fwlink/?linkid=157861) | Sicherheitsanfälligkeiten in Remotedesktopverbindung können Remotecodeausführung ermöglichen (970927)                     | [CVE-2009-1929](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |
  
Betroffene Software und Downloadadressen  
----------------------------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
**Wie verwende ich diese Tabellen?**  
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.
  
**Hinweis**: Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
#### Systemkomponenten des Windows-Betriebssystems

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[RDP-Version 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864)\*\*\*  
(KB958471) und [RDP-Version 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2) (KB958470)  
(Kritisch)  
[RDP-Version 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(Kritisch)  
[RDP-Version 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2)  
(KB973354)  
(Kritisch)  
[Microsoft Outlook Express 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f340af34-b9a0-44fb-b595-dbb346c727bf)  
(KB973354)  
(Kritisch)  
[Windows Media Player 9](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0)  
(KB973869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=240977d6-3581-4058-b9f1-7847e4edcf8a)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 und Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[RDP-Version 5.1 für Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)  
(KB958470)  
(Kritisch)  
[RDP-Version 5.2 für Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046)\*\*\*\*  
(KB958469)  
(Kritisch)  
[RDP-Version 5.2 für Windows XP Service Pack 3:](http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046)  
(KB958469)  
(Kritisch)  
[RDP-Version 6.0 für Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(Hoch)  
[RDP-Version 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c67b5506-00ea-47cc-a0e8-897057b7380c)  
(KB973354)  
(Kritisch)  
[Windows Media Player 9, Windows Media Player 10 und Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=34b2b14d-5811-4635-ba83-f837dcb03d04)  
(KB973540)  
(Kritisch)  
(Nur Windows XP Service Pack 2)  
[Windows Media Player 9, Windows Media Player 10 und Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f)  
(KB973540)  
(Kritisch)  
(Nur Windows XP Service Pack 3)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592)  
(KB973869)  
(Kritisch)  
[Microsoft MSWebDVD ActiveX-Steuerelement](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36)  
(KB973815)  
(Kritisch)  
[ActiveX-Steuerelement HtmlInput-Objekt](http://www.microsoft.com/downloads/details.aspx?familyid=46aa443c-4e7b-4bd5-8b4e-0068c3dc0e79)  
(KB973768)  
(Kritisch)  
(nur Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b3331388-1e52-4924-b512-23275a8fde84)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 5.2 für Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda)  
(KB958469)  
(Kritisch)  
[RDP-Version 6.0 für Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b)\*\*\*\*  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da)  
(KB973354)  
(Kritisch)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6)  
(KB973540)  
(Kritisch)  
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99)  
(KB973869)  
(Kritisch)  
[Microsoft MSWebDVD ActiveX-Steuerelement](http://www.microsoft.com/downloads/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade)  
(KB973815)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
(Kritisch)  
[RDP-Version 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3119ab1e-6729-40a1-b28f-0dab50502be6)  
(KB973354)  
(Kritisch)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ab054890-983b-4414-ad0a-da1b2d2a4895)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561)  
(KB973869)  
(Kritisch)  
[Microsoft MSWebDVD ActiveX-Steuerelement](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=301ad191-8d3f-41d3-b41c-e2e863893f73)  
(KB973815)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=57393588-dc96-4bda-ab1e-ae550961e5d4)  
(KB958469)  
(Kritisch)  
[RDP-Version 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=957c2e01-89a1-4550-aacb-de8ff896d762)\*\*\*\*  
(KB956744)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e)  
(KB973354)  
(Kritisch)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa)  
(KB973869)  
(Kritisch)  
[Microsoft MSWebDVD ActiveX-Steuerelement](http://www.microsoft.com/downloads/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc)  
(KB973815)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[RDP-Version 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028)  
(KB958469)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9)  
(KB973354)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement der DHTML-Bearbeitungskomponente](http://www.microsoft.com/downloads/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac)  
(KB973869)  
(Kritisch)  
[Microsoft MSWebDVD ActiveX-Steuerelement](http://www.microsoft.com/downloads/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218)  
(KB973815)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 6.0 unter Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
(Hoch)  
[RDP-Version 6.1 für Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement HtmlInput-Objekt](http://www.microsoft.com/downloads/details.aspx?familyid=59fefa17-0ad4-4a62-82be-e6a2b7a0aec3)  
(KB973768)  
(Kritisch)  
(nur Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Vista: [Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(Hoch)  
Nur Windows Vista Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f)\*\*\*\*\* (KB972594)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d77f406d-11cb-4d19-94ec-938b356c3427)  
(Mittel)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 6.0 unter Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(Hoch)  
[RDP-Version 6.1 unter Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd)  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294)  
(KB973507)  
(Kritisch)  
[ActiveX-Steuerelement HtmlInput-Objekt](http://www.microsoft.com/downloads/details.aspx?familyid=92de8a2e-2d50-4278-937e-ccb862c5ab8f)  
(KB973768)  
(Kritisch)  
(nur Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Vista x64 Edition: [Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(Hoch)  
Nur Windows Vista x64 Edition Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 und .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7a41b8c1-f955-474e-a08e-5e73964327d1)  
(Mittel)
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a)\*\*  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f)\*\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4)\*\*  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc)\*  
(KB973507)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913)\*  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für 32-Bit-Systeme: [Microsoft .NET Framework 2.0 Service Pack 1 und .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e)\*  
(Mittel)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261)\*\*  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f)\*\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0)\*\*  
(KB973540)  
(Kritisch)  
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd)\*  
(KB973507)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93)\*  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für x64-basierte Systeme: [Microsoft .NET Framework 2.0 Service Pack 1 und .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6e5d1db9-efef-4112-8138-62f14670cf0d)\*  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP-Version 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8)  
(KB956744)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows ATL-Komponente](http://www.microsoft.com/downloads/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c)  
(KB973507)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für Itanium-basierte Systeme: [Microsoft .NET Framework 2.0 Service Pack 1 und .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) sowie [Microsoft .NET Framework 2.0 Service Pack 2 und .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(Hoch
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d)  
(Mittel)
</td>
</tr>
</table>
 
**Hinweise für Windows Server 2008**

**\*Die Server Core-Installation von Windows Server 2008 ist betroffen.** Für unterstützte Editionen von Windows Server 2008 gilt dieses Update mit der gleichen Bewertung des Schweregrads. Dabei spielt es keine Rolle, ob Windows Server 2008 mit der Server Core-Installationsoption installiert wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie unter [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008r2/editionen/r2-vergleich-server-core.mspx).

**\*\*Die Server Core-Installation von Windows Server 2008 ist nicht betroffen.** Die durch dieses Update behobenen Sicherheitsanfälligkeiten betreffen unterstützte Editionen von Windows Server 2008 nicht, wenn Windows Server 2008 mit der Server Core-Installationsoption installiert wurde. Weitere Informationen zu dieser Installationsoption finden Sie unter [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008r2/editionen/r2-vergleich-server-core.mspx).

**Hinweise für MS09-044**

***Benutzer von RDP-Version 5.0 unter Microsoft Windows 2000 Service Pack 4 müssen sowohl KB958471 als auch KB958470 installieren.

****Administratoren haben diesen gebrauchsfertigen Download u. U. manuell installiert.

Weitere Updatedateien finden Sie außerdem im Unterabschnitt „Clientsoftware für Mac“ in dem Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

**Hinweis für MS09-036**

*****Weil IIS 7.0 nicht auf Windows Vista Starter und Windows Vista Home Basic ausgeführt werden kann, sind die folgenden Editionen nicht betroffen: Windows Vista Starter (32 Bit), Windows Vista Home Basic (32 Bit) und Windows Vista Home Basic (64 Bit).

#### Clientsoftware für Mac

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Remotedesktop
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Remotedesktopverbindungs-Client für Mac
</td>
<td style="border:1px solid black;">
[Remotedesktopverbindungs-Client für Mac 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871)**\***  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise für MS09-044**

*Dieser Download aktualisiert Remotedesktopverbindungs-Client für Mac 2.0 auf Remotedesktopverbindungs-Client für Mac 2.0.1, der die Sicherheitsanfälligkeit behebt.

Weitere Updatedateien finden Sie außerdem im Unterabschnitt „Windows-Betriebssystem und Komponenten“ in dem Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Office Web Components
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Web Components Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Web Components Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(Kritisch)  
[Microsoft Office 2003 Web Components Service Pack 1 für Microsoft Office System 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be)\*  
(KB947318)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Weitere Office-Software
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Small Business Accounting 2006
</td>
<td style="border:1px solid black;">
[Microsoft Office Small Business Accounting 2006](http://www.microsoft.com/downloads/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82)  
(KB968377)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweise für MS09-043**

*SQL Server 2008 und Microsoft Forefront Threat Management Gateway Medium Business Edition verteilen die betroffene Komponente von Office 2003 Web Components für das Microsoft Office System 2007. Das Update für die Office 2003 Internet Components für das Microsoft Office System 2007 sucht nach SQL Server 2008 und Microsoft Forefront Threat Management Gateway Medium Business Edition und bietet Benutzern das Update an.

Weitere Updatedateien finden Sie außerdem in den weiteren Unterabschnitten unter dem Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Entwicklertools und Software

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585)  
(KB969172)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis für MS09-043**

Weitere Updatedateien finden Sie außerdem in den weiteren Unterabschnitten unter dem Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Server und Sicherheitssoftware

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f79a073-27e8-46ef-87d8-f09b93521326)\*  
(KB947826)  
(Kritisch)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006 Standard Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(Kritisch)  
[Microsoft Internet Security and Acceleration Server 2006 Enterprise Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=495839b6-0322-4755-997d-4a7762c53333)  
(KB971388)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweise für MS09-043**

\*Microsoft ISA Server 2004 Standard Edition wird als eigenständiges Produkt angeboten. Microsoft ISA Server 2004 Standard Edition wird auch als Komponente von Windows Small Business Server 2003 Premium Edition Service Pack 1 und Windows Small Business Server 2003 R2 Premium Edition angeboten.

Weitere Updatedateien finden Sie außerdem in den weiteren Unterabschnitten unter dem Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Sicherheits-Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) und [Windows-Update](http://go.microsoft.com/fwlink/?linkid=21130) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Hinweis:** Am 1. August 2009 hat Microsoft den Support für Office Update und das Inventurprogramm für Office Update eingestellt. Verwenden Sie [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), um weiterhin die aktuellen Updates für Microsoft Office-Produkte zu erhalten. Weitere Informationen finden Sie in [Informationen zum Microsoft Office Update: Häufig gestellte Fragen (FAQs)](http://office.microsoft.com/de-de/downloads/fx010402221031.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Microsoft stellt Anleitungen zur Erkennung und Bereitstellung von Sicherheitsupdates bereit. Diese Anleitungen enthalten Empfehlungen und Informationen, anhand derer IT-Experten verstehen können, wie die verschiedenen Tools für die Erkennung und Bereitstellung der Sicherheitsupdates verwendet werden. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 961747](http://support.microsoft.com/kb/961747/de).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 für Windows 2000 und neuere Betriebssysteme schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch das Sicherheitsupdate-Inventurprogramm (SUIT) verwenden, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/systemcenter/sccm/default.mspx).

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=de) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

**Updatekompatibilitätsbewertung und Anwendungskompatibilitäts-Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc766043(ws.10).aspx), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199/de): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Neue, überarbeitete und veröffentlichte Updates für andere Microsoft-Produkte als Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

#### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx) aufgeführt sind.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Security Guidance für Updateverwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086/de).

**IT Pro Security Community**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Alexander Pfandt von [Digitiria](http://www.digitaria.com/) für den Hinweis auf ein in MS09-036 beschriebenes Problem.
-   Ryan Smith und Alex Wheeler von [IBM ISS X-Force](http://www.iss.net/) für den ersten Hinweis auf ein in MS09-037 beschriebenes Problem.
-   Robert Freeman von [IBM ISS X-Force](http://www.iss.net/) für den Hinweis auf ein in MS09-037 beschriebenes Problem.
-   David Dewey von [IBM ISS X-Force](http://www.iss.net/) für den Hinweis auf ein in MS09-037 beschriebenes Problem.
-   Ryan Smith von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf zwei in MS09-037 beschriebene Probleme.
-   Vinay Anantharaman von [Adobe Systems, Inc.](http://www.adobe.com/) für den Hinweis auf zwei in MS09-038 beschriebene Probleme.
-   [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) für den Hinweis auf ein in MS09-039 beschriebenes Problem.
-   LiGen von der [National University of Defense Technology](http://english.nudt.edu.cn/) für den Hinweis auf ein in MS09-039 beschriebenes Problem.
-   Nikita Tarakanov vom [Positive Technologies Research Team](http://en.securitylab.ru/lab/) für den Hinweis auf ein in MS09-040 beschriebenes Problem.
-   Cody Pierce von [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) für den Hinweis auf ein in MS09-041 beschriebenes Problem.
-   Peter Vreugdenhil von [Zero Day Initiative](http://www.zerodayinitiative.com/) für den Hinweis auf zwei in MS09-043 beschriebene Probleme.
-   Peter Vreugdenhil von [Zero Day Initiative](http://www.zerodayinitiative.com/) und Haifei Li von Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) für den Hinweis auf ein in MS09-043 beschriebenes Problem.
-   Sean Larsson von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-043 beschriebenes Problem.
-   Wushi von [Team509](http://www.team509.com/) in Zusammenarbeit mit der Zero Day Initiative für den Hinweis auf ein in MS09-044 beschriebenes Problem.
-   Yamata Li von [Palo Alto Networks](http://www.paloaltonetworks.com/) für den Hinweis auf ein in MS09-044 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über den [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos. Weitere Informationen zu verfügbaren Supportoptionen finden Sie auf der [Microsoft-Website „Hilfe und Support“](http://support.microsoft.com/).
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (11. August 2009): Bulletin Summary veröffentlicht.
-   V1.1 (13. August 2009): Die Liste der RDP-Updates für Windows XP Service Pack 2 und Windows XP Service Pack 3 für MS09-044 wurde entsprechend dem Bulletin korrigiert. Die Neustartanforderungen für MS09-037, MS09-042 und MS09-044 wurden geändert.
-   V2.0 (25. August 2009): Für MS09-044 wurde der Downloadlink für RDP-Version 5.2 für Windows XP Service Pack 2 (KB958469) korrigiert. Außerdem wurde die Fußnote korrigiert, in der eine falsche Installationsreihenfolge für KB958471 und KB958470 vorgeschrieben wurde. Benutzer, die diese Updates erfolgreich installiert haben, müssen sie nicht erneut installieren.
-   V3.0 (8. September 2009): Microsoft hat MS09-037 erneut veröffentlicht, um neue Updates für das ActiveX-Steuerelement HtmlInput-Objekt unter Windows XP Media Center Edition 2005 und alle unterstützten Editionen von Windows Vista anzubieten.
-   V4.0 (27. Oktober 2009): Microsoft hat MS09-043 erneut veröffentlicht, um das Update für Microsoft Office 2003 Service Pack 3 und Microsoft Office 2003 Web Components Service Pack 3 zur Behebung eines Erkennungsproblems erneut anzubieten. Dies ist lediglich eine Erkennungsänderung. Die Binärdateien wurden nicht verändert. Benutzer, die ihre Systeme erfolgreich aktualisiert haben, müssen dieses Update nicht erneut installieren.

*Built at 2014-04-18T01:50:00Z-07:00*
