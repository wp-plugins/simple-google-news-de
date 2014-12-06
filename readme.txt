=== Simple Google News DE ===
Contributors: (baynado)
Donate link: http://internet-pr-beratung.de/
Author URI: http://internet-pr-beratung.de/
Plugin URI: http://internet-pr-beratung.de/simple-google-news-de
Tags: google, google news, rss, feed, news
Requires at least: 2.5
Tested up to: 4.0.1
Stable tag: 3.2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Binde mit diesem einfachen Plugin den Google News Stream zu einem bestimmten Thema in die Sidebar, Deine Artikel oder Seiten ein. 

== Description ==

Dieses Plugin kann als Widget oder per Shortcode genutzt werden.

Das 'Simple Google News DE' WordPress Plugin erleichtert die Anzeige der Google News Ergebnisse auf Deiner WordPress Website. Per Shortcode wird der Google News Stream zu einem Thema in Deinem Artikel oder Seite dargestellt nutze dafür einfach folgenden Shortcode:

[google_news]

Im Widget kannst Du die Region der Nachrichten auswählen, aktuell sin die Regin auf Deutschland, österreich, Schweiz, Großbritannien und die USA beschrähnkt. Auf Anfrage kann ich gerne weitere Regionen hinzufügen.

= Parameter =

Es gibt eine Handvoll  optionale Parameter, die man verwenden kann, um die Ausgabe anzupassen.

**query** � *Default: none*. Verwende diese Option, wenn Du Nachrichten zu einem bestimmten Wort oder Ausdruck von Google News einbinden moechtest.

**limit** � *Default: 5, Max: 10*. Mit dem Parameter "Limit", kannst Du die maximale Anzahl der Ergebnisse festlegen, die in Deinem Beitrag oder Seite angezeigt werden.

**images** � *Default: on*. Die Bilder werden standardmässig angezeigt. Wenn Du sie ausschalten möchtest, stelle den Bildern Parameter auf "Off". Hinweis: Nicht alle Nachrichten Storys werden ein Bild haben.

**length** � *Default: 300*. Der Parameter "length" steuert die Anzahl der Zeichen in der Beschreibung (wird auf das nächste ganze Wort gerundet), die angezeigt werden sollen.

**region** � *Default: de*. Mit dem Parameter "Region", kannst Du  Nachrichten von einem bestimmten Teil der Welt anzeigen lassen. Um die Liste der aktuell unterstützten Regionen zu sehen, besuche [link] (https://support.google.com/news/answer/40237?hl=de "Diese Seite"). Beachte den Parameter "definiert", der in jedem Region Link vorhanden ist. Zum Beispiel österreich hat de_at als Parameter. Das ist der Wert, den Du verwendest, um Nachrichten aus der jeweiligen Region anzuzeigen.

**sort** - *Default: relevancy*. Dieser Parameter gibt Dir zusätzliche Kontrolle über die Ergebnisse, die zurückgegeben werden. Hier ist eine Liste der zulässigen Werte:

* r (Relevanz)
* n nach Datum (neuste zürst)
* d nach Datum (neuste zürst mit Duplikaten)
* o nach Datum (älteste zürst)

**topic** � *Default: none*. Dieser Parameter zeigt Neuigkeiten nach einem Thema an (z.B.: Technologie, Unterhaltung, usw. Zum Beispiel, Technik Ergebnisse werden, mit diesen Shortcode angezeigt:

[google_news limit="2" topic="t"]

Hinweis: der Themen Parameter überschreibt die Abfrageparameter. Also, wenn Du dieses versuchst:

[google_news query="android" topic="t"]

Google News wird also diese Abfrage zu ignorieren.

Die Themen Werte kannst Du nutzen:

* b (Wirtschaft)
* t (Technik)
* e (Unterhaltung)
* s (Sport)
* snc (Wissenschaft)
* m (Gesundheit)
* ir (Schlagzeilen)

== Installation ==

1. Upload von 'simple-google-news-de' in das Verzeichniss '/wp-content/plugins/'
1. Aktiviere das Plugin im 'Plugins' Menü in WordPress
1. Gebe den Shortcode[google_news] in Deinen Artikel oder Seite ein. 

== Frequently Asked Questions ==

= Ich verwende den Shortcode und nichts passiert! =

Das kann zwei Ursachen haben.  Erstens es gibt kein Google News Ergebnis zu Deinem Begriff. Schaue auf news.google.com, ob Google News Dir ein Ergebnis liefert. Zweitens, es wurde ein falscher Wert im Shortcode angegeben.

= Kann ich nach einer exakten Zeichenfolge mit Anführungszeichen suchen? =

Ja! Du musst nur sicherstellen, dass die doppelten Anführungszeichen in einfache Anführungszeichen eingebettet sind, so z.B.: [google_news query='"whatsapp hack"']

== Screenshots ==

1. Dies ist ein Screenshot von meiner Website, wo ich den Shortcode nutze, um Nachrichten über Windows anzuzeigen.

2. Dies ist ein Screenshot von meiner Website, wo ich das Widget nutze, um Nachrichten über Windows in meiner Sidebar anzuzeigen.

== Changelog ==

= 1.0.1 =
* Kleinere Korreturen in der Beschreibung des Plugins
= 1.0.2 =
* Kleinere Korreturen in der Beschreibung des Plugins
= 1.0.3 =
* Plugin hat jetzt ein Icon und Banner 

== Upgrade Notice ==

= 1.0.1 =
* Kleinere Korreturen in der Beschreibung des Plugins
= 1.0.2 =
* Kleinere Korreturen in der Beschreibung des Plugins
= 1.0.3 =
* Plugin hat jetzt ein Icon und Banner 
