---
lang: de
title: "Quiet: Datenschutzerklärung"
---

# Quiet: Datenschutzerklärung

[English](https://encrypster.github.io/quiet-privacy/) · [Oʻzbekcha](https://encrypster.github.io/quiet-privacy/uz/) · [Русский](https://encrypster.github.io/quiet-privacy/ru/) · Deutsch

Zuletzt aktualisiert: 20. November 2026

Quiet ist eine Startbildschirm-App für Android mit Werkzeugen, die helfen, das Handy weniger zu
nutzen: Limits und Sperren für Apps, ein Benachrichtigungsfilter, Statistiken zur
Bildschirmzeit, Fokussitzungen und Graustufen.

## Kurz gesagt

Quiet erhebt nichts für sich selbst. Es gibt kein Konto, keinen Server, keine Werbung und keine
Analyse. Alles, was Quiet speichert, bleibt auf Ihrem Handy und wird entfernt, wenn Sie die App
deinstallieren.

Die einzige Ausnahme ist eine Entscheidung der Eltern: Verbindet ein Elternteil einen eigenen
Telegram-Bot mit der Elternsperre, geht eine kurze Nachricht an diesen Bot, wenn Quiet Inhalte
für Erwachsene schließt (siehe „Nachricht an die Eltern“ unten). Ohne verbundenen Bot wird nichts
gesendet. Solange ein Bot verbunden ist, zeigt das Handy eine Benachrichtigung an.

## Was Quiet auf Ihrem Handy speichert

- Ihre Einstellungen, Favoriten, Regeln, Zeitpläne und Fokusprofile.
- Ein Nutzungsprotokoll: welche Apps im Vordergrund waren und wie lange, und wie oft das Handy
  entsperrt wurde. Es wird so viele Tage aufbewahrt, wie in Quiet eingestellt ist (angezeigt auf
  der Seite „Über Quiet“), und danach gelöscht.
- Benachrichtigungen, die Quiet für Sie zurückhalten soll: App, Titel und Text, bis Sie sie
  öffnen oder löschen, höchstens aber so viele Tage, wie in Quiet eingestellt ist.
- Ob Quiet Pro aktiv ist (nur in der Google-Play-Version).
- Wenn Sie eine Elternsperre einrichten: ein gesalzener Hashwert ihrer PIN, niemals die PIN selbst.
- Wenn ein Elternteil einen Telegram-Bot verbunden hat: dessen Token und Chat sowie die
  Schließungen, die noch nicht gemeldet wurden.

Nichts davon verlässt das Handy, mit Ausnahme der unten beschriebenen Nachrichten an den Bot der
Eltern. Eine Backup-Datei wird nur geschrieben, wenn Sie das wünschen, und zwar an den Ort, den
Sie wählen. Sie enthält nur Einstellungen: keinen Nutzungsverlauf und keine Benachrichtigungen.

## Wofür die einzelnen Zugriffe genutzt werden

- **Bedienungshilfen (Accessibility API).** Quiet liest, welche App auf dem Bildschirm ist, damit
  es die von Ihnen festgelegten Limits, Wartezeiten und Sperren anzeigen kann. Ist der Schalter
  für Shorts und Reels eingeschaltet, liest es außerdem die Namen von Bildschirmelementen in
  YouTube, Instagram und Facebook, um ein kurzes Video vom Rest zu unterscheiden. Während einer
  strengen Sitzung oder solange die Elternsperre aktiv ist, liest es den Text von Seiten der
  Systemeinstellungen: der Seiten zu Quiet, der Seite „Datum und Uhrzeit“ und, unter der
  Elternsperre, der Entwickleroptionen, damit diese geschlossen bleiben. Es führt die von Ihnen
  gewählten Gesten zum Sperren des Bildschirms und zum Öffnen der Benachrichtigungen aus. Ist das
  Schließen von Inhalten für Erwachsene eingeschaltet (Elternsperre), liest es die Wörter auf dem
  Bildschirm in Messengern, Browsern und sozialen Apps, um nach Wörtern zu suchen, die auf
  Inhalte für Erwachsene hinweisen, und in Telegram die Zeile, an der sich ein Bot von einer
  Person, einer Gruppe oder einem Kanal unterscheiden lässt, damit Bots, die die Eltern nicht
  erlaubt haben, geschlossen werden können. Ist zusätzlich die Bildprüfung eingeschaltet (Quiet
  Pro), macht es alle paar Sekunden ein Bild vom Bildschirm, solange eine dieser Apps im
  Vordergrund ist, und lässt es auf dem Handy von einem eingebauten Modell bewerten; das Bild
  wird sofort verworfen und weder gespeichert noch gesendet. All das wird auf dem Handy geprüft.
  Darüber hinaus liest es weder Ihre Eingaben noch Passwörter noch die Inhalte Ihrer Apps. Nichts,
  was es liest oder sieht, wird über das oben genannte Nutzungsprotokoll hinaus gespeichert, und
  nichts vom Bildschirm wird jemals gesendet.
- **Nutzungsdatenzugriff.** Zahlen zur Bildschirmzeit und Tageslimits.
- **Benachrichtigungszugriff.** Zurückhalten oder Stummschalten der Benachrichtigungen von Apps,
  die Sie auswählen.
- **Kalender (optional).** Anzeige Ihres nächsten Termins auf dem Startbildschirm. Termine werden
  beim Anzeigen gelesen und nicht gespeichert.
- **Geräteadministrator (optional).** Sorgt dafür, dass Quiet installiert bleibt, während eine
  von Ihnen gestartete strenge Sitzung läuft und solange für die Elternsperre eine PIN festgelegt
  ist. Er wird für nichts anderes genutzt und lässt sich in Quiet ausschalten, wenn keine strenge
  Sitzung läuft und die Elternsperre offen ist.
- **Geräteeigentümer (optional, von einem Elternteil über einen Computer eingerichtet).** Auf
  einem Handy, auf dem ein Elternteil Quiet zum Geräteeigentümer gemacht hat, verweigert das
  Handy selbst, solange die Elternsperre gesperrt ist, den Abgesicherten Modus, das Zurücksetzen
  auf Werkseinstellungen über die Einstellungen, das Ändern von Datum und Uhrzeit und das
  Hinzufügen neuer Nutzer. Dabei wird nichts gelesen.
- **Netzwerk (nur für den Telegram-Bot der Eltern).** Wird für nichts anderes genutzt.
- **Kontakte (optional).** Suche nach einem Kontakt anhand seines Namens in der App-Suche, wenn
  Sie das einschalten. Namen werden während der Suche gelesen und nicht gespeichert.
- **Liste der installierten Apps.** Ein Startbildschirm muss die Apps anzeigen, die sich öffnen
  lassen.

## Nachricht an die Eltern

Ein Elternteil kann einen eigenen Telegram-Bot erstellen und ihn auf der Seite der Elternsperre
verbinden. Von da an sendet Quiet diesem Bot jedes Mal, wenn es Inhalte für Erwachsene schließt,
eine kurze Nachricht für die Eltern: die Uhrzeit, den Namen der App und ob Wörter oder ein Bild
der Grund waren. Wörter, Bilder oder andere Inhalte vom Bildschirm werden niemals gesendet. Die
Nachrichten gehen direkt vom Handy an die Server von Telegram (api.telegram.org) und werden nach
der Datenschutzrichtlinie von Telegram verarbeitet; Quiet hat keinen Server und bewahrt nirgendwo
sonst eine Kopie auf. Der Bot lässt sich auf derselben Seite wieder trennen; solange die
Elternsperre gesperrt ist, können das nur die Eltern. Solange ein Bot verbunden ist, weist eine
Benachrichtigung auf dem Handy darauf hin, dass die Eltern informiert werden.

## Käufe

In der Google-Play-Version wird Quiet Pro über Google Play gekauft. Die Zahlung wickelt Google
nach seiner eigenen Datenschutzerklärung ab. Quiet erfährt nur, ob der Kauf besteht; es erhält
weder Ihren Namen noch Ihre E-Mail-Adresse noch Ihre Zahlungsdaten, und es hat keinen Server.

## Kinder

Quiet richtet sich nicht an Kinder. Ein Elternteil kann es mit der Elternsperre auf dem Handy
eines Kindes einrichten; das Kind sieht dann dieselben Hinweise und, wenn ein Bot verbunden ist,
die Benachrichtigung, dass die Eltern informiert werden. Quiet erhebt von niemandem Daten für
sich selbst.

## Wenn Sie in der EU, im EWR oder im Vereinigten Königreich leben

Die Datenschutz-Grundverordnung (DSGVO) und die UK GDPR geben Ihnen Rechte an Ihren
personenbezogenen Daten. So gelten sie für Quiet.

**Verantwortlich.** Quiet wird entwickelt von Test Developer, Test Street 1, 00000 Test City, test@example.com.

**Was der Entwickler erhält.** Nichts. Quiet hat keinen Server, kein Konto, keine Analyse und
keine Werbung; der Entwickler erhält oder speichert daher niemals personenbezogene Daten über Sie
oder Ihr Kind. Was Quiet speichert (siehe oben), bleibt auf Ihrem Handy und unter Ihrer
Kontrolle: Sie können alles mit „Alles löschen“ in Quiet löschen oder indem Sie die App
deinstallieren.

**Warum Quiet diese Daten auf Ihrem Handy verarbeitet.** Um das zu tun, was Sie eingeschaltet
haben (Art. 6 Abs. 1 lit. b DSGVO). Das Schließen von Inhalten für Erwachsene, die Bildprüfung und
die Nachricht an die Eltern schaltet ein Elternteil unter der Elternsperre ein, um ein Kind zu
schützen (Art. 6 Abs. 1 lit. f DSGVO, das berechtigte Interesse am Schutz Minderjähriger).
Bildschirmbilder werden auf dem Handy bewertet und sofort verworfen.

**Nachricht an die Eltern.** Verbindet ein Elternteil einen eigenen Telegram-Bot, gehen bei jeder
Schließung die Uhrzeit, der Name der App und der Grund vom Handy an Telegram, das diese Angaben
nach seiner eigenen Datenschutzrichtlinie auch außerhalb des EWR verarbeiten kann. Das
entscheiden die Eltern, und sie können es jederzeit beenden, indem sie den Bot trennen; solange
ein Bot verbunden ist, zeigt das Handy des Kindes eine Benachrichtigung an.

**Käufe.** Käufe wickelt Google Play als eigenständiger Verantwortlicher nach der
Datenschutzerklärung von Google ab.

**Ihre Rechte.** Sie können Auskunft über Ihre personenbezogenen Daten, deren Berichtigung oder
Löschung, die Einschränkung der Verarbeitung und die Datenübertragbarkeit verlangen sowie der
Verarbeitung widersprechen. Da der Entwickler keine Daten hat, üben Sie die meisten dieser Rechte
direkt auf dem Handy aus, wie oben beschrieben; Fragen richten Sie bitte an die unten genannte
Kontaktadresse. Außerdem können Sie sich bei der Datenschutzaufsichtsbehörde Ihres Landes
beschweren.

**Kinder.** In der EU kann ein Kind je nach Land ab einem Alter zwischen 13 und 16 Jahren selbst
in Online-Dienste einwilligen; darunter entscheiden die Eltern. Die Elternfunktionen von Quiet
sind dafür gedacht, dass ein Elternteil sie auf dem Handy eines Kindes einrichtet.

## Änderungen

Wenn sich diese Datenschutzerklärung ändert, wird der neue Text unter dieser Adresse mit neuem
Datum veröffentlicht.

## Kontakt

test@example.com

Maßgeblich ist die englische Fassung dieser Datenschutzerklärung.
