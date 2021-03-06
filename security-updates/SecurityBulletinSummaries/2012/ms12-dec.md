---
TOCTitle: 'MS12-DEC'
Title: Microsoft Security Bulletin Summary für Dezember 2012
ms:assetid: 'ms12-dec'
ms:contentKeyID: 61225105
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms12-dec(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Dezember 2012
=====================================================

Veröffentlicht: Dienstag, 11. Dezember 2012 | Aktualisiert: Donnerstag, 20. Dezember 2012

**Version:** 2.0

In diesem Bulletin Summary sind die im Dezember 2012 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Security Bulletins für Dezember 2012 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 6. Dezember 2012 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Am Mittwoch, den 12. Dezember 2012 um 20:00 Uhr (MEZ) führt Microsoft einen englischsprachigen Webcast durch, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für den Security Bulletin-Webcast im Dezember.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us) Ab diesem Datum steht dieser Webcast [auf Anfrage](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us) zur Verfügung.

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software und Downloadadressen**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (2761465)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt drei vertraulich gemeldete Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendsten Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Windows-Kernelmodustreibern können Remotecodeausführung ermöglichen<br />
(2783534)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich und eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die schwerwiegenderen dieser Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Dokument öffnet oder eine schädliche Webseite besucht, in der TrueType- oder OpenType-Schriftartdateien eingebettet sind. Der Angreifer muss den Benutzer zum Besuch dieser Website verleiten, z. B. indem er den Benutzer dazu auffordert, in einer E-Mail-Nachricht auf einen Link zur Website des Angreifers zu klicken.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Word kann Remotecodeausführung ermöglichen (2780642)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Office. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete RTF-Datei mit einer betroffenen Version der Microsoft Office Software öffnet oder eine Vorschau davon anzeigt, oder eine speziell gestaltete RTF-E-Mail Nachricht in Outlook mit Microsoft Word als E-Mail Viewer öffnet. Ein Angreifer, der die Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Exchange können Remotecodeausführung ermöglichen (2784126)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt öffentlich gemeldete Sicherheitsanfälligkeiten und eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Exchange Server. Die schwersten Sicherheitsanfälligkeiten liegen in Microsoft Exchange Server WebReady Document Viewing vor und können Remotecodeausführung im Sicherheitskontext des Transcodierungsdienstes auf dem Exchange Server ermöglichen, wenn ein Benutzer von Outlook Web App (OWA) eine Vorschau einer speziell gestalteten Datei anzeigt. Der Transcodierungsdienst in Exchange, der für WebReady Dokument Viewing verwendet wird, wird im LocalService-Konto ausgeführt. Das LocalService-Konto hat Mindestberechtigungen auf dem lokalen Computer und präsentiert im Netzwerk anonyme Anmeldeinformationen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in der Dateiverarbeitungskomponente von Windows kann Remotecodeausführung ermöglichen (2758857)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer zu einem Ordner navigiert, der eine Datei oder einen Unterordner mit einem speziell gestalteten Namen enthält. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in VBScript kann Remotecodeausführung ermöglichen (2770660)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer einen Benutzer dazu verleitet, ein speziell gestaltetes Office-Dokument mit eingebetteten Inhalten anzuzeigen. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in IP-HTTPS-Komponente kann Umgehung der Sicherheitsfunktion ermöglichen (2765809)<br />
<br />
</strong>Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann die Umgehung der Sicherheitsfunktion ermöglichen, wenn ein Angreifer einem IP-HTTPS-Server, der üblicherweise für Bereitstellungen von Microsoft DirectAccess verwendet wird, ein widerrufenes Zertifikat präsentiert. Um die Sicherheitsanfälligkeit auszunutzen, muss ein Angreifer ein Zertifikat verwenden, das von der Domäne für IP-HTTPS-Serverauthentifizierung herausgegeben wird. Für die Anmeldung bei einem System innerhalb des Unternehmens sind immer noch Anmeldeinformationen für das System oder die Domäne erforderlich.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a><br />
Umgehung der Sicherheitsfunktion</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit in InjectHTMLStream</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4781">CVE-2012-4781</a></td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit in CMarkup</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4782">CVE-2012-4782</a></td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit durch falsche Referenzzählung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4787">CVE-2012-4787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2556">CVE-2012-2556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Diese Sicherheitsanfälligkeit wurde veröffentlicht.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4786">CVE-2012-4786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Remotecodeausführung in Word RTF „listoverridecount“</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2539">CVE-2012-2539</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">Oracle Outside In enthält mehrere ausnutzbare Sicherheitsanfälligkeiten</td>
<td style="border:1px solid black;">Mehrere*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">*Mehrere Sicherheitsanfälligkeiten; weitere Informationen finden Sie im Bulletin MS12-080.<br />
<br />
Diese Sicherheitsanfälligkeiten wurden veröffentlicht.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bezüglich Denial-of-Service in Exchange durch RSS-Feed</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4791">CVE-2012-4791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
<td style="border:1px solid black;">Es handelt sich bei dieser Sicherheitsanfälligkeit um einen Denial-of-Service-Angriff.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows bei Analyse des Dateinamens</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4774">CVE-2012-4774</a></td>
<td style="border:1px solid black;">Nicht betroffen</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">1</a> – Angreifercode wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in DirectPlay bezüglich Heapüberlaufs</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1537">CVE-2012-1537</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">3</a> – Angreifercode unwahrscheinlich</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/cc998259">2</a> – Angreifercode wäre schwer zu erstellen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">(Keine)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Umgehung mit widerrufenem Zertifikat</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2549">CVE-2012-2549</a></td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
<td style="border:1px solid black;">Dies ist eine Sicherheitsanfälligkeit aufgrund der Umgehung von Sicherheitsfunktionen.</td>
</tr>
</tbody>
</table>
  
Betroffene Software und Downloadadressen  
----------------------------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
**Wie verwende ich diese Tabellen?**  
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.
  
**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
#### Systemkomponenten des Windows-Betriebssystems

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="6" style="border:1px solid black;">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e39c8368-9cd3-4f29-8c9c-aa784122bef0)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d1881d12-2a40-4cb1-9428-31d6633746be)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8359ec5a-07f8-4b29-8576-7356a84daf82)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e4a2cd3b-598b-4cf4-8b42-2582d369bab5)  
(KB2753842)  
(Kritisch)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7a7a68cf-42a2-49a4-bf0c-88dd582ddd0d)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f189ee1c-1457-4d50-87cd-5be268b04f16)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=98ceaf36-ef87-4ea3-8b73-bb0a1a624fe0)  
(KB2770660)  
(Hoch)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ed2d3c6e-b90a-49a7-867e-9549b14eb0bf)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=18e165e9-346b-4337-81d2-77f3bf5f5f3f)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5d0a76e1-80d3-4f81-be5e-8d235babaa61)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=27e6c4df-7988-4d03-b2f6-bc9ce37483f9)  
(KB2753842)  
(Kritisch)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d2a59846-74fd-4166-9d65-1cc98cb7d934)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2bf25fc8-6458-4807-bb7d-1c07ec424638)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=421b0c02-e572-4362-b690-73ad63b028de)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=478f4789-0f5e-4bfb-9536-94314f84f12c)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ca71c15-0add-45cd-991f-e5810791c434)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0157c9ee-58c5-419f-ba97-6c4334318b75)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=efe4755b-3bc4-4a65-9826-7ecaa3856093)  
(KB2753842)  
(Kritisch)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=74847cb5-a092-4818-bf7a-912ccaed7a12)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2242a927-cafb-41eb-8bf2-01302b5a5d94)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b487137-8b5a-4f22-8395-f3fc4f25f00b)  
(KB2770660)  
(Hoch)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=66b552b4-8b55-45de-ba0a-940dc24e6f56)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9fb2cf9-3acb-48ac-80ac-f61f1a47a188)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=23c4962c-8526-4e18-9b8d-50f3c3a2bf6d)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=019d80e2-7622-4951-9437-5d613c5fb2fb)  
(KB2753842)  
(Kritisch)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0c9df15-857f-490a-96df-3883a11c3234)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4d97b0a5-1ba7-44f0-88b6-1e0a8039b9b1)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39d79b5b-f11c-465a-8ddd-aecb571c711f)  
(KB2770660)  
(Hoch)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=890d1149-7bb3-4d6e-a4ce-f9116c658eda)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8025298-be72-4ef2-8914-7698494f4368)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=419b9fd2-dbe6-45b5-b025-9712bb9319d6)  
(KB2753842)  
(Kritisch)  
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=323c122b-be77-45e9-805d-ab14f5cc76f9)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=e74713fd-e1bc-4a63-9a00-2f33000eac27)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=312975f6-2269-4c6f-996b-8fb04e8c08d6)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3701a40d-e423-4204-9527-26e527f47fb0)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=394963e9-edd6-4b5d-b9d4-e6fb86d7eb54)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bd3a6f9b-7bfd-40e1-9393-a125030f2964)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0cadef72-625f-4c91-8289-c10a96bb3423)  
(KB2753842)  
(Kritisch)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f2854a4e-2597-49ab-8a85-715ea9194208)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebd25f89-e6d9-4c48-a673-f665d189905c)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cd60c749-bb24-4147-9699-a1a75939a28f)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2856c7b8-d5c0-444d-8273-5bd116f8898b)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a0c6dbd-e537-43d7-97cc-0d3df354e46a)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=482fadb3-0974-40f3-af35-f29210913c81)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dd5eb06a-c805-4518-a784-5e29d7636037)  
(KB2753842)  
(Kritisch)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b6baf170-65b0-4068-b2a0-196c3e4b3aed)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7629d85-5c18-4979-a8e2-054a6175cf21)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[](http://www.microsoft.com/downloads/details.aspx?familyid=?...?)[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6f2c1d9-b775-48a0-b154-cf61b1e2674c)</a>
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a4824a10-4011-4ce5-9454-693d42acddf3)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e3d584f5-fc25-4e66-a911-4595018c51e3)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ffff647e-8d05-4c77-aea6-542ab8d76c57)  
(KB2761465)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20ffdbfd-c786-41ca-9367-d7499108d711)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=750797e5-1da7-49a9-8c27-ff35fe7516a1)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ca4a5972-faec-412a-b51a-130253cebcab)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=8f22603d-3a0d-49da-9691-671c0c950867)  
(KB2761465)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cfeb7a06-5812-4a49-b69b-88be06d63d71)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4d49cd73-feea-44c7-86f2-048dd69233a4)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=68e6d5c4-cb20-4291-8864-4270db36ead0)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2293a5fb-4a1c-41d9-ab67-b89e00078029)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=202b3919-0075-4c54-a189-123de852fc7b)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0345e31f-6d0d-4d46-8f02-8b2ffbf795f0)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(Kritisch)  
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(Kritisch)  
[Windows 7 für 32-Bit-Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(Kritisch)  
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(Kritisch)  
[Windows 7 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Keine Bewertung des Schweregrads<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(Kritisch)  
[Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
**Keine**
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
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=28fb32a1-12fd-420d-94ff-570742a02b8d)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 8 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=385265c4-f920-4ac1-b474-a166b3d3ab42)  
(KB2753842)  
(Kritisch)  
[Windows 8 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=75969782-d3f8-40dd-8922-4408eefad6f3)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 8 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=15f86dbf-d8db-445c-8996-cc789c8a894d)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 für 64-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=ad0ee30f-b550-434b-9fe0-ff418e052d3f)  
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 8 für 64-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=543af274-d6cf-4f85-a120-b7f3936d7fc2)  
(KB2753842)  
(Kritisch)  
[Windows 8 für 64-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=2332059d-30d3-4b44-b172-f054e26d8971)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows 8 für 64-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=dfdda0c8-a440-49ab-832b-cdd343c57770)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=96fda694-876a-45e9-911a-b68b3bd03290)  
(KB2761465)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a)  
(KB2753842)  
(Kritisch)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73)  
(KB2779030)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=59be5ec7-df5a-4f01-8e27-ad76f1fe76bb)  
(KB2770660)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[2]</sup>
(KB2761465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2753842)  
(Kritisch)  
Windows RT<sup>[1]</sup>
(KB2779030)  
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
<th colspan="6" style="border:1px solid black;">
Server Core-Installationsoption
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609) (Server Core-Installation)  
(KB2753842)  
(Hoch)  
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a) (Server Core-Installation)  
(KB2779030)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863) (Server Core-Installation)  
(KB2758857)  
(Kritisch)
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
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de) (Server Core-Installation)  
(KB2753842)  
(Hoch)  
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27) (Server Core-Installation)  
(KB2779030)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06) (Server Core-Installation)  
(KB2758857)  
(Kritisch)
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
Windows Server 2008 R2 für x64-basierte Systeme (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (Server Core-Installation)  
(KB2753842)  
(Hoch)  
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (Server Core-Installation)  
(KB2779030)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (Server Core-Installation)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (Server Core-Installation)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (Server Core-Installation)  
(KB2753842)  
(Hoch)  
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (Server Core-Installation)  
(KB2779030)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (Server Core-Installation)  
(KB2758857)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (Server Core-Installation)  
(KB2765809)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a) (Server Core-Installation)  
(KB2753842)  
(Hoch)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73) (Server Core-Installation)  
(KB2779030)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563) (Server Core-Installation)  
(KB2765809)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise für MS12-077**

<sup>[1]</sup>Bewertungen des Schweregrads treffen für dieses Update für die angegebene Software nicht zu, da die in diesem Bulletin erörterten bekannten Angriffsmethoden in einer Standardkonfiguration blockiert werden. Microsoft empfiehlt jedoch den Benutzern dieser Software, dieses Sicherheitsupdate als tiefgreifende Verteidigungsmaßnahme zu installieren.

<sup>[2]</sup>Dieses Update ist nur über [Windows Update](http://update.microsoft.com/windowsupdate/) verfügbar.

**Hinweis** **für MS12-078**

<sup>[1]</sup>Das Update ist nur über [Windows-Update](http://update.microsoft.com/windowsupdate/) verfügbar.

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Suites und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6947d500-f197-4001-bb39-1c4221af1b36)  
(KB2760497)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1 (32-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=68c69b37-c544-4f24-8589-4212b868dd69)  
(KB2760410)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1 (64-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=9d776c2b-1a9a-4ccb-9e76-dd2cb0f9a80d)  
(KB2760410)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Andere Microsoft Office-Software
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=4ccaabd9-5128-4505-ba2f-20bcf02b97ec)  
(KB2760498)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise** **für MS12-079**

<sup>[1]</sup>Für Microsoft Office Word 2007 müssen Benutzer zusätzlich zu dem Sicherheitsupdatepaket KB2760421 auch das Sicherheitsupdate für Microsoft Office Compatibility Pack (KB2760416) installieren, um vor der in diesem Bulletin beschriebenen Sicherheitsanfälligkeit geschützt zu sein.

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Server Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=605fc9bc-a05c-4466-ace6-9c2af087d797)  
(KB2746157)  
(Kritisch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e43b1164-d768-4152-b9a3-d1491e2f3cba)  
(KB2787763)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a49ed58-9dab-4d48-ae8a-c7139e3b34ba)  
(KB2785908)  
(Kritisch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Word-Automatisierungsdienste](http://www.microsoft.com/downloads/details.aspx?familyid=62007dcd-80db-42e4-8478-9e81f89cab98)  
(KB2760405)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c98d8ef3-e9a8-4e7c-9e0a-02e192bab39c)  
(KB2687412)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für** **MS12-079**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/bb245732). Im [TechNet Sicherheitscenter](http://technet.microsoft.com/de-de/security/default.aspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Endbenutzer können das [Microsoft-Sicherheitscenter](http://www.microsoft.com/de-de/security/default.aspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de) und [Windows Update](http://update.microsoft.com/windowsupdate/) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. und können am einfachsten durch eine Suche nach dem Begriff „Sicherheitsupdate“ ermittelt werden.

Benutzern von Microsoft Office für Mac kann Microsoft AutoUpdate für Mac helfen, Ihre Microsoft-Software auf dem neuesten Stand zu halten. Weitere Informationen zur Verwendung von Microsoft AutoUpdate für Mac finden Sie unter [Automatisch nach Softwareupdates suchen](http://mac2.microsoft.com/help/office/14/de-de/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Außerdem können Sicherheitsupdates vom [Microsoft Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS12-001“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

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

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://technet.microsoft.com/en-us/library/cc917507.aspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können diese Updates mit dem Elevated Rights Deployment Tool (im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) verfügbar) installieren.

**Updatekompatibilitätsbewertung und Anwendungskompatibilitäts-Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc749197), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

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

-   [Rosario Valotta](https://sites.google.com/site/tentacoloviola) für den Hinweis auf zwei in MS12-077 beschriebene Probleme.
-   Fermin J. Serna von [Google Inc](http://www.google.com) für den Hinweis auf ein in MS12-077 beschriebenes Problem.
-   Eetu Luodemaa und Joni Vähämäki von [Documill](http://www.documill.com) in Zusammenarbeit mit dem Chromium Security Rewards Program für den Hinweis auf ein in MS12-078 beschriebenes Problem.
-   Einer Person, die mit dem [Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)-Programm zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS12-079 beschriebenes Problem.
-   Lucas Apa von [IOActive](http://ioactive.co.uk/) für den Hinweis auf ein in MS12-081 beschriebenes Problem.
-   [Aniway](mailto:aniway.anyway@gmail.com) in Zusammenarbeit mit [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS12-082 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Sicherheitslösungen für IT-Experten: [TechNet Sicherheit – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617.aspx)
-   So schützen Sie Ihren Computer, auf dem Windows ausgeführt wird, vor Viren und schädlicher Software: [Viruslösung und Security Center](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx)

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (11. Dezember 2012): Bulletin Summary veröffentlicht.
-   V1.1 (12. Dezember 2012): Der Eintrag für die Neustartanforderung in MS12-082 wurde korrigiert. Dies ist lediglich eine Informationsänderung. Die Dateien des Sicherheitsupdates wurden nicht verändert.
-   V2.0 (20. Dezember 2012): Für MS12-078 wurde das Update KB2753842 erneut veröffentlicht, um ein Problem mit OpenType-Schriftarten zu beheben, die nicht richtig dargestellt werden, nachdem das ursprüngliche Update installiert wurde. Benutzer, die erfolgreich das ursprüngliche Update KB2753842 installiert haben, müssen das erneut veröffentlichte Update installieren.

*Built at 2014-04-18T01:50:00Z-07:00*