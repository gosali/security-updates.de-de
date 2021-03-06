---
TOCTitle: 'MS10-FEB'
Title: Microsoft Security Bulletin Summary für Februar 2010
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61225082
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms10-feb(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Februar 2010
====================================================

Veröffentlicht: Dienstag, 9. Februar 2010 | Aktualisiert: Mittwoch, 10. Februar 2010

**Version:** 1.1

In diesem Bulletin Summary sind die im Februar 2010 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für Februar 2010 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 4. Februar 2010 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 10. Februar 2010 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für den Security Bulletin-Webcast im Februar](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us). Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/aktuell/default.mspx)

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178850">MS10-006</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in SMB können Remotecodeausführung ermöglichen (978251)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete SMB-Antwort auf eine vom Client initiierte SMB-Anforderung sendet. Um diese Sicherheitsanfälligkeiten auszunutzen, muss ein Angreifer den Benutzer dazu verleiten, eine SMB-Verbindung zu einem schädlichen SMB-Server zu initiieren.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179067">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Windows Shell kann Remotecodeausführung ermöglichen (975713)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows 2000, Windows XP und Windows Server 2003. Andere Versionen von Windows sind nicht von diesem Sicherheitsupdate betroffen. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn eine Anwendung wie ein Webbrowser speziell gestaltete Daten über den Windows Shell Handler an die ShellExecute API-Funktion übergibt.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179106">MS10-008</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate von ActiveX-Kill Bits (978262)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit für Microsoft-Software. Dieses Sicherheitsupdate wird für alle unterstützten Editionen von Microsoft Windows 2000 und Windows XP als Kritisch eingestuft und als Hoch für alle unterstützten Editionen von Windows Vista und Windows 7, Mittel für alle unterstützten Editionen von Windows Server 2003 und Niedrig für alle unterstützten Editionen von Windows Server 2008 und Windows Server 2008 R2.<br />
<br />
Diese Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite anzeigt, die mit Internet Explorer ein ActiveX-Steuerelement instanziiert. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. Dieses Update beinhaltet außerdem Kill Bits für vier ActiveX-Steuerelemente von Drittanbietern.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Windows TCP/IP können Remotecodeausführung ermöglichen (974145)</strong><br />
<br />
Dieses Sicherheitsupdate behebt vier vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn speziell gestaltete Pakete an einen Computer gesendet werden, auf dem IPv6 aktiviert ist. Ein Angreifer kann versuchen, die Sicherheitsanfälligkeit auszunutzen, indem er speziell gestaltete ICMPv6-Pakete erstellt und diese dann an ein System sendet, auf dem IPv6 aktiviert ist. Diese Sicherheitsanfälligkeit kann nur ausgenutzt werden, wenn der Angreifer on-link ist.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167321">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft DirectShow kann Remotecodeausführung ermöglichen (977935)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft DirectShow. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete AVI-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178812">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Office (MSO) kann Remotecodeausführung ermöglichen (978214)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Office, die Remotecodeausführung ermöglichen kann, wenn ein Benutzer eine speziell gestaltete Office-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Office PowerPoint können Remotecodeausführung ermöglichen (975416)</strong><br />
<br />
Dieses Sicherheitsupdate behebt sechs vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office PowerPoint. Die Sicherheitsanfälligkeiten können eine Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete PowerPoint-Datei öffnet. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179066">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Windows Server 2008 Hyper-V kann Denial-of-Service ermöglichen (977894)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Windows Server 2008 Hyper-V und Windows Server 2008 R2 Hyper-V. Die Sicherheitsanfälligkeit kann Denial-of-Service ermöglichen, wenn von einem authentifizierten Benutzer eine fehlerhafte Sequenz von Computeranweisungen auf einem der virtuellen Gastcomputer ausgeführt wird, die vom Hyper-V Server gehostet werden. Ein Angreifer benötigt gültige Anmeldeinformationen und muss sich lokal bei einem virtuellen Gastcomputer anmelden können, um diese Sicherheitsanfälligkeit auszunutzen. Die Sicherheitsanfälligkeit kann nicht per Remotezugriff oder von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179798">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im Windows Client/Server-Runtime-Subsystem kann Erhöhung von Berechtigungen ermöglichen (978037)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Microsoft Windows Client/Server-Runtime-Subsystem (CSRSS) in Microsoft Windows 2000, Windows XP und Windows Server 2003. Andere Versionen von Windows sind nicht betroffen. Die Sicherheitsanfälligkeit kann Erhöhung von Berechtigungen ermöglichen, wenn ein Angreifer sich beim System anmeldet und eine speziell gestaltete Anwendung startet, die dafür entwickelt wurde, weiter ausgeführt zu werden, nachdem der Angreifer sich wieder abgemeldet hat. Ein Angreifer benötigt gültige Anmeldeinformationen und muss sich lokal anmelden können, um diese Sicherheitsanfälligkeit auszunutzen. Die Sicherheitsanfälligkeit kann nicht von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in SMB-Server können Remotecodeausführung ermöglichen (971468)</strong><br />
<br />
Dieses Sicherheitsupdate behebt mehrere vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Angreifer ein speziell gestaltetes SMB-Paket erstellt und das Paket an ein betroffenes System sendet. Mithilfe empfohlener Vorgehensweisen für die Firewall und standardisierten Firewallkonfigurationen können Netzwerke vor Remoteangriffen von außerhalb des Unternehmens geschützt werden, mit denen versucht wird, diese Sicherheitsanfälligkeiten auszunutzen.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=181196">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Kerberos kann zu einem Denial-of-Service-Angriff führen (977290)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann einen Denial-of-Service ermöglichen, wenn eine speziell gestaltete Ticketerneuerungsanforderung von einem authentifizierten Benutzer in einem vertrauenswürdigen Nicht-Windows-Kerberos-Bereich an die Windows-Kerberos-Domäne gesendet wird. Der Denial-of-Service kann bestehen bleiben, bis der Domänencontroller neu gestartet wird.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten im Windows-Kernel können Erhöhung von Berechtigungen ermöglichen (977165)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich und eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Diese Sicherheitsanfälligkeiten können eine Erhöhung von Berechtigungen ermöglichen, wenn sich ein Angreifer bei dem System anmeldet und eine speziell gestaltete Anwendung ausführt. Um eine dieser Sicherheitsanfälligkeit auszunutzen, muss ein Angreifer über gültige Anmeldeinformationen verfügen und sich lokal anmelden können. Die Sicherheitsanfälligkeiten können nicht per Remotezugriff oder von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=180620">MS10- 005</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Paint kann Remotecodeausführung ermöglichen (978706)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Paint. Diese Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete JPEG-Bilddatei mit Microsoft Paint anzeigt. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Mittel</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach absteigender Bewertung der Ausnutzbarkeit und dann CVE ID aufgeführt.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259.aspx).
  
| Kennung des Bulletins                                      | Titel der Sicherheitsanfälligkeit                                                                                | CVE-ID                                                                            | Ausnutzbarkeitsindex – Bewertung                                                                                     | Wichtige Hinweise                                                                                 |  
|------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|  
| [MS10-006](http://go.microsoft.com/fwlink/?linkid=178850)  | Sicherheitsanfälligkeit im SMB-Client aufgrund einer Racebedingung                                               | [CVE-2010-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Eine Remoteangriffsmethode kann DOS ermöglichen; eine lokale Angriffsmethode kann EoP ermöglichen |  
| [MS10-011](http://go.microsoft.com/fwlink/?linkid=179798)  | Sicherheitsanfälligkeit in CSRSS bezüglich der lokalen Erhöhung von Berechtigungen                               | [CVE-2010-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Angreifer und Opfer müssen sich bei der gleichen Konsole anmelden                                 |  
| [MS10-007](http://go.microsoft.com/fwlink/?linkid=179067)  | Sicherheitsanfälligkeit bezüglich URL-Überprüfung                                                                | [CVE-2010-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Sicherheitsanfälligkeit bezüglich Heapüberlaufs und LinkedSlideAtom in PowerPoint                                | [CVE-2010-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Sicherheitsanfälligkeit bezüglich ungültiger Arrayindizierung, OEPlaceholderAtom und „placementId“ in PowerPoint | [CVE-2010-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Use-after-Free-Sicherheitsanfälligkeit bezüglich OEPlaceholderAtom in PowerPoint                                 | [CVE-2010-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Sicherheitsanfälligkeit bezüglich Datensatz-Stapelüberlaufs und TextBytesAtom in PowerPoint Viewer               | [CVE-2010-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Sicherheitsanfälligkeit betrifft nur PowerPoint Viewer 2003                                       |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Sicherheitsanfälligkeit bezüglich Datensatz-Stapelüberlaufs und TextCharsAtom in Office PowerPoint Viewer        | [CVE-2010-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Sicherheitsanfälligkeit betrifft nur PowerPoint Viewer 2003                                       |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976)  | Sicherheitsanfälligkeit in SMB bezüglich Entropiemangels bei NTLM-Authentifizierung                              | [CVE-2010-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-015](http://go.microsoft.com/fwlink/?linkid=179062)  | Sicherheitsanfälligkeit im Windows-Kernel bezüglich Ausnahmehandler                                              | [CVE-2010-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-003](http://go.microsoft.com/fwlink/?linkid=178812)  | Sicherheitsanfälligkeit durch Pufferüberlauf in MSO.DLL                                                          | [CVE-2010-0243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-013](http://go.microsoft.com/fwlink/?linkid=167321)  | Sicherheitsanfälligkeit in DirectShow bezüglich Heapüberlaufs                                                    | [CVE-2010-0250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250)  | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                           |  
| [MS10-006](http://go.microsoft.com/fwlink/?linkid=178850)  | Sicherheitsanfälligkeit im SMB-Client aufgrund von Poolbeschädigung                                              | [CVE-2010-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                           |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976)  | Sicherheitsanfälligkeit in SMB bezüglich Überlaufs bei Pfadname                                                  | [CVE-2010-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                           |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976)  | Sicherheitsanfälligkeit in SMB bezüglich Speicherbeschädigung                                                    | [CVE-2010-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                           |  
| [MS10- 005](http://go.microsoft.com/fwlink/?linkid=180620) | Sicherheitsanfälligkeit in MS Paint bezüglich Ganzzahlüberlaufs                                                  | [CVE-2010-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Erfolgreiche Ausnutzung erfordert erheblichen Benutzereingriff                                    |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639)  | Sicherheitsanfälligkeit durch Pufferüberlauf bei Dateipfadverarbeitung durch PowerPoint                          | [CVE-2010-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                           |  
| [MS10-015](http://go.microsoft.com/fwlink/?linkid=179062)  | „Double Free“-Sicherheitsanfälligkeit im Windows-Kernel                                                          | [CVE-2010-0233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                           |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190)  | Sicherheitsanfälligkeit in ICMPv6 bezüglich Routerankündigung                                                    | [CVE-2010-0239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Ausnutzung erfordert vom Angreifer, mit dem Ziel-Host on-link zu sein                             |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190)  | Sicherheitsanfälligkeit im Header bezüglich MDL-Fragmentierung                                                   | [CVE-2010-0240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Sicherheitsanfälligkeit erfordert einen Drittanbieter-Netzwerktreiber                             |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190)  | Sicherheitsanfälligkeit in ICMPv6 bezüglich Routeninformationen                                                  | [CVE-2010-0241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241)  | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Ausnutzung erfordert vom Angreifer, mit dem Ziel-Host on-link zu sein                             |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976)  | Sicherheitsanfälligkeit in SMB bezüglich Nullzeigers                                                             | [CVE-2010-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022)  | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | (Keine)                                                                                           |  
| [MS10-010](http://go.microsoft.com/fwlink/?linkid=179066)  | Sicherheitsanfälligkeit in Hyper-V bezüglich Überprüfung des Instruktionssatzes                                  | [CVE-2010-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026)  | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Sicherheitsanfälligkeit ermöglicht nur-DoS-Bedingung                                              |  
| [MS10-014](http://go.microsoft.com/fwlink/?linkid=181196)  | Sicherheitsanfälligkeit in Kerberos bezüglich Null-Zeigerdereferenzierung                                        | [CVE-2010- 0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035) | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Nur DoS; Ausnutzung nur auf Domänencontrollern in nicht standardmäßigen Konfigurationen möglich   |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190)  | Sicherheitsanfälligkeit in TCP/IP bezüglich selektiver Bestätigung                                               | [CVE-2010-0242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242)  | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | (Keine)                                                                                           |
  
Betroffene Software und Downloadadressen  
----------------------------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
**Wie verwende ich diese Tabellen?**  
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.
  
**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
Keine
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3&displaylang=de)  
(KB977914)  
(Kritisch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146&displaylang=de)  
(KB975560)  
(Kritisch)  
[Quartz in DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b&displaylang=de)<sup>[1]</sup>  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4:](http://www.microsoft.com/downloads/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e5861705-8f49-45cb-8a92-cf052ccf4134)  
(Mittel)
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
Keine
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 und Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f6c4472e-385c-4412-bda9-c2e615e50713)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb&displaylang=de)  
(KB977914)  
(Kritisch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
(Kritisch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
(Mittel)
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204&displaylang=de)  
(KB977914)  
(Kritisch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=90360537-9311-45e2-8047-9a971f90c3c3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f)  
(KB977914)  
(Kritisch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a)  
(Mittel)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[AVI-Filter](http://www.microsoft.com/downloads/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764&displaylang=de)  
(KB977914)  
(Hoch)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f&displaylang=de)  
(KB975560)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
(Mittel)
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
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
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3&displaylang=de)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5&displaylang=de)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Niedrig**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=09e19263-18ba-495e-bcf7-719e957204a7)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c)\*\*  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8&displaylang=de)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47&displaylang=de)\*\*  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fde218c3-90ab-4664-852d-25ca55835054)\*\*  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0&displaylang=de)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10&displaylang=de)\*\*  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7&displaylang=de)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717&displaylang=de)  
(KB975560)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
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
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b3265576-04c1-48b1-8ce9-128843c58cf5)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb&displaylang=de)  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Niedrig**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=cda31c54-8b81-4185-a623-64480ad4b73c)\*\*  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891&displaylang=de)\*\*  
(KB975560)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=3214b347-d901-4aac-85ce-676e4602de87&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9&displaylang=de)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=badd6cab-7738-4401-a68c-c15414388601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68&displaylang=de)  
(KB975560)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e&displaylang=de)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für MS10-013**

<sup>[1]</sup>Das Update für DirectX 9.0 gilt auch für DirectX 9.0a, DirectX 9.0b und DirectX 9.0c unter Microsoft Windows 2000.

**Hinweise für Windows Server 2008 und Windows Server 2008 R2**

**\*Die Server Core-Installation ist betroffen.** Dieses Update gilt, mit der gleichen Bewertung des Schweregrads, wie angezeigt auch für unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2, unabhängig davon, ob bei der Installation die Server Core-Installationsoption verwendet wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

**\*\*Die Server Core-Installation ist nicht betroffen.** Die durch dieses Update behobenen Sicherheitsanfälligkeiten betreffen unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2 wie angegeben nicht, wenn diese mit der Server Core-Installationsoption installiert wurden. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-003**](http://go.microsoft.com/fwlink/?linkid=178812)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://go.microsoft.com/fwlink/?linkid=163639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office für Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-003**](http://go.microsoft.com/fwlink/?linkid=178812)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://go.microsoft.com/fwlink/?linkid=163639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 für Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=47553f45-fa10-40e5-8267-9d42ff560a62)<sup>[1]</sup>  
(KB979674)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=47553f45-fa10-40e5-8267-9d42ff560a62)<sup>[1]</sup>  
(KB979674)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für Microsoft Office für Mac**

<sup>[1]</sup>Aufgrund des kumulativen Wartungsmodells für Microsoft Office 2004 für Mac sind diese Updates identisch.

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Sicherheits-Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) und [Windows-Update](http://go.microsoft.com/fwlink/?linkid=21130) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Hinweis:** Am 1. August 2009 hat Microsoft den Support für Office Update und das Inventurprogramm für Office-Update eingestellt. Verwenden Sie [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), um weiterhin die aktuellen Updates für Microsoft Office-Produkte zu erhalten. Weitere Informationen finden Sie in [Informationen zum Microsoft Office Update: Häufig gestellte Fragen (FAQs)](http://office.microsoft.com/de-de/downloads/fx010402221031.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Microsoft stellt Anleitungen zur Erkennung und Bereitstellung von Sicherheitsupdates bereit. Diese Anleitungen enthalten Empfehlungen und Informationen, anhand derer IT-Experten verstehen können, wie die verschiedenen Tools für die Erkennung und Bereitstellung der Sicherheitsupdates verwendet werden. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 961747](http://support.microsoft.com/kb/961747/de).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS) können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Microsoft Windows 2000 und neuere Betriebssysteme, Office XP und höher, Exchange Server 2003 und SQL Server 2000 schnell und sicher bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/de-de/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch das Sicherheitsupdate-Inventurprogramm (SUIT) verwenden, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/systemcenter/sccm/default.mspx).

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können diese Updates mit dem Elevated Rights Deployment Tool (im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) verfügbar) installieren.

**Updatekompatibilitätsbewertung und Microsoft Application Compatibility Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc766043(ws.10).aspx), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199/de): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

#### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx) aufgeführt sind.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Patchmanagement](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086/de).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Damian Frizza von [Core Security Technologies](http://www.coresecurity.com/) für den Hinweis auf ein in MS10-003 beschriebenes Problem.
-   Carsten Eiram von [Secunia](http://secunia.com/) für den Hinweis auf ein in MS10-004 beschriebenes Problem.
-   Sean Larsson von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf zwei in MS10-004 beschriebene Probleme.
-   SkD von [Zero Day Initiative](http://www.zerodayinitiative.com/) von [TippingPoint](http://www.tippingpoint.com/) für den Hinweis auf ein in MS10-004 beschriebenes Problem.
-   Cody Pierce von [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) für den Hinweis auf ein in MS10-004 beschriebenes Problem.
-   Tielei Wang von ICST-ERCIS (Engineering Research Center of Info Security, Institute of Computer Science & Technology, Peking University / China) in Zusammenarbeit mit [Secunia](http://secunia.com/) für den Hinweis auf ein in MS10-005 beschriebenes Problem.
-   Laurent Gaffié von [stratsec](http://www.stratsec.net/) für den Hinweis auf zwei in MS10-006 beschriebene Probleme.
-   Brett Moore, der mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, für den Hinweis auf ein in MS10-007 beschriebenes Problem.
-   [Lostmon Lords](http://lostmon.blogspot.com/) für den Hinweis auf ein in MS10-007 beschriebenes Problem.
-   Shaun Colley von [NGS Software](http://www.ngssoftware.com/) für den Hinweis auf ein in MS10-008 beschriebenes Problem.
-   Sumit Gwalani, Drew Hintz und Neel Mehta vom [Google Security Team](http://www.google.com/) für den Hinweis auf drei in MS10-009 beschriebene Probleme.
-   Jan Bottorff für den Hinweis auf ein in MS10-010 beschriebenes Problem.
-   Matthew 'j00ru' Jurczyk und Gynvael Coldwind von [Hispasec](http://www.hispasec.com/) für den Hinweis auf ein in MS10-011 beschriebenes Problem.
-   Joshua Morin von [Codenomicon](http://www.codenomicon.com/) für den Hinweis auf ein in MS10-012 beschriebenes Problem.
-   Florian Rienhardt von [BSI](http://www.bsi.bund.de/) für den Hinweis auf ein in MS10-012 beschriebenes Problem.
-   Hernan Ochoa (unabhängiger Berater/Forscher im Bereich der Informationssicherheit) für den Hinweis auf ein in MS10-012 beschriebenes Problem
-   Einer Person, die mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS10-013 beschriebenes Problem
-   Tavis Ormandy von [Google Inc.](http://www.google.com/) für den Hinweis auf ein in MS10-015 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über den [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos. Weitere Informationen zu verfügbaren Supportoptionen finden Sie auf der [Microsoft-Website „Hilfe und Support“](http://support.microsoft.com/).
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (9. Februar 2010): Bulletin Summary veröffentlicht.
-   V1.1 (10. Februar 2010): Die Neustartanforderungen für MS10-005 wurden korrigiert.

*Built at 2014-04-18T01:50:00Z-07:00*
