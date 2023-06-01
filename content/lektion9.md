## Lerneinheit 9 - Suchmaschinen und Discovery-Systeme
Wie immer zuerst: [das heutige gemeinsame Dokument](https://pad.gwdg.de/F1wvRpdtR8-Mcv8so8NjUQ#)

### Elasticsearch, Solr und My SQL
Wenn ich das Thema Elasticsearch höre, bin ich etwas zwiegespalten. Einerseits teile ich damit eher negative Erfahrungen, andererseits finde ich das Thema interessant. In meiner früheren Stelle war Elasticsearch ständig Thema (der Suchindex wurde für eine Art Online Shop verwendet). Ich weiss nicht warum, aber wir hatten ständig Probleme mit der dynamischen Anzeige der Suchergebnisse (zu langsame Aktualisierung). Ich gehe an dieser Stelle aber nicht weiter darauf ein. Es fällt mir jedenfalls leichter zu verstehen, was Solr ist/macht. Solr ist nämlich der Suchindex bzw. die Suchmaschine auf welchem VuFind basiert.

Ich wollte trotzdem etwas darüber erfahren, was Solr genau ausmacht oder von Elasticsearch abhebt bzw. unterscheidet. Websuchen nach Solr und Elasticsearch geben sehr viele Ergebnisse aus und das über diverse Jahre. Viele davon stellen die Fragen, welche Unterschiede bestehen und welches der beiden nun das bessere ist.  
* 2015: [Warum wir Solr für unser Suchmodul nutzen anstelle von ElasticSearch](https://www.integer-net.de/warum-wir-solr-fuer-unser-suchmodul-nutzen-anstelle-von-elasticsearch/)
* 2019: [Elasticsearch: Die flexible Search Engine](https://www.ionos.de/digitalguide/server/konfiguration/elasticsearch/)
* 2020: [Solr Vs Elasticsearch: Which Search Engine is Better?](https://serverguy.com/comparison/solr-vs-elasticsearch/)
* 2022: [Solr vs Elasticsearch: Performance Differences & More. How to Decide Which One Is Best for You](https://sematext.com/blog/solr-vs-elasticsearch-differences/#1-apache-solr-vs-elasticsearch-engine-performance-scalability-benchmark)
* 2023: [System Properties Comparison Elasticsearch vs. MySQL vs. Solr](https://db-engines.com/en/system/Elasticsearch%3BMySQL%3BSolr)  

Der letzte Link zeigt auch noch einen Vergleich mit MySQL, welche ebenfalls als Suchmaschine in Form einer Datenbank aufgeführt wird. Im Detail werde ich hier aber nicht auf MySQL eingehen. 

Zurück zu Elasticsearch und Solr:
Elasticsearch ist moderner, kostenlos (aber nicht Open Source) und mittlerweile am beliebtesten. Solr unterstützt mehr Programmiersprachen, hat eine bessere Precision und ist Open Source. Dies ist nur kleine Auswahl von Ergebnissen, welche sich auf all den verschiedenen Seiten finden lässt. Es gäbe noch viele weitere Punkte, aber ich lasse die Aufzählung mal kurz. 
Nachfolgend ist noch eine Grafik zu sehen, welche die Aussage, dass Elasticsearch am beliebtesten sei, noch zusätzlich unterstützt.  
![Beliebte Suchmaschinen](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/beliebtheit.png?raw=true)  
(Bildquelle: Kuć, 2022)

### Ein wenig Praxis mit Solr und VuFind
In der Übung zum Vergleich von Solr und VuFind war es zuerst etwas mühsam die Daten zu vergleichen (oder ging es nur mir so?). In der Breakout Session mit einer Kommilitonin fand ich diverse Dinge in VueFind nicht. Jedoch machte mich die Kollegin darauf aufmerksam, dass sich meine "vermissten" Daten in den übrigen Laschen/Tabs verstecken. Diese hatte ich komplett übersehen. Nun gut, so lückenhaft scheint VuFind dann doch nicht. 

Als die Übung dann schon fertig war und ich einen Screenshot machen wollte, merkte ich dann noch, dass Solr nicht responsive ist. Wenn ich es richtig verstanden habe, handelt es sich bei Solr ja um ein Backendsystem bzw. ist für die Technik. Daher ist Responsive Design nicht wichtig und auch sonst ist es nicht relevant wie das UI aussieht. 
Mir fiel das fehlende Responsive Design nur auf, da ich die beiden Fenster nicht schön nebeneinander legen konnte für die Erstellung eines Screenshots. Bei Solr überlappte der Ergebnistext mit der Suchmaske (siehe Bild). Ich hatte hier ein paar Daten angeschaut und sie zum Vergleich angestrichen. Jedoch war ich mir nicht immer sicher, ob ich nun das richtige Feld in Solr markiert hatte. Nur schon allein den Titel "The Journal of Psychology" ist in Solr an diversen Stellen zu finden (glaube 4x). Ich markierte einfach jenen Eintrag mit "title:"The Journal of psychology", da dies für mich am logischsten schien. 
![Vergleich Solr und VuFind](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/vrgl_solr_vufind.png?raw=true)  

### Discovery Systeme
Wir warfen am Ende nur noch einen kurzen Blick auf Discovery Systeme. Dabei fanden auch Alma oder Swisscovery kurz Erwähnung.

**Quellen:**  
Rafal Kuć, R. (2022, January 7). Solr vs Elasticsearch: Performance Differences & More. How to Decide Which One Is Best for You. [https://sematext.com/blog/solr-vs-elasticsearch-differences/#comparing-solr-vs-elasticsearch-what-are-the-main-differences](https://sematext.com/blog/solr-vs-elasticsearch-differences/#comparing-solr-vs-elasticsearch-what-are-the-main-differences)  

[nach oben](#lerneinheit-9---suchmaschinen-und-discovery-systeme)
