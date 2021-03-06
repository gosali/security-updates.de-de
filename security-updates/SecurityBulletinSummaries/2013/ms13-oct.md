---
TOCTitle: 'MS13-OCT'
Title: Microsoft Security Bulletin Summary für Oktober 2013
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61225125
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms13-oct(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Oktober 2013
====================================================

Veröffentlicht: Dienstag, 8. Oktober 2013 | Aktualisiert: Mittwoch, 6. November 2013

**Version:** 1.2

In diesem Bulletin Summary sind die im Oktober 2013 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Security Bulletins für Oktober 2013 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 3. Oktober 2013 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Am Mittwoch, dem 9. Oktober 2013, um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im Oktober.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software**.

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Kennung des Bulletins</th>
<th style="border:1px solid black;" >Titel des Bulletins und Kurzzusammenfassung</th>
<th style="border:1px solid black;" >Bewertung des maximalen Schweregrads und Sicherheitsauswirkung</th>
<th style="border:1px solid black;" >Neustartanforderung</th>
<th style="border:1px solid black;" >Betroffene Software</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (2879017)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich und acht vertraulich gemeldete Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendsten Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der die schwerwiegendste dieser Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Windows-Kernelmodustreibern können Remotecodeausführung ermöglichen (2870008)</strong><br />
<br />
Dieses Sicherheitsupdate behebt sieben vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer freigegebene Inhalte anzeigt, in die OpenType- oder TrueType-Schriftartdateien eingebettet sind. Nutzt ein Angreifer diese Sicherheitsanfälligkeiten erfolgreich aus, kann er vollständige Kontrolle über ein betroffenes System erlangen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in .NET Framework können Remotecodeausführung ermöglichen (2878890)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten und eine öffentlich gemeldete Sicherheitsanfälligkeit in Microsoft .NET Framework. Die schwerwiegendste der Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer mithilfe eines Browsers, der XBAP-Anwendungen instanziieren kann, eine Website mit einer speziell gestalteten OTF-Datei (OpenType Font) besucht.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in der Bibliothek der allgemeinen Windows-Steuerelemente kann Remotecodeausführung ermöglichen (2864058)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete Webanforderung an eine ASP.NET-Webanwendung sendet, die auf einem betroffenen System ausgeführt wird. Ein Angreifer kann diese Sicherheitsanfälligkeit ohne Authentifizierung ausnutzen, um beliebigen Code auszuführen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft SharePoint Server können Remotecodeausführung ermöglichen (2885089)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office Server-Software. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Office-Datei in einer betroffenen Version von Microsoft SharePoint Server, Microsoft Office-Diensten oder Web Apps öffnet.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Excel können Remotecodeausführung ermöglichen (2885080)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Office-Datei mit einer betroffenen Version von Microsoft Excel oder anderer betroffener Microsoft Office-Software öffnet. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Word können Remotecodeausführung ermöglichen (2885084)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn eine speziell gestaltete Datei in einer betroffenen Version von Microsoft Word oder anderer betroffener Microsoft Office-Software geöffnet wird. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Silverlight kann Offenlegung von Information ermöglichen (2890788)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Silverlight. Die Sicherheitsanfälligkeit kann Offenlegung von Informationen ermöglichen, wenn ein Angreifer eine Website mit einer speziell gestalteten Silverlight-Anwendung hostet, mit der diese Sicherheitsanfälligkeit ausgenutzt werden kann, und dann einen Benutzer zum Anzeigen der Website verleitet. Der Angreifer kann auch beeinträchtigte Websites und Websites nutzen, die von Benutzern bereitgestellte Inhalte oder Anzeigen akzeptieren oder hosten. Solche Websites können speziell gestaltete Inhalte enthalten, mit denen diese Sicherheitsanfälligkeit ausgenutzt werden kann. Ein Angreifer kann Benutzer jedoch nicht zum Besuch einer solchen Website zwingen. Er muss den Benutzer zum Besuch einer Webseite verleiten. Zu diesem Zweck wird der Benutzer normalerweise dazu gebracht, in einer E-Mail oder einer Instant Messenger-Nachricht auf einen Link zur Website des Angreifers zu klicken. Es besteht ebenfalls die Möglichkeit, speziell gestalteten Webinhalt mithilfe von Bannerwerbungen anzuzeigen oder Webinhalt auf andere Weise an betroffene Systeme zu übermitteln.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Kein Neustart erforderlich.</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Nur Sicherheitsanfälligkeiten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde, sind enthalten.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).
  
In den unten stehenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Kennung des Bulletins</th>
<th style="border:1px solid black;" >Titel der Sicherheitsanfälligkeit</th>
<th style="border:1px solid black;" >CVE-ID</th>
<th style="border:1px solid black;" >Bewertung der Ausnutzbarkeit für aktuelle Softwareversionen</th>
<th style="border:1px solid black;" >Bewertung der Ausnutzbarkeit für ältere Softwareversionen</th>
<th style="border:1px solid black;" >Bewertung der Ausnutzbarkeit durch Denial-of-Service</th>
<th style="border:1px solid black;" >Wichtige Hinweise</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit wurde öffentlich gemeldet.<br />
<br />
Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit in Internet Explorer 8 und Internet Explorer 9 auszunutzen.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit in Internet Explorer 8 auszunutzen.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit betrifft auch <a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows USB-Beschreibung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit durch Win32k-Verwendung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Erhöhung von Berechtigungen im App-Container</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Vorläufig</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit durch Offenlegung von Informationen, die eine Erhöhung von Berechtigungen ermöglichen kann.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k bezüglich leerer Seite</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit im Kernel-Subsystem von DirectX Graphics durch doppelten Abruf</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich TrueType-Schriftart in CMAP-Tabelle</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit betrifft auch <a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Entity Expansion</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Es handelt sich bei dieser Sicherheitsanfälligkeit um einen Denial-of-Service-Angriff.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von JSON</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Es handelt sich bei dieser Sicherheitsanfälligkeit um einen Denial-of-Service-Angriff.<br />
<br />
Diese Sicherheitsanfälligkeit wurde öffentlich gemeldet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Comctl32 bezüglich Ganzzahlüberlaufs</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Excel bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit betrifft auch <a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Parametereinschleusung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Excel bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit betrifft auch <a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Excel bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Silverlight</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit durch Offenlegung von Informationen, die zur Umgehung der Sicherheitsfunktion führen kann.</td>
</tr>
</tbody>
</table>
  
Betroffene Software  
-------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
**Wie verwende ich diese Tabellen?**  
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Bewertung des Schweregrads des Softwareupdates ebenfalls aufgeführt.
  
**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
#### Systemkomponenten des Windows-Betriebssystems

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5" style="border:1px solid black;">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
(Kritisch)  
Internet Explorer 7  
(2879017)  
(Kritisch)  
Internet Explorer 8  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2847311)  
(Kritisch)  
Windows XP Service Pack 3  
(2862330)  
(Hoch)  
Windows XP Service Pack 3  
(2862335)  
(Hoch)  
Windows XP Service Pack 3  
(2868038)  
(Hoch)  
Windows XP Service Pack 3  
(2883150)  
(Kritisch)  
Windows XP Service Pack 3  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
(Kritisch)  
Internet Explorer 7  
(2879017)  
(Kritisch)  
Internet Explorer 8  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2847311)  
(Kritisch)  
Windows XP Professional x64 Edition Service Pack 2  
(2862330)  
(Hoch)  
Windows XP Professional x64 Edition Service Pack 2  
(2862335)  
(Hoch)  
Windows XP Professional x64 Edition Service Pack 2  
(2868038)  
(Hoch)  
Windows XP Professional x64 Edition Service Pack 2  
(2883150)  
(Kritisch)  
Windows XP Professional x64 Edition Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des** **Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
(Mittel)  
Internet Explorer 7  
(2879017)  
(Mittel)  
Internet Explorer 8  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2847311)  
(Kritisch)  
Windows Server 2003 Service Pack 2  
(2862330)  
(Hoch)  
Windows Server 2003 Service Pack 2  
(2862335)  
(Hoch)  
Windows Server 2003 Service Pack 2  
(2868038)  
(Hoch)  
Windows Server 2003 Service Pack 2  
(2883150)  
(Kritisch)  
Windows Server 2003 Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
(Mittel)  
Internet Explorer 7  
(2879017)  
(Mittel)  
Internet Explorer 8  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2847311)  
(Kritisch)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862330)  
(Hoch)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862335)  
(Hoch)  
Windows Server 2003 x64 Edition Service Pack 2  
(2868038)  
(Hoch)  
Windows Server 2003 x64 Edition Service Pack 2  
(2883150)  
(Kritisch)  
Windows Server 2003 x64 Edition Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
(Mittel)  
Internet Explorer 7  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2847311)  
(Kritisch)  
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2862330)  
(Hoch)  
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2862335)  
(Hoch)  
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2868038)  
(Hoch)  
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2883150)  
(Kritisch)  
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Hoch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Kritisch)  
Internet Explorer 8  
(2879017)  
(Kritisch)  
Internet Explorer 9  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2847311)  
(Kritisch)  
Windows Vista Service Pack 2  
(2855844)  
(Kritisch)  
Windows Vista Service Pack 2  
(2862330)  
(Hoch)  
Windows Vista Service Pack 2  
(2862335)  
(Hoch)  
Windows Vista Service Pack 2  
(2864202)  
(Hoch)  
Windows Vista Service Pack 2  
(2868038)  
(Hoch)  
Windows Vista Service Pack 2  
(2876284)  
(Hoch)  
Windows Vista Service Pack 2  
(2883150)  
(Kritisch)  
Windows Vista Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861193)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Kritisch)  
Internet Explorer 8  
(2879017)  
(Kritisch)  
Internet Explorer 9  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2847311)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(2855844)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(2862330)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(2862335)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(2864202)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(2868038)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(2876284)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(2883150)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861193)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Mittel)  
Internet Explorer 8  
(2879017)  
(Mittel)  
Internet Explorer 9  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2847311)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2855844)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2862330)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2862335)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2864202)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2868038)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2876284)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2883150)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861193)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Mittel)  
Internet Explorer 8  
(2879017)  
(Mittel)  
Internet Explorer 9  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2847311)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2855844)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2862330)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2862335)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2864202)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2868038)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2876284)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2883150)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4  
(2861188)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861193)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2864058)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2847311)  
(Kritisch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2862330)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2862335)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2864202)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2868038)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2876284)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2883150)  
(Kritisch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Hoch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Kritisch)  
Internet Explorer 9  
(2879017)  
(Kritisch)  
Internet Explorer 10  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2847311)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2855844)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2862330)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2862335)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2864202)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2868038)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2876284)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2883150)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Kritisch)  
Internet Explorer 9  
(2879017)  
(Kritisch)  
Internet Explorer 10  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2847311)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2855844)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2862330)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2862335)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2864202)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2868038)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2876284)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2883150)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Mittel)  
Internet Explorer 9  
(2879017)  
(Mittel)  
Internet Explorer 10  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2847311)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2855844)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2862330)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2862335)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2864202)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2868038)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2876284)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2883150)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2864058)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2847311)  
(Kritisch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2855844)  
(Kritisch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2862330)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2862335)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2864202)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2868038)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2876284)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2883150)  
(Kritisch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2847311)  
(Kritisch)  
Windows 8 für 32-Bit-Systeme  
(2862330)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(2862335)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(2863725)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(2864202)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(2868038)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(2883150)  
(Kritisch)  
Windows 8 für 32-Bit-Systeme  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2861704)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2863243)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861702)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2847311)  
(Kritisch)  
Windows 8 für 64-Bit-Systeme  
(2862330)  
(Hoch)  
Windows 8 für 64-Bit-Systeme  
(2862335)  
(Hoch)  
Windows 8 für 64-Bit-Systeme  
(2863725)  
(Hoch)  
Windows 8 für 64-Bit-Systeme  
(2864202)  
(Hoch)  
Windows 8 für 64-Bit-Systeme  
(2868038)  
(Hoch)  
Windows 8 für 64-Bit-Systeme  
(2883150)  
(Kritisch)  
Windows 8 für 64-Bit-Systeme  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2861704)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2863243)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861702)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(Kritisch)  
Windows Server 2012  
(2862330)  
(Hoch)  
Windows Server 2012  
(2862335)  
(Hoch)  
Windows Server 2012  
(2863725)  
(Hoch)  
Windows Server 2012  
(2864202)  
(Hoch)  
Windows Server 2012  
(2868038)  
(Hoch)  
Windows Server 2012  
(2883150)  
(Kritisch)  
Windows Server 2012  
(2884256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2861704)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2863243)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861702)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(Kritisch)  
Windows RT  
(2862330)  
(Hoch)  
Windows RT  
(2862335)  
(Hoch)  
Windows RT  
(2863725)  
(Hoch)  
Windows RT  
(2864202)  
(Hoch)  
Windows RT  
(2868038)  
(Hoch)  
Windows RT  
(2883150)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>
(Kritisch)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1 für 64-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>
(Kritisch)
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
<th colspan="5" style="border:1px solid black;">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>
(Mittel)
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
<th colspan="5" style="border:1px solid black;">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>
(Kritisch)
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
<th colspan="5" style="border:1px solid black;">
Server Core-Installationsoption
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung** **des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2847311)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2862330)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2862335)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2864202)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2876284)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2883150)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2864058)  
(Keine Bewertung des Schweregrads)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2847311)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2862330)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2862335)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2864202)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2876284)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2883150)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2847311)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2862330)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2862335)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2864202)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2876284)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2883150)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Hoch)  
Microsoft .NET Framework 4  
(2858302)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861208)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2864058)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(2847311)  
(Kritisch)  
Windows Server 2012 (Server Core-Installation)  
(2862330)  
(Hoch)  
Windows Server 2012 (Server Core-Installation)  
(2862335)  
(Hoch)  
Windows Server 2012 (Server Core-Installation)  
(2863725)  
(Hoch)  
Windows Server 2012 (Server Core-Installation)  
(2864202)  
(Hoch)  
Windows Server 2012 (Server Core-Installation)  
(2883150)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2861704)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2863243)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2861702)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(2864058)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)
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
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für MS13-080**

<sup>[1]</sup>Für Internet Explorer 11 müssen Benutzer das Update-Rollup für Windows RT 8.1, Windows 8.1 und Windows Server 2012 R2 übernehmen: Oktober 2013 (2883200). Das Update-Rollup 2883200 enthält sowohl sicherheitsrelevante als auch nicht sicherheitsrelevante Änderungen. Weitere Informationen und verfügbare Downloadadressen finden Sie im [Microsoft Knowledge Base-Artikel 2883200](http://support.microsoft.com/kb/2883200).

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2826020)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2827324)  
(Hoch)  
Microsoft Office 2007 Service Pack 3  
(2760585)  
(Hoch)  
Microsoft Office 2007 Service Pack 3  
(2760591)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2827330)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (32-Bit-Editionen)  
(2826033)  
(Hoch)  
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)  
(2826023)  
(Hoch)  
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)  
(2826035)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (64-Bit-Editionen)  
(2826033)  
(Hoch)  
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)  
(2826023)  
(Hoch)  
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)  
(2826035)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32-Bit-Editionen)  
(2826033)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(2826023)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(2826035)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64-Bit-Editionen)  
(2826033)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(2826023)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(2826035)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32-Bit-Editionen)  
(2827238)  
(Hoch)  
Microsoft Office 2013 (32-Bit-Editionen)  
(2817623)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64-Bit-Editionen)  
(2827238)  
(Hoch)  
Microsoft Office 2013 (64-Bit-Editionen)  
(2817623)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2827238)  
(Hoch)  
Microsoft Office 2013 RT  
(2817623)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office für Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office für Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011  
(2889496)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Andere Microsoft Office-Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2827326)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2827329)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 

#### Microsoft Server Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (32-Bit-Versionen)  
(2596741)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (64-Bit-Versionen)  
(2596741)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wssloc)  
(2589365)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2589365)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für MS13-084**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Office-Dienste und Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(Hoch)  
Word-Automatisierungsdienste  
(2826022)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(Hoch)  
Word-Automatisierungsdienste  
(2826022)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Excel Services  
(2752002)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word-Automatisierungsdienste  
(2826036)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2826030)  
(Hoch)  
Microsoft Excel Web App 2010 Service Pack 1  
(2826028)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2826030)  
(Hoch)  
Microsoft Excel Web App 2010 Service Pack 2  
(2826028)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für MS13-084**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Entwicklertools und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-087**](http://go.microsoft.com/fwlink/?linkid=324590)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 bei Installation auf dem Mac  
(2890788)  
(Hoch)  
Microsoft Silverlight 5 Developer Runtime bei Installation auf dem Mac  
(2890788)  
(Hoch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(2890788)  
(Hoch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(2890788)  
(Hoch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(2890788)  
(Hoch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(2890788)  
(Hoch)
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

Es stehen mehrere Ressourcen zur Verfügung, um Administratoren bei der Bereitstellung von Sicherheitsupdates zu helfen.

-   Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter.
-   Windows-Server Update Services (WSUS), Systems Management Server (SMS) und System Center Configuration Manager helfen Administratoren beim Verteilen von Sicherheitsupdates.
-   Die im Anwendungskompatibilitäts-Toolkit enthaltenen Komponenten zur Updatekompatibilitätsbewertung helfen dabei, die Vereinbarkeit von Windows-Updates mit installierten Anwendungen zu testen und zu überprüfen.

Weitere Informationen zu diesen und weiteren verfügbaren Tools finden Sie unter [Sicherheitstools](http://technet.microsoft.com/de-de/security/cc297183).

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Für die Veröffentlichung des Bulletins, die am zweiten Dienstag jedes Monats stattfindet, hat Microsoft eine aktualisierte Version des Microsofts Windows-Tool zum Entfernen schädlicher Software in Windows Update, Microsoft Update, den Windows Server Update Services und dem Download Center veröffentlicht. Für außerplanmäßige Veröffentlichungen des Security Bulletins ist keine aktualisierte Version des Microsoft Windows-Tool zum Entfernen schädlicher Software erhältlich.

#### Nicht sicherheitsrelevante Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199/de): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/de-de/windowsserver/bb332157.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

#### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://go.microsoft.com/fwlink/?linkid=215201) aufgeführt sind.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Patchmanagement](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086/de).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://technet.microsoft.com/de-de/security/cc136632.aspx) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

**MS13-080**

-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3872).
-   Jose A. Vazquez von Yenteasy -Security Research in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3873).
-   Amol Naik in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3874).
-   Einer Person, die mit [VeriSign iDefense Labs](http://labs.idefense.com) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3874).
-   Jose A. Vazquez von Yenteasy –Security Research in Zusammenarbeit mit [VeriSign iDefense Labs](http://labs.idefense.com) für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3875).
-   Ivan Fratric vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3882).
-   Jose A. Vazquez von Yenteasy – Security Research für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3882).
-   Jose A. Vazquez von Yenteasy – Security Research für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3885).
-   Jose A. Vazquez von Yenteasy –Security Research in Zusammenarbeit mit [VeriSign iDefense Labs](http://labs.idefense.com) für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3886).
-   Yoshihiro Ishikawa von [LAC Co.](http://www.lac.co.jp/) für die Zusammenarbeit mit uns an der Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3893).
-   Hoodie22 in Zusammenarbeit mit dem National Cyber Security Centre der Niederlande für die Zusammenarbeit mit uns an der Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3897).
-   Daniel Chechik vom Trustwave SpiderLabs Team für die Zusammenarbeit mit uns an der Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3897).
-   Renato Ettisberger von der [IOprotect GmbH](http://ioprotect.ch/) für die Zusammenarbeit mit uns an der Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3897).

**MS13-081**

-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten (CVE-2013-3128).
-   Andy Davis von der [NCC Group](http://www.nccgroup.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Windows USB-Beschreibung (CVE-2013-3200).
-   Lucas Bouillot von ANSSI für den Hinweis auf die Sicherheitsanfälligkeit in Windows USB-Beschreibung (CVE-2013-3200).
-   Seth Gibson und Dan Zentner von [Endgame](http://www.endgame.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k bezüglich leerer Seite (CVE-2013-3881).
-   ZombiE, in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich TrueType-Schriftart in CMAP-Tabelle (CVE-2013-3895).

**MS13-082**

-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten (CVE-2013-3128).
-   James Forshaw von [Context Information Security](http://www.contextis.com/) für den Hinweis auf die Sicherheitsanfälligkeit durch Entity Expansion (CVE-2013-3860).

**MS13-083**

-   孙晓山 für den Hinweis auf die Sicherheitsanfälligkeit in Comctl32 bezüglich Ganzzahlüberlaufs (CVE-2013-3195).

**MS13-084**

-   Mateusz Jurczyk, Ivan Fratric und Ben Habichte vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Microsoft Excel bezüglich Speicherbeschädigung (CVE-2013-3889).
-   Nutan kumar panda für den Hinweis auf die Sicherheitsanfälligkeit durch Parametereinschleusung (CVE-2013-3895).
-   Ari Elias-Bachrach und Angela Kelso von den [National Institutes of Health](http://nih.gov/) für die Zusammenarbeit mit uns an den in diesem Bulletin enthaltenen Tiefenverteidigungsänderungen.

**MS13-085**

-   Mateusz Jurczyk, Ivan Fratric und Ben Habichte vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Microsoft Excel bezüglich Speicherbeschädigung (CVE-2013-3889).
-   Mateusz Jurczyk, Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Microsoft Excel bezüglich Speicherbeschädigung (CVE-2013-3890).

**MS13-086**

-   Yuhong Bao für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung (CVE-2013-3891).
-   Mateusz Jurczyk, Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung (CVE-2013-3892).

**MS13-087**

-   Vitaliy Toropov für den Hinweis auf die Sicherheitsanfälligkeit in Silverlight (CVE-2013-3896).

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Sicherheitslösungen für IT-Experten: [TechNet Sicherheit – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)
-   So schützen Sie Ihren Computer, auf dem Windows ausgeführt wird, vor Viren und schädlicher Software: [Viruslösung und Security Center](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx)

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (8. Oktober 2013): Bulletin Summary veröffentlicht.
-   V1.1 (10. Oktober 2013): In MS13-080 wurde die Bewertung der Ausnutzbarkeit im Ausnutzbarkeitsindex für CVE-2013-3871 entfernt. Bei der Beinhaltung dieses CVE im ursprünglichen Ausnutzbarkeitsindex handelte es sich um einen Dokumentationsfehler. CVE-2013-3871 wird in einem zukünftigen Security Bulletin behoben. Dies ist lediglich eine Informationsänderung. In MS13-082 wurde das Bulletin überarbeitet, um anzuzeigen, dass Server Core-Installationen von Windows Server 2012 von der im Update 2861194 behobenen Sicherheitsanfälligkeit betroffen sind. Es wurden keine Änderungen an der Erkennungslogik oder an den Sicherheitsupdatedateien vorgenommen. Benutzer, die ihre Systeme bereits erfolgreich aktualisiert haben, müssen keine Maßnahmen ergreifen.
-   V1.2 (6. November 2013): In MS13-084 wurde der Produktname für das Update für den Microsoft Office Web Apps Server 2013 (2827222) korrigiert.

*Built at 2014-04-18T01:50:00Z-07:00*
