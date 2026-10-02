# KI-Nutzungsprotokoll, Gruppe <NN>

**Verwendete Werkzeuge:** <z. B. ChatGPT (GPT-5), GitHub Copilot, Claude, lokale Modelle>

---

## Teil 1 + 2: Gruppenarbeit

| # | Artefakt | Wofür eingesetzt | Was kam heraus | Was wir damit gemacht haben |
|---|---|---|---|---|
| 1 | B2 Modell | „Kritisiere unser EER-Modell“ | Vorschlag, `adresse` als eigenen Entitätstyp auszulagern | **Verworfen.** In unserer Miniwelt hat jede Person genau eine Adresse und wir fragen nie nach Adressen. Auslagerung hätte einen Join ohne Nutzen erzeugt. |
| 2 | B5 DDL | Generierung der `CREATE TABLE`-Statements aus unserem Schema | Lauffähige DDL, aber alle Zeitspalten als `timestamp` | **Angepasst.** Auf `timestamptz` umgestellt, weil Termine über die Zeitumstellung hinweg eindeutig bleiben müssen. |
| 3 | B6 Testdaten | 20 `INSERT`-Zeilen pro Tabelle | Plausible Daten, aber alle in der Mitte des Wertebereichs | **Ergänzt.** Grenzfälle, NULL-Fall und LEFT-JOIN-Waise selbst hinzugefügt. |
| 4 | B7 Abfrage A4 | Entwurf einer CTE | Funktionierende CTE | **Übernommen mit Änderung.** Aliasse umbenannt, Kommentar mit User-Story-Bezug ergänzt. Wir haben die Ausführung Zeile für Zeile nachvollzogen. |

---

## Teil 3: Änderungsszenario (je Person eigenständig ausfüllen)

### <Nachname 1>, Szenario T<n>

| # | Wofür eingesetzt | Was kam heraus | Was ich damit gemacht habe |
|---|---|---|---|
| 1 | | | |

### <Nachname 2>, Szenario T<n>

| # | Wofür eingesetzt | Was kam heraus | Was ich damit gemacht habe |
|---|---|---|---|
| 1 | | | |

---

## Die drei wichtigsten verworfenen Vorschläge

1. **<Vorschlag>**: verworfen, weil <Begründung aus unserer Miniwelt>.
2. **<Vorschlag>**: verworfen, weil …
3. **<Vorschlag>**: verworfen, weil …

---

## Was wir ohne KI nicht geschafft hätten und was wir dadurch weniger gelernt haben

<3–5 Sätze, ehrlich. Diese Antwort wird nicht bewertet, aber gelesen.>
