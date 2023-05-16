## Lerneinheit 9 - Suchmaschinen und Discovery-Systeme
Wie immer zuerst: [das heutige gemeinsame Dokument](https://pad.gwdg.de/F1wvRpdtR8-Mcv8so8NjUQ#)

### Elasticsearch und Solr
Wenn ich das Thema Elasticsearch höre, bin ich etwas zwiegespalten. Einerseits teile ich damit eher negative Erfahrungen, andererseits finde ich das Thema doch interessant. In meiner früheren Stelle war Elasticsearch immer wieder Thema (wurde für eine Art Online Shop verwendet). Ich weiss nicht warum, aber wir hatten ständig Probleme mit der dynamischen Anzeige der Suchergebnisse (zu langsame Aktualisierung) und es gab dadurch Reklamationen von den Anbieter:innen. Ich gehe an dieser Stelle aber nicht weiter darauf ein, da ich nicht wirklich beurteilen kann, ob das Problem an Elasticsearch lag oder sonst etwas dafür verantwortlich war. Trotzdem finde ich es mal schön, dass ich hier ein Thema höre, dass mir zur Abwechslung mal nicht ganz fremd ist. Zudem fällt es mir dadurch einfacher zu verstehen, was Solr ist/macht.  

Ich wollte trotzdem etwas darüber erfahren, was Solr nun genau ausmacht oder von Elasticsearch abhebt bzw. unterscheidet. Websuchen nach Solr und Elasticsearch geben sehr viele Ergebnisse aus und das über diverse Jahre. Viele davon stellen die Fragen, welche Unterschiede bestehen und welches der beiden nun das bessere ist.  
* 2015: [https://www.integer-net.de/warum-wir-solr-fuer-unser-suchmodul-nutzen-anstelle-von-elasticsearch/]()https://www.integer-net.de/warum-wir-solr-fuer-unser-suchmodul-nutzen-anstelle-von-elasticsearch/
* 2019: [https://www.ionos.de/digitalguide/server/konfiguration/elasticsearch/](https://www.ionos.de/digitalguide/server/konfiguration/elasticsearch/)
* 2020: [https://serverguy.com/comparison/solr-vs-elasticsearch/](https://serverguy.com/comparison/solr-vs-elasticsearch/)
* 2022: [https://sematext.com/blog/solr-vs-elasticsearch-differences/#1-apache-solr-vs-elasticsearch-engine-performance-scalability-benchmark](https://sematext.com/blog/solr-vs-elasticsearch-differences/#1-apache-solr-vs-elasticsearch-engine-performance-scalability-benchmark)
* 2023: [https://db-engines.com/de/system/Elasticsearch%3BSolr](https://db-engines.com/de/system/Elasticsearch%3BSolr)

Elasticsearch ist moderner, kostenlos (aber nicht Open Source) und mittlerweile am beliebtesten. Solr unterstützt mehr Programmiersprachen, hat eine bessere Precision und ist Open Source. Dies ist nur kleine Auswahl von Ergebnissen, welche sich auf all den verschiedenen Seiten finden lässt. Es gäbe noch viele weitere Punkte, aber ich lasse die Aufzählung mal kurz. 
Nachfolgend ist noch eine Grafik zu sehen, welche die Aussage, dass Elasticsearch am beliebtesten sei, noch zusätzlich unterstützt.
![Beliebte Suchmaschinen](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/beliebtheit.png?raw=true)  
(Bildquelle: Kuć, 2022)

### Ein wenig Praxis
In der Übung zum Vergleich von Solr und VuFind war es zuerst etwas mühsam die Daten zu vergleichen (oder ging es nur mir so?). In der Breakout Session mit einer Kommilitonin fand ich divere Dinge in VueFind nicht. Jedoch machte mich die Kollegin darauf aufmerksam, dass sich meine "vermissten" Daten in den übrigen Laschen/Tabs verstecken. Diese hatte ich komplett übersehen. Nun gut, so lückenhaft scheint VuFind dann doch nicht. 

Als die Übung dann schon fertig war und ich einen Screenshot machen wollte, merkte ich dann noch, dass Solr nicht responsive ist. Wenn ich es richtig verstanden habe, handelt es sich bei Solr ja um ein Backendsystem bzw. ist für die Technik. Daher ist Responsive Design nicht wichtig und auch sonst ist es nicht relevant wie das UI aussieht. Daher fange ich gar nicht erst damit an. ;-)
Mir fiel das fehlende Responsive Design nur auf, da ich die beiden Fenster nicht schön nebeneinander legen konnte für die Erstellung eines Screenshots. Bei Solr überlappte der Ergebnistext mit der Suchmaske (siehe Bild). Ich hatte hier ein paar Daten angeschaut und sie zum Vergleich angestrichen. Jedoch war ich mir nicht immer sicher, ob ich nun das richtige Feld in Solr markiert hatte. Nur schon allein den Titel "The Journal of Psychology" ist in Solr an diversen Stellen zu finden (glaube 4x). Ich markierte einfach jenen Eintrag mit "title:"The Journal of psychology", da dies für mich am logischsten schien. 
![Vergleich Solr und VuFind](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/vrgl_solr_vufind.png?raw=true)


**Quellen:**
Rafal Kuć, R. (2022, January 7). Solr vs Elasticsearch: Performance Differences & More. How to Decide Which One Is Best for You.[https://sematext.com/blog/solr-vs-elasticsearch-differences/#comparing-solr-vs-elasticsearch-what-are-the-main-differences](https://sematext.com/blog/solr-vs-elasticsearch-differences/#comparing-solr-vs-elasticsearch-what-are-the-main-differences)

[nach oben](#lerneinheit-8---suchmaschinen-und-discovery-systeme)
