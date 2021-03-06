---
TOCTitle: 'MS13-JUL'
Title: Microsoft Security Bulletin Summary für Juli 2013
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61225120
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms13-jul(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Juli 2013
=================================================

Veröffentlicht: Dienstag, 9. Juli 2013 | Aktualisiert: Dienstag, 27. August 2013

**Version:** 3.0

In diesem Bulletin Summary sind die im Juli 2013 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Security Bulletins für Juli 2013 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 4. Juli 2013 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Am Mittwoch, dem 10. Juli 2013, um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im Juli.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=en-us) Ab diesem Datum steht dieser Webcast [auf Anfrage](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us) zur Verfügung.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in .NET Framework und Silverlight können Remotecodeausführung ermöglichen (2861561)</strong><br />
<br />
Dieses Sicherheitsupdate behebt fünf vertraulich und zwei öffentlich gemeldete Sicherheitsanfälligkeiten in Microsoft .NET Framework und Microsoft Silverlight. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn eine vertrauenswürdige Anwendung ein bestimmtes Codemuster verwendet. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der angemeldete Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten</strong> <strong>in Windows-Kernelmodustreibern können Remotecodeausführung ermöglichen (2850851)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt zwei öffentlich und sechs vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer freigegebene Inhalte anzeigt, in die speziell gestaltete TrueType-Schriftarten eingebettet sind. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in</strong> <strong>GDI+</strong> <strong>kann Remotecodeausführung ermöglichen (2848295)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows, Microsoft Office, Microsoft Lync und Microsoft Visual Studio. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer freigegebene Inhalte anzeigt, in die speziell gestaltete TrueType-Schriftarten eingebettet sind.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft Visual Studio,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (2846071)</strong> <strong><br />
<br />
</strong>Dieses Sicherheitsupdate behebt siebzehn vertraulich gemeldete Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendsten Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der die schwerwiegendste dieser Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft DirectShow kann Remotecodeausführung ermöglichen (2845187)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Bilddatei öffnet. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Endbenutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Windows Media Format kann Remotecodeausführung ermöglichen (2847883)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Mediendatei öffnet. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Endbenutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Windows Defender kann Erhöhung von Berechtigungen ermöglichen (2847927)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Windows Defender für Windows 7 und Windows Defender unter Windows Server 2008 R2. Die Sicherheitsanfälligkeit kann aufgrund der von Windows Defender verwendeten Pfadnamen eine Erhöhung von Berechtigungen ermöglichen. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann beliebigen Code ausführen und vollständige Kontrolle über das betroffene System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Ein Angreifer muss über gültige Anmeldeinformationen verfügen, um diese Sicherheitsanfälligkeit ausnutzen zu können. Die Sicherheitsanfälligkeit kann nicht von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Kein Neustart erforderlich.</td>
<td style="border:1px solid black;">Microsoft Sicherheitssoftware</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Zugriffsverletzung auf Array</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit wurde veröffentlicht.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Umgehung der Stellvertreterreflektion</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Einschleusung anonymer Methoden</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Arrayzuweisung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit wurde veröffentlicht.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Stellvertreterserialisierung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Null-Zeiger</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k bezüglich Speicherzuordnung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k bezüglich Dereferenzierung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit bezüglich Denial-of-Service in der aktuellen Softwareversion.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit bezüglich Denial-of-Service in der aktuellen Softwareversion.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k durch Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit durch Offenlegung von Informationen, die eine Erhöhung von Berechtigungen ermöglichen kann.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k durch Pufferüberschreibung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Win32k-Lese-AVs</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit wurde veröffentlicht.<br />
<br />
Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit zur Erhöhung von Berechtigungen auszunutzen.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit durch Internet Explorer 8 auszunutzen.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Shift JIS bezüglich Zeichencodierung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit, die sich auf die Offenlegung von Informationen bezieht.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in DirectShow bezüglich willkürlichen Überschreibens von Speicher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Vorläufig</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in WMV Videodecoder bezüglich Remotecodeausführung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Vorläufig</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Windows 7 Defender durch fehlerhaften Pfadnamen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
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
<th colspan="8" style="border:1px solid black;">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 Service Pack 3  
(nur Media Center Edition 2005 Service Pack 3 und Tablet PC Edition 2005 Service Pack 3)  
(2833951)  
(Hoch)  
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows XP Service Pack 3  
(nur Windows XP Tablet PC Edition 2005)  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(Kritisch)  
Internet Explorer 7  
(2846071)  
(Kritisch)  
Internet Explorer 8  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 11<sup>[1]</sup>
(wmvdecod.dll)  
(nur Media Center Edition)  
(2834904)  
(Kritisch)  
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(nur Media Center Edition)  
(2834905)  
(Kritisch)  
Windows Media Format Runtime 9  
(wmvdmod.dll)  
(2803821)  
(Kritisch)  
Windows Media Format Runtime 9.5<sup>[2]</sup>
(wmvdmod.dll)  
(2834902)  
(Kritisch)  
Windows Media Format Runtime 9.5<sup>[3]</sup>
(wmvdmod.dll)  
(2834903)  
(Kritisch)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
  
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(Kritisch)  
Internet Explorer 7  
(2846071)  
(Kritisch)  
Internet Explorer 8  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(Kritisch)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(Kritisch)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833949)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(Mittel)  
Internet Explorer 7  
(2846071)  
(Mittel)  
Internet Explorer 8  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(Mittel)  
Internet Explorer 7  
(2846071)  
(Mittel)  
Internet Explorer 8  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(Kritisch)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(Kritisch)  
Windows Media Format Runtime 11  
(wmvdmod.dll)  
(2834904)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(Hoch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(Mittel)  
Internet Explorer 7  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2835622)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Vista Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows Vista Service Pack 2  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(Kritisch)  
Internet Explorer 8  
(2846071)  
(Kritisch)  
Internet Explorer 9  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2835622)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(Kritisch)  
Internet Explorer 8  
(2846071)  
(Kritisch)  
Internet Explorer 9  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(Kritisch)  
wmv9vcm.dll (Codec)  
(2845142)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2835622)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(Mittel)  
Internet Explorer 8  
(2846071)  
(Mittel)  
Internet Explorer 9  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(Kritisch)  
wmv9vcm.dll (Codec)\[5\]  
(2845142)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(Hoch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(Kritisch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2835622)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(Mittel)  
Internet Explorer 8  
(2846071)  
(Mittel)  
Internet Explorer 9  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(Kritisch)  
wmv9vcm.dll (Codec)\[5\]  
(2845142)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(Hoch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(Kritisch)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(Hoch)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(Kritisch)  
Internet Explorer 9  
(2846071)  
(Kritisch)  
Internet Explorer 10  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(Kritisch)  
Internet Explorer 9  
(2846071)  
(Kritisch)  
Internet Explorer 10  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Windows GDI+)  
(2834886)  
(Kritisch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(Mittel)  
Internet Explorer 9  
(2846071)  
(Mittel)  
Internet Explorer 10  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2833959)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2840633)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2844289)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833958)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840632)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows 8 für 32-Bit-Systeme  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2833959)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2840633)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2844289)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833958)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840632)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows 8 für 64-Bit-Systeme  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung** **des Gesamtschweregrads**
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
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2833959)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2840633)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2844289)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833958)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840632)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
(Kritisch)  
Windows Server 2012  
(Journal)  
(2835364)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
(Kritisch)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;" colspan="2">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840632)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Server Core-Installationsoption
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;" colspan="2">
**Keine**
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
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
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
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(Hoch)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(Hoch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(Kritisch)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833957)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840642)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(Windows GDI+)  
(2834886)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2833959)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(2840633)  
(Hoch)  
Microsoft .NET Framework 3.5  
(2844289)  
(Hoch)  
Microsoft .NET Framework 4.5  
(2833958)  
(Kritisch)  
Microsoft .NET Framework 4.5  
(2840632)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(2850851)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(DirectWrite)  
(2835361)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;" colspan="2">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweise für MS13-052**

<sup>[1]</sup>**.NET Framework 4 und .NET Framework 4 Client Profile sind betroffen.** Die .NET Framework Version 4 Redistributable Packages sind in zwei Profilen verfügbar: .NET Framework 4 und .NET Framework 4 Client Profile. .NET Framework 4 Client Profile ist Teil von .NET Framework 4. Die in diesem Update behobene Sicherheitsanfälligkeit betrifft sowohl .NET Framework 4 als auch .NET Framework 4 Client Profile. Weitere Informationen finden Sie im MSDN-Artikel [Installieren von .NET Framework](http://msdn.microsoft.com/library/5a4x27ek).

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

**Hinweis für** **MS13-053** **und** **MS13-055**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

**Hinweis** **für** **MS13-054**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

**Hinweise** **für MS13-057**

<sup>[1]</sup>Dieses Update wird nur Systemen angeboten, die auf Windows Media Format Runtime 11 oder Windows Media Player 11 aktualisiert wurden.
<sup>[2]</sup>Dieses Update wird nur Systemen angeboten, auf denen Windows Media Format Runtime 9.5 NL ausgeführt wird.
<sup>[3]</sup>Dieses Update wird nur Systemen angeboten, auf denen Windows Media Format Runtime 9.5 L ausgeführt wird.
\[4\]Dieses Update wird nur angeboten, wenn die optionale Funktion „Desktopdarstellung“ aktiviert ist.
\[5\]Dieses Update wird nur angeboten, wenn die optionale Funktion „Desktopdarstellung“ aktiviert und der Codec wmv9vcm.dll vorhanden ist. Weitere Informationen finden Sie im Bulletin.

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817480)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687309)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)  
(2687276)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)  
(2687276)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für MS13-054**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Entwicklertools und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1<sup>[1]</sup>
(2856545)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 bei Installation auf dem Mac  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation auf dem Mac  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten 32-Bit-Editionen von Microsoft Windows-Clients  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten x64-basierten Editionen von Microsoft Windows-Clients  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten 32-Bit-Editionen von Microsoft Windows-Servern  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten x64-basierten Editionen von Microsoft Windows-Servern  
(2847559)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(2847559)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für MS13-052**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

**Hinweise** **für MS13-054**

<sup>[1]</sup>Dieses Update ist nur im Microsoft Download Center verfügbar.

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Communication-Plattformen und -Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-Bit)  
(2843160)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-Bit)  
(2843160)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)  
(2843162)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)  
(2843163)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-Bit)  
(2817465)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-Bit)  
(2817465)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-Bit)  
(2817465)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-Bit)  
(2817465)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis für MS13-054**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Sicherheitssoftware

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Antispyware
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-058**](http://go.microsoft.com/fwlink/?linkid=308992)
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
Windows Defender für Windows 7 (x86)
</td>
<td style="border:1px solid black;">
Windows Defender für Windows 7 (x86)  
(2847927)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Defender für Windows 7 (x64)
</td>
<td style="border:1px solid black;">
Windows Defender für Windows 7 (x64)  
(2847927)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Defender unter Windows Server 2008 R2 (x64)
</td>
<td style="border:1px solid black;">
Windows Defender unter Windows Server 2008 R2 (x64)  
(2847927)  
(Hoch)
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/bb245732). Im [TechNet Sicherheitscenter](http://technet.microsoft.com/de-de/security/default.aspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Endbenutzer können das [Microsoft-Sicherheitscenter](http://www.microsoft.com/de-de/security/default.aspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de) und [Windows Update](http://update.microsoft.com/windowsupdate/) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. und können am einfachsten durch eine Suche nach dem Begriff „Sicherheitsupdate“ ermittelt werden.

Benutzern von Microsoft Office für Mac kann Microsoft AutoUpdate für Mac helfen, Ihre Microsoft-Software auf dem neuesten Stand zu halten. Weitere Informationen zur Verwendung von Microsoft AutoUpdate für Mac finden Sie unter [Automatisch nach Softwareupdates suchen](http://www.microsoft.com/germany/mac).

Außerdem können Sicherheitsupdates vom [Microsoft Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS13-001“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Anleitungen zur Erkennung und Bereitstellung:**

Microsoft stellt Anleitungen zur Erkennung und Bereitstellung von Sicherheitsupdates bereit. Diese Anleitungen enthalten Empfehlungen und Informationen, anhand derer IT-Experten verstehen können, wie die verschiedenen Tools für die Erkennung und Bereitstellung der Sicherheitsupdates verwendet werden. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 961747](http://support.microsoft.com/kb/961747/de).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/de-de/security/cc184924.aspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS) können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Microsoft Windows 2000 und neuere Betriebssysteme, Office XP und höher, Exchange Server 2003 und SQL Server 2000 bis Microsoft Windows 2000 und neuere Betriebssysteme schnell und sicher bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://technet.microsoft.com/de-de/windowsserver/bb332157.aspx).

**SystemCenter Configuration Manager**

System Center Configuration Manager-Softwareupdateverwaltung vereinfacht die komplizierte Aufgabe des Bereitstellens und Verwaltens von Updates auf IT-Systemen im gesamten Unternehmen. Mit System Center Configuration Manager können IT-Administratoren Updates von Microsoft-Produkten auf verschiedenen Geräten bereitstellen, einschließlich Desktops, Laptops, Servern und mobilen Geräten.

Die automatisierte Bewertung der Sicherheitsanfälligkeiten in System Center Configuration Manager erkennt den Bedarf an Updates und berichtet über empfohlene Aktionen. Die Softwareupdateverwaltung in System Center Configuration Manager ist auf Microsoft Windows Software Update Services (WSUS) aufgebaut, eine lange erprobte Updateinfrastruktur, die IT-Administratoren weltweit vertraut ist. Weitere Informationen zu System Center Configuration Manager finden Sie auf der Website [System Center Technical Resources](http://technet.microsoft.com/de-de/systemcenter/bb980621).

**Systems Management Server 2003**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen.

**Hinweis:** System Management Server 2003 wurde am 12. Januar 2010 aus dem grundlegenden Support genommen. Weitere Informationen zu Produktlebenszyklen finden Sie auf der Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de). Die nächste Version von SMS, System Center Configuration Manager, ist jetzt verfügbar (siehe den früheren Abschnitt, **System Center Configuration Manager**).

Weitere Informationen dazu, wie Administratoren mithilfe von SMS 2003 Sicherheitsupdates bereitstellen können, finden Sie in [Szenarien und Vorgehensweisen für Microsoft Systems Management Server 2003: Softwareverteilung und Patchverwaltung](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/de-de/systemcenter/bb545936).

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://technet.microsoft.com/en-us/library/cc917507.aspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können diese Updates mit dem Elevated Rights Deployment Tool (im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/de-de/download/details.aspx?id=1846) verfügbar) installieren.

**Updatekompatibilitätsbewertung und Anwendungskompatibilitäts-Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc749197), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Für die Veröffentlichung des Bulletins, die am zweiten Dienstag jedes Monats stattfindet, hat Microsoft eine aktualisierte Version des Microsofts Windows-Tool zum Entfernen schädlicher Software in Windows Update, Microsoft Update, den Windows Server Update Services und dem Download Center veröffentlicht. Für außerplanmäßige Veröffentlichungen des Security Bulletins ist keine aktualisierte Version des Microsoft Windows-Tool zum Entfernen schädlicher Software erhältlich.

#### Nicht sicherheitsrelevante Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
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

**MS13-052**

-   Ling Chuan Lee und Lee Yee Chan vom [F-13 Laboratory](http://www.f13-labs.net/) für den Hinweis auf die Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten (CVE-2013-3129).
-   Alon Fliess für den Hinweis auf die Sicherheitsanfälligkeit durch Zugriffsverletzung auf Array (CVE-2013-3131).
-   James Forshaw von [Context Information Security](http://www.contextis.com/) für den Hinweis auf die Sicherheitsanfälligkeit durch Umgehung der Stellvertreterreflektion (CVE-2013-3132).
-   James Forshaw von [Context Information Security](http://www.contextis.com/) für den Hinweis auf die Sicherheitsanfälligkeit durch Einschleusung anonymer Methoden (CVE-2013-3133).
-   James Forshaw von [Context Information Security](http://www.contextis.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Stellvertreterserialisierung (CVE-2013-3171).
-   Vitaliy Toropov für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Null-Zeiger (CVE-2013-3178).

**MS13-053**

-   Jon Butler und Nils von MWR Labs in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k bezüglich Speicherzuordnung (CVE-2013-1300).
-   Alexander Chizhov von [Dr. Web](http://drweb.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k bezüglich Dereferenzierung (CVE-2013-1340).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit im Fensterhandle von Win32k (CVE-2013-1345).
-   Ling Chuan Lee und Lee Yee Chan vom [F13 Laboratory](http://www.f13-labs.net/) für den Hinweis auf die Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten (CVE-2013-3129).
-   Yinliang von [Tencent PC Manager](http://guanjia.qq.com) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k durch Offenlegung von Informationen (CVE-2013-3167).
-   [Mateusz “j00 ru“ Jurczyk](http://j00ru.vexillium.org/) von [Google Inc](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k durch Pufferüberlauf (CVE-2013-3172).
-   Wen Yujie und Guo Pengfei vom [Qihoo 360 Security Center](http://www.360.cn/) für den Hinweis auf die Sicherheitsanfälligkeit in Win32k durch Pufferüberschreibung (CVE-2013-3173).

**MS13-054**

-   Ling Chuan Lee und Lee Yee Chan vom [F13 Laboratory](http://www.f13-labs.net/) für den Hinweis auf die Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten (CVE-2013-3129).

**MS13-055**

-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3115).
-   SkyLined in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3143).
-   Simon Zuckerbraun in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3144).
-   Toan Pham Van in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3145).
-   Toan Pham Van in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3146).
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3147).
-   Omair in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3148).
-   Bluesea in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3149).
-   [Omair](http://krash.in/) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3150).
-   Toan Pham Van in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3151).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3152).
-   e6af8de8b1d4b2b6d5ba2610cbf9cd38 in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3153).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3161).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3162).
-   Jose Antonio Vazquez Gonzalez in Zusammenarbeit mit [VeriSign iDefense Labs](http://labs.idefense.com) für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung (CVE-2013-3163).
-   Scott Bell von [Security-Assessment.com](http://www.security-assessment.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3164).
-   Masato Kinugawa für den Hinweis auf die Sicherheitsanfälligkeit in Shift JIS bezüglich Zeichencodierung (CVE-2013-3166).
-   Mark Yason von IBM X-Force für die Zusammenarbeit mit uns an der in diesem Bulletin enthaltenen Tiefenverteidigungsänderung (CVE-2013-4015)

**MS13-056**

-   Andrés Gómez Ramírez für den Hinweis auf die Sicherheitsanfälligkeit in DirectShow bezüglich willkürlichen Überschreibens von Speicher – CVE-2013-3174.

**MS13-057**

-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit in WMV Videodecoder bezüglich Remotecodeausführung (CVE-2013-3127).

**MS13-058**

-   Alton Blom von [Reserve Bank of Australia](http://www.rba.gov.au/) für den Hinweis auf die Sicherheitsanfälligkeit in Microsoft Windows 7 Defender durch fehlerhaften Pfadnamen (CVE-2013-3154).

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Sicherheitslösungen für IT-Experten: [TechNet Sicherheit – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)
-   So schützen Sie Ihren Computer, auf dem Windows ausgeführt wird, vor Viren und schädlicher Software: [Viruslösung und Security Center](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx)

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (9. Juli 2013): Bulletin Summary veröffentlicht.
-   V1.1 (9. Juli 2013): Bei MS13-055 wurde die Bewertung der Ausnutzbarkeit im **Ausnutzbarkeitsindex** für CVE-2013-3163 überarbeitet. Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit durch Internet Explorer 8 auszunutzen. Dies ist lediglich eine Informationsänderung.
-   V2.0 (13. August 2013): Das Bulletin für MS13-052 wurde überarbeitet, um die Updates 2840628, 2840632, 2840642, 2844285, 2844286, 2844287 und 2844289 erneut zu veröffentlichen. Das Bulletin für MS13-057 wurde überarbeitet, um das Update 2803821 für Windows 7 und Windows 2008 R2 erneut zu veröffentlichen. Endbenutzer müssen die erneut veröffentlichten Updates installieren, die auf ihre Systeme zutreffen. Weitere Informationen finden Sie in den jeweiligen Bulletins.
-   V3.0 (27. August 2013): Das Bulletin für MS13-057 wurde überarbeitet, um das Sicherheitsupdate 2803821 für Windows XP, Windows Server 2003, Windows Vista und Windows Server 2008 erneut zu veröffentlichen; ebenso wie das Sicherheitsupdate 2834902 für Windows XP und Windows Server 2003; des Weiteren das Sicherheitsupdate 2834903 für Windows XP; außerdem das Sicherheitsupdate 2834904 für Windows XP und Windows Server 2003; und schließlich das Sicherheitsupdate 2834905 für Windows XP. Benutzer von Windows XP, Windows Server 2003, Windows Vista und Windows Server 2008 sollten die erneut veröffentlichten Updates installieren, die auf ihre Systeme zutreffen. Weitere Informationen finden Sie im Bulletin.

*Built at 2014-04-18T01:50:00Z-07:00*
