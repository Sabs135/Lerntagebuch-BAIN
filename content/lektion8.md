## Lerneinheit 8 - Metadaten modellieren und Schnittstellen nutzen 2
Wie immer zuerst: [das heutige gemeinsame Dokument](https://pad.gwdg.de/1a2uYR-wRziCkvy3RL6gjA#)

### Konvertierung und Migration
Heute betrachteten wir das Thema der Daten-Konvertierung. Wir wollten die Daten konvertieren, so dass danach nur noch alles in MARC21 vorhanden ist. In unserem Beispiel würde dies die Daten betreffen, die in DublinCore und EAD vorliegen. Wenn Daten von einem bestimmten Datenformat oder System in ein anderes konvertiert werden müssen, bedeutet dies stets ein Mapping. Ich konnte bisher in keiner Lektion einen Bezug zu meiner Arbeitswelt herstellen (weder im Archiv- noch Bibliotheksbereich tätig). Aber immerhin konnte ich heute das erste Mal beim Thema Mapping nachempfinden, was das bedeutet. An meiner alten Stelle war ich in Projekt involviert, in welchen wir Daten von einem Legacy System in ein neues überführt hatten. Damit die Daten möglichst vollständig und möglichst verlustfrei im neuen landeten, war auch hier ein Mapping vorab nötig. Der Datenexport und -import erfolgte dort mittels XML.  
Interessant war auch hier das kurz behandelte Thema, was bei einem Crosswalk passieren kann. Es gibt zwar die bestehenden Metadatenstandards, jedoch pflegt nicht jede Bibliothek alle Daten genau gleich oder nutzt alle Felder. Im Fall einer Konvertierung können hier Ungleichheiten entstehen und schliesslich Datenverluste. 

Um keinen Datenverlust zu erhalten, wäre es am besten keine Konvertierung zu machen. Jedoch führt nicht wirklich ein Weg daran vorbei, wenn man danach mehr Daten/Services anbieten möchte. Man müsste sich also entscheiden:
* will man lieber weniger, dafür "saubere" Daten behalten?
* oder will man mehr Daten anbieten, nimmt dafür aber das Risiko auf Qualitätsverluste in Kauf?

Gemäss einer weltweiten Studie sind Einbussen bei einer Migration, beispielsweise auf eine neue Software, aber nichts Aussergewöhnliches. Eine Studie meldete, dass es bei Migrationen bei rund einem Drittel von Unternehmen zu Verlusten von Daten kommt (Kroll, 2016). Dies muss natürlich nicht auch bei einer hier gennanten Konvertierung der Fall sein. Aber ich denke, dass man sich des Risikos schon vorab bewusst sein sollte. Bei unseren diversen Übungen in den vergangenen Lerneinheiten (beispielsweise [Lektion 4](https://sabs135.github.io/Lerntagebuch-BAIN/content/lektion4.html)) war auch stets zu sehen, dass es immer wieder dazu kam, dass Kleinigkeiten fehlten. Am Ende summieren sich auch viele kleine fehlende Bestandteile zu einer relevanten Anzahl. 

### Transformation von Metadaten mit OpenRefine 
Wie bereits in der [dritten Lektion](https://sabs135.github.io/Lerntagebuch-BAIN/content/lektion3.html) kam erneut OpenRefine zum Einsatz. Mit einer Übung zum Thema _Reverse Engineering_ betrachten wir die Konvertierung von CSV Daten nach MARCXML. Der Begriff Reverse Engineering war heute ein neuer Begriff für mich. Diese Tätigkeit soll dabei helfen ein besseres Verständnis über einen bestimmten Prozess zu erhalten, indem ein Prozess umgekehrt wird und die einzelnen Komponenten genauer betrachtet werden (t2informatik GmbH).
Die beiden Daten, also jene im CSV in OpenRefine und die nach MARCXML exportieren Daten, konnten verglichen werden. Im nachfolgenden Screenshot sieht man die beiden Daten. 
![Übung in Open Refine](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/uebung_OpenRefine.png?raw=true)

Auch in der Darstellung mit MARCXML sind die Daten gut und klar erkennbar. Einige Elemente waren ein wenig eigenartig auf den ersten Blick. Ein Beispiel dafür war, dass die Autoren einfach gesplittet wurden und Autor Nr 1 das Feld 100 erhielt und alle anderen das Feld 700. Dies war so in der Spezifikation festgehalten. Dadurch war es bei allen Einträgen dasselbe und alle übrigend Autor:innen (wenn mehr als eine/r) wurde dem Feld 700 zugeordnet.
Dies und weitere Details zu den Unterschieden sind im [OpenRefine Wiki](https://github.com/OpenRefine/OpenRefine/wiki/Export-as-MARCXML) zu finden. 

**Quellen:**
* Kroll. (2016, März 22). _Kroll Ontrack Umfrage: Ein Drittel aller Unternehmen verlieren Daten bei der Migration. Pressemitteilungen._ Verfügbar unter: [https://www.ontrack.com/de-de/pressemitteilungen/details/umfrage-migration](https://www.ontrack.com/de-de/pressemitteilungen/details/umfrage-migration)
* t2informatik GmbH (n.d.). _Reverse Engineering._ Verfügbar unter: [https://t2informatik.de/wissen-kompakt/reverse-engineering/](https://t2informatik.de/wissen-kompakt/reverse-engineering/)

[nach oben](#lerneinheit-8---metadaten-modellieren-und-schnittstellen-nutzen-2)
