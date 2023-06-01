## Lerneinheit 10 - Linked Data
Und noch ein letztes Mal: [das heutige gemeinsame Dokument](https://pad.gwdg.de/_6j1KL1wS9O7PD09pYDGoA#)

### ChatGPT
Der Start in die Lektion erfolgte mit ChatGPT. Wirklich oft hatte ich diesen bisher noch nicht gebraucht, wenn dann mehr aus Spass mit Freund:innen. In der heutigen Übung in der Breakout Session hatte die eine Kommilitionin eine Idee für eine Frage, welche sie in die [Demo-Version](https://chat.chatgptdemo.net/) eingab. Sie fragte nach den "Vorteilen und Nachteilen von Alma". Ich gab dieselbe Frage auch ein, jedoch unabsichtlich mit einer anderen Schreibweise. Als die Kommilitionin die Antworten vorlas, stellte ich fest, dass wir komplett andere Antworten erhielten. Dass eine andere Schreibweise gleich zu solchen Abweichungen in der Antwort führen kann, war mir neu. Eine ganz kurze Recherche zeigte aber, dass dies nicht wirklich aussergewöhnlich ist. So kann man über den Button "Regenerate response" sogar eine neue Antwort auf dieselbe Frage anstossen (siehe auch [Blogartikel des Business Insider](https://www.businessinsider.de/wirtschaft/chat-gpt-diese-anleitung-zeigt-euch-schritt-fuer-schritt-wie-ihr-den-chatbot-von-openai-nutzen-koennt-b/)).
Somit wäre nicht mal nötig die Frage neu oder anders zu formulieren. Passt mir die erste Antwort also nicht, nehme ich einfach die zweite Antwort, oder die dritte usw. Da ich Alma nicht wirklich kenne, kann ich nicht beurteilen, ob die Antworten auch etwas Wahres haben und welche der beiden "besser" wäre. 
![Vergleich der Fragen in ChatGPT](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/Vrgl_fragen_chatgpt.png?raw=true)

Dass ChatGPT gerne mal halluziniert, ist mittlerweile ja auch nicht mehr wirklich etwas Neues. Die Kommilitionen fragte ChatGPT daher absichtlich, was der Unterschied zwischen Alma und einem erfundenen Begriff war. Ich mag mich nicht mehr genau erinnern, aber der erfundene Begriff startete mit "Archive ...". Wenig erstaunte dann die Antwort von ChatGPT, dass dieses (wohlgemerkt erfundene(!)) System sehr gut im Archivbereich geeignet wäre. Unser Versuch war ja nur ein Test. Solche Ergebnisse zeigen, dass ChatGPT zwar auf KI, also "(Künstlicher) Intelligenz" beruht, aber dies hier noch nicht bedeutet, dass alles was ausgespuckt wird, auch so stimmt. Dies zeigt wie wichtig Medienkompetenz ist und dass nicht alles einfach für wahr genommen werden darf. 

### Metadaten anreichern mit OpenRefine und Wikidata
Zum Abschluss des Unterrichts in BAIN nutzen wir erneut OpenRefine. Dies hatten wir bereits in der [Lektion 3](https://sabs135.github.io/Lerntagebuch-BAIN/content/lektion3.html) und [Lektion 8](https://sabs135.github.io/Lerntagebuch-BAIN/content/lektion8.html) genutzt. Im heutigen Beispiel wollten wir bestehende Daten mit Daten aus Wikidata verküpfen. Wikidata ist eine Wissensdatenbank, welche 2012 ins Leben gerufen wurde und immer mehr und mehr Einträge erhält (gemäss [Wikipedia](https://de.wikipedia.org/wiki/Wikidata)). 
Reconciliation war dabei ein häufiger Begriff. Da mir dieser bisher noch nicht geläufig war, recherchierte ich erneut dazu. 

Reconciliation ist insbesondere bei der Datenmigration wichtig, da es sich um einen Verifikationsprozess handelt. Im Verlauf von Datenmigrationen besteht die Möglichkeit, dass es zu Inkonsistenzen oder Fehler beim Mapping kommt und durch die Reconciliation werden allfällige Fehler aufgedeckt bzw. dadurch eine Datenkonsistenz sichergestellt (Experian, n.d.). In der Einleitung des entwickelten Entwurfs für einen Standard vom  W3C Community Group steht dazu: 
> Integrating data from sources which do not share common unique identifiers often requires matching (or reconciling, merging) records which refer to the same entities. 	The promises of the Linked Open Data movement, the ability to mix up data from different publishers expressed in a common language (such as RDF) rely on being able to identify identities across services. (...)

In der Übung in OpenRefine bin ich mir nicht hundertprozentig sicher, ob ich alles korrekt nachgemacht hatte. An einer Stelle hatte ich kurz den Faden verloren. Jedoch konnte ich am Ende einige Werte auswählen, die ich zusätzlich als Spalte in meiner Tabelle anzeigen wollte. So hatte ich bei meinem zusätzlich noch das Geschlecht und den Sterbeort hinzugefügt.

![Reconcile Daten](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/openrefine_reconcile.png?raw=true)
![Vergleich der Anfangsdaten und Enddaten](https://github.com/Sabs135/Lerntagebuch-BAIN/blob/main/img/openrefine_vrgl_anfang_ende.png?raw=true)

Ich fand das gezeigte Beispiel recht einfach und doch sehr anschaulich. Man hätte die Tabelle auch noch um viele weitere Attribute erweitern und so noch viel mehr Daten anzeigen können. 

**Quellen:**
Experian. (n.d.). _What is Data Reconciliation?_[https://www.experian.co.uk/business/glossary/data-reconciliation/](https://www.experian.co.uk/business/glossary/data-reconciliation/)  
Jackson, S. (2023). _Chat GPT: Diese Anleitung zeigt euch Schritt für Schritt, wie ihr den Chatbot von OpenAI nutzen könnt. Business Insider._
[https://www.businessinsider.de/wirtschaft/chat-gpt-diese-anleitung-zeigt-euch-schritt-fuer-schritt-wie-ihr-den-chatbot-von-openai-nutzen-koennt-b/](https://www.businessinsider.de/wirtschaft/chat-gpt-diese-anleitung-zeigt-euch-schritt-fuer-schritt-wie-ihr-den-chatbot-von-openai-nutzen-koennt-b/)  
W3C Community Group. (2023). _Reconciliation Service API v0.1._ [https://www.w3.org/community/reports/reconciliation/CG-FINAL-specs-0.1-20230321/](https://www.w3.org/community/reports/reconciliation/CG-FINAL-specs-0.1-20230321/)

[nach oben](#lerneinheit-10---linked-data)
