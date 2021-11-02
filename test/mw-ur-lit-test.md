---
lang: de-DE
css: mw-ur-lit-test.css
pagetitle: mw-ur-lit.csl tests
---

[//]: # (
  pandoc --from=markdown test/mw-ur-lit-test.md -C --biblio test/mw-ur-lit-test.yaml --lua-filter template/section-refs.lua --metadata=section-refs-level:2 --to=html5 -s -o test/mw-ur-lit-test.htm --csl mw-ur-lit.csl --reference-location=block
  )

# mw-ur-lit.csl Referenz

Folgende Beispiele sollen Varianten des Belegens/Zitierens aufzeigen, fixieren und für Veränderungen am `.csl`-Stil nachvollziehbar machen.


## Monografie + Varianten

Buch, ein Autor, Ort und Verlag.[@autore:buchti:2021.]

Buch, ein Autor, Ort und Verlag, mit Seite.[@autore:buchti:2021, 21.]

Buch, ein Autor, Ort und Verlag, mit Seiten.[@autore:buchti:2021, 21-22.]

Buch, ein Autor, mit Reihe, Ort und Verlag, mit Seiten.[@autore:buchti:2020, 21-22.]

Buch, ein Autor, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Prefix.[Vgl. @autore:buchti:2019, 21-22.]

Buch, mehrere Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[@autore:buchti:2018, 21-22.]

Buch, ab vier Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[@autore:buchti:2017, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit Nummer und Text, Zusatz.[@autore:buchti:2000, 21-22.]

Buch, ein Autor, ohne Ort.[@autore:buchti:2001, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit nur Ziffer in der Eingabe, Zusatz.[@autore:buchti:2002, 21-22.]

Buch, ein Autor, ohne Verlag.[@autore:buchti:2010, 21-22.]

Zwei Autoren.[@dotzle:medien:2017, 22.]

Vier Autoren.[@dotzle:medien:2017e, 22.]

Fünf Autoren, leicht abgeänderter Titel, aber wegen Unterscheidbarkeit im Kurzbeleg (*disambiguation*) wird hier nicht mit *et al.* abgekürzt.[@dotzle:medien:2017f, 22.]

Zwei Autoren, ein Hg.[@dotzle:medien:2017g, 22.]

Zwei Autoren, zwei Hg.[@dotzle:medien:2017h, 22.]

Zwei Autoren, drei Hg.[@dotzle:medien:2017i, 22.]

Zwei Autoren, vier Hg., zwei Übers., ein Übers. gleichzeitig Hg.[@dotzle:medien:2017j, 22.]

Zwei Autoren, ein Übs. und gleichzeitig Hg.[@dotzle:medien:2017k, 22.]

Zwei Autoren, ein Übs. und gleichzeitig Hg., Auflagennummer.[@dotzle:medien:2017l, 22.]

ISBN wird nicht angezeigt.[@dotzle:medien:2017n, 22.]

Test mit Zotero-Extra-Feld.[@dotzle:medien:2017q, 22.]

Test mit Zotero-Extra-Feld 2.[@dotzle:medien:2017r, 22.]

Test mit Zotero-Edition-Feld.[@dotzle:medien:2017s, 22.]

Test mit Zotero-Extra-Feld, DOI.[@dotzle:medien:2017t, 22.]

Fünf Autoren, hier mit *et al.*, da keine weiteren Ununterscheidbarkeiten dadurch hervorgerufen werden.[@person:dinge:2021, 20.]


## Sammelband, Herausgeberschaft

Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel Beispiel.[Vgl. die Argumentation diesbezüglich bei @gerhar:strukt:1993, 60-61.]

[@gerhar:strukt:1900.]

[@gerhar:strukt:1900a.]


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

[@cukor:woman:1900.]


## Serie

Serie Serienfolge Serie Serienfolge.[Besonders gut gelungen bei @simon:thewi:2002.]




## Video (auf bspw. Youtube, Vimeo, ...)


TODO year-suffix sorting TODO

Ein Video auf der Plattform Youtube.[@primal:howsp:2021, 00:02:50--00:04:10.]

Youtubevideo, weiterer Autor/Reg., Studionahme.[@primal:howsp:2010, 00:10:00--00:20:00.]

Youtubevideo, weiterer Autor/Reg., wie oben aber ohne Studionahme.[@primal:howsp:2010a, 00:10:00--00:20:00.]

Youtubevideo, nur ein Name.[@primal:howsp:2010b, 00:10:00--00:20:00.]



## Musikvideo, Kunst-Video

Besondere Videos

[@bjork:human:2019.]

Video mit vielen bibliogr. Informationen.[@nna:origin:2021.]

[@regina:origin:2021]


TODO bei Film ... schauen, was wirklich vorne stehen soll und nach was sich das `year-suffix` bilden soll. | Film, Film, Reg1, Reg2, Extra-Autor1, Extra-Autor2, Extra-Autor3, Extra-Editor1, Extra-Editor2, Extra-Editor3.[@regina:origin:2021a]


## weitere Quellen

Der Vollständigkeit halber noch die weiteren, in den Gestaltungsrichtlinien verwendeten, Quellen, welche mit dem Zitationsstil der CSL-Datei umgesetzt werden können:

Thema Thema Thema.[@bier:typoku:2009.]

„Direkte Textübernahme direkte Textübernahme ... Test wegen pandoc markdown Seitensuffix und weiterer Ausführung nach `\;` escaped Strichpunkt“[@brink:anfert:2013, 159\; Hervorhebungen im Original.] und eigene Einordnung.

„Direkte Textübernahme direkte Textübernahme“[@anderm:duden:2000, 99.] und eigene Einordnung.


Thema Thema Thema.[@zahn:oculus:1685, 181.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort und Bibliothekskatalog.[@zahn:oculus:1685e.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten.[@zahn:oculus:1685e, 99-100.]

Buch mit Kurztitelangabe, Angabe zu Archiv, Archivstandort, Bibliothekskatalog und Seiten. Zudem Fake-DOI und Fake-URL.[@zahn:oculus:1685f, 99-100.]
