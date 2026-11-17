# Korpuslinguistik des Arabischen – لسانيات المدونات العربية

**Status:** Arbeitsfassung · **Schwerpunkt:** moderne arabische Sprachdaten · **Sprachen:** Deutsch / العربية

## 1. Definition und Erkenntnisinteresse

Korpuslinguistik untersucht Sprache anhand systematisch zusammengestellter und dokumentierter Sammlungen realer Sprachdaten. Ein Korpus ist nicht einfach eine große Textmenge: Auswahl, Genre, Zeitraum, Varietät, Erhebung, Bereinigung, Annotation und Lizenz bestimmen, welche Fragen sich damit beantworten lassen.

Für das Arabische ist die Korpusarbeit besonders anspruchsvoll, weil geschriebene Standardsprache, gesprochene regionale Varietäten, gemischte Register und digitale Schreibweisen nebeneinander vorkommen. Ein Korpus, das überwiegend Nachrichten enthält, ist kein repräsentatives Abbild des gesamten Arabischen.

## 2. Korpusdesign und Repräsentativität

Vor dem Aufbau eines Korpus sind Forschungsfrage und Zielpopulation zu definieren. Relevante Dimensionen sind:
- Varietät und Region;
- Register, Genre und Kommunikationssituation;
- Zeitraum und Aktualität;
- Medium: Schrift, Audio, Video oder digitale Interaktion;
- Sprecher:innen- bzw. Autor:innenprofil, soweit ethisch und rechtlich vertretbar;
- Umfang, Sampling und Erhebungsverfahren.

Repräsentativität ist stets relativ zu einer definierten Zielpopulation. Ein ausgewogenes Nachrichtenkorpus kann für Nachrichtenregister nützlich sein, aber keine Aussagen über private Gespräche oder regionale Dialekte legitimieren.

## 3. Besonderheiten arabischer Daten

Arabische Korpusdaten bringen mehrere technische und linguistische Herausforderungen mit sich:

1. **Orthographische Variation:** Hamza-Schreibung, alif maqṣūra, tāʾ marbūṭa, optionale Diakritika und unterschiedliche Schreibkonventionen.
2. **Diakritika:** Kurze Vokale fehlen in vielen Texten; automatische Vokalisierung bleibt fehleranfällig.
3. **Clitika:** Präpositionen, Konjunktionen, Artikel und Pronominalsuffixe können orthographisch mit dem Stamm verbunden sein.
4. **Morphologische Mehrdeutigkeit:** Eine unvokalisierte Zeichenfolge kann mehrere Analysen und Lemmata zulassen.
5. **Dialektschreibung:** Es existiert keine vollständig einheitliche Orthographie für alle Dialekte und Plattformen.
6. **Code-Switching:** Arabische und nichtarabische Segmente sowie Arabizi können in derselben Äußerung auftreten.
7. **Transkription:** Gesprochene Daten erfordern nachvollziehbare Regeln für Pausen, Überlappung, Abbrüche und nichtsprachliche Ereignisse.

Normalisierung kann Suche und Modellierung erleichtern, darf aber die Originaldaten nicht ersetzen. Empfehlenswert ist, Rohform und normalisierte Form getrennt zu speichern und jede Transformation zu dokumentieren.

## 4. Annotation und Metadaten

Je nach Forschungsziel können Korpora mit Wortarten, Lemmata, morphologischen Merkmalen, syntaktischen Strukturen, semantischen Rollen, Diskursfunktionen oder Sprecherwechseln annotiert werden. Annotation ist theorie- und richtlinienabhängig. Ein Tagset bildet keine neutrale, alternativlose Beschreibung der Sprache.

Ein Mindestdatensatz sollte enthalten:
- eindeutige Dokument- und Segment-ID;
- Quelle, Datum und Erhebungsweg;
- Varietät, Register und Genre, soweit bekannt;
- Transkriptions- und Normalisierungsregeln;
- Annotationsschema und Version;
- Lizenz und Zugriffsbedingungen;
- Informationen zu Einwilligung, Datenschutz und De-Identifizierung.

Bei manueller Annotation sind Richtlinien, Schulung, Inter-Annotator-Übereinstimmung und Konfliktlösung zu dokumentieren.

## 5. Korpusabfragen und quantitative Auswertung

Konkordanzen zeigen Belege im Kontext; Frequenzlisten geben Verteilungen wieder; Kollokationsanalysen untersuchen typische Ko-Vorkommen. Für belastbare Vergleiche müssen Tokenisierung, Lemma- oder Wortformzählung, Korpusgröße, Genreverteilung und Normalisierung offengelegt werden.

Relative Häufigkeiten können Vergleiche erleichtern, lösen aber Probleme unterschiedlicher Zusammensetzung nicht automatisch. Statistische Signifikanz ersetzt weder Effektgrößen noch linguistische Interpretation. Jede quantitative Aussage braucht repräsentative Daten und eine klar definierte Analyseeinheit.

## 6. Ressourcenlandschaft: Beispiele

Die folgenden Ressourcen sind Ausgangspunkte für Recherche, nicht automatisch für jede Fragestellung geeignet:

| Ressource | Schwerpunkt | Hinweise |
|---|---|---|
| MADAR | Parallele Sätze aus MSA und Dialekten von 25 Städten | Reisedomäne; nicht repräsentativ für spontane Alltagsgespräche; nicht-kommerzielle Bedingungen prüfen |
| Curras | Palästinensisches Dialektkorpus mit morphologischer Annotation | Korpusportal dokumentiert Daten und Annotation; Lizenz und Version jeweils prüfen |
| Baladi | Libanesische Dialektdaten | Umfang und Genres begrenzt; nicht mit dem gesamten Libanesischen gleichsetzen |
| Arabic-PADT / UD | Syntaktisch annotierte MSA-Daten | Nachrichten- bzw. formelle Textdomäne; Tagset und Lizenz beachten |
| Masader | Metakatalog arabischer NLP-Datensätze | Katalog, nicht selbst ein einzelnes Sprachkorpus; Datensatzlizenzen separat prüfen |

Die Datenressourcen unterscheiden sich nach Genre, Umfang, Varietät, Annotation und Nutzungsrechten. Vor einer Veröffentlichung oder Weiterverwendung ist immer die aktuelle Originaldokumentation maßgeblich.

## 7. Korpusethik, Urheberrecht und Datenschutz

Öffentliche Zugänglichkeit bedeutet nicht automatisch freie Weiterverwendung. Forschende müssen Urheberrecht, Datenbankrechte, Plattformbedingungen, Einwilligung und Datenschutz prüfen. Besonders bei Social-Media-Daten können Re-Identifizierung und Kontextverlust Risiken schaffen.

Sensible Daten sind zu minimieren und gegebenenfalls zu de-identifizieren. Zitate sollten so gewählt werden, dass sie Forschungsfragen beantworten, ohne unnötig private Inhalte offenzulegen. Für jedes Korpus sind Herkunft, Lizenz, Zugriff und mögliche Einschränkungen nachvollziehbar zu dokumentieren.

## 8. Reproduzierbarkeit und Versionierung

Korpusversionen, Skripte, Normalisierungsregeln, Annotationsrichtlinien und Abfrageparameter sollten archiviert werden. Wo Daten aus rechtlichen Gründen nicht geteilt werden dürfen, können Metadaten, Code, aggregierte Ergebnisse und ein reproduzierbares Analyseprotokoll veröffentlicht werden.

Ein wissenschaftlich brauchbarer Korpus besitzt eine zitierfähige Version und eine stabile Beschreibung. Nachträgliche Änderungen sollten als neue Version dokumentiert werden.

## 9. Häufige Fehlschlüsse

- Große Datenmengen sind nicht automatisch repräsentativ.
- Ein Nachrichtenkorpus repräsentiert nicht „das Arabische“.
- Normalisierte Dialektschreibung ist nicht die einzige legitime Schreibweise.
- Automatische Annotationen sind Hypothesen bzw. Modelloutputs, keine fehlerfreien Fakten.
- Ein öffentlich erreichbarer Datensatz ist nicht automatisch offen lizenziert.
- Korpusfrequenzen allein erklären keine sozialen oder pragmatischen Funktionen.

## 10. Weiterführende Ressourcen und Literatur

- Bouamor, Houda, et al. 2018. “The MADAR Arabic Dialect Corpus and Lexicon.” Proceedings of LREC 2018.
- Ditters, Everhard. 2013/2017. “Issues in Arabic Computational Linguistics.” In *The Oxford Handbook of Arabic Linguistics*. DOI: 10.1093/oxfordhb/9780199764136.013.010.
- Masader: ARBML, Katalog arabischer NLP-Datensätze: https://arbml.github.io/masader/
- MADAR Project: https://sites.google.com/nyu.edu/madar/
- Currasat: https://sina.birzeit.edu/currasat/about-en.html
- Universal Dependencies, Arabic-PADT: https://universaldependencies.org/treebanks/ar_padt/
- NNLP-IL, Arabic Resources: https://github.com/NNLP-IL/Arabic-Resources

## Verwandte Artikel

- [Morphologie des modernen Arabischen](morphology-modern-arabic.md)
- [Syntax des modernen Arabischen](syntax-modern-arabic.md)
- [Arabische Dialektologie](../sociolinguistics/arabic-dialectology.md)
