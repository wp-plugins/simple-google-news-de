=== Simple Google News DE ===
Contributors: (baynado)
Donate link: http://internet-pr-beratung.de/
Author URI: http://internet-pr-beratung.de/
Plugin URI: http://internet-pr-beratung.de/simple-google-news-de
Tags: google, google news, rss, feed, news
Requires at least: 2.5
Tested up to: 3.6.1
Stable tag: 2.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Binde mit diesem einfachen Plugin den Google News Stream zu einem bestimmten Thema in die Sidebar, Deine Artikel oder Seiten ein. 

== Beschreibung ==

Dieses Plugin kann als Widget oder per Shortcode genutzt werden.

Das 'Simple Google News DE' WordPress Plugin erleichtert die Anzeige der Google News Ergebnisse auf Deiner WordPress Website. Per Shortcode wird der Google News Stream zu einem Thema in Deinem Artikel oder Seite dargestellt nutze daf�r einfach folgenden Shortcode:

[google_news]

Im Widget kannst Du die Region der Nachrichten ausw�hlen, aktuell sin die Regin auf Deutschland, �sterreich, Schweiz, Gro�britannien und die USA beschr�nkt. Auf Anfrage kann ich gerne weitere Regionen hinzuf�gen.

= M�gliche Parameter =

Es gibt eine Handvoll  optionale Parameter, die man verwenden kanne, um die Ausgabe nach W�nschen anzupassen.

**query** � *Default: none*. Verwende diese Option, wenn Du nach einem bestimmten Wort oder Ausdruck bei Google News m�chtest.

**limit** � *Default: 5, Max: 10*. Mit dem Parameter "Limit", kannst Du die maximale Anzahl der Ergebnisse festlegen, die Sin Deinem Beitrag oder Seite angezeigt werden.

**images** � *Default: on*. Die Bilder werden standardm��ig angezeigt. Wenn Du sie ausschalten m�chtest, stelle den Bildern Parameter auf "Off". Hinweis: Nicht alle Nachrichten Storys werden ein Bild haben.

**length** � *Default: 300*. Der Parameter "length" steuert die Anzahl der Zeichen in der Beschreibung (wird auf das n�chste ganze Wort gerundet) angezeigt werden sollen.

**region** � *Default: de*. Mit dem Parameter "Region", kannst Du  Nachrichten von einem bestimmten Teil der Welt anzeigen. Um die Liste der derzeit unterst�tzten Regionen zu sehen, besuchen [link] (https://support.google.com/news/answer/40237?hl=de "Diese Seite"). Beachte den Parameter "definiert", die in jeder Region Link vorhanden ist. Zum Beispiel �sterreich de_at Parameter auf 'de_at' eingestellt ist. Das ist der Wert, den Du verwendest, um Nachrichten aus der jeweiligen Region anzuzeigen.

**sort** - *Default: relevancy*. Dieser Parameter gibt Dir zus�tzliche Kontrolle �ber die Ergebnisse, die zur�ckgegeben werden. Hier ist eine Liste der zul�ssigen Werte:

* r (f�r Relevanz)
* n nach Datum (neuste zuerst)
* d nach Datum (neuste zuerst mit Duplikaten)
* o nach Datum (�lteste zuerst)

**topic** � *Default: none*. Wenn Du regelm��ig Neuigkeiten nach einem Thema anzeigen m�chtest (z.B.: Technologie, Unterhaltung, usw.), kannst Du dies mit diesem Parameter tun. Zum Beispiel, wenn Du Technik Ergebnisse zeigen m�chtest, w�rdes Du diesen Shortcode nutzen:

[google_news limit="2" topic="t"]

Hinweis: der Themen Parameter �berschreibt die Abfrageparameter. Also, wenn Du dieses versuchst:

[google_news query="android" topic="t"]

Google News w�rde also diese Abfrage zu ignorieren.

Die Themen Werte kannst Du nutzen:

* b (f�r Wirtschaft)
* t (f�r Technik)
* e (f�r Unterhaltung)
* s (f�r Sport)
* snc (for science)
* m (f�r Gesundheit)
* ir (f�r Schlagzeilen)

== Installation ==

1. Upload von 'simple-google-news-de' in das Verzeichniss '/wp-content/plugins/'
1. Activier das Plugin im 'Plugins' Men� in WordPress
1. F�ge den Shortcode[google_news] in deinen Artikel oderSeite ein 

== Frequently Asked Questions ==

= Ich verwende den Shortcode und nichts passiert! =

Es gibt hierf�r zwei Ursachen.  Erstens es gibt kein Google News Ergebnis zu Deinem Begriff. �berpr�fe auf news.google.com, ob Google News Dir ein Ergebnis liefert. Zweitens, es wurde ein ung�ltiger Wert im Shortcode angegeben.

= Kann ich nach einer exakten Zeichenfolge mit Anf�hrungszeichen suchen? =

Ja! Du musst nur sicherstellen, dass die doppelten Anf�hrungszeichen in einfache Anf�hrungszeichen eingebettet sind, so z.B.: [google_news query='"whatsapp hack"']

== Screenshots ==

1. Dies ist ein Screenshot von meiner Website, wo ich den Shortcode nutze, um Nachrichten �ber Windows anzuzeigen.

2. Dies ist ein Screenshot von meiner Website, wo ich das Widget nutze, um Nachrichten �ber Windows in meiner Sidebar anzuzeigen.

== Changelog ==


== Upgrade Notice ==

