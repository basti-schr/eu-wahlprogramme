# EU-Wahlprogramme
### Maschinenlesbare Wahlprogramme der Europawahl 2019

Die Wahlprogramme der größten deutschen Parteien zur Europawahl 2019. Zum analysieren und Spaß haben hier in maschienenlesbarer Form als **Markdown**.

Wenn ihr noch Fehler findet oder weitere Wahlprogramme hinzufügen wollt, freuen wir uns über **Pull Requests** und **Issues**!

---

Die PDFs der Wahlprogramme wurden zunächst mit der Website [pdf2md](http://pdf2md.morethan.io/) in ein Textformat gebracht, das manchmal besser und manchmal schwieriger zu verwenden war. 
Mit viel Handarbeit und Suchen und Ersetzen mit RegEx wurde möglichst viel halbautomatisch in eine schöne Form gebracht. 

Mit ```(\w)-\n(\w)```-->```$1$2``` oder ```([a-z,])\n+(\w)```-->```$1 $2``` kann man gleich viele überflüssige Absätze entfernen. 
```\n+(\d.\d\. .+)\n+```-->```\n\n## $1\n``` Kann je nach Format Überschriften in  der zweiten Ebene finden und formatieren.

Linktipp: [https://regexr.com/](https://regexr.com/) Falls dir RegEx Ausdrücke noch nicht so gut liegen.
