---
layout: ../layouts/LegalLayout.astro
title: Datenschutzerklärung
description: Wie miszori.dev, Mensaplan Zürich, amőba und vault mit Personendaten umgehen.
lang: de
updated: Stand 8. November 2026
other:
  href: /privacy/
  lang: en
  label: English
---

Diese Erklärung gilt für meine Website [miszori.dev](https://miszori.dev) und meine Apps [Mensaplan Zürich](https://mensa.miszori.dev), [amőba](https://amoeba.miszori.dev) und [vault](https://vault.miszori.dev). Es sind private, nicht kommerzielle Projekte. Ich halte mich an das Schweizer Datenschutzgesetz (DSG) und, soweit sie anwendbar ist, an die EU-Datenschutz-Grundverordnung (DSGVO).

Kurz gesagt: Es gibt keine Konten für Besucherinnen und Besucher, keine Werbung und keine Tracking-Cookies, und ich verkaufe oder teile Ihre Daten nicht. Ihre Einstellungen bleiben in Ihrem Browser.

## Verantwortlicher

Gergő Miszori, Schweiz  
E-Mail: [gergo@miszori.dev](mailto:gergo@miszori.dev)

Schreiben Sie an diese Adresse, wenn Sie Fragen zu Ihren Daten haben oder Ihre Rechte ausüben möchten.

## Cloudflare (alle Websites)

Jede Anfrage an diese Websites läuft über Cloudflare (Cloudflare, Inc., USA). Cloudflare liefert sie aus, schützt sie vor Angriffen und stellt HTTPS bereit; miszori.dev wird vollständig von Cloudflare ausgeliefert. Dafür verarbeitet Cloudflare Ihre IP-Adresse und technische Angaben zu jeder Anfrage, etwa die aufgerufene Adresse, die Uhrzeit, Ihren Browser (User-Agent) und die Seite, von der Sie kommen. Cloudflare handelt in meinem Auftrag, gestützt auf seinen Auftragsverarbeitungsvertrag. Für manche Daten, etwa Sicherheits- und Missbrauchsprotokolle, ist Cloudflare selbst verantwortlich; wie Cloudflare diese Daten bearbeitet und wie lange es sie aufbewahrt, steht in der [Datenschutzerklärung von Cloudflare](https://www.cloudflare.com/privacypolicy/).

Dabei können Daten in die USA übermittelt werden. Cloudflare ist unter dem EU-US- und dem Swiss-US Data Privacy Framework zertifiziert, das die EU und die Schweiz als angemessenen Schutz anerkennen.

Rechtsgrundlage ist mein berechtigtes Interesse, die Websites sicher und zuverlässig auszuliefern (Art. 6 Abs. 1 lit. f DSGVO).

### Cloudflare Web Analytics (miszori.dev und Mensaplan Zürich)

Diese beiden Websites zählen mit Cloudflare Web Analytics die Seitenaufrufe und sehen grob, wie sie genutzt werden. Dabei werden keine Cookies gesetzt, nichts in Ihrem Browser gespeichert und keine Profile erstellt. Ich sehe nur Gesamtzahlen, nie einzelne Besucherinnen oder Besucher. Ein Inhaltsblocker kann es verhindern. Rechtsgrundlage ist mein berechtigtes Interesse zu wissen, ob und wie die Websites genutzt werden (Art. 6 Abs. 1 lit. f DSGVO).

## Hosting (Mensaplan Zürich, amőba und vault)

Diese Apps laufen auf einem gemieteten Server in einem Rechenzentrum in Ungarn (EU). Der Hosting-Anbieter speichert die unten beschriebenen Daten in meinem Auftrag.

Ein gemeinsamer Proxy vor den Apps protokolliert Verbindungen. Weil der ganze Verkehr über Cloudflare kommt, sieht er nur die Adressen von Cloudflare, nicht Ihre.

## Mensaplan Zürich

- **Server-Log.** Der Webserver protokolliert jede Anfrage: Ihre IP-Adresse, die Uhrzeit, die Seite, Ihren Browser (User-Agent), die Seite, von der Sie kommen, und das Land, das Cloudflare meldet. Ich nutze das Log, um die App zu betreiben und Fehler oder Angriffe zu finden. Es ist auf 30 MB begrenzt; ist es voll, werden die ältesten Einträge automatisch gelöscht.
- **Einstellungen und Favoriten** (Standorte, Ernährung, Allergene, Budget, Sprache, markierte Mensen und Gerichte) werden nur in Ihrem Browser (Local Storage) gespeichert und nie an den Server gesendet.
- **Standort.** Wenn Sie die Mensen nach Entfernung sortieren, fragt Ihr Browser nach Ihrem Standort. Er wird nur in Ihrem Browser zur Berechnung der Entfernungen genutzt und nie gesendet oder gespeichert.
- **Offline-Menüs.** Die App speichert die Menüs aller angebotenen Tage (bis zu zehn) mit ihren Fotos in Ihrem Browser, damit sie offline funktioniert. Sie enthalten keine Personendaten.

Rechtsgrundlage für das Log ist mein berechtigtes Interesse an einer sicheren, funktionierenden App (Art. 6 Abs. 1 lit. f DSGVO).

## amőba

- **Benutzername.** Um online zu spielen, wählen Sie einen Benutzernamen. Er wird den anderen Spielerinnen und Spielern in Ihren Spielen und Räumen angezeigt und mit einer Liste anstössiger Wörter abgeglichen.
- **Spieldaten.** Ihre Sitzung, Räume und Züge werden nur im Arbeitsspeicher des Servers gehalten und nie auf die Festplatte geschrieben. Eine Sitzung wird 10 Minuten nach dem Verlassen gelöscht (1 Minute, wenn Sie nie einen Namen gewählt haben); bei einem Neustart des Servers ist alles weg.
- **IP-Adresse.** Solange Sie verbunden sind, hält der Server Ihre IP-Adresse im Arbeitsspeicher, um zu begrenzen, wie viele Verbindungen und neue Sitzungen eine Adresse öffnen kann. Sie wird weder protokolliert noch gespeichert.
- **Ihr Browser** speichert Ihren Benutzernamen und ein Sitzungstoken (Local Storage), damit Sie sich wieder mit einem Spiel verbinden können.
- Spiele gegen Amőbot und auf demselben Gerät laufen vollständig in Ihrem Browser und senden nichts an den Server.

Rechtsgrundlage ist die Bereitstellung des gewünschten Spiels (Art. 6 Abs. 1 lit. b DSGVO) und mein berechtigtes Interesse, Missbrauch zu verhindern (Art. 6 Abs. 1 lit. f DSGVO).

## vault

Mit vault teile ich Dateien und Texte mit bestimmten Personen.

- **Inhalte.** Dateien und Texte werden vor dem Hochladen in meinem Browser verschlüsselt. Der Schlüssel steht nur im Link; der Server speichert also nur verschlüsselte Daten und kann sie nicht lesen. Ein Paket wird gelöscht, wenn es abläuft, bei einem Einmal-Link nach dem einen Download oder wenn ich es lösche.
- **Abrufprotokoll.** Wenn Sie ein Paket herunterladen oder anzeigen, speichert der Server die Uhrzeit, Ihre IP-Adresse und die Angaben zu Browser, Betriebssystem und Gerät, die Ihr Browser mitsendet (User-Agent und Client Hints). Das Protokoll ist so verschlüsselt, dass nur ich es lesen kann. Ich nutze es, um zu sehen, ob und wann ein Paket abgerufen wurde, und um den Missbrauch eines weitergegebenen Links zu erkennen. Es wird bis 90 Tage nach Ablauf des Pakets aufbewahrt.
- **IP-Adresse.** Der Server nutzt Ihre IP-Adresse ausserdem im Arbeitsspeicher, um fehlgeschlagene Anfragen zu begrenzen. Das Log des Webservers enthält keine IP-Adressen und keine Browserangaben.

Rechtsgrundlage ist mein berechtigtes Interesse, Dateien sicher zu teilen und zu wissen, ob sie angekommen sind (Art. 6 Abs. 1 lit. f DSGVO).

## Cookies und Browserspeicher

Keine dieser Websites setzt Cookies. Mensaplan Zürich, amőba und miszori.dev (für das helle oder dunkle Design) speichern Einstellungen im Local Storage Ihres Browsers, nur damit die Website so funktioniert, wie Sie sie eingestellt haben. Sie können sie jederzeit in den Website-Einstellungen Ihres Browsers löschen.

## Wer Daten erhält

Nur Cloudflare und mein Hosting-Anbieter, wie oben beschrieben, und nur in meinem Auftrag. Ich verkaufe keine Daten und gebe sie nicht weiter, ausser das Gesetz verpflichtet mich dazu.

## Müssen Sie Daten angeben?

Nein. Ohne Ihre IP-Adresse und die technischen Anfragedaten können die Websites Ihnen aber nicht ausgeliefert werden, und ohne Benutzernamen können Sie amőba nicht online spielen.

## Ihre Rechte

Sie können Auskunft über Ihre Daten verlangen und sie berichtigen, löschen oder einschränken lassen. Sie können Ihre Daten in einem übertragbaren Format verlangen. Diese Rechte ergeben sich aus der DSGVO (Art. 15–20) und dem DSG. Senden Sie Ihre Anfrage an [gergo@miszori.dev](mailto:gergo@miszori.dev); sie ist kostenlos.

Um Log-Einträge oder Abrufprotokolle zu Ihnen zu finden, brauche ich Angaben wie Ihre IP-Adresse und die Zeit Ihres Besuchs, weil ich sonst nicht erkennen kann, welche Einträge Ihre sind.

Sie können sich auch bei einer Aufsichtsbehörde beschweren: in der Schweiz beim [Eidgenössischen Datenschutz- und Öffentlichkeitsbeauftragten (EDÖB)](https://www.edoeb.admin.ch), in der EU bei der Behörde des Landes, in dem Sie wohnen oder arbeiten.

Es gibt keine automatisierten Einzelentscheidungen und kein Profiling.

## Ihr Widerspruchsrecht

**Soweit ich Ihre Daten aufgrund meines berechtigten Interesses bearbeite (Art. 6 Abs. 1 lit. f DSGVO), können Sie jederzeit aus Gründen, die sich aus Ihrer besonderen Situation ergeben, widersprechen (Art. 21 DSGVO).** Ich höre dann damit auf, es sei denn, ich habe zwingende schutzwürdige Gründe, die Ihre Interessen, Rechte und Freiheiten überwiegen, oder die Bearbeitung dient Rechtsansprüchen. Senden Sie Ihren Widerspruch an [gergo@miszori.dev](mailto:gergo@miszori.dev).

## Änderungen

Ich passe diese Erklärung an, wenn sich die Websites ändern. Das Datum oben zeigt die aktuelle Fassung.
