# Projekt-Gesamtbericht: KLARBLICK (Arbeitsname) – kamerafreie Display-Brille für den deutschen Markt

*Stand: 20.11.2026. Geprüft wurden `01-research.md`, `02-strategy.md`, `03-copywriting.md`, `04-prototype/index.html` und `05-qa-report.md`.*

---

## Management Summary

Das Team hat in fünf Phasen eine durchgängige Kette erarbeitet: Marktanalyse, Positionierung, Marketingtexte, Landingpage-Prototyp und Qualitätsprüfung. Kern des Ergebnisses ist eine klare und gut belegte strategische Wette. KLARBLICK greift Meta nicht im Kamera-Massenmarkt an, sondern wird als **Display-Brille ohne Kamera für berufstätige Brillenträger** positioniert, mit Gleitsicht über Partner-Optiker und Datenverarbeitung in der EU. Diese Linie zieht sich ohne Bruch von der Recherche bis zur Webseite, und die Webseite setzt die Texte fast wortgleich um. Die Schwachstellen liegen weniger in der Umsetzung als im Fundament: Die Abgrenzung zum direkten Vorbild Even Realities ist dünn, Machbarkeit, Kosten und Hardware-Beschaffung fehlen vollständig, und der Zeitplan (Pilot ab Juni 2027) setzt ein Produkt voraus, für das es noch keinen Entwicklungspfad gibt. Außerdem verspricht die Webseite Dinge im Präsens, die es noch nicht gibt. Das Ergebnis ist ein überzeugendes Konzept- und Kommunikationspaket. Eine Investitionsentscheidung lässt sich darauf noch nicht stützen.

---

## Überblick über die Ergebnisse der Phasen

| Phase | Ergebnis | Status |
|---|---|---|
| 01 Marktforschung | Gut belegter Bericht mit 32 Quellen zu Markt, Wettbewerb, Zielgruppen, Recht (DSGVO, AI Act, TDDDG, Batterieverordnung) und Chancen. Schätzungen und Lücken sind sauber gekennzeichnet. | Abgeschlossen. Kernzahlen für DE (Marktgröße, Absatz) fehlen bzw. sind nicht verifiziert. |
| 02 Strategie | Positionierung „kamerafrei, Display, Gleitsicht über Optiker, EU-Daten“, Zielgruppenpriorisierung, Wettbewerbsvergleich und GTM in vier Phasen (Dez. 2026 bis 2029). | Abgeschlossen. Stark in Logik und Quellenbezug, schwach bei Machbarkeit, Kosten, Preis und Abgrenzung zu Even Realities. |
| 03 Copywriting | Slogan, Hero, vier Kernvorteile, CTA, acht Präsentationsaussagen und interne Hinweise (kein Preis, kein Siegel, keine Untertitel auf der Startseite). | Abgeschlossen. Markentreu, aber mit einigen Überversprechen und einem Du/Sie-Bruch. |
| 04 Prototyp | Einseitige, responsive Landingpage (HTML/CSS, ohne Abhängigkeiten) mit Hero, vier Vorteilskarten, CTA, Quellenfußnote und Demo-Hinweis. | Als Demo nutzbar. Gelbe QA-Punkte sind offen, darunter funktionslose CTA-Buttons. |
| 05 QA | Sieben gelbe Befunde, keine roten. Syntax, Semantik, Kontrast und Strategietreue geprüft. | Abgeschlossen. Prüfung solide, aber auf Technik und Text fokussiert. Inhaltliche Risiken (siehe unten) wurden nicht erfasst. Wegen fehlender roter Punkte gab es keine Korrekturschleife, die gelben Punkte sind daher alle offen. |

---

## Stärken

1. **Durchgängige Linie von der Analyse bis zur Webseite.** Die Strategie leitet sich direkt aus den Befunden der Recherche ab: Bitkom 76 % / 82 % / 62 %, HmbBfDI-Prüfbericht, HateAid-Anzeige gegen Händler, Lücke bei Display plus Sehstärke in DE. Die Texte übernehmen Positionierung und Kurzform („Sieht alles für dich. Filmt niemanden.“), und der Prototyp setzt die Texte bis auf eine Ergänzung wortgleich um. Abweichungen von der Positionierung habe ich nicht gefunden.

2. **Ehrlicher Umgang mit Unsicherheit.** Recherche und Strategie trennen konsequent zwischen Belegen, eigenen Annahmen und Datenlücken („Informationen unzureichend, weitere Recherche empfohlen“). Die nicht verifizierte MarketsandMarkets-Zahl wird zum Beispiel ausdrücklich nur als Größenordnung behandelt. Das macht die Unterlagen belastbarer als übliche Pitch-Dokumente.

3. **Strategisch kluge Grundentscheidung.** Wer den Kamerakonflikt meidet, hat in Deutschland gleich mehrere Vorteile: weniger Rechtsrisiko für Hersteller und Händler, ein glaubwürdiges Argument gegenüber Arbeitgebern und Betriebsräten und einen Optikerkanal, den Meta kaum bedient. Auch die „Was wir bewusst nicht sind“-Liste ist diszipliniert, besonders der dauerhafte Verzicht auf Gesichtserkennung mit Blick auf Art. 5 AI Act.

4. **Gute Disziplin bei den Texten.** Der Copywriter hat Preis, Prüfsiegel und Live-Untertitel bewusst weggelassen, weil sie noch nicht entschieden oder belegt sind. Die Strategie-Vorgabe „Nutzen statt Verzicht kommunizieren“ ist in den Kernvorteilen gut umgesetzt (Stichwortzettel, Übersetzung im Kundengespräch, Blick beim Gegenüber).

5. **Technisch sauberer Prototyp.** Semantisches HTML, `lang="de"`, responsives Grid, `clamp()`-Typografie, Kontrast nach WCAG AA (das Akzent-Blau auf Weiß liegt rechnerisch bei etwa 5:1, die QA-Angabe stimmt). Die Bitkom-Zahl hat eine korrekte Quellenfußnote, Demo-Status und Arbeitsname sind transparent gekennzeichnet.

6. **Realistischer GTM-Ansatz.** Ein Go/No-Go-Kriterium in Phase 0 (mindestens 10 verbindliche Optiker-Zusagen), der Pilot in Großstädten und der bewusste Verzicht auf Elektronikmärkte und Fielmann in Phase 1 sind gut begründet.

---

## Verbesserungsbedarf

### A. Inhaltlich und strategisch (wichtiger als die QA-Befunde)

1. **Die Abgrenzung zu Even Realities trägt nicht.** Die Positionierung sagt „anders als Meta und Even Realities … vom ersten Tag an mit Gleitsichtgläsern … beim Optiker vor Ort“. Laut Recherche bietet Even Realities aber bereits Ein- und Mehrstärkengläser an, Gleitsicht über Partner-Optiker, und hat eine deutschsprachige Seite für die Schweiz. Die eigene Vergleichstabelle zeigt dasselbe Modell: „über Partner-Optiker“ gegenüber „nur über Partner“. Der eigentliche Unterschied liegt also nur in der Dichte des Optikernetzes und im Datenschutzversprechen. Das lässt sich kopieren, sobald Even Realities in Deutschland Ernst macht. Kamerafreiheit ist ein Kategorie-Merkmal und kein Alleinstellungsmerkmal von KLARBLICK.

2. **Es fehlt jede Aussage dazu, wie das Produkt entsteht.** Keine Phase behandelt Hardware, Displaytechnik (Waveguides sind laut Recherche knapp, siehe Metas verzögerter EU-Start), Herstellkosten, Eigenentwicklung oder OEM-Partner. Die Recherche liefert dafür sogar einen Ansatz: Vuzix verlagert seinen Fokus auf OEM und Waveguides. Ohne Antwort auf diese Frage sind Preisrahmen und Zeitplan nicht prüfbar.

3. **Der Zeitplan ist vermutlich unrealistisch.** Phase 0 endet im Mai 2027, und schon ab Juni 2027 sollen Partner-Optiker Geräte mit Gleitsicht anpassen. Bis dahin müssten CE-Konformität (RED, EMV), eine Klärung zum Medizinprodukterecht der Korrekturgläser und ein serienreifes Gerät vorliegen. Bei einer Eigenentwicklung ist das in sechs bis sieben Monaten kaum zu schaffen. Das Ziel „vor Apple Ende 2027 im Markt“ hängt komplett an dieser offenen Frage.

4. **Die Webseite verspricht Dinge, die es noch nicht gibt.** Der Copywriter hat das Prüfsiegel richtigerweise weggelassen, weil es noch nicht erteilt ist. Andere, ebenso unbelegte Zusagen stehen aber im Präsens: „Eine verständliche Datenschutz-Dokumentation auf Deutsch ist öffentlich einsehbar“, „Sie bekommen sie vom ersten Tag an … auch als Gleitsicht“ und „Bedienen können Sie alles mit dem deutschen Sprachassistenten“. Das ist inkonsequent und bei einer Veröffentlichung wettbewerbsrechtlich riskant (irreführende Werbung).

5. **Bei der Garantie verspricht die Webseite mehr als die Strategie.** Die Strategie formuliert: Service „unabhängig vom Kaufkanal, *solange der Kauf über einen zertifizierten Partner läuft*“. Text und Webseite sagen dagegen: „bei jedem zertifizierten Partner, *egal, wo Sie gekauft haben*“. Das ist eine weitreichendere Garantiezusage, als die Strategie vorsieht.

6. **Der Slogan ist mehrdeutig und hat einen Tonbruch.** „Sieht alles für dich“ legt bei einer Brille, deren Kernversprechen „keine Kamera“ ist, gerade Sehen und Erfassen nahe. Skeptische Leser können das als Widerspruch verstehen. Außerdem duzt der Slogan, während der übrige Text siezt. Die QA hat den Du/Sie-Bruch gemeldet, die Ursache liegt aber schon in der Strategie. Den Slogan sollte man mit der Zielgruppe testen.

7. **Die Bedienung passt nicht zum Einsatzszenario.** Die Kernszenarien sind Meeting, Kundengespräch und Vortrag. Dort ist Sprachsteuerung sozial genauso heikel wie eine Kamera. Even Realities löst das mit einem Ring. Strategie und Texte behandeln stille Bedienung (Touch, Ring, Smartphone) nicht.

8. **Eine Präsentationsaussage ist zu pauschal.** „Brillenträger gehen bisher leer aus“ (Kernaussage 2) passt nicht zur eigenen Recherche: Meta hat eine Optics-Linie ab 469 €, Even Realities bietet Mehrstärkengläser. Präziser wäre: „Display-Brillen mit Gleitsicht und Beratung vor Ort gibt es in Deutschland kaum.“

9. **Markenname und Markenschutz.** „KLARBLICK“ ist als Arbeitsname gesetzt. Der Begriff ist in der Augenoptik naheliegend und wird vermutlich schon von Dritten genutzt (Optiker, Brillenputzmittel o. Ä.). Das habe ich nicht geprüft, eine Recherche bei DPMA und EUIPO sollte vor jeder externen Nutzung erfolgen.

### B. Prototyp und QA

10. **Alle gelben QA-Punkte sind offen.** Weil es keine roten Punkte gab, wurde nichts korrigiert. Für eine Präsentation störend sind vor allem die CTA-Buttons ohne Funktion (alle Links zeigen auf `#termin` und damit auf den Bereich, in dem sie selbst stehen) und die enge Kopfzeile auf kleinen Handys. Vor einem Livegang sind Impressum und Datenschutzerklärung Pflicht.

11. **Die QA-Aussage „wortgleich“ stimmt nicht ganz.** Der Satz im Hero „76 % der Deutschen … KLARBLICK hat deshalb gar keine Kamera.“ steht so nicht in `03-copywriting.md`. Er stammt aus Präsentationsaussage 1 und wurde vom Entwickler ergänzt. Inhaltlich ist er vertretbar. Die QA nennt ihn selbst als Verallgemeinerung und Verzicht-Formulierung, bestätigt aber trotzdem Wortgleichheit.

12. **Es fehlt ein Produktbild.** Die Karte „Ein Versprechen, das man sieht“ wirbt mit sichtbarer Kamerafreiheit, die Seite zeigt aber kein Bild und keine Grafik der Brille. Für das zentrale Argument fehlt damit der Beleg auf der Seite.

13. **Der Hauptkanal kommt auf der Webseite nicht vor.** Laut GTM sind unabhängige Optiker der Hauptkanal, und Phase 0 hängt an Optiker-Zusagen. Die Seite spricht aber nur Endkunden an. Einen Bereich „Partner-Optiker werden“ gibt es nicht, ebenso wenig Optikersuche, FAQ oder „So funktioniert es“.

14. **Die QA hat nur Technik und Text geprüft.** Rechtliche Wirkung (Werbeaussagen, Garantie), Plausibilität und Machbarkeit wurden nicht geprüft. Die Punkte 4, 5 und 6 in Abschnitt A wären bei einer inhaltlichen Prüfung als rot einzustufen, sobald die Seite veröffentlicht wird.

---

## Empfohlene nächste Schritte (nach Priorität)

1. **Produktmachbarkeit klären (Voraussetzung für alles Weitere).** Eigenentwicklung oder OEM bzw. White-Label prüfen (z. B. Waveguide- und OEM-Anbieter wie Vuzix ansprechen). Herstellkosten, Lieferzeiten für Displays und Bedienkonzept (Touch, Ring, Sprache) festlegen. Den Zeitplan der Phasen 0 und 1 danach realistisch neu planen.
2. **Die Abgrenzung zu Even Realities schärfen.** Even Realities in DACH genau analysieren (Euro-Preis, Partner-Optiker, Gleitsicht-Prozess). Daraus einen Vorteil ableiten, der sich nicht leicht kopieren lässt, z. B. Exklusivverträge mit Optiker-Einkaufsverbünden, ein überprüfbares Datenschutzgutachten oder ein Angebot für Arbeitgeber und Betriebsräte.
3. **Rechtliche Grundlagen schaffen.** Medizinprodukterechtliche Einordnung der Korrekturgläser, CE-Weg, Status der Wearable-Ausnahme in der Batterieverordnung und eine Markenrecherche zu „KLARBLICK“ (DPMA/EUIPO).
4. **Webseiten-Aussagen absichern, bevor etwas veröffentlicht wird.** Unbelegte Zusagen ins Futur setzen oder entfernen („geplant“, „zum Marktstart“). Die Garantie auf den Wortlaut der Strategie zurückführen. Ansprache vereinheitlichen (Sie) und Slogan-Varianten mit 20–30 Personen aus der Zielgruppe testen.
5. **Prototyp für die Präsentation fertigstellen.** Gelbe QA-Punkte 1 bis 7 umsetzen (eigene Ziele für Buchung und Vorbestellung mit Dummy-Formular, Kopfzeile mobil, „76 % der Befragten“, Platzhalter-Links für Datenschutz-Dokumentation, Impressum und Datenschutzerklärung, `aria-label` an der Fußnote). Dazu ein Produktvisual und einen Bereich „Partner-Optiker werden“ ergänzen.
6. **Datenlücken schließen, die für die Investitionsentscheidung zählen.** Marktdaten kaufen (NIQ/GfK oder Statista), Zahl der Gleitsichtträger in DE ermitteln, 10–15 Optiker-Interviews zu Marge und Anpassungsaufwand führen und Preis-Interviews bzw. eine Conjoint-Studie für den Korridor zwischen 419 € und 899 € durchführen.
7. **Regulatorisches Umfeld beobachten.** Ausgang der HateAid-Anzeige, mögliche Maßnahmen der HmbBfDI und ein Deutschland-Start von Google/Samsung können die Positionierung stärken oder schwächen und sollten quartalsweise geprüft werden.
8. **Segment 2 (Live-Untertitel) erst nach geklärter Hilfsmittelerstattung budgetieren.** Bis dahin wie geplant als Verbandspilot behandeln.
