# QA-Prüfbericht

**Geprüft:** `04-prototype/index.html`
**Abgeglichen mit:** `02-strategy.md`, `03-copywriting.md` (für die Bitkom-Zahl zusätzlich `01-research.md`)
**Hinweis:** „KLARBLICK“ ist der vom CEO festgelegte Arbeitsname und wird nicht als Fehler gewertet.

---

## 🔴 Muss korrigiert werden

Keine Befunde. Es gibt keine Syntaxfehler, keine inhaltlichen Widersprüche zu Strategie oder Texten und keine vergessenen Platzhalter.

---

## 🟡 Sollte korrigiert werden

1. **Die CTA-Buttons im Abschnitt `<section class="cta" id="termin">` verweisen auf sich selbst.** Beide Buttons (`href="#termin"`) liegen innerhalb von `#termin`, ein Klick bewirkt also nichts.
   *Vorschlag:* Eigene Ziele wie `#buchung` und `#vorbestellen` mit Platzhalter-Abschnitt oder Dummy-Formular (PLZ-Feld plus Button) anlegen.
2. **Die Kopfzeile kann auf schmalen Handys (ca. 320–360 px) eng werden.** `.topbar .container` hat kein `gap` und kein `flex-wrap`, Logo und Link stoßen aneinander.
   *Vorschlag:* `gap: 1rem;` ergänzen und unter 480 px den Linktext kürzen („Termin buchen“).
3. **Die Formulierung im Hero-Satz zur Bitkom-Zahl ist etwas zu weit gefasst.** „76 % der Deutschen“ verallgemeinert die Grundgesamtheit.
   *Vorschlag:* „76 % der Befragten in Deutschland“. Der Satz „KLARBLICK hat deshalb gar keine Kamera.“ betont den Verzicht. Nutzenorientierter wäre: „… keine Kamera – Sie können sie überall tragen.“
4. **Ein Versprechen ohne Link** (Karte 04): „Datenschutz-Dokumentation öffentlich einsehbar“, aber auf der Seite gibt es keinen Link dorthin.
   *Vorschlag:* Einen Platzhalter-Link „Datenschutz-Dokumentation ansehen“ ergänzen.
5. **Im Footer fehlen Impressum und Datenschutzerklärung.** Für einen Livegang in Deutschland sind beide Pflicht.
   *Vorschlag:* Platzhalter-Links anlegen.
6. **Du/Sie-Wechsel:** Der Slogan duzt („für dich“), der übrige Text siezt.
   *Vorschlag:* Mit dem Copywriter klären.
7. **Barrierefreiheit beim Fußnoten-Link:** Ein Screenreader liest nur „1“ vor.
   *Vorschlag:* `aria-label="Quelle 1"` ergänzen.

---

## 🟢 Bestandene Punkte

- **HTML-Syntax:** korrekt und semantisch (header/main/section/article/footer), `lang="de"`, saubere Überschriften-Hierarchie.
- **Textübernahme:** wortgleich mit `03-copywriting.md`, kein Platzhalter übrig geblieben.
- **Copywriter-Hinweise eingehalten:** kein Preis, kein Prüfsiegel, keine Live-Untertitel, Bitkom-Zahl mit Quelle und Jahr.
- **Positionierung:** alle Strategie-Kernpunkte abgebildet, keine Widersprüche.
- **CTA:** klare Hauptaktion (Beratungstermin), die dreimal erscheint und sich deutlich von der sekundären Aktion abhebt.
- **Responsive Layout:** Grid wechselt bei 760 px, Buttons umbrechen sauber, Typografie mit `clamp()`.
- **Kontrast:** etwa 5:1, erfüllt WCAG AA.
- **Transparenz:** Demo-Hinweis und Arbeitsname im Footer gekennzeichnet.

---

## Fazit: Lieferfähig?

**Ja, als Prototyp lieferfähig.** Es gibt keine 🔴-Befunde. Vor einer Präsentation sollten die Punkte 1 und 2 behoben werden, vor einem echten Livegang zusätzlich die Punkte 4 und 5.
