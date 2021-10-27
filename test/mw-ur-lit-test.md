---
lang: de-DE
css: mw-ur-lit-test.css
pagetitle: mw-ur-lit.csl tests
---

[//]: # (
  pandoc --from=markdown test/mw-ur-lit-test.md -C --biblio=test/mw-ur-lit-test.yaml --lua-filter template/section-refs.lua --metadata=section-refs-level:2 --to=html5 -s -o test/mw-ur-lit-test.htm
  )

# mw-ur-lit.csl tests

Dies ist ein Typoblindtext. An ihm kann man sehen, ob alle Buchstaben da sind und wie sie aussehen. Manchmal benutzt man Worte wie Hamburgefonts, Rafgenduks oder Handgloves, um Schriften zu testen.

Manchmal Sätze, die alle Buchstaben des Alphabets enthalten - man nennt diese Sätze »Pangrams«. Sehr bekannt ist dieser: The quick brown fox jumps over the lazy old dog.

Oft werden in Typoblindtexte auch fremdsprachige Satzteile eingebaut (AVAIL® and Wefox™ are testing aussi la Kerning), um die Wirkung in anderen Sprachen zu testen. In Lateinisch sieht zum Beispiel fast jede Schrift gut aus.


## Monografie + Varianten

Buch, ein Autor, Ort und Verlag.[Buch, ein Autor, Ort und Verlag: @autore:buchti:2021.]

Buch, ein Autor, Ort und Verlag, mit Seite.[Buch, ein Autor, Ort und Verlag, mit Seite: @autore:buchti:2021, 21.]

Buch, ein Autor, Ort und Verlag, mit Seiten.[Buch, ein Autor, Ort und Verlag, mit Seiten: @autore:buchti:2021, 21-22.]

Buch, ein Autor, mit Reihe, Ort und Verlag, mit Seiten.[Buch, ein Autor, mit Reihe, Ort und Verlag, mit Seiten: @autore:buchti:2020, 21-22.]

Buch, ein Autor, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten.[Buch, ein Autor, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten: @autore:buchti:2019, 21-22.]

Buch, mehrere Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[Buch, mehrere Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz: @autore:buchti:2018, 21-22.]

Buch, ab vier Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz.[Buch, ab vier Autoren, mit Reihe und Reihennummer, Ort und Verlag, mit Seiten und Zusatz: @autore:buchti:2017, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit Nummer und Text, Zusatz.[Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit Nummer und Text, Zusatz: @autore:buchti:2000, 21-22.]

Buch, ein Autor, ohne Ort.[Buch, ein Autor, ohne Ort: @autore:buchti:2001, 21-22.]

Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit nur Ziffer in der Eingabe, Zusatz.[Buch, ein Autor, Reihe und Reihennummer, Auflagendetails mit nur Ziffer in der Eingabe, Zusatz: @autore:buchti:2002, 21-22.]

Buch, ein Autor, ohne Verlag.[Buch, ein Autor, ohne Verlag: @autore:buchti:2010, 21-22.]

Fünf Autoren, aber wegen *disambiguation* wird hier nicht mit *et al.* abgekürzt.[Fünf Autoren, aber wegen *disambiguation* wird hier nicht mit *et al.* abgekürzt: @dotzle:medien:2017f, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017, 22.]

Text.[Vgl. beispielsweise bei @person:dinge:2021, 20.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017d, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017e, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017f, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017g, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017h, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017i, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017j, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017k, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017l, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017m, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017n, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017o, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017p, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017q, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017r, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017s, 22.]

Text.[Vgl. beispielsweise bei @dotzle:medien:2017t, 22.]

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

Ein Video auf der Plattform Youtube.[Video zu SpaceX und der Übertragung der Landung; Technisches zum Thema: @primal:howsp:2021, 00:02:50--00:04:10.]



## Musikvideo, Kunst-Video

Abc Defg Hijk Lmno Pqrs.[Besonders bei @bjork:human:2019.]



## weitere Quellen

Der Vollständigkeit halber noch die weiteren, in den Gestaltungsrichtlinien verwendeten, Quellen, welche mit dem Zitationsstil der CSL-Datei umgesetzt werden können:

Thema Thema Thema.[Besonders gut zusammengestellt bei @bier:typoku:2009.]

„Direkte Textübernahme direkte Textübernahme“[@brink:anfert:2013, 159\; Hervorhebungen im Original.] und eigene Einordnung.

„Direkte Textübernahme direkte Textübernahme“[@anderm:duden:2000, 99.] und eigene Einordnung.


Thema Thema Thema.[Siehe hierzu einschlägig @zahn:oculus:1685, 181.]
