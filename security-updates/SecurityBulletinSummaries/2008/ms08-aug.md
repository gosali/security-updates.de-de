---
TOCTitle: 'MS08-AUG'
Title: Microsoft Security Bulletin Summary für August 2008
ms:assetid: 'ms08-aug'
ms:contentKeyID: 61225056
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms08-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für August 2008
===================================================

Veröffentlicht: Dienstag, 12. August 2008 | Aktualisiert: Mittwoch, 15. Oktober 2008

**Version:** 3.0

In diesem Bulletin Summary sind die im August 2008 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für August 2008 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 7. August 2008 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 13. August 2008 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im August.](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374631&culture=en-us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

Die Security Bulletins für diesen Monat, nach Schweregrad geordnet:

Kritisch (6)
------------


| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-046                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit im Microsoft Windows-Farbverwaltungssystem kann Remotecodeausführung ermöglichen (952954)**](http://go.microsoft.com/fwlink/?linkid=120576)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Kurzzusammenfassung**                     | Dieses Update behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Microsoft-Farbverwaltungssystem (ICM), das Remotecodeausführung im Kontext des aktuellen Benutzers ermöglichen kann. Wenn ein Benutzer mit administrativen Benutzerrechten angemeldet ist, kann ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Betroffene Software**                     | **Microsoft Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-045                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Kumulatives Sicherheitsupdate für Internet Explorer (953838)**](http://go.microsoft.com/fwlink/?linkid=122772)                                                                                                                                                                                                                                                                                                                                                        |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt fünf vertraulich gemeldete und eine öffentlich gemeldete Sicherheitsanfälligkeit. Wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt, können alle dieser Sicherheitsanfälligkeiten Remotecodeausführung ermöglichen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                      |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                       |
| **Betroffene Software**                     | **Microsoft Windows, Internet Explorer.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                      |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-041                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit im ActiveX-Steuerelement für den Snapshot Viewer für Microsoft Access kann Remotecodeausführung ermöglichen (955617)**](http://go.microsoft.com/fwlink/?linkid=122912)                                                                                                                                                                                                                                                                                                                                                       |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im ActiveX-Steuerelement für den Snapshot Viewer für Microsoft Access. Ein Angreifer kann die Sicherheitsanfälligkeit ausnutzen, indem er eine speziell gestaltete Website erstellt. Wenn ein Benutzer die Website anzeigt, kann die Sicherheitsanfälligkeit die Codeausführung von Remotestandorten aus ermöglichen. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der angemeldete Benutzer erlangen. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                                       |
| **Betroffene Software**                     | **Microsoft Office.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                         |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-043                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeiten in Microsoft Excel können Remotecodeausführung ermöglichen (954066)**](http://go.microsoft.com/fwlink/?linkid=124306)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt vier vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office Excel, die Remotecodeausführung ermöglichen können, wenn ein Benutzer eine speziell gestaltete Excel-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeiten erfolgreich aus, kann er vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Betroffene Software**                     | **Microsoft Office.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-051                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeiten in Microsoft PowerPoint können Remotecodeausführung ermöglichen (949785)**](http://go.microsoft.com/fwlink/?linkid=120394)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt drei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office PowerPoint und Microsoft Office PowerPoint Viewer, die Remotecodeausführung ermöglichen können, wenn ein Benutzer eine speziell gestaltete PowerPoint-Datei öffnet. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann vollständige Kontrolle über das betroffene System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Betroffene Software**                     | **Microsoft Office.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-044                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Microsoft Office Filters kann Remotecodeausführung ermöglichen (924090)**](http://go.microsoft.com/fwlink/?linkid=120819)                                                                                                                                                                                                                                                                            |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt fünf vertraulich gemeldete Sicherheitsanfälligkeiten. Diese Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Bilddatei mit Microsoft Office anzeigt. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                  |
| **Betroffene Software**                     | **Microsoft Office.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                    |

Hoch (5)
--------


| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-047                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit bei Verarbeitung der IPSec-Richtlinie kann Offenlegung von Information ermöglichen (953733)**](http://go.microsoft.com/fwlink/?linkid=120577)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Kurzzusammenfassung**                     | Dieses Update behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in der Art und Weise, wie bestimmte Windows IPSec-Regeln (Internet Protocol Security) angewendet werden. Diese Sicherheitsanfälligkeit kann bewirken, dass Systeme IPSec-Richtlinien ignorieren und Netzwerkverkehr in Klartext übertragen. Dies wiederum führt zur Offenlegung von Informationen, die im Netzwerk verschlüsselt sein sollen. Ein Angreifer, der den Datenverkehr im Netzwerk anzeigt, kann die Inhalte des Datenverkehrs anzeigen und möglicherweise ändern. Diese Sicherheitsanfälligkeit ermöglicht einem Angreifer keine Codeausführung oder direkte Erhöhung von Berechtigungen. Sie kann aber dazu führen, dass der Angreifer nützliche Informationen sammelt, mit denen das betroffene System noch weiter gefährdet werden kann. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Auswirkung der Sicherheitsanfälligkeit:** | Offenlegung von Informationen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Betroffene Software**                     | **Microsoft Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-049                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeiten in Ereignissystem können Remotecodeausführung ermöglichen (950974)**](http://go.microsoft.com/fwlink/?linkid=104923)                                                                                                                                                                                                                                                                                                                    |
| **Kurzzusammenfassung**                     | Dieses Update behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten im Microsoft Windows-Ereignissystem, die Remotecodeausführung ermöglichen können. Nutzt ein Angreifer diese Sicherheitsanfälligkeiten erfolgreich aus, kann er vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren; Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen administrativen Benutzerrechten erstellen. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                      |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                   |
| **Betroffene Software**                     | **Microsoft Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                     |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-048                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsupdate für Outlook Express und Windows Mail (951066)**](http://go.microsoft.com/fwlink/?linkid=117705)                                                                                                                                                                                                                                                                                                                                                                                              |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Outlook Express und Windows Mail. Die öffentliche gemeldete Sicherheitsanfälligkeit kann zur Offenlegung von Informationen führen, wenn ein Benutzer eine speziell gestaltete Webseite unter Verwendung von Internet Explorer besucht. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Auswirkung der Sicherheitsanfälligkeit:** | Offenlegung von Informationen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update kann einen Neustart erfordern.                                                                                                                                                                                                                                                                                                                                                                       |
| **Betroffene Software**                     | **Microsoft Windows, Outlook Express, Windows Mail.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                   |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-050                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Windows Messenger kann Offenlegung von Informationen ermöglichen (955702)**](http://go.microsoft.com/fwlink/?linkid=108245)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine öffentlich gemeldete Sicherheitsanfälligkeit in unterstützten Versionen von Windows Messenger. Infolge dieser Sicherheitsanfälligkeit kann Scripting eines ActiveX-Steuerelements die Offenlegung von Informationen im Kontext des angemeldeten Benutzers ermöglichen. Ein Angreifer kann ohne Wissen des angemeldeten Benutzers den Status ändern, Kontaktinformationen erhalten und Audio- und Video-Chat-Sitzungen initiieren. Ein Angreifer kann auch die Anmeldekennung des Benutzers erfassen, sich von einem Remotestandort aus beim Messenger-Client des Benutzers anmelden und diesen Benutzer imitieren. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Auswirkung der Sicherheitsanfälligkeit:** | Offenlegung von Informationen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update nur für Windows Messenger 4.7 auf unterstützten Editionen von Windows XP erfordert. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Betroffene Software**                     | **Microsoft Windows, Windows Messenger.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

<p></br></p>

| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-042                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Microsoft Word kann Remotecodeausführung ermöglichen (955048)**](http://go.microsoft.com/fwlink/?linkid=123160)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine öffentlich gemeldete Sicherheitsanfälligkeit in Microsoft Word. Diese Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Word-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Betroffene Software**                     | **Microsoft Office.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

Betroffene Software und Downloadadressen
----------------------------------------

**Wie verwende ich diese Tabelle?**  

In dieser Tabelle finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Sie sollten jedes aufgeführte Softwareprogramm und jede Komponente überprüfen, um zu sehen, ob Sicherheitsupdates erforderlich sind. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.

**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Prüfen Sie für jede aufgeführte Kennung der Bulletins die gesamte Spalte, um basierend auf den in Ihrem System installierten Programmen und Komponenten alle Updates zu finden, die Sie installieren müssen.

#### Windows-Betriebssystem:

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
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://go.microsoft.com/fwlink/?linkid=120576)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://go.microsoft.com/fwlink/?linkid=122772)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://go.microsoft.com/fwlink/?linkid=120577)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://go.microsoft.com/fwlink/?linkid=104923)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://go.microsoft.com/fwlink/?linkid=117705)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://go.microsoft.com/fwlink/?linkid=108245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=db455d17-435f-46d7-b2dd-5babb5a1eeb3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1557b93b-ecba-4f42-b89d-db0ee067d65b)  
(Kritisch)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=aa780735-5928-4c46-89a4-63a814954796)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1b2ad648-7dc9-407a-99f6-f39922746027)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6257bfae-35f0-4c0e-b960-bca7aa6f86f7)  
(Hoch)  
[Microsoft Outlook Express 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=dab178f7-c282-41f4-acb1-a86e6aa4c91b)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://go.microsoft.com/fwlink/?linkid=120576)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://go.microsoft.com/fwlink/?linkid=122772)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://go.microsoft.com/fwlink/?linkid=120577)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://go.microsoft.com/fwlink/?linkid=104923)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://go.microsoft.com/fwlink/?linkid=117705)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://go.microsoft.com/fwlink/?linkid=108245)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d313f42c-f43f-48ea-82ef-3bc33077c7fa)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=69af2f30-138e-4b15-ab8d-4fce44cc0bc2)  
(Kritisch)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8e2125c7-52cb-4052-82a3-2d3c6a953752)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=01a34aa4-a456-4efc-a93a-c3c682b0181c)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=91469f2f-461c-4a67-8738-d42520427f6b)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f588f7e-c4ed-42a0-b157-54b1eda60474)  
(KB946648)  
(Hoch)  
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3150c6b8-f50b-4b84-a7ce-c8daf77c080c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4780b89e-9735-4d3f-8def-34e7337ff604)  
(Kritisch)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=39b41e4b-3237-409d-a818-ab0517c5e7cf)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=246b2686-e330-47a2-b4d4-68f218ad4021)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=2220aece-79d2-426f-90ec-24a17470567a)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](http://www.microsoft.com/downloads/details.aspx?familyid=a5fc5457-832f-4ee8-be60-4cc8518d1c10)  
(KB946648)  
(Hoch)  
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://go.microsoft.com/fwlink/?linkid=120576)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://go.microsoft.com/fwlink/?linkid=122772)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://go.microsoft.com/fwlink/?linkid=120577)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://go.microsoft.com/fwlink/?linkid=104923)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://go.microsoft.com/fwlink/?linkid=117705)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://go.microsoft.com/fwlink/?linkid=108245)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=828d8fdc-8534-4621-85a5-08aec255496f)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0617a5dd-dce9-4de0-b0a0-ce38efe13524)  
(Kritisch)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b3c2e2fd-1cb9-491b-937c-053dd59a65bf)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=92a3d08f-c117-4b24-bc78-2b913d270df6)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=30f2244a-f6fd-4fc1-a871-abf6958cb660)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=302315a8-ccb2-47c2-9104-b8e1d1f49aa0)  
(KB954723)  
(Mittel)  
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0a13776f-d543-41df-b904-d51e368c81cc)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=32a63f52-9fe6-48e3-bb4e-7d4dda5e0a90)  
(Kritisch)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=88a26b76-f7df-45c9-8ed0-7d3cd71c1987)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6bfbb6d8-5106-4adf-83cb-35ffc6e8eaf8)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3287f006-cbb2-4c6d-820c-32833e08035a)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=be94d138-7d7b-489e-baa6-e214950be6b9)  
(KB954723)  
(Mittel)  
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Mittel)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9566493f-4260-4072-947a-527887d2cd63)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1855997e-a3be-46b1-a0bc-bb55eb0045fe)  
(Kritisch)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=97d0d37d-5d76-4bc3-8cbd-1e3976c82acf)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=45356565-697f-41b3-9879-3edd11dbcb7e)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c8570e40-355b-4a9b-933d-53ae021cbda5)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e4b72618-536b-4a21-bd91-d91be9ca24e5)  
(KB954723)  
(Mittel)  
[Windows Messenger 5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
(Mittel)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://go.microsoft.com/fwlink/?linkid=120576)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://go.microsoft.com/fwlink/?linkid=122772)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://go.microsoft.com/fwlink/?linkid=120577)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://go.microsoft.com/fwlink/?linkid=104923)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://go.microsoft.com/fwlink/?linkid=117705)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://go.microsoft.com/fwlink/?linkid=108245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista und Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=13cba012-dd20-48f9-8e44-e4cb104c4cad)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista and Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3f21a8a2-9861-4fef-9d1e-caf5f7822c1a)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista and Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6418c78f-f008-4028-beb1-5a5ea8e797a1)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3851bcf8-f971-4d38-b27f-97396854aac0)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ead919c2-d548-47b7-9cd6-80f991266428)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=aa04a754-fbfb-42a7-89d2-14373e3f4742)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e03ccfb0-3ea3-4c59-adcf-9882d7086013)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3bf7eb8a-b347-4661-be2d-682adc713769)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-046**](http://go.microsoft.com/fwlink/?linkid=120576)
</td>
<td style="border:1px solid black;">
[**MS08-045**](http://go.microsoft.com/fwlink/?linkid=122772)
</td>
<td style="border:1px solid black;">
[**MS08-047**](http://go.microsoft.com/fwlink/?linkid=120577)
</td>
<td style="border:1px solid black;">
[**MS08-049**](http://go.microsoft.com/fwlink/?linkid=104923)
</td>
<td style="border:1px solid black;">
[**MS08-048**](http://go.microsoft.com/fwlink/?linkid=117705)
</td>
<td style="border:1px solid black;">
[**MS08-050**](http://go.microsoft.com/fwlink/?linkid=108245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4b52ff2f-d2f5-4c20-b6cf-86d86c56b0f8)\*\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c3363df6-39dc-4910-9ce5-66553155378e)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0640f95e-1eee-4dd1-b4dd-2b82b7e984b9)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=dc3c4b63-acd3-4469-8d47-e0562d99ee65)\*\*  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=df9814a6-5be0-4ac1-a767-a0eae8d5ee5d)\*\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=39dd1722-412b-469d-a475-b6513764838c)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=51a93538-5e94-4f81-a6e0-d497a7b4899d)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5f973f54-2322-4b41-8c1a-3e712c0da8ae)\*\*  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ffc3cfcb-73fe-4a6d-9595-e9d7a5b3d3f7)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e9c6cd46-30ad-46ee-9c8b-d0b446e660c4)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=390da130-749d-4890-aad7-be91e15b32bb)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9226cd85-1445-4976-a126-757c5d142ffd)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**\*Die Server Core-Installation von Windows Server 2008 ist betroffen.** Für unterstützte Editionen von Windows Server 2008 gilt dieses Update mit der gleichen Bewertung des Schweregrads. Dabei spielt es keine Rolle, ob Windows Server 2008 mit der Server Core-Installationsoption installiert wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie unter [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/core.mspx).

**\*\*Die Server Core-Installation von Windows Server 2008 ist nicht betroffen.** Die durch dieses Update behobene Sicherheitsanfälligkeit betrifft unterstützte Editionen von Windows Server 2008 nicht, wenn Windows Server 2008 mit der Server Core-Installationsoption installiert wurde. Weitere Informationen zu dieser Installationsoption finden Sie unter [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/core.mspx).

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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://go.microsoft.com/fwlink/?linkid=122912)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://go.microsoft.com/fwlink/?linkid=124306)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://go.microsoft.com/fwlink/?linkid=120394)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://go.microsoft.com/fwlink/?linkid=120819)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://go.microsoft.com/fwlink/?linkid=123160)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 8
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
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=458985c3-9c6f-4049-81cd-0d0389c81f11)  
(KB955428)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=54e4031d-298f-480c-88d5-0ad3b2b62ba9)  
(KB955441)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4bf8688e-e5b9-4e53-a1a1-8cf1acfdb80b)  
(KB951582)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e7c044d8-778a-4985-b25b-4f7f6e4abadd)  
(KB949007)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3ab323ec-9f92-453c-b7c7-9a95a9efcaea)  
(KB921595)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=34b655f8-1922-4246-94ca-ed381c3e3b13)  
(KB955440)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9bbf7550-f5c4-4b9b-bd86-1e7be6c42eb5)  
(KB951551)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f8921074-7985-4d42-ac2b-d2f3b1d466ba)  
(KB948995)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c7146dfc-e1be-4d13-877b-1d9bcacc4a64)  
(KB954463)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 und Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2003 Service Pack 2 und Microsoft Office Access 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fd698517-a504-427d-9e5f-fde8f102142c)  
(KB955439)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
(Hoch)  
[Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)\*\*  
(KB948988)  
(Hoch)  
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)\*\*  
(KB948988)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e0df2f6e-1102-461d-829f-5f3e2d7eb4b3)  
(KB921598)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
(Hoch)  
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office System 2007 und Microsoft Office System 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Excel 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
(Hoch)  
[Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef)  
(KB951338)  
(Hoch)  
[Microsoft Office PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef)  
(KB951338)  
(Hoch)
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
Weitere Office-Software
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://go.microsoft.com/fwlink/?linkid=122912)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://go.microsoft.com/fwlink/?linkid=124306)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://go.microsoft.com/fwlink/?linkid=120394)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://go.microsoft.com/fwlink/?linkid=120819)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://go.microsoft.com/fwlink/?linkid=123160)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 Service Pack 1
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
[Microsoft Office Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Snapshot Viewer für Microsoft Access
</td>
<td style="border:1px solid black;">
[Snapshot Viewer für Microsoft Access](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7c22bb32-7ce3-4ff2-8366-ba2eb5135833)  
(KB957198)  
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
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=911c8872-dec8-4b8e-9708-93dcabd3e036)  
(KB949041)  
(Hoch)
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
Microsoft Office Excel Viewer 2003 und Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
(Hoch)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b574d906-7f09-49b0-80bf-e84dee8c4583)  
(KB955472)  
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
Microsoft Office Converter Pack
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
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=199b08c7-6d79-4930-8f0c-31034629c485)  
(KB925256)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
(Hoch)  
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007](http://ww.microsoft.com/downloads/details.aspx?displaylang=de&familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
(Hoch)  
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1](http://ww.microsoft.com/downloads/details.aspx?displaylang=de&familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
(Hoch)
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
Microsoft Office SharePoint Server 2007 und Microsoft Office SharePoint Server 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a7731749-b026-4765-808a-e151b990f0e1)\*  
(KB953397)  
(Hoch)  
[Microsoft Office SharePoint Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a7731749-b026-4765-808a-e151b990f0e1)\*  
(KB953397)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 x64 Edition und Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)\*  
(KB953397)  
(Hoch)  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)\*  
(KB953397)  
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
<th colspan="6" style="border:1px solid black;">
Microsoft Office für Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-041**](http://go.microsoft.com/fwlink/?linkid=122912)
</td>
<td style="border:1px solid black;">
[**MS08-043**](http://go.microsoft.com/fwlink/?linkid=124306)
</td>
<td style="border:1px solid black;">
[**MS08-051**](http://go.microsoft.com/fwlink/?linkid=120394)
</td>
<td style="border:1px solid black;">
[**MS08-044**](http://go.microsoft.com/fwlink/?linkid=120819)
</td>
<td style="border:1px solid black;">
[**MS08-042**](http://go.microsoft.com/fwlink/?linkid=123160)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads des Bulletins**
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB956343)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB956343)  
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
Microsoft Office 2008 für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9515c70d-be80-4ade-856a-ea542f7d84e1)  
(KB956344)  
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
 
**\*Hinweis für Microsoft Office SharePoint Server 2007, Microsoft Office SharePoint Server 2007 Service Pack 1, Microsoft Office SharePoint Server 2007 x64 Edition und Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1 (MS08-043):** Das im Security Bulletin MS08-043 enthaltene Update gilt für Server, auf denen Excel Services installiert ist, z. B. die Standardkonfiguration von Microsoft Office SharePoint Server 2007 Enterprise und Microsoft Office SharePoint Server 2007 für Websites. Microsoft Office SharePoint Server 2007 Standard enthält Excel Services nicht.

**\*\*Hinweis für Microsoft Office PowerPoint 2003 Service Pack 2 und Microsoft Office PowerPoint 2003 Service Pack 3 (MS08-051):** Microsoft hat im Microsoft Download Center neue Updatepakete (Version 2) veröffentlicht. Benutzer, die Version 1 dieses Updates manuell vom Microsoft Download Center installiert haben, müssen Version 2 dieses Updates neu installieren. Benutzer, die dieses Update mit Microsoft Update oder Office Update installiert haben, müssen es nicht neu installieren. Weitere Informationen, einschließlich weiterer Optionen zur Installation oder Problemumgehung, finden Sie im Bulletin [MS08-051](http://go.microsoft.com/fwlink/?linkid=120394).

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Security Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind auch über [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) und [Office Update](http://office.microsoft.com/de-de/downloads/default.aspx) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Zu den Sicherheitsupdates dieses Monats stellt Microsoft Anleitungen zur Erkennung und Bereitstellung zur Verfügung: Diese Anleitungen geben auch IT-Profis Informationen zum Einsatz der verschiedenen Tools und zur Bereitstellung des Sicherheitsupdates. Behandelt werden u. a. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) und das Erweiterte Sicherheitsupdate-Inventurprogramm (ESUIT). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

Mit dem Microsoft Baseline Security Analyzer können Sie als Administrator Systeme sowohl lokal als auch remote auf fehlende Sicherheitspatches und fehlerhafte Konfigurationen überprüfen. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch die Website [Software Updates Service Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2/downloads/featurepacks/suspack/default.mspx) besuchen, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/smserver/default.mspx).

**Hinweis:** SMS nutzt Microsoft Baseline Security Analyzer und das Microsoft Office Detection Tool, um eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates bereitzustellen. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2003/downloads/featurepacks/adminpack.mspx) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

**Updatekompatibilitätsbewertung und Anwendungskompatibilitäts-Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), die im [Anwendungskompatibilitäts-Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Anwendungskompatibilitäts-Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen bösartiger Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services für 2008. Umfasst alle Windows-Inhalte.
-   [Neue, überarbeitete und veröffentlichte Updates für andere Microsoft-Produkte als Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214,aspx).

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Security Guidance für Updateverwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   [ISC/SANS](http://isc.sans.org/) für den Hinweis auf ein in MS08-042 beschriebenes Problem.
-   [VeriSign iDefense VCP](http://www.idefense.com/vcp) für den Hinweis auf ein in MS08-043 beschriebenes Problem.
-   [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) für den Hinweis auf ein in MS08-043 beschriebenes Problem.
-   Jeremy Funk für den Hinweis auf ein in MS08-043 beschriebenes Problem.
-   Shaun Colley von [NGS Software](http://www.nextgenss.com/) für den Hinweis auf ein in MS08-044 beschriebenes Problem.
-   Damian Put in Zusammenarbeit mit der [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/) für den Hinweis auf ein in MS08-044 beschriebenes Problem.
-   Einer Person, die mit [iDefense VCP](http://labs.idefense.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS08-044 beschriebenes Problem.
-   Damian Put in Zusammenarbeit mit [iDefense VCP](http://labs.idefense.com/) für den Hinweis auf ein in MS08-044 beschriebenes Problem.
-   Yamata Li von [Palo Alto Networks](http://www.paloaltonetworks.com/) für den Hinweis auf ein in MS08-045 beschriebenes Problem.
-   Tavis Ormandy vom [Google Security Team](http://www.google.com/) für den Hinweis auf ein in MS08-045 beschriebenes Problem.
-   Sam Thomas, der mit [TippingPoint](http://www.tippingpoint.com/) und der [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, für den Hinweis auf ein in MS08-045 beschriebenes Problem.
-   [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) für den Hinweis auf ein in MS08-045 beschriebenes Problem.
-   Jun Mao von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS08-046 beschriebenes Problem.
-   Jorge Luis Alvarez Medina von [Core Security Technologies](http://www.coresecurity.com/) für den Hinweis auf ein in MS08-048 beschriebenes Problem.
-   Yamata Li von [Palo Alto Networks](http://www.paloaltonetworks.com/) für den Hinweis auf ein in MS08-049 beschriebenes Problem.
-   Haifei Li vom [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com) von Fortinet für den Hinweis auf ein in MS08-050 beschriebenes Problem.
-   Vadim Pogulievsky vom [Malicious Code Research Center](http://www.finjan.com/securitylab.aspx?id=547) bei Finjan für den Hinweis auf ein in MS08-050 beschriebenes Problem.
-   Ruben Santamarta von [Reversemode.com](http://reversemode.com/) in Zusammenarbeit mit [iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS08-051 beschriebenes Problem.
-   ADLab von [Venustech](http://www.venustech.com.cn/) für den Hinweis auf ein in MS08-051 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über die [Microsoft Support Services](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos.
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (12. August 2008): Bulletin Summary veröffentlicht.
-   V2.0 (20. August 2008): Dem Abschnitt „Betroffene Software und Downloadadressen“ in MS08-043 wurde ein Hinweis hinzugefügt, um zu erklären, dass dieses Update für Server gilt, auf denen Excel Services installiert sind, z. B. die Standardkonfiguration von Microsoft Office SharePoint Server 2007 Enterprise und Microsoft Office SharePoint Server 2007 für Websites. Microsoft Office SharePoint Server 2007 Standard enthält Excel Services nicht. Außerdem wurde dem Abschnitt „Betroffene Software und Downloadadressen“ in MS08-051 ein Hinweis hinzugefügt, dass Microsoft im Microsoft Download Center neue Updatepakete (Version 2) für Microsoft Office PowerPoint 2003 Service Pack 2 und Microsoft Office PowerPoint 2003 Service Pack 3 veröffentlicht hat. Benutzer, die Version 1 dieses Updates manuell vom Microsoft Download Center installiert haben, müssen Version 2 dieses Updates neu installieren. Benutzer, die dieses Update mit Microsoft Update oder Office Update installiert haben, müssen es nicht neu installieren.
-   V3.0 (15. Oktober 2008): Das Update für Snapshot Viewer für Microsoft Access (MS08-041) wurde hinzugefügt. Benutzer, die das Update für Microsoft Office 2000 Service Pack 3, Office XP Service Pack 2, Office 2003 Service Pack 2 oder Office 2003 Service Pack 3 erfolgreich installiert haben, müssen das Update für den eigenständigen Snapshot Viewer für Microsoft Access nicht erneut installieren.

*Built at 2014-04-18T01:50:00Z-07:00*
