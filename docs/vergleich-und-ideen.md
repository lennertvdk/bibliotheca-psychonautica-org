# Website-Vergleich: was wir von zwei Vorbildern übernehmen können

Stand: 26.09.2026 · Arbeitsnotiz zum Besprechen, danach umsetzen

Verglichen wurden:

- **psychedelia-stiftung.de** — inhaltlich nah, ähnliche Zielgruppe, ähnlich jung
- **embassyofthefreemind.com** (Bibliotheca Philosophica Hermetica, Amsterdam) — **das eigentliche Vorbild**: eine private Sammlung esoterischer Literatur, die zu einer öffentlichen Institution geworden ist. Genau der Weg, den wir vor uns haben.

---

## Kurzfazit

Die Embassy zeigt, wie unser Projekt in zehn Jahren aussehen könnte. Der entscheidende
Unterschied ist nicht Design, sondern **was im Zentrum steht**: bei ihnen der Bestand
selbst — durchsuchbar, digitalisiert, mit Artikeln zu einzelnen Objekten. Bei uns steht
dort aktuell der Satz *„Die Liste des bis jetzt erfassten Bibliotheksbestandes kann beim
Verein angefordert werden."* Das ist eine Sackgasse an der Stelle, wo bei ihnen das
Herzstück liegt.

Die Psychedelia-Stiftung ist strukturell näher an unserer Grösse (4 Navipunkte, eine
Handvoll Seiten) und hat zwei Muster, die wir direkt kopieren können: die nach
**Zielgruppe** sortierte Kontaktaufnahme und den Newsletter.

---

## Die drei grossen Ideen

### 1. Den Bestand online sichtbar machen

Die Embassy hat *Full Library Catalogue* und *Digitised & Translated Catalogue* als
eigene Navigationspunkte. Der Katalog ist bei ihnen kein Anhang, sondern das Produkt.

Für uns: auch eine schlichte, statische, alphabetische Liste dessen, was bisher
inventarisiert ist, wäre um Klassen besser als „auf Anfrage". Sie ist der einzige
glaubwürdige Beweis, dass die Bibliothek wirklich existiert und betreut wird — genau
das, was Sammler sehen wollen, bevor sie einen Nachlass vermachen.

- Stufe 1: Inventar als sortierbare HTML-Tabelle exportieren (auch 200 Titel reichen)
- Stufe 2: nach Thema filterbar, an die bestehende Themenliste andocken
- Stufe 3: durchsuchbar, mit Digitalisaten

Aufwand Stufe 1 hängt davon ab, in welcher Form das Inventar heute vorliegt.
**Lennert ist das Format nicht bekannt → Frage geht an Tom: wird überhaupt digital
inventarisiert, und wenn ja, womit (Excel, Access, Zettelkasten, Bibliothekssoftware)?**
Das ist die erste Frage, die beantwortet sein muss — alles Weitere hängt daran.

### 2. Ein Artikel pro Objekt

Auf der Embassy-Startseite stehen neun ausführliche Fachartikel, jeder über ein
konkretes Stück aus der Sammlung. Das erzeugt gleichzeitig wissenschaftliche
Glaubwürdigkeit **und** Auffindbarkeit über Google — eine Sammlungsseite ohne Texte
wird nicht gefunden.

Wir haben mit `Beitrag.html` bereits ein Artikel-Template, es ist nur leer.
Ein einziger echter Artikel — etwa über die von Hofmann und Ott signierte Ausgabe —
würde mehr für unsere Glaubwürdigkeit tun als jeder Redesign.

### 3. Anfragen nach Zielgruppe statt nach Thema

Die Psychedelia-Stiftung fragt nicht „worum geht es?", sondern „wer bist du?":
*Studierende und Peers · Medien · Fachpersonen · Öffentlicher Sektor*, jeweils mit
Button „Anfrage starten →". Das Formular öffnet sich darunter und übernimmt das Thema
automatisch.

Unsere vier Interesse-Checkboxen machen fast dasselbe, aber thematisch sortiert, was
schwächer ist — Menschen ordnen sich leichter selbst ein als ihr Anliegen. Umbau zu:

- Ich habe eine Sammlung oder Bibliothek
- Ich verwalte einen Nachlass *(eigene, behutsame Ansprache — oft Trauerfall)*
- Ich möchte mithelfen
- Ich forsche / bin Studentin oder Student
- Presse

Die Technik dafür steht schon: `Kontakt.html?interesse=…` füllt das Formular korrekt
vor, ist getestet.

---

## Kleinere Übernahmen, nach Aufwand

### Schnell (Stunden)

| Idee | Von wem | Warum |
|---|---|---|
| **Newsletter-Anmeldung im Footer** | beide | Wir haben gar keine. Billigster Weg, mit Leuten in Kontakt zu bleiben, die *später* eine Sammlung vermachen. Embassy gibt ihrem sogar einen Namen (*Codex Hermeticus*) — Marke statt Formular. |
| **Ankündigungsleiste über der Navigation** | Embassy | Sie kündigen dort neue Öffnungszeiten an. Bei uns: Basel 2028, neue Nachlässe, Veranstaltungen. |
| **Adresse + Öffnungszeiten dauerhaft im Footer** | Embassy | Wir sagen nirgends, ob man Solothurn überhaupt besuchen kann. Auch „Besuch nach Vereinbarung" ist eine Antwort — im Moment ist es eine offene Frage. |
| **Partner-Logos als eigener Block** | beide | Wir nennen Gaia Media und Nachtschatten, zeigen aber nur ein Logo. Beide Vorbilder führen ihr Netzwerk prominent — fremde Reputation färbt ab. |

### Mittel (Tage)

| Idee | Von wem | Warum |
|---|---|---|
| **Roger als Gründerfigur** | Embassy | Die Embassy hat eine eigene Seite für ihren Gründer Joost Ritman. Roger Liggenstorfer plus 40 Jahre Nachtschatten ist eine mindestens ebenso gute Geschichte und unser stärkstes Glaubwürdigkeits-Asset. Steht aktuell als eine Zeile auf *Der Verein*. |
| **Der Ort als Geschichte** | Embassy | *„House with the Heads — A Monument to Free Thinking"*: das Gebäude ist Teil der Erzählung. Wir haben die Räume des Nachtschatten Verlags und ab 2028 Basel — bei uns ist das eine Fussnote. |
| **Objektfotografie statt Regalfotografie** | Embassy | Ihre Bilder zeigen einzelne Stücke, aufwendig fotografiert. Unsere zeigen Regale, Staub und Spinnweben. Für den Nachlass-Abschnitt ist das richtig — das ist das Problem, das wir lösen. Auf der Bestandsseite arbeitet es gegen uns: dort muss das „Nachher" stehen. |

### Gross (Wochen, eigene Entscheidung nötig)

- **Veranstaltungen / Academy.** Die Embassy hat Kurse, Führungen, Ausstellungen; die
  Psychedelia-Stiftung Dialogformate. Unser Termine-Tab ist leer. Das ist keine
  Website-Frage, sondern eine Vereinsfrage — aber die Website sollte den Platz dafür
  schon haben (hat sie).
- **Einnahmen jenseits von Mitgliedschaft und Spende.** Embassy: Tickets, Café,
  Raumvermietung, Shop. Für uns vorerst unrealistisch, aber Basel 2028 ist der Moment,
  wo das relevant wird.

---

## Was wir bewusst *nicht* übernehmen

- **Die Mega-Navigation der Embassy.** Sechs Menüpunkte mit je 5–6 Unterpunkten — sie
  haben über dreissig Seiten. Wir haben sieben. Unsere flache Leiste ist für unsere
  Grösse richtig; wenn Katalog und Artikel dazukommen, gruppieren wir, statt Punkte
  anzuhängen.
- **Cookie-Banner und Tracking.** Beide Seiten empfangen einen mit einem Cookie-Dialog.
  Wir haben aktuell keinerlei Tracker — das ist ein datenschutzrechtlicher Vorteil und
  ein besserer erster Eindruck. Nicht ohne konkreten Anlass aufgeben.
- **Die Abstraktionsebene der Psychedelia-Stiftung.** *„Eine Brücke zwischen Forschung,
  Kultur und Gesellschaft"* könnte auf jeder Stiftungsseite stehen. Unser
  *„Bücher, die sonst verloren gingen"* ist konkreter und besser. Nicht verwässern.

---

## Was uns die beiden Seiten über unsere Lücken sagen

Beide Vorbilder haben, was wir noch nicht haben, und es ist in beiden Fällen
**kein Design, sondern Inhalt**:

1. echte Texte über echte Objekte
2. einen sichtbaren Bestand
3. Fotos von Menschen und Dingen, nicht von Regalen
4. einen laufenden Kanal (Newsletter) statt nur eines Formulars

Unsere 39 `[PLATZHALTER]` auf den öffentlichen Seiten sind damit nicht ein kosmetisches
Restproblem, sondern genau der Abstand zwischen uns und diesen Seiten.

---

## Fragen an dich und Tom

1. **In welchem Format liegt das Inventar vor?** Lennert weiss es nicht — also direkt
   an Tom. Davon hängt ab, ob die Katalogseite ein Nachmittag oder ein Projekt ist.
2. Kann man die Bibliothek in Solothurn besuchen — und unter welchen Bedingungen?
3. Gibt es jemanden, der einen ersten Artikel über ein Objekt schreiben würde?
   (Tom? Roger? eine Studentin?)
4. Newsletter: wollen wir den, und wer betreut ihn?
5. Dürfen wir Objekte aus der Sammlung neu fotografieren — und wer kann das?
