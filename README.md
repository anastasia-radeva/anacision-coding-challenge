anacision Coding Challenge
Bewerbung bei anacision.
 
 
Aufgabe 1: Datenexploration und Vorhersagemodell
 
Wir schicken dir im Nachgang einen Datensatz zu („flights.csv“), der Informationen über Flüge enthält. Bitte:
- führe eine explorative Datenanalyse durch, insbesondere bezüglich der Frage, welche Faktoren/Treiber Verspätungen bei Ankünften (arr_delay) und Abflügen (dep_delay) beeinflussen.
- erstelle ein Vorhersagemodell für die binäre Aussage, ob ein Abflug mehr als 30 Minuten verspätet ist (ohne Nutzung der Verspätung der Ankunft). Nutze dazu einen geeigneten Evaluationsdatensatz.
 
In unserem Termin bitte wir dich, das Vorgehen und die Ergebnisse Deiner deskriptiven Datenanalyse vorzustellen. Bitte keine PowerPoint Folien erstellen, ein jupyter Notebook oder ähnliches reicht aus.
 
 
Aufgabe 2: Software Engineering
 
Bitte schreibe eine robuste, wartbare, und erweiterbare Kommandozeilenanwendung, mit der man CSV Dateien anzeigen kann. Die Anzeige soll im Terminal stattfinden, es ist kein GUI notwendig. In unserem Termin bitte wir dich, das Vorgehen und deine App vorzustellen. Bitte keine PowerPoint Folien erstellen, die Vorstellung des Codes in der IDE genügt.
 
Im Nachgang erhältst du ein Beispiel für eine Datei („Personen.csv“). Nutze sie gerne für die Implementierung und die Vorstellung deiner Umsetzung.
 
Die Logik der Anwendung ist simpel: Sie ruft eine CSV Datei auf, die dann angezeigt werden soll. Bei Aufruf soll die Datei per Argument spezifiziert werden können.
 
Die Anzeige soll folgenden Anforderungen entsprechen:
- Jede Seite wird mit Spaltenüberschriften ausgegeben
- Jede Seite besteht aus 10 Dateneinträgen (Zeilen)
- Es gibt Zellenseparierungzeichen (Genau wie im Beispiel)
- Die Spalten haben eine feste Breite, die dem längsten Eintrag je Spalte entspricht
- Durch Drücken der Tasten F/P/N/L/E werden die im Beispiel gezeigten Befehle ausgeführt (Hierfür kannst du z.B. den input() Befehl benutzen)
 
Die einzelnen Seiten werden als Tabelle mit Überschrift und Zellenmarkierung dargestellt. Du kannst davon ausgegangen, dass die CSV Dateien wie folgt aussehen:
- Die erste Zeile enthält die Überschriften
- Die Spalten sind durch “;“ getrennt, die Kodierung ist utf-8
- Eine neue Zeile ist durch einen Zeilenumbruch codiert, andere Zeilenumbrüche gibt es nicht
 
