# Lerneinheit 8 - Metadaten modellieren und Schnittstellen nutzen 2
Wie immer zuerst: [das heutige gemeinsame Dokument](https://pad.gwdg.de/1a2uYR-wRziCkvy3RL6gjA#)

**Konvertierung und Migration**
Heute betrachteten wir das Thema der Daten-Konvertierung. Wir wollten die Daten konvertieren, so dass danach nur noch alles in MARC 21 vorhanden ist. In unserem Beispiel würde dies die Daten betreffen, die in DublinCore und EAD vorliegen. Wenn Daten von einem bestimmten Datenformat oder System in ein anderes konvertiert werden müssen, bedeutet dies stets ein Mapping. Ich konnte bisher in keiner Lektion einen Bezug zu meiner Arbeitswelt herstellen (weder im Archiv- noch Bibliotheksbereich). Aber immerhin konnte ich heute das erste Mal beim Thema Mapping nachempfinden, was das bedeutet. An meiner alten Stelle war ich in Projekt involviert, in welchen wir Daten von einem Legacy System in ein neues überführt hatten. Damit die Daten möglichst vorllständig und möglichst verlustfrei im neuen landeten, war auch hier ein Mapping vorab nötig. 
Interessant war auch hier das kurz behandelte Thema, was bei einem Crosswalke passieren kann. Es gibt zwar die bestehenden Metadatenstandards, jedoch pflegt nicht jede Bibliothek alle Daten genau gleich oder nutzt alle Felder. Im Fall einer Konvertierung können hier Ungleichheiten entstehen und schliesslich Datenverluste. 

Um keinen Datenverlust zu erhalten, wäre am besten keine Konvertierung zu machen. Jedoch führt nicht wirklich ein Weg daran vorbei, wenn man danach mehr Daten/Services anbieten möchte. Es führt aus diesem Grund fast kein Weg daran vorbei. Gemäss einer weltweiten Studie (Kroll, 2016) sind Einbussen bei einer Migration, beispielsweise auf eine neue Software, aber nichts Aussergewöhnliches. Die Studie meldete, dass es bei Migrationen bei rund einem Drittel von Unternehmen zu Datenverlusten kommt (Kroll, 2016).


**Transformation von Metadaten mit OpenRefine**
Wie bereits in der [zweiten Lektion](lektion2.md) kam erneut OpenRefine zum Einsatz. Mit einer Übung betrachten wir die Konvertierung von CSV Daten nach MARCXML. 
Im nachfolgenden Screenshot sieht man die beiden Daten. 
![Übung in Open Refine](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/uebung_OpenRefine.png?raw)

Auch in der Darstellung mit MARCXML sind die Daten gut und klar erkennbar. Einige Elemente waren ein wenig eigenartig auf den ersten Blick. Ein Beispiel dafür war, dass die Autoren einfach gesplittet wurden und Autor Nr 1 das Feld 100 erhielt und alle anderen das Feld 700. 



**Quellen:**
Kroll. (2016, März 22). _Kroll Ontrack Umfrage: Ein Drittel aller Unternehmen verlieren Daten bei der Migration. Pressemitteilungen._ Verfügbar unter:
https://www.ontrack.com/de-de/pressemitteilungen/details/umfrage-migration


[nach oben](#lerneinheit-8---metadaten-modellieren-und-schnittstellen-nutzen-2)
