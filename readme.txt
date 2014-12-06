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

Das 'Simple Google News DE' WordPress Plugin erleichtert die Anzeige der Google News Ergebnisse auf Deiner WordPress Website. Per Shortcode wird der Google News Stream zu einem Thema in Deinem Artikel oder Seite dargestellt nutze dafür einfach folgenden Shortcode:

[google_news]

Im Widget kannst Du die Region der Nachrichten auswählen, aktuell sin die Regin auf Deutschland, Österreich, Schweiz, Großbritannien und die USA beschränkt. Auf Anfrage kann ich gerne weitere Regionen hinzufügen.

= Mögliche Parameter =

Es gibt eine Handvoll  optionale Parameter, die man verwenden kanne, um die Ausgabe nach Wünschen anzupassen.

**query** – *Default: none*. Verwende diese Option, wenn Du nach einem bestimmten Wort oder Ausdruck bei Google News möchtest.

**limit** – *Default: 5, Max: 10*. Mit dem Parameter "Limit", kannst Du die maximale Anzahl der Ergebnisse festlegen, die Sin Deinem Beitrag oder Seite angezeigt werden.

**images** – *Default: on*. Die Bilder werden standardmäßig angezeigt. Wenn Du sie ausschalten möchtest, stelle den Bildern Parameter auf "Off". Hinweis: Nicht alle Nachrichten Storys werden ein Bild haben.

**length** – *Default: 300*. Der Parameter "length" steuert die Anzahl der Zeichen in der Beschreibung (wird auf das nächste ganze Wort gerundet) angezeigt werden sollen.

**region** – *Default: de*. Mit dem Parameter "Region", kannst Du  Nachrichten von einem bestimmten Teil der Welt anzeigen. Um die Liste der derzeit unterstützten Regionen zu sehen, besuchen [link] (https://support.google.com/news/answer/40237?hl=de "Diese Seite"). Beachte den Parameter "definiert", die in jeder Region Link vorhanden ist. Zum Beispiel Österreich de_at Parameter auf 'de_at' eingestellt ist. Das ist der Wert, den Du verwendest, um Nachrichten aus der jeweiligen Region anzuzeigen.

**sort** - *Default: relevancy*. Dieser Parameter gibt Dir zusätzliche Kontrolle über die Ergebnisse, die zurückgegeben werden. Hier ist eine Liste der zulässigen Werte:

* r (für Relevanz)
* n nach Datum (neuste zuerst)
* d nach Datum (neuste zuerst mit Duplikaten)
* o nach Datum (älteste zuerst)

**topic** – *Default: none*. Wenn Du regelmäßig Neuigkeiten nach einem Thema anzeigen möchtest (z.B.: Technologie, Unterhaltung, usw.), kannst Du dies mit diesem Parameter tun. Zum Beispiel, wenn Du Technik Ergebnisse zeigen möchtest, würdes Du diesen Shortcode nutzen:

[google_news limit="2" topic="t"]

Hinweis: der Themen Parameter überschreibt die Abfrageparameter. Also, wenn Du dieses versuchst:

[google_news query="android" topic="t"]

Google News würde also diese Abfrage zu ignorieren.

Die Themen Werte kannst Du nutzen:

* b (für Wirtschaft)
* t (für Technik)
* e (für Unterhaltung)
* s (für Sport)
* snc (for science)
* m (für Gesundheit)
* ir (für Schlagzeilen)

== Installation ==

1. Upload von 'simple-google-news-de' in das Verzeichniss '/wp-content/plugins/'
1. Activier das Plugin im 'Plugins' Menü in WordPress
1. Füge den Shortcode[google_news] in deinen Artikel oderSeite ein 

== Frequently Asked Questions ==

= Ich verwende den Shortcode und nichts passiert! =

Es gibt hierfür zwei Ursachen.  Erstens es gibt kein Google News Ergebnis zu Deinem Begriff. Überprüfe auf news.google.com, ob Google News Dir ein Ergebnis liefert. Zweitens, es wurde ein ungültiger Wert im Shortcode angegeben.

= Kann ich nach einer exakten Zeichenfolge mit Anführungszeichen suchen? =

Ja! Du musst nur sicherstellen, dass die doppelten Anführungszeichen in einfache Anführungszeichen eingebettet sind, so z.B.: [google_news query='"whatsapp hack"']

== Screenshots ==

1. Dies ist ein Screenshot von meiner Website, wo ich den Shortcode nutze, um Nachrichten über Windows anzuzeigen.

2. Dies ist ein Screenshot von meiner Website, wo ich das Widget nutze, um Nachrichten über Windows in meiner Sidebar anzuzeigen.

== Changelog ==


== Upgrade Notice ==

