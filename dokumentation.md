---
lang: de-DE
bibliography: mw-ur-lit.yaml
csl: mw-ur-lit.csl
css: template/style.css
pagetitle: mw-ur-lit (CSL für MW-UR-Gestaltungsrichtlinien)
---

[//]: # (
  pandoc --from=markdown dokumentation.md --to=html5 --output=index.htm --standalone --citeproc --lua-filter=template/section-refs.lua --metadata=section-refs-level:2 --include-in-header=template/dokumentation-meta.htm --wrap=none --reference-location=block
  )

# mw-ur-lit

Kurzbelege und Vollbelege im Stile der [Gestaltungsrichtlinien der Medienwissenschaft](https://www.uni-regensburg.de/assets/sprache-literatur-kultur/medienwissenschaft/pdfs/studium-materialien/mw-gestaltungsrichtlinien.pdf) an der Universität Regensburg. Zur Verwendung in Literaturverwaltungsprogrammen wie [Zotero](https://www.zotero.org/) oder [Mendeley](https://www.mendeley.com/) und zur weiteren Unterstützung im akademischen Schreiben mit Word, Writer, Pandoc &hellip;

Stand: 20. Juni 2023.

## Literaturverwaltung

Kein System papierner oder softwaregestützter Literaturverwaltung kommt ohne Sorgfalt aus. Keine wissenschaftliche Arbeit wird sich unter Zuhilfenahme eines dieser Verwaltungssysteme von alleine schreiben. Die Verwendung eines Literaturverwaltungssystems mit korrespondierenden Zitationsstil-Dateien setzt vielleicht sogar noch mehr ein Interesse oder die behände Auseinandersetzung mit den Traditionen hinsichtlich des akademischen Schreibens und Veröffentlichens des jeweiligen Fachs voraus; und manchmal werden Synergieeffekte sich erst nach langem, steinigen Verwendungsweg zeigen.

Wer dieses Unterfangen dennoch eingehen will, der erhält hier:

* die vorgefertigte [CSL-Datei (mw-ur-lit.csl)](https://maybegeek.github.io/mw-ur-lit/mw-ur-lit.csl){.button}

Zur weiteren Verwendung hier beispielhaft die Quellen für den Import  und der Link zur Github-Seite dieses Projekts:

* die [verzeichneten Quellen der Gestaltungsrichtlinien](https://maybegeek.github.io/mw-ur-lit/mw-ur-lit.yaml) als *Better CSL YAML*
* sowie die Projektseite von [mw-ur-lit bei Github](https://github.com/maybegeek/mw-ur-lit)

Beispielhaft nun die unterstützten Quellentypen, die jeweils zu befüllenden Felder in Zotero sowie ein Beispielsatz mit Kurzbeleg in der Fußnote (Fußnotenapparat am Ende der Seite) und Vollbeleg im heidenelkenroten Kästchen. Die Beispiele sind den Gestaltungsrichtlinien entnommen.


## Monografie

Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase.[Vgl. beispielsweise bei @dotzle:medien:2017, 22.]

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Mediengeschichte als Historische Techno-Logie`
* `Autor:` `Dotzler, Bernhard J.`
* `Autor:` `Roesler-Keilholz, Silke`
* `Ort:` `Baden-Baden`
* `Verlag:` `Nomos`
* `Datum:` `2017`
:::



## Sammelband, Herausgeberschaft

Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel.[Vgl. die Argumentation diesbezüglich bei @gerhar:strukt:1993, 60-61.]

::: {.zotero-fields}
* `Eintragsart:` `Buchteil`
* `Titel:` `Strukturen und Funktionen moderner Öffentlichkeit`
* `Autor:` `Gerhards, Jürgen`
* `Autor:` `Neidhardt, Friedhelm`
* `Herausgeber:` `Langenbucher, Wolfgang R.`
* `Buchtitel:` `Politische Kommunikation. Grundlagen, Strukturen, Prozesse`
* `Reihe:` `Studienbücher zur Publizistik- und Kommunikationswissenschaft`
* `Nummer der Reihe:` `2`
* `Auflage:` `2., überarb. Auflage`
* `Ort:` `Wien`
* `Verlag:` `Braumüller`
* `Datum:` `1993`
* `Seiten:` `52-89`
:::


Hier nun die „[d]irekte Textübernahme direkte Textübernahme Textübernahme Textübernahme Textübernahme“[@amento:experi:2003, 60.] eigener Text.

::: {.zotero-fields}
* `Eintragsart:` `Zeitschriftenartikel`
* `Titel:` `Experiments in social data mining: The TopicShop system`
* `Autor:` `Amento, Brian`
* `Autor:` `Terveen, Loren G.`
* `Autor:` `Hill, William C.`
* `Autor:` `Hix, Deborah`
* `Autor:` `Schulman, Robert`
* `Publikation:` `ACM Transactions on Computer-Human Interaction (TOCHI)`
* `Band:` `10`
* `Ausgabe:` `1`
* `Seiten:` `54-85`
* `Datum:` `2003`
* `Zeitschriften-Abkürzung:` `ACM Trans. Comput.-Hum. Interact.`
* `DOI:` `10.1145/606658.606661`
:::


Wie schon mit der herausgebenden Autorenschaft zum Thema meisterhaft ausgewiesen.[Siehe hierzu @heibac:asthet:2015.]

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Ästhetik der Materialität`
* `Herausgeber:` `Heibach, Christiane`
* `Herausgeber:` `Rohde, Carsten`
* `Reihe:` `HfG Forschung`
* `Nummer der Reihe:` `6`
* `Ort:` `München`
* `Verlag:` `Fink`
* `Datum:` `2015`
:::



## Gesammelte Schriften, Anthologien

Dinge und Sachen Dinge und Sachen Dinge und Sachen Dinge und Sachen besonders bei Benjamin.[Vgl. hierzu @benjam:kleine:1977, 370.]

::: {.zotero-fields}
* `Eintragsart:` `Buchteil`
* `Titel:` `Kleine Geschichte der Photographie`
* `Autor:` `Benjamin, Walter`
* `Herausgeber:` `Tiedemann, Rolf`
* `Herausgeber:` `Schweppenhäuser, Rolf`
* `Buchtitel:` `Walter Benjamin: Gesammelte Schriften. Bd. II, 1. Aufsätze, Essays, Vorträge`
* `Ort:` `Frankfurt am Main`
* `Verlag:` `Suhrkamp`
* `Datum:` `1977`
* `Seiten:` `368-385`
* `Extra:` `Original Date: 1931`
:::



## Wissenschaftliche Fachzeitschrift

„Direkte Textübernahme direkte Textübernahme“[@stegba:diesc:2001, 48.] eigener Text.

::: {.zotero-fields}
* `Eintragsart:` `Zeitschriftenartikel`
* `Titel:` `Die schweigende Mehrheit – „Lurker“ in internetbasierten Diskussionsforen`
* `Autor:` `Stegbauer, Christian`
* `Autor:` `Rausch, Alexander`
* `Publikation:` `Zeitschrift für Soziologie`
* `Band:` `30`
* `Ausgabe:` `1`
* `Seiten:` `48-64`
* `Datum:` `2001`
:::



## Webseite

„Direkte Textübernahme direkte Textübernahme“[@oreill:whati:2005.] eigener Text.

::: {.zotero-fields}
* `Eintragsart:` `Webseite`
* `Titel:` `What Is Web 2.0. Design Patterns and Business Models for the Next Generation of Software`
* `Autor:` `O’Reilly, Tim`
* `Datum:` `2003`
* `URL:` `https://www.oreilly.com/pub/a/web2/archive/what-is-web-20.html`
* `Heruntergeladen am:` `2019-06-29`
:::



## Wikipedia

Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase.[Vgl. hierzu @wikipe:univer:2019.]

::: {.zotero-fields}
* `Eintragsart:` `Enzyklopädieartikel`
* `Titel:` `Universität Regensburg`
* `Autor:` `Wikipedia`
* `Titel der Enzyklopädie:` `Wikipedia, Die freie Enzyklopädie`
* `Datum:` `2019-07-11`
* `URL:` `https://de.wikipedia.org/w/index.php?title=Universit%C3%A4t_Regensburg&oldid=190335453`
* `Heruntergeladen am:` `2019-07-22`
:::



## Twitter, Facebook, …

Paraphrase Paraphrase Dinge und Sachen Paraphrase Dinge und Sachen.[Vgl. @ur.reg:furda:2021.]

::: {.zotero-fields}
* `Eintragsart:` `Webseite`
* `Titel:` `Animal study shows sleeping brain behaves as if it's remembering: http://stan.md/RrqyEt #sleep #neuroscience #research`
* `Autor:` `@StanfordMed`
* `Datum:` `2012-10-09`
* `URL:` `https://twitter.com/StanfordMed/status/255644688630046720`
* `Heruntergeladen am:` `2021-09-28`
* `Extra:` `[Twitter, Tweet]`
:::


Paraphrase Paraphrase Dinge und Sachen Paraphrase Dinge und Sachen.[Vgl. @stanfo:animal:2012.]

::: {.zotero-fields}
* `Eintragsart:` `Webseite`
* `Titel:` `Für das Wintersemester 2021/22 ist die lang erwartete Rückkehr zu einem möglichst weitreichenden Präsenzlehrbetrieb geplant`
* `Autor:` `UR.Regensburg`
* `Datum:` `2021-09-23`
* `URL:` `https://www.facebook.com/UR.Regensburg/photos/a.714984458891629/1739632266426838/`
* `Heruntergeladen am:` `2021-09-26`
* `Extra:` `[Facebook, Status Update]`
:::

::: {.kommentar}
* Inhalte bei Dienstanbietern aus dem Microblogging-Bereich weisen oftmals keine dedizierte(n) Überschrift/Titel auf. Hierzu bediene man sich dann einer sinntragenden Anzahl der ersten dort verwendeten Wörter.
* Oftmals gibt es ein Kürzel für Verfasserin/Verfasser, dies soll hier dann auch verwendet werden.
* In eckige Klammern kommt der Dienstanbietername und die dortige Rubrik.
:::



## Werbung, RAW

„Direkte Textübernahme direkte Textübernahme“[@doppel:sitzna:2007.] eigener Text.

::: {.zotero-fields}
* `Eintragsart:` `Dokument`
* `Titel:` `Sitznachbar`
* `Autor:` `Doppelherz`
* `Datum:` `2007`
* `Extra:` `ARD Radio-Kreativ-Wettbewerb 2007; Broschüre und CD-Rom. [Werbung]`
:::


„Direkte Textübernahme direkte Textübernahme“[@gesell:ohdie:1952.] eigener Text.

::: {.zotero-fields}
* `Eintragsart:` `Dokument`
* `Titel:` `Oh die herrlichen Berge`
* `Autor:` `Gesellschaft zur Förderung der Photographie`
* `Datum:` `1952`
* `URL:` `https://raw.uni-regensburg.de/details.php?r=616`
* `Heruntergeladen am:` `2013-09-18`
* `Archiv:` `Regensburger Archiv für Werbeforschung`
* `Standort im Archiv:` `R-Nummer: 616`
* `Extra:` `PROPHOTO vom 12.7.1952. [Werbung, Audio]`
:::


::: {.kommentar}
* Hier gibt es eine kleine Abweichung zur PDF-Version der Gestaltungsrichtlinien. Die `R-Nummer` wurde auch im Vollbeleg visuell näher zum `Regensburger Archiv für Werbeforschung` positioniert. Im `Extra`-Feld kann darüberhinaus und in anderen Fällen noch genügend weiter wichtige Information dann auch komma- oder punktsepariert angegeben werden.
:::



## Bild/Gemälde und Fotografie


Abc defg hi Jklm nop qr St.[Vgl. beispielsweise besonders trefflich realisiert in @friedr:mannu:1818.]

::: {.zotero-fields}
* `Eintragsart:` `Kunstwerk`
* `Titel:` `Mann und Frau den Mond betrachtend [Mann und Frau in Betrachtung des Mondes]`
* `Künstler:` `Friedrich, Caspar David`
* `Medium:` `[Öl auf Leinwand]`
* `Kurztitel:` `Mann und Frau den Mond betrachtend`
* `Archiv:` `Alte Nationalgalerie Berlin`
* `URL:` `https://w.wiki/6eW`
* `Heruntergeladen am:` `2019-07-22`
* `Extra:` `Issued: 1818/1824`
* `Extra:` `In: Wikipedia, Die freie Enzyklopädie`
:::

Abc defg hi Jklm nop qr St.[Vgl. beispielsweise besonders trefflich realisiert in @ray:larmes:1930.]

::: {.zotero-fields}
* `Eintragsart:` `Kunstwerk`
* `Titel:` `Larmes [Tränen]`
* `Künstler:` `Ray, Man`
* `Datum:` `1930`
* `Kurztitel:` `Larmes`
* `Extra:` `In: Rosalind Krauss & Jane Livingston (Hg.) (1985). L'amour fou. Photography and Surrealism. Washington: Abbeville Press. S. 118`
:::



## Film

Film Film Film Bewegtbild Bewegtbild Bewegtbild Film Film Film. Film Film Film Bewegtbild Bewegtbild Bewegtbild Film Film Film.[Besonders gut gelungen bei @cukor:awoma:1941.]

::: {.zotero-fields}
* `Eintragsart:` `Film`
* `Titel:` `A Woman's Face [Die Frau mit der Narbe]`
* `Regisseur:` `Cukor, Georges`
* `Verleih:` `MGM`
* `Datum:` `1941`
* `Format:` `[DVD/2017]`
* `Kurztitel:` `A Woman's Face`
* `Extra:` `Publisher Place: US`
:::



## Serie

Serie Serienfolge Serie Serienfolge.[Besonders gut gelungen bei @simon:thewi:2002.]

::: {.zotero-fields}
* `Eintragsart:` `Film`
* `Titel:` `The Wire: „The Target“`
* `Regisseur:` `Simon, David`
* `Regisseur:` `Colesberry, Robert F.`
* `Verleih:` `S01E01; HBO`
* `Datum:` `2002`
* `Format:` `[DVD/2010]`
* `Extra:` `Publisher Place: US`
:::



## Video (auf bspw. Youtube, Vimeo, ...)

Ein Video auf der Plattform Youtube. Aufnahmen der Apollo 11-Mission aus 1969; wiederaufbereitet.[Besonders der angegebene, fiktive Zeitraum der Aufnahme zeigt Dinge und Sachen eindrucksvoll, @nasa:apollo11:2014, 00:02:50--00:04:10.]

::: {.kommentar}
* In Anlehnung an die willentliche Unterscheidung aller Bewegtbild/Kunstwerk-Quellen im Gegensatz zur Notation konventioneller Quellentypen führt hier der Titel die Kurz- und Vollbelege an.*
:::

::: {.zotero-fields}
* `Eintragsart:` `Videoaufnahme`
* `Titel:` `Restored Apollo 11 Moonwalk – Original NASA EVA Mission Video – Walking on the Moon `
* `Regisseur:` `NASA`
* `URL:` `https://youtu.be/S9HdPi9Ikhk`
* `Heruntergeladen am:` `2023-04-28`
* `Extra:` `[Youtube, Video]`
:::



## Musikvideo, Kunst-Video

Abc Defg Hijk Lmno Pqrs.[Besonders bei @bjork:human:2019.]

::: {.zotero-fields}
* `Eintragsart:` `Film`
* `Titel:` `Human Behaviour (HD)`
* `Datum:` `2019`
* `URL:` `https://youtu.be/p0mRIhK9seg`
* `Heruntergeladen am:` `2021-09-26`
* `Extra:` `Artist: Björk`
* `Extra:` `Mitautor: Nellee Hooper. Regisseur: Michel Gondry. Release: 1993. One Little Indian Records. [Youtube, Musikvideo]`
:::

::: {.kommentar}
* Die spezielle Variante -- und Zuspitzung zu vorherigem Beispiel --; beim deutlich kunstvolleren Video wird die Künstlerin, der Künstler, die Band, die Urheberin, der Urheber ... im Klammernausdruck des Kurzbelegs mitbenannt. Zur Eingabe in Zotero kann das Extra-Feld verwendet werden und dort mittels Artist: Name oder Artist: Bezeichner1; Bezeichner2 & Bezeichner3 diese Information eingegeben werden. Ebenfalls weitere Informationen können mit neuer Zeile beginnend dort abgelegt werden. Die Unterscheidung zum oberen Beleg erreichen wir, indem das dedizierte Regisseur-Feld in Zotero hier nicht belegt wird, sondern diese Informationen im Freitext eingegeben werden.*
:::



## weitere Quellen

Der Vollständigkeit halber noch die weiteren, in den Gestaltungsrichtlinien verwendeten, Quellen, welche mit dem Zitationsstil der CSL-Datei umgesetzt werden können:

Thema Thema Thema.[Besonders gut zusammengestellt bei @bier:typoku:2009.]

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Typokurz – Einige wichtige typografische Regeln`
* `Autor:` `Bier, Christoph`
* `Datum:` `2009`
* `URL:` `https://zvisionwelt.files.wordpress.com/2012/01/typokurz.pdf`
* `Heruntergeladen am:` `2019-06-29`
:::

„Direkte Textübernahme direkte Textübernahme“[@brink:anfert:2013, 159\; Hervorhebungen im Original.] und eigene Einordnung.

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Anfertigung wissenschaftlicher Arbeiten. Ein prozessorientierter Leitfaden zur Erstellung von Bachelor-, Master- und Diplomarbeiten`
* `Autor:` `Brink, Alfred`
* `Auflage:` `4., korr. und akt. Auflage`
* `Ort:` `Wiesbaden`
* `Verlag:` `Springer Fachmedien`
* `Datum:` `2013`
:::

„Direkte Textübernahme direkte Textübernahme“[@anderm:duden:2000, 99.] und eigene Einordnung.

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Duden. Wie verfasst man wissenschaftliche Arbeiten? Ein Leitfaden für das Studium und die Promotion`
* `Autor:` `Andermann, Ulrich`
* `Autor:` `Drees, Martin`
* `Autor:` `Grätz, Frank`
* `Ort:` `Mainz`
* `Verlag:` `Verlag Hermann Schmidt`
* `Datum:` `2000`
:::

Thema Thema Thema.[Siehe hierzu einschlägig @zahn:oculus:1685, 181.]

::: {.zotero-fields}
* `Eintragsart:` `Buch`
* `Titel:` `Oculus Artificialis Teledioptricus Sive Telescopium`
* `Autor:` `Zahn, Johannes`
* `Ort:` `Würzburg`
* `Verlag:` `Quirin Heil`
* `Datum:` `1685`
:::
