---
TOCTitle: 'MS15-OCT'
Title: Microsoft Security Bulletin Summary für Oktober 2015
ms:assetid: 'ms15-oct'
ms:contentKeyID: 70396649
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms15-oct(v=Security.10)'
---

Microsoft Security Bulletin Summary für Oktober 2015
====================================================

Veröffentlicht: 13. Oktober 2015 | Aktualisiert: 27. Oktober 2015

**Version:** 2.0

In diesem Bulletin Summary sind die im Oktober 2015 veröffentlichten Security Bulletins aufgeführt.

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

Kurzzusammenfassungen
---------------------

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software**.

<p></p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Kennung des Bulletins</strong></td>
<td style="border:1px solid black;"><strong>Titel des Bulletins und Kurzzusammenfassung</strong></td>
<td style="border:1px solid black;"><strong>Bewertung des maximalen Schweregrads<br />
und Auswirkung der Sicherheitsanfälligkeit</strong></td>
<td style="border:1px solid black;"><strong>Neustartanforderung</strong></td>
<td style="border:1px solid black;"><strong>Bekannte<br />
Probleme</strong></td>
<td style="border:1px solid black;"><strong>Betroffene Software</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (3096441)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Microsoft Edge (3096448) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Edge. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann die Offenlegung von Informationen ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Microsoft Edge anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für JScript und VBScript zum Unterbinden von Remotecodeausführung (3089659)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in den JScript- und VBScript-Skriptmodulen in Microsoft Windows. Die schwerwiegenderen dieser Sicherheitsrisiken können Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete Website hostet, die darauf ausgelegt ist, die Sicherheitsanfälligkeiten über Internet Explorer auszunutzen (oder eine manipulierte Website oder eine Website nutzt, die von Benutzern bereitgestellte Inhalte oder Werbung akzeptiert oder hostet) und dann Benutzer dazu verleitet, diese Website zu besuchen. Ein Angreifer kann auch ein als „initialisierungssicher“ gekennzeichnetes ActiveX-Steuerelement in eine Anwendung oder ein Microsoft Office-Dokument einbetten, die das Grafikwiedergabemodul von Internet Explorer hostet, um den Benutzer zu der speziell gestalteten Website zu leiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows-Shell zum Unterbinden von Remotecodeausführung (3096443) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Symbolleistenobjekt in Windows öffnet oder ein Angreifer einen Benutzer dazu verleitet, speziell gestaltete Inhalte online zu betrachten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdates für Microsoft Office zum Unterbinden von Remotecodeausführung (3096440) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Office. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Microsoft Office-Datei öffnet. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann beliebigen Code im Kontext des aktuellen Benutzers ausführen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Office Services und Web Apps,<br />
Microsoft Server-Software </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows-Kernel zum Unterbinden der Erhöhung von Berechtigungen (3096447)<br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Das schwerwiegenderen dieser Sicherheitsanfälligkeiten können die Erhöhung von Berechtigungen ermöglichen, wenn sich ein Angreifer bei einem betroffenen System anmeldet und eine speziell gestaltete Anwendung ausführt.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Im Ausnutzbarkeitsindex sind nur Sicherheitsanfälligkeiten enthalten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).
  
In den nachfolgenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.
 
<p> </p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Kennung des Bulletins</strong></td>
<td style="border:1px solid black;"><strong>Titel der Sicherheitsanfälligkeit</strong></td>
<td style="border:1px solid black;"><strong>CVE-ID</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit für<br />
aktuelle Softwareversion</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit für<br />
ältere Softwareversionen</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit<br />
durch Denial-of-Service</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6042">CVE-2015-6042</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6044">CVE-2015-6044</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6045">CVE-2015-6045</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6046">CVE-2015-6046</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6047">CVE-2015-6047</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6048">CVE-2015-6048</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6049">CVE-2015-6049</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6050">CVE-2015-6050</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer bezüglich der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6051">CVE-2015-6051</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">ASLR-Umgehung durch VBScript und JScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Internet Explorer durch Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6053">CVE-2015-6053</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6056">CVE-2015-6056</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-106">MS15-106</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich der Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Edge bezüglich der Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6057">CVE-2015-6057</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-107">MS15-107</a></td>
<td style="border:1px solid black;">Umgehung des XSS-Filters in Microsoft Edge</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6058">CVE-2015-6058</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2482">CVE-2015-2482</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">ASLR-Umgehung durch VBScript und JScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6052">CVE-2015-6052</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6055">CVE-2015-6055</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-108">MS15-108</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Skriptmodul bezüglich der Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6059">CVE-2015-6059</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit durch Symbolleiste</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2515">CVE-2015-2515</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-109">MS15-109</a></td>
<td style="border:1px solid black;">Use-after-free-Sicherheitsanfälligkeit durch Microsoft-Tableteingabebereich</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2548">CVE-2015-2548</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2555">CVE-2015-2555</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft SharePoint bezüglich Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2556">CVE-2015-2556</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2557">CVE-2015-2557</a></td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2558">CVE-2015-2558</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Spoofing-Sicherheitsanfälligkeit in Microsoft Office Web Apps durch siteübergreifende Skripterstellung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6037">CVE-2015-6037</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-110">MS15-110</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft SharePoint durch Umgehung von Sicherheitsfunktionen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6039">CVE-2015-6039</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 – Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit im Windows-Kernel durch Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2549">CVE-2015-2549</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows bezüglich der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2550">CVE-2015-2550</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei vertrauenswürdigem Start durch Umgehung der Sicherheitsfunktionen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2552">CVE-2015-2552</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Bereitstellungspunkt durch Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2553">CVE-2015-2553</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-111">MS15-111</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Objektreferenz bezüglich der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2554">CVE-2015-2554</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
</tbody>
</table>
  
Betroffene Software  
-------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Bewertung des Schweregrads des Softwareupdates ebenfalls aufgeführt.
  
**Hinweis** Für eine Sicherheitsanfälligkeit müssen möglicherweise mehrere Sicherheitsupdates installiert werden. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
### Windows-Betriebssysteme und -Komponenten

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(Kritisch)  
Internet Explorer 8  
(3093983)  
(Kritisch)  
Internet Explorer 9  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3080446)  
(Kritisch)  
Windows Vista Service Pack 2  
(3093513)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(Kritisch)  
Internet Explorer 8  
(3093983)  
(Kritisch)  
Internet Explorer 9  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3080446)  
(Kritisch)  
Windows Vista x64 Edition Service Pack 2  
(3093513)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(Mittel)  
Internet Explorer 8  
(3093983)  
(Mittel)  
Internet Explorer 9  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(Mittel)  
Internet Explorer 8  
(3093983)  
(Mittel)  
Internet Explorer 9  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(Kritisch)  
Internet Explorer 9  
(3093983)  
(Kritisch)  
Internet Explorer 10  
(3093983)  
(Kritisch)  
Internet Explorer 11  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3080446)  
(Kritisch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3093513)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(Kritisch)  
Internet Explorer 9  
(3093983)  
(Kritisch)  
Internet Explorer 10  
(3093983)  
(Kritisch)  
Internet Explorer 11  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3080446)  
(Kritisch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(3093513)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
(3093983)  
(Mittel)  
Internet Explorer 9  
(3093983)  
(Mittel)  
Internet Explorer 10  
(3093983)  
(Mittel)  
Internet Explorer 11  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 und Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
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
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT und Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3093983)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
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
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3097617)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3097617)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105210)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3097617)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3097617)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3097617)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-106**](https://technet.microsoft.com/de-de/library/security/ms15-106)
</td>
<td style="border:1px solid black;">
[**MS15-107**](https://technet.microsoft.com/de-de/library/security/ms15-107)
</td>
<td style="border:1px solid black;">
[**MS15-108**](https://technet.microsoft.com/de-de/library/security/ms15-108)
</td>
<td style="border:1px solid black;">
[**MS15-109**](https://technet.microsoft.com/de-de/library/security/ms15-109)
</td>
<td style="border:1px solid black;">
[**MS15-111**](https://technet.microsoft.com/de-de/library/security/ms15-111)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.7 und VBScript 5.7  
(3094996)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
JScript 5.8 und VBScript 5.8  
(3094995)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)
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
Windows Server 2012  
(Server Core-Installation)  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3088195)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)
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
Windows Server 2012 R2  
(Server Core-Installation)  
(3080446)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3088195)  
(Hoch)
</td>
</tr>
</table>
 
### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3085615)  
(Hoch)  
Microsoft Visio 2007 Service Pack 3  
(3085542)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32-Bit-Editionen)  
(3085609)  
(Hoch)  
Microsoft Visio 2010 Service Pack 2 (32-Bit-Editionen)  
(3085514)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64-Bit-Editionen)  
(3085609)  
(Hoch)  
Microsoft Visio 2010 Service Pack 2 (64-Bit-Editionen)  
(3085514)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32-Bit-Editionen)  
(3085583)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64-Bit-Editionen)  
(3085583)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3085583)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32-Bit-Edition)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32-Bit-Edition)  
(2920693)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64-Bit-Edition)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64-Bit-Edition)  
(2920693)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office für Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Excel für Mac 2011  
(3097266)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 für Mac
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 für Mac  
(3097264)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Weitere Office-Software**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3085619)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(3085618)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-110**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Microsoft Office-Dienste und Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(3054994)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(3085596)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(3085568)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3085520)  
(Hoch)  
Microsoft Excel Web App 2010 Service Pack 2  
(3085595)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3085571)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-110**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Microsoft Server-Software 

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)  
(2596670)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)  
(2596670)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2  
(2553405)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-110**](https://technet.microsoft.com/de-de/library/security/ms15-110)
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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3085567)  
(Hoch)  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3085582)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-110**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

Tools und Hinweise zur Erkennung und Bereitstellung von Sicherheitsupdates
--------------------------------------------------------------------------

Es stehen mehrere Ressourcen zur Verfügung, um Administratoren bei der Bereitstellung von Sicherheitsupdates zu helfen.

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter.

Windows Server Update Services (WSUS), Systems Management Server (SMS) und System Center Configuration Manager erleichtern Administratoren die Verteilung von Sicherheitsupdates.

Die im Anwendungskompatibilitäts-Toolkit enthaltenen Komponenten zur Updatekompatibilitätsbewertung helfen dabei, die Vereinbarkeit von Windows-Updates mit installierten Anwendungen zu testen und zu überprüfen.

Weitere Informationen zu diesen und weiteren verfügbaren Tools finden Sie unter [Sicherheitstools](http://technet.microsoft.com/de-de/security/cc297183).

Danksagung
----------

Microsoft würdigt die Bemühungen derjenigen Benutzer der Sicherheitscommunity, die uns dabei helfen, Kunden durch eine verantwortliche Offenlegung von Sicherheitsanfälligkeiten zu schützen. Weitere Informationen finden Sie unter [Danksagung](https://technet.microsoft.com/de-de/library/security/dn903755.aspx). 

Weitere Informationen
---------------------

### Microsoft Windows-Tool zum Entfernen bösartiger Software

Für die Veröffentlichung des Bulletins, die am zweiten Dienstag jedes Monats stattfindet, hat Microsoft eine aktualisierte Version des Microsofts Windows-Tool zum Entfernen schädlicher Software in Windows Update, Microsoft Update, den Windows Server Update Services und dem Download Center veröffentlicht. Für außerplanmäßige Veröffentlichungen des Security Bulletins ist keine aktualisierte Version des Microsoft Windows-Tool zum Entfernen schädlicher Software erhältlich.

### Nicht sicherheitsrelevante Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](https://support.microsoft.com/de-de/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/de-de/windowsserver/bb332157.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://technet.microsoft.com/de-de/security/dn467918) aufgeführt sind.

### Sicherheitsstrategien und Community

**Updateverwaltungsstrategien**

Auf der Seite [Patchmanagement](http://technet.microsoft.com/de-de/library/bb466251.aspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsanfälligkeiten sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=de-de) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](https://support.microsoft.com/de-de/kb/913086).

**IT Pro Security Community**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://technet.microsoft.com/de-de/security/cc136632.aspx) Website mit anderen IT-Profis über das Thema Sicherheit.

### Support

Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.

Sicherheitslösungen für IT-Experten: [TechNet Security – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)

Hilfe beim Schützen des Computers, auf dem Windows ausgeführt wird, vor Viren und Schadsoftware: [Safety and Security Center](http://www.microsoft.com/de-de/security/default.aspx)

Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx?ln=de)

### Haftungsausschluss

Die Informationen in der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

### Revisionen

-   V1.0 (13. Oktober 2015): Bulletin Summary veröffentlicht.
-   V1.1 (14. Oktober 2015): Das Bulletin Summary wurde überarbeitet, um den Titel von CVE-2015-6046 im Ausnutzbarkeitsindex zu korrigieren. Dies ist lediglich eine Informationsänderung.
-   V1.2 (15. Oktober 2015): Das Bulletin wurde überarbeitet, um die Bewertung der Ausnutzbarkeit von CVE-2015-6046 zu korrigieren. Dies ist lediglich eine Informationsänderung.
-   V2.0 (27. Oktober 2015) Für MS15-106 wurde das Bulletin Summary überarbeitet, um die Veröffentlichung eines neuen kumulativen Updates (3105210) für Windows 10 anzukündigen, das eine weitere Sicherheitsanfälligkeit (CVE-2015-6045) behebt, und um diese Sicherheitsanfälligkeit dem Ausnutzbarkeitsindex hinzuzufügen. Nur Benutzer mit Windows 10-Systemen müssen dieses neue Update installieren. Ältere Systeme sind entweder nicht betroffen oder haben dieses Update bereits mit den ursprünglichen Updates vom 13. Oktober 2015 erhalten. Weitere Informationen und Downloadlinks finden Sie im Microsoft Knowledge Base-Artikel 3105210.

*Seite generiert am 26.10.2015 um 22:41:00-07:00.*