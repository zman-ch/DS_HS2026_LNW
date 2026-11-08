# Zusätzliche Übungs-Arbeitspakete AP04–AP09 (LNW 1, Block II)

Aufbau, Punkte, Bewertungsschema und Namensgebung wie AP01–AP03. Jedes Paket enthält das
Aufgaben-Notebook und ein separates, **ausgeführtes** Lösungs-Notebook (`…_Musterloesung.ipynb`)
mit den korrekten Ergebnissen (Tabellen, Kennzahlen, Grafiken) zum Abgleich.

**Installation:** Die Ordner `AP04` … `AP09` in `DS_HS2026_LNW_I_Examples/` kopieren (neben AP01–AP03)
und das Notebook im jeweiligen Ordner öffnen. Es werden nur die Pakete aus `requirements.txt` benötigt.

| AP | Thema | Daten | Schwerpunkte |
|---|---|---|---|
| AP04 | Relationale Daten / SQL | `cinema.db` (wie AP01) | Normalisierung, Plausibilitätsregeln, Schlüssel; Fan-out durch überflüssigen JOIN, GROUP BY auf Namen statt PK; Zeitstempel vergleichen, HAVING + LEFT JOIN |
| AP05 | Scraping, Aufbereitung, EDA | PhoneMarkt (wie AP02) | Duplikate, Skalenniveaus, Min-Max-/Robust-Scaling; TB/Dezimal-Parsing, inner vs. left merge; optionale HTML-Elemente, `pd.cut`, Datumsumwandlung + Liniendiagramm |
| AP06 | Machine Learning | VeloMarkt (wie AP03) | Over-/Underfitting, Koeffizienten-Einheiten, Schwellenwert τ; unfairer Modellvergleich + MSE statt RMSE, vertauschte Split-Variablen + `confusion_matrix`-Argumente; Tiefe-Schleife, `predict_proba`, Tree-Interpretation |
| AP07 | Relationale Daten / SQL | **neu:** `hotel.db` (Hotelkette «AlpenStay») | m:n-Beziehungen, Dubletten/MDM, NULL-Logik; Preis×Nächte + Stornos, WHERE hebt LEFT JOIN auf; `NOT IN` + NULL, CASE-Zählung, Ganzzahldivision |
| AP08 | Scraping, Aufbereitung, EDA | **neu:** WohnMarkt (Mietinserate, verschachteltes JSON) | MAR, IQR-Regel/Ausreisser vs. Fehler, One-Hot-Encoding; 0 statt None, Jahres- statt Monatsmiete; `<th>/<td>`-Tabellen, JSON + left merge + `dropna=False`, `pivot_table` + Heatmap |
| AP09 | Machine Learning | **neu:** ReTech (Occasions-Laptops) | Data Leakage, OLS-Interpretation, Residuenmuster/Nichtlinearität; getrennte Splits von X und y, Regressor statt Classifier + ROC aus harten Labels; OLS-RMSE, RF-Feature-Importance, Classification Tree + AUC |

Die Hinweise «Nicht Teil der Antwort» in den Musterlösungen verweisen auf die Folien (Seitenzahlen
geprüft) und enthalten Kontrollabfragen. Mit «Einschätzung (nicht offiziell)» markierte Bewertungshinweise
sind meine Interpretation des Bewertungsschemas, keine Vorgabe der Dozierenden.

`DS_HS2026_LNW_I_Examples_Lecturer_Only_Zusatz/` enthält die Generatoren der neuen Datensätze
(AP07–AP09, analog zum Ordner `…_Lecturer_Only`) — für die Übungen nicht nötig.
