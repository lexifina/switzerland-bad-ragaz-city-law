# Bad Ragaz (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Bad Ragaz, St. Gallen, Switzerland, which global-law reads at `switzerland/st-gallen/bad-ragaz/acts/`.

The municipal law of the municipality of Bad Ragaz (Gemeinde Bad Ragaz, canton of St. Gallen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of St. Gallen is in [lexifina/switzerland-st-gallen-law](https://github.com/lexifina/switzerland-st-gallen-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

70 acts with 70 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | one version (the oldest available), 1 May 2020 |
| `1-1-2/` | Region Sarganserland-Werdenberg, Statuten (SRS 1.1-2) | 1 | one version (the oldest available), 1 January 2024 |
| `1-3-1/` | Gebührentarif Einbürgerungsverfahren (SRS 1.3-1) | 1 | as enacted, 1 January 2018 |
| `1-6-1/` | Geschäftsreglement (SRS 1.6-1) | 1 | as enacted, 1 January 2010 |
| `1-6-2/` | Zusatz-Spesenreglement für den Gemeindepräsidenten oder Gemeindepräsidentin (hätte auch Gültigkeit für vollamtliche Gemeinderäte) (SRS 1.6-2) | 1 | as enacted, 1 January 2008 |
| `1-6-3/` | Vereinbarung über die Führung der idsl (SRS 1.6-3) | 1 | as enacted, 1 August 2018 |
| `1-7-1/` | Personalreglement (SRS 1.7-1) | 1 | as enacted, 1 January 2017 |
| `1-7-1-1/` | Ausführungsbestimmungen zum Personalreglement (SRS 1.7-1.1) | 1 | one version (the oldest available), 1 January 2024 |
| `1-7-1-2/` | Spesenreglement (SRS 1.7-1.2) | 1 | as enacted, 1 January 2008 |
| `1-7-1-3/` | Weiterbildung, Regelung Kostenübernahme (SRS 1.7-1.3) | 1 | as enacted, 7 May 2002 |
| `2-1-1/` | Reglement über die Delegation von Zuständigkeiten im Bereich des Zivilrechts (SRS 2.1-1) | 1 | as enacted, 8 February 2006 |
| `2-1-2/` | Reglement über die Kosten der Nachführung der amtlichen Vermessung (SRS 2.1-2) | 1 | as enacted, 1 March 2020 |
| `2-1-3/` | Vereinbarung über die gemeinsame Führung des Grundbuchamtes (SRS 2.1-3) | 1 | as enacted, 1 October 2022 |
| `2-1-4/` | Vereinbarung über die Führung des Regionalen Zivilstandsamtes Sarganserland (SRS 2.1-4) | 1 | as enacted, 1 January 2009 |
| `4-2-1/` | Schulordnung (SRS 4.2-1) | 1 | as enacted, 1 January 2020 |
| `4-2-2/` | Reglement für die Schulleitung (SRS 4.2-2) | 1 | as enacted, 1 January 2020 |
| `4-2-3/` | Reglement über den Robert-Hohl-Bildungsfonds (SRS 4.2-3) | 1 | as enacted, 1 December 2024 |
| `5-3-1/` | Vereinbarung Bevölkerungsschutz-Region Sarganserland (SRS 5.3-1) | 1 | as enacted, 1 January 2023 |
| `5-5-1/` | Feuerschutzreglement (SRS 5.5-1) | 1 | as enacted, 1 January 2023 |
| `6-1-2-rrwf/` | Reglement über die Reserve Werterhalt Finanzvermögen (SRS 6.1-2) | 1 | as enacted, 1 January 2023 |
| `6-6-1/` | Benützungsvorschriften Mehrzweckgebäude Bad Ragaz (SRS 6.6-1) | 1 | as enacted, 1 January 2003 |
| `6-6-2/` | Benützungsreglement für Schulanlagen (SRS 6.6-2) | 1 | as enacted, 1 August 2021 |
| `6-6-3/` | Benützungsordnung der Sportanlagen Ri-Au und Giessenpark (SRS 6.6-3) | 1 | as enacted, 1 January 2024 |
| `6-6-3-1/` | Betriebsreglement Sportplatz Ri-Au (SRS 6.6-3.1) | 1 | as enacted, 1 January 1986 |
| `7-1-1/` | Baureglement (SRS 7.1-1) | 1 | one version (the oldest available), 1 May 2010 |
| `7-1-2-svo/` | Schutzverordnung (SRS 7.1-2) | 1 | as enacted, 8 May 2009 |
| `7-1-3/` | Kernzonenreglement (SRS 7.1-3) | 1 | as enacted, 3 May 1990 |
| `7-1-4/` | Parkplatzreglement (SRS 7.1-4) | 1 | as enacted, 26 October 1983 |
| `7-3-1/` | Pilzschutzverordnung (SRS 7.3-1) | 1 | as enacted, 1 January 1998 |
| `7-3-2/` | Vereinbarung über die Pilzkontrolle Sarganserland (SRS 7.3-2) | 1 | as enacted, 1 July 2017 |
| `7-3-3/` | Schutzzonenreglement Föhrenwald (SRS 7.3-3) | 1 | as enacted, 14 May 1979 |
| `7-3-4/` | Schutzzonenreglement Grundwasserschutzzone für die Quelle Gisibel (SRS 7.3-4) | 1 | as enacted, 8 June 1993 |
| `7-3-5/` | Grundwasserschutzzone für die Quelle «Pardatsch», Schutzzonenreglement (SRS 7.3-5) | 1 | as enacted, 15 July 1998 |
| `7-3-6/` | Grundwasserschutzzone für das Grundwasser-Pumpwerk «Sarelli», Schutzzonenreglement (SRS 7.3-6) | 1 | as enacted, 5 February 1999 |
| `7-3-7/` | Grundwasserschutzzone für die Quellen Rüti, Sergeuris: Schutzzonenreglement (SRS 7.3-7) | 1 | as enacted, 16 February 1999 |
| `7-3-8/` | Grundwasserschutzareal «Uf der Insel», Bad Ragaz, Schutzarealreglement (SRS 7.3-8) | 1 | as enacted, 2 November 2000 |
| `7-3-9/` | Grundwasserschutzzonen für die Bölliquellen (SRS 7.3-9) | 1 | as enacted, 2 May 2011 |
| `7-3-10/` | Grundwasserschutzzonen für die Quellen Talbühel, Schutzzonenreglement (SRS 7.3-10) | 1 | as enacted, 12 April 2016 |
| `7-3-11/` | Schutzzonenreglement für die geplante Grundwasserfassung Neugüeter (SRS 7.3-11) | 1 | as enacted, 29 April 2020 |
| `7-3-12/` | Schutzarealreglement für das Grundwasserschutzareal Heulöser (SRS 7.3-12) | 1 | as enacted, 25 January 2024 |
| `7-4-2-1-warmeverbundreglement/` | Reglement für Anschlüsse an das Wärmeverteilnetz und Lieferung von Wärme-Energie (SRS 7.4.2-1) | 1 | as enacted, 1 January 1998 |
| `7-4-3-1/` | Wasserreglement (SRS 7.4.3-1) | 1 | as enacted, 1 January 2011 |
| `7-4-3-2/` | Abwasserreglement (SRS 7.4.3-2) | 1 | as enacted, 1 January 2011 |
| `7-4-3-2-1/` | Gebührentarif für die Abwasserbeseitigung (SRS 7.4.3-2.1) | 1 | one version (the oldest available), 1 January 2021 |
| `7-4-3-3/` | Vereinbarung betreffend Anschluss der Abwässer aus dem Gebiet Valens an die Kanalisation und die Abwasserreinigungsanlage von Bad Ragaz (Ergänzung zum Vertrag betreffend die Ableitung der Schmutzwasser aus dem Einzugsgebiet des Dorfes Pfäfers in die Abwasserreinigungsanlage Bad Ragaz vom 26. August 1974) (SRS 7.4.3-3) | 1 | as enacted, 3 May 2007 |
| `7-4-4-1-abfallreglement/` | Reglement über die Abfallbewirtschaftung und Abfallentsorgung (SRS 7.4.4-1) | 1 | as enacted, 1 January 2004 |
| `7-4-4-1-1/` | Vollzugsvorschriften zum Reglement über die Abfallbewirtschaftung und Abfallentsorgung (SRS 7.4.4-1.1) | 1 | as enacted, 1 January 2004 |
| `7-4-4-1-2/` | Gebührentarif zum Reglement über die Abfallbewirtschaftung und Abfallentsorgung (Abfallreglement) (SRS 7.4.4-1.2) | 1 | one version (the oldest available), 1 January 2025 |
| `7-4-4-2/` | Statuten des Vereins für Abfallentsorgung (SRS 7.4.4-2) | 1 | one version (the oldest available), 31 December 2012 |
| `7-7-1/` | Nutzungsabgabe für die Benützung von öffentlichem Grund (gesteigerter Gemeingebrauch) (SRS 7.7-1) | 1 | as enacted, 19 February 2013 |
| `7-7-2-parkierungsreglement/` | Reglement über das Parkieren auf öffentlichem Grund (SRS 7.7-2) | 1 | as enacted, 1 January 2002 |
| `7-7-2-1/` | Gebührentarif für die Parkplätze auf öffentlichem Grund (SRS 7.7-2.1) | 1 | one version (the oldest available), 1 September 2019 |
| `8-1-1/` | Vereinbarung über den Zweckverband Pflegezentrum Sarganserland (SRS 8.1-1) | 1 | one version (the oldest available), 1 January 2021 |
| `8-1-2/` | Vereinbarung der Zweckverbandsgemeinden PZSL über den Ausbildungsverbund Sarganserland (SRS 8.1-2) | 1 | as enacted, 1 April 2022 |
| `8-2-1/` | Friedhofreglement (SRS 8.2-1) | 1 | one version (the oldest available), 11 August 2009 |
| `8-2-1-1/` | Gebührentarif Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 9 June 2009 |
| `8-3-1/` | Vereinbarung über den Betrieb der regionalen Tierkörpersammelstelle in Bad Ragaz (SRS 8.3-1) | 1 | as enacted, 1 January 2022 |
| `8-3-1-1/` | Reglement über die Beseitigung von Tierkörpern und Tierkörperteilen sowie den Betrieb der regionalen Tierkörpersammelstelle in Bad Ragaz (SRS 8.3-1.1) | 1 | as enacted, 7 April 2022 |
| `8-7-1-altersheimreglement/` | Reglement für das Altersheim Allmend (SRS 8.7-1) | 1 | as enacted, 1 January 2017 |
| `8-7-1-1/` | Hausordnung Altersheim Allmend (SRS 8.7-1.1) | 1 | as enacted, 1 May 2007 |
| `8-7-1-2/` | Taxordnung Altersheim Allmend (SRS 8.7-1.2) | 1 | as enacted, 1 January 2023 |
| `8-7-2/` | Kompetenzordnung für das Sozialamt (SRS 8.7-2) | 1 | as enacted, 1 May 2017 |
| `8-7-3/` | Sozialhilfe-Unterstützungsrichtlinien (SRS 8.7-3) | 1 | as enacted, 1 January 2023 |
| `8-7-4/` | Vereinbarung über die Führung der Mütter- und Väterberatung Sarganserland (MVBS) (SRS 8.7-4) | 1 | as enacted, 1 January 2017 |
| `8-7-5/` | Vereinbarung «Zweckverband Soziale Dienste Sarganserland» (SRS 8.7-5) | 1 | as enacted, 1 January 2024 |
| `9-4-1-campingreglement/` | Verordnung über die Errichtung und den Betrieb von Camping- und Zeltplätzen in der politischen Gemeinde Bad Ragaz (SRS 9.4-1) | 1 | as enacted, 30 July 1979 |
| `9-4-2/` | Reglement über die Kurtaxen (SRS 9.4-2) | 1 | one version (the oldest available), 1 January 2008 |
| `9-4-2-1/` | Ausführungsbestimmungen zum Reglement über die Kurtaxen (SRS 9.4-2.1) | 1 | as enacted, 1 January 1999 |
| `9-5-1/` | Gastwirtschaftsreglement (SRS 9.5-1) | 1 | as enacted, 10 January 1986 |
| `9-5-2-ladenoffnungsreglement/` | Reglement über die Ladenöffnung (SRS 9.5-2) | 1 | as enacted, 1 July 2015 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://badragaz.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@badragaz.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
