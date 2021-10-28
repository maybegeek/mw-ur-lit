---
lang: de-DE
css: mw-ur-lit-test.css
pagetitle: mw-ur-lit.csl tests
---

[//]: # (
  pandoc --from=markdown test/mw-ur-lit-test.md -C --biblio=test/mw-ur-lit-test.yaml --lua-filter template/section-refs.lua --metadata=section-refs-level:2 --to=html5 -s -o test/mw-ur-lit-test.htm
  )

# mw-ur-lit.csl tests

Folgende Beispiele sollen Varianten des Belegens/Zitierens aufzeigen, fixieren und für Veränderungen am `.csl`-Stil nachvollziehbar machen.


## Monografie + Varianten

Buch, ein Autor, Ort und Verlag.[Buch, ein Autor, Ort und Verlag:<br>⇉ @autore:buchti:2021.]

Buch, ein Autor, Ort und Verlag, mit Seite.[Buch, ein Autor, Ort und Verlag, mit Seite:<br>⇉ @autore:buchti:2021, 21.]

Buch, ein Autor, Ort und Verlag, mit Seiten.[Buch, ein Autor, Ort und Verlag, mit Seiten:<br>⇉ @autore:buchti:2021, 21-22.]

Buch, ein Autor, mit Reihe, Ort und Verlag, mit Seiten.[Buch, ein Autor, mit Reihe, Ort und Verlag, mit Seiten:<br>⇉ @autore:buchti:2020, 21-22.]

Buch, ein Autor, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten.[Buch, ein Autor, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten:<br>⇉ @autore:buchti:2019, 21-22.]

Buch, mehrere Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[Buch, mehrere Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz:<br>⇉ @autore:buchti:2018, 21-22.]

Buch, ab vier Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[Buch, ab vier Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz:<br>⇉ @autore:buchti:2017, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit Nummer und Text, Zusatz.[Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit Nummer und Text, Zusatz:<br>⇉ @autore:buchti:2000, 21-22.]

Buch, ein Autor, ohne Ort.[Buch, ein Autor, ohne Ort:<br>⇉ @autore:buchti:2001, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit nur Ziffer in der Eingabe, Zusatz.[Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit nur Ziffer in der Eingabe, Zusatz:<br>⇉ @autore:buchti:2002, 21-22.]

Buch, ein Autor, ohne Verlag.[Buch, ein Autor, ohne Verlag:<br>⇉ @autore:buchti:2010, 21-22.]

Zwei Autoren.[Zwei Autoren:<br>⇉ @dotzle:medien:2017, 22.]

Vier Autoren.[Vier Autoren:<br>⇉ @dotzle:medien:2017e, 22.]

Fünf Autoren, leicht abgeänderter Titel, aber wegen Unterscheidbarkeit im Kurzbeleg (*disambiguation*) wird hier nicht mit *et al.* abgekürzt.[Fünf Autoren, leicht abgeänderter Titel, aber wegen Unterscheidbarkeit im Kurzbeleg (*disambiguation*) wird hier nicht mit *et al.* abgekürzt:<br>⇉ @dotzle:medien:2017f, 22.]

Zwei Autoren, ein Hg.[Zwei Autoren, ein Hg.:<br>⇉ @dotzle:medien:2017g, 22.]

Zwei Autoren, zwei Hg.[Zwei Autoren, zwei Hg.:<br>⇉ @dotzle:medien:2017h, 22.]

Zwei Autoren, drei Hg.[Zwei Autoren, drei Hg.:<br>⇉ @dotzle:medien:2017i, 22.]

Zwei Autoren, vier Hg., zwei Übers., ein Übers. gleichzeitig Hg.[Zwei Autoren, vier Hg., zwei Übers., ein Übers. gleichzeitig Hg.:<br>⇉ @dotzle:medien:2017j, 22.]

Zwei Autoren, ein Übs. und gleichzeitig Hg.[Zwei Autoren, ein Übs. und gleichzeitig Hg.:<br>⇉ @dotzle:medien:2017k, 22.]

Zwei Autoren, ein Übs. und gleichzeitig Hg, Auflagennummer.[Zwei Autoren, ein Übs. und gleichzeitig Hg, Auflagennummer:<br>⇉ @dotzle:medien:2017l, 22.]

ISBN wird nicht angezeigt.[ISBN wird nicht angezeigt:<br>⇉ @dotzle:medien:2017n, 22.]

Test mit Zotero-Extra-Feld.[Test mit Zotero-Extra-Feld:<br>⇉ @dotzle:medien:2017q, 22.]

Test mit Zotero-Extra-Feld 2.[Test mit Zotero-Extra-Feld 2:<br>⇉ @dotzle:medien:2017r, 22.]

Test mit Zotero-Edition-Feld.[Test mit Zotero-Edition-Feld:<br>⇉ @dotzle:medien:2017s, 22.]

Test mit Zotero-Extra-Feld, DOI.[Test mit Zotero-Extra-Feld, DOI:<br>⇉ @dotzle:medien:2017t, 22.]

Fünf Autoren, hier mit *et al.*, da keine weiteren Ununterscheidbarkeiten dadurch hervorgerufen werden.[Fünf Autoren, hier mit *et al.*, da keine weiteren Ununterscheidbarkeiten dadurch hervorgerufen werden:<br>⇉ @person:dinge:2021, 20.]


## Sammelband, Herausgeberschaft

Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel.[Vgl. die Argumentation diesbezüglich bei @gerhar:strukt:1993, 60-61.]


Hier nun die „[d]irekte Textübernahme direkte Textübernahme Textübernahme Textübernahme Textübernahme“[@amento:experi:2003, 60.] eigener Text.


Wie schon mit der herausgebenden Autorenschaft zum Thema meisterhaft ausgewiesen.[Siehe hierzu @heibac:asthet:2015.]



## Gesammelte Schriften, Anthologien

Dinge und Sachen Dinge und Sachen Dinge und Sachen Dinge und Sachen besonders bei Benjamin.[Vgl. hierzu @benjam:kleine:1977, 370.]



## Wissenschaftliche Fachzeitschrift

„Direkte Textübernahme direkte Textübernahme“[@stegba:diesc:2001, 48.] eigener Text.



## Webseite

„Direkte Textübernahme direkte Textübernahme“[@oreill:whati:2005.] eigener Text.



## Wikipedia

Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase Paraphrase.[Vgl. hierzu @wikipe:univer:2019.]



## Twitter, Facebook, …

Paraphrase Paraphrase Dinge und Sachen Paraphrase Dinge und Sachen.[Vgl. @ur.reg:furda:2021.]



Paraphrase Paraphrase Dinge und Sachen Paraphrase Dinge und Sachen.[Vgl. @stanfo:animal:2012.]



## Werbung, RAW

„Direkte Textübernahme direkte Textübernahme“[@doppel:sitzna:2007.] eigener Text.


„Direkte Textübernahme direkte Textübernahme“[@gesell:ohdie:1952.] eigener Text.


## Bild/Gemälde und Fotografie


Abc defg hi Jklm nop qr St.[Vgl. beispielsweise besonders trefflich realisiert in @friedr:mannu:1818.]

Abc defg hi Jklm nop qr St.[Vgl. beispielsweise besonders trefflich realisiert in @ray:larmes:1930.]



## Film

Film Film Film Bewegtbild Bewegtbild Bewegtbild Film Film Film. Film Film Film Bewegtbild Bewegtbild Bewegtbild Film Film Film.[Besonders gut gelungen bei @cukor:awoma:1941.]



## Serie

Serie Serienfolge Serie Serienfolge.[Besonders gut gelungen bei @simon:thewi:2002.]




## Video (auf bspw. Youtube, Vimeo, ...)

Ein Video auf der Plattform Youtube.[Video zu SpaceX und der Übertragung der Landung; Technisches zum Thema:<br>⇉ @primal:howsp:2021, 00:02:50--00:04:10.]



## Musikvideo, Kunst-Video

Besondere Videos ... .[Besondere Videos:<br>⇉  @bjork:human:2019.]

Video mit vielen bibliogr. Informationen.[@nna:titel:2021.]

[@regina:titel:2021]


## weitere Quellen

Der Vollständigkeit halber noch die weiteren, in den Gestaltungsrichtlinien verwendeten, Quellen, welche mit dem Zitationsstil der CSL-Datei umgesetzt werden können:

Thema Thema Thema.[Besonders gut zusammengestellt bei:<br>⇉  @bier:typoku:2009.]

„Direkte Textübernahme direkte Textübernahme ... Test wegen pandoc markdown Seitensuffix und weiterer Ausführung nach `\;` escaped Strichpunkt“[Test wegen pandoc markdown Seitensuffix und weiterer Ausführung nach `\;` escaped Strichpunkt:<br>⇉  @brink:anfert:2013, 159\; Hervorhebungen im Original.] und eigene Einordnung.

„Direkte Textübernahme direkte Textübernahme“[... :<br>⇉ @anderm:duden:2000, 99.] und eigene Einordnung.


Thema Thema Thema.[Siehe hierzu einschlägig:<br>⇉  @zahn:oculus:1685, 181.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort und Bibliothekskatalog.[Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort und Bibliothekskatalog:<br>⇉  @zahn:oculus:1685e.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten. TODO Kursivierung bei Archivname überprüfen TODO.[Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten. TODO Kursivierung bei Archivname überprüfen TODO:<br>⇉  @zahn:oculus:1685e, 99-100.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten. Zudem Fake-DOI und Fake-URL. TODO Kursivierung bei Archivname überprüfen TODO.[Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten. Zudem Fake-DOI und Fake-URL. TODO Kursivierung bei Archivname überprüfen TODO:<br>⇉  @zahn:oculus:1685f, 99-100.]
