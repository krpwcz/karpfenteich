# Leitfaden _Diplomarbeits-DB_

## Ausgangslage

(Maximal 400 Zeichen.)

Aus _Leowiki_:

> Die Ausgangssituation. So wie in den Ausgangslagen in SYP/ITP zu schreiben. Keine Beschreibung von wünschenswerten Features, höchstens in der Form von fehlenden Features.

In dieses Feld kommt also die Beschreibung der Ausgangsbasis und Problemsituation, durch die es zu diesem _DA_-Projekt gekommen ist. Wird die Diplomarbeit gemeinsam mit einer Firma geschrieben, kann natürlich auch der (relevante) Aufgabenbereich des Unternehmens/der Abteilung beschrieben werden.

Beispiel:

> Die Firma Leo-Industries verwendet Prüfmaschinen zur automatisierten Begutachtung der produzierten Erzeugnisse. Derzeit ist es noch nicht möglich eine anstehende, notwendige Wartung dieser Maschinen automatisch zu erkennen und die jeweils zuständige Person bzw. Abteilung darüber in Kenntnis zu setzen. Dies wäre jedoch von großem Vorteil, da dadurch Ausfälle - und dadurch sowohl Wartezeiten als auch Kosten - minimiert werden könnten.

## Untersuchungsanliegen der individuellen Themenstellungen

(Maximal 800 Zeichen.)

Aus _Leowiki_:

> Die Untersuchungsanliegen sollen nach KandidatInnen getrennt aufgelistet sein Es sind eben Dinge zu untersuchen, also auch so formulieren; keine Ziele, oder zu erwartende (Teil-)Artefakte

> Beispiele:

> * Evaluieren, welche NN-Architekturen für die Erkennung gewinnversprechender Aktienkurs-Muster möglich sind

> * Prüfen, ob für die Erstellung einer mobilen Audio-Guide-App Ionic sinnvoll verwendet werden kann.

> * Untersuchen, wie ein benutzerfreundliches UI für die Anwendung … aussehen soll

> Das zieht auch eine gewisse Methodik nach sich. Beispielsweise beim UI: Dass nicht nur irgendein UI hingerotzt werden soll, sondern auch mit den potentiellen AnwenderInnen Usability-Tests gemacht werden sollen, etc.

Wie der Name schon sagt, geht es um _Untersuchungs_-Anliegen - somit dienen die Beispielsätze (und -Wörter wie _Prüfen_, _Untersuchen_...) aus dem _Leowiki_ als gute Grundlage.

Mir ist absolut klar, dass nur wenige Themen klar zwischen den Team-Mitgliedern aufgetrennt werden können - wie beispielsweise _UI_ und _Backend_, wo es meist klare Präferenzen und Stärken der Team-Mitglieder gibt. Punkte ohne klare Trennung könnt ihr ja von verschiedenen Blickwinkeln beleuchten, wie mein Beispiel unterhalb zeigt - die jeweils ersten zwei Punkte behandeln das gleiche Thema. Arbeiten würdet ihr (inoffiziell) natürlich gemeinsam dran.

Beispiel:

> Fr. Musterfrau:

> Recherchieren, wie die Messdaten verschiedener Maschinen über die Schnittstelle (Beckhoff ADS) einheitlich und Nutzer-freundlich abgefragt werden können.

> Analysieren, welche Vorverarbeitungsschritte nötig sind, um die Messdaten für einen Machine Learning-Algorithmus nutzbar zu machen.

> Evaluieren, mit welchen Metriken die Leistung eines ML-Modells bestimmt werden kann und wie diese weiter verbessert werden kann.

> Hr. Kowalski:

> Analysieren, welche Messdaten abgefragt und wie diese für das Ablegen in einer Datenbank modelliert werden können.

> Prüfen, welche Machine Learning-Algorithmen für die Vorhersage von Wartungen geeignet sind.

> Eruieren, bei welchen Kriterien und auf welche Weise eine potentiell notwendige Wartung signalisiert werden kann.

## Zielsetzung

(Maximal 400 Zeichen.)

Aus _Leowiki_:

> Das globale Ziel der gesamten Arbeit. Hier darf auch auf den Kunden-Nutzen eingegangen werden. Wenn relevant auch wirtschaftlicher Nutzen der Anwendung

Beispiel:

> Ziel ist ein Softwareprodukt, welches unterstützend Mess- und Produktionsprozesse auf möglicherweise notwendige Wartungen überprüft, und bei Auffälligkeiten zuständige Personen oder Abteilungen benachrichtigt. Durch diese vorbeugende Wartung sollen Ausfälle und somit Wartezeiten und Kosten minimiert werden.

## Geplantes Ergebnis der individuellen Themenstellungen

(Maximal 400 Zeichen.)

Aus _Leowiki_:

> Hier die jeweiligen Ergebnisse der einzelnen KandidatInnen auflisten. Dabei können die Ergebnisse durchaus von den Untersuchungsanliegen abgeleitet werden. Beispielsweise wird aus „Untersuchen, wie ein benutzerfreundliches UI…“ sicherlich das Ergebnis „Ein benutzerfreundliches UI …“ abgeleitet werden können. Dies ist aber nicht zwingend bei jedem Ergebnis der Fall.

> Zusätzlich muss hier noch eine Kostenschätzung (nicht aufgeschlüsselt, sondern nur die Gesamtsumme und die wichtigsten ein bis zwei Kostenpunkte) dokumentiert werden. Wording: Maximale Kosten: xxxxx € für Raspberry Pi 4. Bei keinen zu erwartenden Kosten ist „Keine zu erwartenden Kosten“ zu dokumentieren.

Wie beschrieben, ist das Umformulieren der Untersuchungsanliegen eine billige Strategie - beachtet aber das Zeichenlimit (400 statt 800!). Auch hier gilt der Punkt bzgl. dem Aufteilen von gleichen Themen durch cleveres Formulieren.

Beispiel:

> Fr. Musterfrau:

> Eine GUI über die die Abfrage der Messdaten konfiguriert und durchgeführt werden kann.

> Eine Vorverarbeitungs-Pipeline in Python mit der die Messdaten für das Trainieren eines Modells und die Vorhersage vorbereitet werden.

> Eine ausführliche Evaluierung des trainierten Modells mit sinnvollen Metriken und realistischen Daten.

> Hr. Kowalski:

> Modellierung einer Datenbank zur Speicherung der Messdaten.

> Experimenteller Einsatz verschiedener ML-Algorithmen in einem Jupyter Notebook und abschließende Bereitstellung als Web Service.

> Implementierung eines konfigurierbaren Benachrichtigungs-Systems, das Verantwortliche bzw. Abteilungen über bevorstehende Wartungen informiert.

## Meilensteine

Aus _Leowiki_:

> 1. Die Meilensteine sollen sich auf das Projekt beziehen und nicht auf die Dokumentation (aka schriftliche Arbeit).
> 2. Es sollen mindestens 5 bis 7 Milestones und das jeweils zugehörige Datum angegeben werden.
> 3. Milestones sind in Form einer Aussage formuliert, deren Gültigkeit man überprüfen kann. Bsp: "Die Datenschnittstelle in Richtung Anlagensteuerung ist implementiert und getestet" (gut). "Implementieren der Datenschnittstelle" (schlecht!)
> 4. Die Abgabe der Diplomarbeit zum Abgabetermin ist kein Meilenstein, der in der Datenbank dokumentiert werden darf.
> 5. Die KandidatInnen sollen sich in diesem Punkt schon soweit mit dem Thema auseinandergesetzt haben, dass sie sinnvolle Angaben zum Projekt machen können.

Beachtet hier, dass ein Datum angegeben werden muss, obwohl auf der Plattform _Der Abgabetermin muss nicht angeführt werden._ steht. Ansonsten sollen wie gesagt _nur projektrelevante_ Meilensteine eingetragen werden, _keine_ Angaben zur Diplomarbeit wie z.B. _Kapitel 3 fertig_.

Beispiel:

> 1. Die Messdaten können über die GUI abgefragt und in einer Datenbank gespeichert werden.
> 2. Die Daten wurden vorverarbeitet und ein erstes Modell wurde trainiert.
> 3. Ein Web-Service wurde vorbereitet, mit dem ein Modell für Vorhersagen genutzt werden kann.
> 4. Das Modell wurde umfangreich evaluiert und durch Anpassung der Hyperparameter und Vorverarbeitung optimiert.
> 5. Ein Benachrichtigungs-System wurde implementiert und getestet.

# Individuelle Themenstellungen der Kandidatin/des Kandidaten

Hier müssen die ProjektmitarbeiterInnen eingetragen werden. Bei _Individuelle Themenstellung_ kann man ganz pragmatisch _Siehe "Untersuchungsanliegen der individuellen Themenstellungen"._ hinschreiben. Bei _Arbeitsaufwand_ ist 180 Stunden ein guter Richtwert.

# Mögliche Kooperationspartner/innen bzw. Auftraggeber/innen

Der Punkt ist recht klein und wird leicht übersehen - hier gehören die Daten der Partnerfirma inkl. einer Ansprechpartnerin/eines Ansprechpartners hin.

## Rechtliche Regelung

Ich lasse hier folgenden Standard-Text verwenden - sollte in den meisten Fällen für euch ebenfalls zutreffend sein:

> Es wurde mündlich vereinbart, dass sowohl Code als auch Ergebnisse den ProfessorInnen demonstriert werden dürfen. Sämtliche potentiell firmenkritischen Daten und Bilder werden bei der Einbindung in die Diplomarbeit entsprechend unkenntlich gemacht.

Sollte eure Partnerfirma nach einer _Sperre_ der Diplomarbeit fragen, könnt ihr folgende Informationen aus dem _Leowiki_ kommunizieren:

> Physische Diplomarbeiten (das ausgedruckte Werk) sind bei uns nicht öffentlich zugänglich. Die DA-Betreuer*innen müssen natürlich das Recht haben, die Arbeit zu lesen und auch den Source-Code einzusehen. Im Rahmen der Reife- und Diplomprüfung liegt bei der Präsentation und Diskussion der DA die schriftliche Arbeit (nicht der Source Code) als Tischexemplar auf und kommt anschließend bei uns an der Schule ins Archiv, welches nur über den Abteilungsvorstand oder den Schulleiter zugänglich ist.