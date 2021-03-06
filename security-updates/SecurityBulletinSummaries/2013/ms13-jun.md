---
TOCTitle: 'MS13-JUN'
Title: Microsoft Security Bulletin Summary für Juni 2013
ms:assetid: 'ms13-jun'
ms:contentKeyID: 61225121
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms13-jun(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Juni 2013
=================================================

Veröffentlicht: Dienstag, 11. Juni 2013

**Version:** 1.0

In diesem Bulletin Summary sind die im Juni 2013 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Security Bulletins für Juni 2013 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 6. Juni 2013 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Am Mittwoch, dem 12. Juni 2013, um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im Juni.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us) Ab diesem Datum steht dieser Webcast [auf Anfrage](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us) zur Verfügung.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299498">MS13-047</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (2838727)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt neunzehn vertraulich gemeldete Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendsten Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der die schwerwiegendste dieser Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301748">MS13-048</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Windows-Kernel kann Offenlegung von Informationen ermöglichen (2839229)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Windows. Die Sicherheitsanfälligkeit kann die Offenlegung von Informationen ermöglichen, wenn ein Angreifer sich bei einem System anmeldet und eine speziell gestaltete Anwendung ausführt, oder wenn er einen lokal angemeldeten Benutzer dazu verleitet, eine speziell gestaltete Anwendung auszuführen. Ein Angreifer benötigt gültige Anmeldeinformationen und muss sich lokal anmelden können, um diese Sicherheitsanfälligkeit auszunutzen. Beachten Sie, dass diese Sicherheitsanfälligkeit einem Angreifer keine Codeausführung oder direkte Erhöhung von Berechtigungen ermöglicht, sondern dazu führt, dass der Angreifer Informationen sammelt, mit denen ein betroffenes System noch weiter gefährdet werden könnte.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301749">MS13-049</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Kernelmodustreiber kann Denial of Service ermöglichen (2845690)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Denial-of-Service ermöglichen, wenn ein Angreifer speziell gestaltete Pakete an den Server sendet. Mithilfe empfohlener Vorgehensweisen für die Firewall und standardisierten Firewallkonfigurationen können Netzwerke vor Remoteangriffen von außerhalb des Unternehmens geschützt werden.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299243">MS13-050</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Komponenten der Windows-Druckwarteschlange kann Erhöhung von Berechtigungen ermöglichen (2839894)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Erhöhung von Berechtigungen ermöglichen, wenn ein authentifizierter Angreifer eine Druckerverbindung löscht. Ein Angreifer benötigt gültige Anmeldeinformationen und muss sich anmelden können, um diese Sicherheitsanfälligkeit auszunutzen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296303">MS13-051</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Office kann Remotecodeausführung ermöglichen (2839571)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Office. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Office-Dokument mit einer betroffenen Version von Microsoft Office Software öffnet oder eine Vorschau einer speziell gestalteten E-Mail-Nachricht in Outlook anzeigt oder die Nachricht öffnet, während Microsoft Word als E-Mail-Leseanwendung verwendet wird. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Nur Sicherheitsanfälligkeiten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde, sind enthalten.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).
  
In den unten stehenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.
  
| Kennung des Bulletins                                     | Titel der Sicherheitsanfälligkeit                                           | CVE-ID                                                                           | Bewertung der Ausnutzbarkeit für aktuelle Softwareversionen                                             | Bewertung der Ausnutzbarkeit für ältere Softwareversionen                                     | Bewertung der Ausnutzbarkeit durch Denial-of-Service | Wichtige Hinweise                                                                                                  |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3110) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3111) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3112) | [2](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wäre schwer zu erstellen | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3113) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3114) | [2](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wäre schwer zu erstellen | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3116) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3117) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3118) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | Nicht betroffen                                                                               | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3119) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3120) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | Nicht betroffen                                                                               | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3121) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| MS13-047                                                  | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3122) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| MS13-047                                                  | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3123) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3124) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3125) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | Nicht betroffen                                                                               | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3139) | Nicht anwendbar                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | Dies ist eine Tiefenverteidigungsmaßnahme für die aktuelle Software.                                               |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3141) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung | [CVE-2013-3142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3142) | [2](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wäre schwer zu erstellen | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | (Keine)                                                                                                            |  
| [MS13-048](http://go.microsoft.com/fwlink/?linkid=301748) | Sicherheitsanfälligkeit im Kernel durch Offenlegung von Informationen       | [CVE-2013-3136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3136) | [3](http://technet.microsoft.com/de-de/security/cc998259) – Angreifercode unwahrscheinlich              | [3](http://technet.microsoft.com/de-de/security/cc998259) – Angreifercode unwahrscheinlich    | Dauerhaft                                            | Dies ist eine Sicherheitsanfälligkeit, die sich auf die Offenlegung von Informationen bezieht.                     |  
| [MS13-049](http://go.microsoft.com/fwlink/?linkid=301749) | Sicherheitsanfälligkeit in TCP/IP bezüglich Ganzzahlüberlaufs               | [CVE-2013-3138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3138) | [3](http://technet.microsoft.com/de-de/security/cc998259) – Angreifercode unwahrscheinlich              | [3](http://technet.microsoft.com/de-de/security/cc998259) – Angreifercode unwahrscheinlich    | Dauerhaft                                            | Es handelt sich bei dieser Sicherheitsanfälligkeit um einen Denial-of-Service-Angriff.                             |  
| [MS13-050](http://go.microsoft.com/fwlink/?linkid=299243) | Sicherheitsanfälligkeit in der Druckwarteschlange                           | [CVE-2013-1339](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1339) | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich           | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Dauerhaft                                            | (Keine)                                                                                                            |  
| [MS13-051](http://go.microsoft.com/fwlink/?linkid=296303) | Sicherheitsanfälligkeit in Office durch Pufferüberlauf                      | [CVE-2013-1331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1331) | Nicht betroffen                                                                                         | [1](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Angreifercode wahrscheinlich | Nicht anwendbar                                      | Microsoft ist sich gezielter Angriffe bewusst, bei denen versucht wird, diese Sicherheitsanfälligkeit auszunutzen. |
  
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(Kritisch)  
Internet Explorer 7  
(2838727)  
(Kritisch)  
Internet Explorer 8  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2839229)  
(Hoch)
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(Kritisch)  
Internet Explorer 7  
(2838727)  
(Kritisch)  
Internet Explorer 8  
(2838727)  
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
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(Mittel)  
Internet Explorer 7  
(2838727)  
(Mittel)  
Internet Explorer 8  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2839229)  
(Hoch)
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(Mittel)  
Internet Explorer 7  
(2838727)  
(Mittel)  
Internet Explorer 8  
(2838727)  
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
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(Mittel)  
Internet Explorer 7  
(2838727)  
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
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Kritisch)  
Internet Explorer 8  
(2838727)  
(Kritisch)  
Internet Explorer 9  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839229)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839894)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Kritisch)  
Internet Explorer 8  
(2838727)  
(Kritisch)  
Internet Explorer 9  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung** **des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Mittel)  
Internet Explorer 8  
(2838727)  
(Mittel)  
Internet Explorer 9  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2839229)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(2839894)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Mittel)  
Internet Explorer 8  
(2838727)  
(Mittel)  
Internet Explorer 9  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(2839894)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Kritisch)  
Internet Explorer 9  
(2838727)  
(Kritisch)  
Internet Explorer 10  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2839229)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(2839894)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Kritisch)  
Internet Explorer 9  
(2838727)  
(Kritisch)  
Internet Explorer 10  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung** **des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Mittel)  
Internet Explorer 9  
(2838727)  
(Mittel)  
Internet Explorer 10  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(2839894)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2839229)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2845690)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(2839894)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2845690)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845690)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT  
(2845690)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(2839894)  
(Hoch)
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
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
(2839229)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(2839894)  
(Hoch)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(2839894)  
(Hoch)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2845690)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(2839894)  
(Hoch)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(2845690)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(2839894)  
(Hoch)
</td>
</tr>
</table>
 

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
[**MS13-051**](http://go.microsoft.com/fwlink/?linkid=296303)
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
(2817421)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office für Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011  
(2848689)  
(Hoch)
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/bb245732). Im [TechNet Sicherheitscenter](http://technet.microsoft.com/de-de/security/default.aspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Endbenutzer können das [Microsoft-Sicherheitscenter](http://www.microsoft.com/de-de/security/default.aspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de) und [Windows Update](http://update.microsoft.com/windowsupdate/) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. und können am einfachsten durch eine Suche nach dem Begriff „Sicherheitsupdate“ ermittelt werden.

Benutzern von Microsoft Office für Mac kann Microsoft AutoUpdate für Mac helfen, Ihre Microsoft-Software auf dem neuesten Stand zu halten. Weitere Informationen zur Verwendung von Microsoft AutoUpdate für Mac finden Sie unter [Automatisch nach Softwareupdates suchen](http://mac2.microsoft.com/help/office/14/de-de/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

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

**MS13-047**

-   Scott Bell von [Security-Assessment.com](http://www.security-assessment.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3110).
-   SkyLined in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3111).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3112).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3113).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3114).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3116).
-   Ivan Fratric und Ben Hawkes vom [Google Security Team](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3117).
-   [Omair](http://krash.in/) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3118).
-   Stephen Fewer von [Harmony Security](http://www.harmonysecurity.com) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3119).
-   SkyLined in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3120).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3121).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3122).
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3123).
-   [Omair](http://krash.in/) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3124).
-   Amol Naik in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3124).
-   [Omair](http://krash.in/) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3125).
-   Amol Naik in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3125).
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit in Internet Explorer beim Skriptdebugging (CVE-2013-3126).
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) zusammenarbeitet aber anonym bleiben möchte, für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3141).
-   Toan Pham Van in Zusammenarbeit mit der [Zero Day Initiative](http://www.zerodayinitiative.com/) von [HP](http://www.hpenterprisesecurity.com/products) für den Hinweis auf die Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Internet Explorer (CVE-2013-3142).

**MS13-048**

-   [Mateusz “j00 ru“ Jurczyk](http://j00ru.vexillium.org/) von [Google Inc](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit im Kernel durch Offenlegung von Informationen (CVE-2013-3136).

**MS13-051**

-   Andrew Lyons und Neel Mehta von [Google Inc](http://www.google.com/) für den Hinweis auf die Sicherheitsanfälligkeit in Office durch Pufferüberlauf (CVE-2013-1331).

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Sicherheitslösungen für IT-Experten: [TechNet Sicherheit – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)
-   So schützen Sie Ihren Computer, auf dem Windows ausgeführt wird, vor Viren und schädlicher Software: [Viruslösung und Security Center](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx)

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (11. Juni 2013): Bulletin Summary veröffentlicht.
-   

*Built at 2014-04-18T01:50:00Z-07:00*
