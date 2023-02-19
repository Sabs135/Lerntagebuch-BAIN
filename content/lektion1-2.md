## Lerneinheit 1 & 2: Technische Grundlagen

Wie bereits kurz in der Einführung angetönt, sind die Kenntnisse der einzelnen Personen in Bezug auf Bibliotheks- und Archivsoftware unterschiedlich. Dies spielt aber keine Rolle, denn es sollen die Grundlagen vermittelt werden. Die Grundlagenvermittlung zeigte sich auch bei den Themen der zwei Lerneinheiten des heutigen Tags: **Technische Grundlagen 1 und 2**. 

### Schaubild
Uns wurde das Schaubild zu den Lehrinhalten aufzeigt und erklärt. Dieses werden wir im Lauf des Semesters immer wieder sehen und daher werden die Details der einzelnen Fragmente auch später nochmals besprochen. Vereinfacht in einem Satz zeigt das Schaubild die "Datenernte" (mittels OAI-PMH-Schnittstelle*) verschiedener Katalogisierungssysteme (Koha, ArchiveSpace, DSpace) und wie diese am Ende in einem Discovery System / Suchindex landen. 
 
_*OAI-PMH: Open Archives Initiative Protocol for Metadata Harvesting. Ein festgelegter Standard des OAI_  

![Schaubild](https://user-images.githubusercontent.com/92395466/219941621-da392eed-b847-4772-a2d1-7793d1ea995d.png)


Die auf der linken Seite angezeigten Katalogisierungssysteme sind folgende:

* Koha: für Bibliotheken
* ArchiveSpace: für Archive
* DSpace: für Publikationsdaten (Repository für Online-Dokumente)

Die durch die Schnittstelle geernteten Daten existieren in je einer XML-Datei in den verschiedenen Metadatenstandards (MARC21-XML, EAD, Dublin Core). Diese XML werden exportiert und mittels Crosswalks (in diesem Kurs anhand der Software marcEdit (XLST)) zusammengefügt und in einem MARC21-XML exportiert. Mit dem Suchindex Solr ergibt dies letztlich eine Suchoberfläche mit VuFind, welche es ermöglicht, dass nur ein Suchschlitz für alle Daten benötigt wird. Dies ist von Vorteil für die Nutzenden, da sie ihre Suchbegriffe nur an einem Ort eintragen müssen. In der Praxis ist dies auch bei dem ETH Wissensportal zu finden. Weiterführende Details dazu hier:

> Neubauer, W. & Piguet, A. (2014). Das Wissensportal der Bibliothek der ETH Zürich. In K. Söllner & W. Sühl-Strohmenger (Ed.), _Handbuch Hochschulbibliothekssysteme: Leistungsfähige Informationsinfrastrukturen für Wissenschaft und Studium_ (pp. 439-454). Berlin, München, Boston: De Gruyter Saur. https://doi.org/10.1515/9783110310092-041


### Crashkurs in Terminalbefehlen, Github, Git und Codespace
Da die Mehrheit der ganze Klasse, ich eingeschlossen, nicht ganz fit im Umgang den oben genannten Tools oder Anwendungen waren, gab es zum Einstieg des Nachmittags eine kurze Wiederholung. Die letzte Anwendung von Terminalbefehlen liegt bei mir etwa ein Jahr zurück. Meine Kenntnisse zu Github und Git waren bisher auch eher oberflächlich. Codespace hingegen war komplett neu. Ich nutzte bisher immer heruntergeladene Software Studio Visual Code. Dass es dafür nun auch eine Online-Version gibt, war neu für mich. Da ich für meinen Major bereits zwei Kurse lang die Software genutzt habe, war die Oberfläche selbst aber nicht neu für mich. 


### HedgeDoc und Markdown
Der Klasse wurde in Moodle der Link zu einem [gemeinsamen HedgeDoc Dokument](https://pad.gwdg.de/Nj7bLYj_QHqaP9o29V0yGw#) geteilt. Von diesem kollaborativen Open Source Editor hatte ich bisher noch nie gehört und ich finde es eine tolle Abwechslung. Da die Klasse HedgeDoc nicht kannte, wurden uns auch die wichtigsten Funktionalitäten gezeigt. Als super Eigenschaft von HedgeDoc finde ich die Teilungsmöglichkeit, sprich, dass man gleichzeitig den Bearbeitungsmodus und den "fertigen" Modus sieht. So kann man Formatierungsfehler oder sonstige Fehler sofort sehen. Der gesamte Inhalt, welcher in der Lektion besprochen wurde, war im Hedgedoc Dokument zu finden. Das Dokument ersetzte quasi die PowerPoint Präsentation, welche sonst in jeder anderen Vorlesung gebraucht wird. Ich fand diese Abwechslung auch mal gut. Ich fand auch die Listen gut, welcher der Dozent für die Übungen vorbereitet hatte. So konnte man, sobald man deine Übung fertig hatte, seinen Namen reinschreiben. Dies gab einen guten Überblick.

Als Sprache wird Markdown verwendet. Ich hatte bisher schon oft von davon gelesen, oder den Namen am einen oder anderen Ort gesehen, aber ich hatte Markdown bisher weder angewendet noch gelernt, wie die Sprache funktioniert. Die Frage des Dozenten an die Klasse zeigte, dass die Mehrheit kein Markdown kannte bzw. nicht wusste, wie sie anzuwenden ist. Aus diesem Grund erhielten wir Zeit um selbstständig ein [Markdown-Tutorial](https://www.markdowntutorial.com) durchzuarbeiten. Ich empfand dieses Tutorial als sehr hilfreich. Der Mix aus kurzer Erklärung und Möglichkeit es auszuprobieren war optimal. Es zeigt einem die wichtigsten Dinge, um einen Text mittels Markdown erstellen zu können. Bei zwei Übungen wollte zwar partout die nächste Übung nicht erscheinen und im Vergleich mit der Nachbarin war der Fehler auch nicht zu sehen. Zum Glück gibt es aber den Skip Button, der hier den Sprung zur nächsten Übung ermöglichte. Am Ende des Tutorials hatte ich auf jeden Fall das Gefühl einen Einblick in Markdown erhalten zu haben und die wichtigsten Funktionen nun zu kennen. 

Beim Schreiben von diesem Text hier, war ich bei einzelnen Punkten aber bereits wieder etwas unsicher. Da das Tutorial zwar super zum Üben war, aber nicht ideal ist um auf einen Blick alle Funktionen zu sehen, habe ich meist auf die [Basic Syntax]( https://www.markdownguide.org/basic-syntax/) Seite des Markdown Guides zurückgegriffen.

 
### Die Suche nach dem passenden Blog-Portal

Zwei Klassenkameraden, welche bereits vertiefte Kenntnisse über die Inhalte des heutigen Vormittags hatten, konnten den Vormittag bereits für die Erstellung ihres Blogs nutzen. Sie waren auch die ersten, welche ihre Blogs in die Liste des gemeinsamen HedgeDoc Dokuments schrieben. Da sie es mit Github versuchten, wollten auch ich und meine Sitznachbarinnen es damit versuchen. Wir hatten einige Startschwierigkeiten und befürchteten, dass Github eventuell zu viel Aufwand generieren würde. Bevor wir zu viel Zeit in die Erstellung eines Github-Blogs verwendeten, wollten wir einen Blick auf HedgeDoc werfen. Aufgrund des heutigen Blogs fanden wir drei, dass dies auch eine gute Option wäre. Jedoch stellte bereits die Registrierung eine erste Schwierigkeit dar. Die Registrierung über die Webseite der [GWDG](https://pad.gwdg.de/) war leider nicht möglich. Um sich darüber registrieren zu können, verlangt es eine Academic ID (siehe Meldung auf nachfolgendem Screenshot). Im dargestellten Dropdown waren zwar diverse Einrichtungen aufgeführt, aber es waren ausschliesslich welche aus Deutschland zu finden. Die Registrierung mit der E-Mail der FHGR oder mit der sonst an vielen Orten verfügbaren [SWITCHaai]( https://www.switch.ch/aai/) war nicht möglich.  
![Darstellung GWDG](https://user-images.githubusercontent.com/92395466/219939264-2f4e3622-0777-4c1d-bb8c-5808a2de3eea.png)

Alternativ fanden wir die Möglichkeit HedgeDoc auch in einer Demo-Version zu nutzen. Die URL dafür war auch eine andere. Vergleiche:
* Von GWDG: <https://pad.gwdg.de/>   
* Demo-Version, ohne GWDG: <https://demo.hedgedoc.org/>

Der Dozent recherchierte netterweise für uns, was die Demo-Version in diesem Fall genau bedeuten würde. Es wäre grundsätzlich möglich die Demoversion zu nutzen, wenn wir nach jeder Bearbeitung einen Download der Seite machen würden. Dies, damit nicht plötzlich unser ganzer Blog weg wäre. Eine Garantie, dass der Blog unverändert aktiv bleibt, existiert bei der Demoversion nicht. Zwar wäre es eine Möglichkeit dadurch HedgeDoc zu verwenden, aber ich fände es sehr ärgerlich, wenn man genau das eine Mal vergisst einen Export zu machen und dann mein Blog aufgrund irgendwelcher Änderungen komplett weg wäre. Aufgrund dessen wechselte ich wieder zurück auf Github. 

Nun schreibe ich meinen Blog auch in Github und habe es zumindest geschafft eine Seite zu erstellen, welche navigierbar und lesbar ist. Ich denke, dass ich dies somit dabei belassen und am Blog in Github festhalten werde.  

