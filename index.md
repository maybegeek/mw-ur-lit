---
lang: de-DE
bibliography: mw-ur-lit-keys.json
csl: mw-ur-lit.csl
css: style.css
pagetitle: mw-ur-lit (CSL für MW UR Gestaltungsrichtlinien)
---

<!-- pandoc index.md --filter pandoc-citeproc --lua-filter section-refs.lua -M section-refs-level=2 -o index.htm -s -->

# mw-ur-lit

Kurzbelege und Vollbelege im Stile der [Gestaltungsrichtlinien der Medienwissenschaft](https://www.uni-regensburg.de/sprache-literatur-kultur/medienwissenschaft/medien/pdfs/studium-materialien/mw-gestaltungsrichtlinien.pdf) an der Universität Regensburg. Zur Verwendung in Literaturverwaltungsprogrammen wie [Zotero](https://www.zotero.org/) oder [Mendeley](https://www.mendeley.com/) und zur weiteren Unterstützung im akademischen Schreiben mit Word, Writer, Pandoc &hellip;


## Literaturverwaltung

Kein System papierner oder softwaregestützter Literaturverwaltung kommt ohne Sorgfalt aus. Keine wissenschaftliche Arbeit wird sich unter Zuhilfenahme eines dieser Verwaltungssysteme von alleine schreiben. Die Verwendung eines Literaturverwaltungssystems mit korrespondierenden Zitationsstil-Dateien setzt vielleicht sogar noch mehr ein Interesse oder die behände Auseinandersetzung mit den Traditionen hinsichtlich des akademischen Schreibens und Veröffentlichens des jeweiligen Fachs voraus; und manchmal werden Synergieeffekte sich erst nach langem, steinigen Verwendungsweg zeigen.

Wer dieses Unterfangen dennoch eingehen will, der erhält hier:

* die vorgefertigte [CSL-Datei (mw-ur-lit.csl)](https://maybegeek.github.io/mw-ur-lit/mw-ur-lit.csl),
* wie auch die [verzeichneten Quellen aus den Gestaltungsrichtlinien](https://maybegeek.github.io/mw-ur-lit/mw-ur-lit.json) und
* die [verzeichneten Quellen aus den Gestaltungsrichtlinien (mit BBT keys)](https://maybegeek.github.io/mw-ur-lit/mw-ur-lit-keys.json)


## Monografie

*Beispiel:* Paraphrase Paraphrase Paraphrase.[Vgl. @dotzl:2017, 22.]

* `Eintragsart:` Buch
* `Titel:` Mediengeschichte als Historische Techno-Logie
* `Autor:` Dotzler, Bernhard J.
* `Autor:` Roesler-Keilholz, Silke
* `Ort:` Baden-Baden
* `Verlag:` Nomos
* `Datum:` 2017


## Herausgeberschaft

*Beispiel:* Wie schon mit der herausgebenden Autorenschaft zum Thema gezeigt.[Siehe hierzu @heiba:2015.]

* `Eintragsart:` Buch
* `Titel:` Ästhetik der Materialität
* `Herausgeber:` Heibach, Christiane
* `Herausgeber:` Rohde, Carsten
* `Reihe:` HfG Forschung
* `Nummer der Reihe:` 6
* `Ort:` München
* `Verlag:` Fink
* `Datum:` 2015


## Wissenschaftliche Fachzeitschrift

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“[@stegb:2001, 48.] eigener Text.

* `Eintragsart:` Zeitschriftenartikel
* `Titel:` Die schweigende Mehrheit – „Lurker“ in internetbasierten Diskussionsforen
* `Autor:` Stegbauer, Christian
* `Autor:` Rausch, Alexander
* `Band:` 30
* `Ausgabe:` 1
* `Seiten:` 48-64
* `Datum:` 2001


## Sammelband

*Beispiel:* Paraphrase Paraphrase Paraphrase.[Vgl. @gerha:1993, 60.]

* `Eintragsart:` Buchteil
* `Titel:` Strukturen und Funktionen moderner Öffentlichkeit
* `Autor:` Gerhards, Jürgen
* `Autor:` Neidhardt, Friedhelm
* `Herausgeber:` Langenbucher, Wolfgang R.
* `Buchtitel:` Politische Kommunikation. Grundlagen, Strukturen, Prozesse
* `Reihe:` Studienbücher zur Publizistik- und Kommunikationswissenschaft
* `Nummer der Reihe:` 2
* `Auflage:` 2., überarb. Auflage
* `Ort:` Wien
* `Verlag:` Braumüller
* `Datum:` 1993
* `Seiten:` 52-89

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“[@ament:2003, 60.] eigener Text.

* `Eintragsart:` Zeitschriftenartikel
* `Titel:` Experiments in social data mining: The TopicShop system
* `Autor:` Amento, Brian
* `Autor:` Terveen, Loren G.
* `Autor:` Hill, William C.
* `Autor:` Hix, Deborah
* `Autor:` Schulman, Robert
* `Publikation:` ACM Transactions on Computer-Human Interaction (TOCHI)
* `Band:` 10
* `Ausgabe:` 1
* `Seiten:` 54-85
* `Datum:` 2003
* `Zeitschriften-Abkürzung:` ACM Trans. Comput.-Hum. Interact.
* `DOI:` 10.1145/606658.606661


## Webseite

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“[@orei:2005.] eigener Text.

* `Eintragsart:` Webseite
* `Titel:` What Is Web 2.0. Design Patterns and Business Models for the Next Generation of Software
* `Autor:` O’Reilly, Tim
* `Datum:` 2003
* `URL:` https://www.oreilly.com/pub/a/web2/archive/what-is-web-20.html
* `Heruntergeladen am:` 2019-06-29


## Wikipedia

*Beispiel:* Paraphrase Paraphrase Paraphrase.[Vgl. @wikip:2019.]

* `Eintragsart:` Enzyklopädieartikel
* `Titel:` Universität Regensburg
* `Autor:` Wikipedia
* `Titel der Enzyklopädie:` Wikipedia, Die freie Enzyklopädie
* `Datum:` 2019-07-11
* `URL:` https://de.wikipedia.org/w/index.php?title=Universit%C3%A4t_Regensburg&oldid=190335453
* `Heruntergeladen am:` 2019-07-22


## Werbung

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“[@doppe:2007.] eigener Text.

* `Eintragsart:` Dokument
* `Titel:` Sitznachbar
* `Autor:` Doppelherz
* `Datum:` 2007
* `Extra:` ARD Radio-Kreativ-Wettbewerb 2007; Broschüre und CD-Rom. [Werbung]

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“[@gesel:1952.] eigener Text.

* `Eintragsart:` Dokument
* `Titel:` Oh die herrlichen Berge
* `Autor:` Gesellschaft zur Förderung der Photographie
* `Datum:` 1952
* `URL:` https://raw.uni-regensburg.de/details.php?r=616
* `Heruntergeladen am:` 2013-09-18
* `Archiv:` Regensburger Archiv für Werbeforschung
* `Standort im Archiv:` R-Nummer: 616
* `Extra:` PROPHOTO vom 12.7.1952, HWA_1_863.mp3. [Werbung, Audio]

## weitere Quellen

Der Vollständigkeit halber noch die weiteren, in den Gestaltungsrichtlinien verwendeten, Quellen, welche mit dem Zitationsstil der CSL-Datei umgesetzt werden können:

*Beispiel:* Thema Thema Thema.[Besonders gut zusammengestellt bei @bier:2009.]

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“.[@brink:2013, 159\; Hervorhebungen im Original.]

*Beispiel:* „Direkte Textübernahme direkte Textübernahme“.[@ander:2000, 99.]

*Beispiel:* Thema Thema Thema.[Siehe hierzu einschlägig @zahn:1685, 181.]
