# Notizen zur Arbeit
## Rahmenbedingungen
- 2000 Wörter (Nur Text, lieber zu viel als zu wenig)
- Video, ist für ihn nicht wichtig, nur Beiwerk
- Abweichende Titel zwischen der hochgeladenen Arbeit und dem Titel, der im Online Campus angemeldet wurde, führt automatisch zum Nichtbestehen
- Titel-/Themenänderungen können eigenständig durchgeführt werden, ebenso ist eine wiederholte Ab-/Anmeldung im Rahmen der Fristen möglich.
- Die Ehrenwörtliche Erklärung ist der Arbeit bitte beizufügen. Fehlt diese, erfolgt ein Notenabschlag von 0,3 
- Bei Internetquellen muss das Abrufdatum mit angegeben werden. Bei vereinzelten Verstößen erfolgt ein gesamter Notenabschlag. Sollte das Abrufdatum mehrfach vor der offiziellen Bearbeitungszeit liegen, gilt die Arbeit als nicht bestanden
- Fehlende Quellen im Quellenverzeichnis oder Quellen, die im Quellenverzeichnis angegeben aber im Text nicht verwendet werden, führen zu einem Notenabschlag (ganze Note), bei mehrfachen Verstößen auch zum Nichtbestehen der Arbeit
- Direkte und indirekte Zitate sind kenntlich zu machen, bei mehreren Verstößen gilt die Arbeit als nicht bestanden (in Einzelfällen Notenabschlag von 0,7)
- Als Orientierung sollte der Leitfaden wissenschaftlichen Arbeitens (zu finden im Online Campus) herangezogen werden
- Die Bewertung der Arbeit erfolgt nach wissenschaftlichen Kriterien gemäß FOM Checkliste, im Wesentlichen: Einhaltung der Formalien, Methodik, Inhalt, Problemlösung, Stringenz 
- Anzahl der Quellen ist egal

## Gliederung
1. Einleitung
    1.1 Problemstellung
    1.2 Zielsetzung (Forschungsfrage, Thema Einleiten, Motivation)
    1.3 Aufbau der Arbeit
2. Grundlagen (Grundkonzepte, Begriffserklärungen)
    2.1 Konventionelle Softwareentwicklung
    2.2 Agile Softwareentwicklung
    2.3 Klassische Beziehung Entwicklung und Betrieb
3. Prinzipien und Chancen von DevOps (anderer Name, Literaturrecherche)
    3.1 Organisatorische Konzepte
    3.2 Tooling (CICD usw.)
    3.3 Chancen/Vorteile
    3.4 DevSecOps
4. Fazit (Fazit und Zusammenfassung)
    - Kritik!

## Themenspezifische Notizen
DevOps hat zwei Hauptbereiche: 
- Organisatorisches 
- CICD Tools (S. 277 im Skript)

## [Leitfaden zum Prozess](Leitfaden_Seminararbeiten_Stand_Nov_2020.pdf)


Zum Wörter zählen 450 Wörter abziehen, dann echte Anzahl.


- Definition, Ursprung und Ziel:



DevOps Zusammenfassung:
Halstenberg:
    - In der IT-Welt: Schnellstmögliche Produktivsetzung um schnell Feedback zu bekommen und Produkt-Unsicherheit und Risiken zu minimieren
    -> Erhöht Reaktionszeiten was in VUCA wichtig ist
    - Cloud Computing erlaubt Skalierung und automatisierung von Ressourcen
    - Die einzelnen Elemente des DevOps sind bereits etabliert: Agilität, IT-Service Management, Kanban, Lean, Automatisierung
    Was neu ist, ist die Anwendung dieser Konzepte, um eine Brücke zwischen Entwicklung, Betrieb und Business zu schaffen
    - DevOps streamlined Prozesse um sie komplett dem Kundennutzen unterzuordnen
    - Wie? Gemischte Querschnittsteams aus den drei Bereichen bilden
 - Säulen: Die Säulen von DevOps: CA(L)M(A)S
    - Culture
    - Automation
    - (Lean)
    - Measurement
    - (Added Value)
    - Sharing

 - Mehrwert in einer VUCA-Welt:
    - volatil, unsicher, komplex, mehrdeutig
    - IT muss deswegen schnell auf kurzfristige Änderungen reagieren können
    - Time-to-Market wird durch DO drastisch reduziert
    - Time-to-Value, also zeit bis zum ersten Kundennutzen umso wichtiger
      IT Service ist möglicherweise noch nicht perfekt, der Kunde kann aber bereits
      Vorteile daraus ziehen und man kann auf der anderen Seite bereits Feedback ziehen
      Gut weil Volatilität ausgespielt werden kann, aber auch komplexität (unklare Ursache/Wirkung) durch schnelleres Feedback
    
 - Es müssen drei Grundlegende Wege optimiert werden:
    - Weg von Anforderung eingekippt nach Produktivsetzung (durch Wertstromanalyse)
    - Möglichst kurze Feedbackschleifen Bspw. durch Automatisierte Tests, Visualisierung von Auslastung, Nähe von Entwicklern zum Betrieb
    - Dritter Weg: Lernen aus dem Feedback und Experimentieren um das Team und Prozesse zu stärken

 - Abgrenzung:
    - DevOps ist nicht standardisiert, sondern entwickelt sich ständig weiter
    - Nicht ausschließlich Tools, sondern auch Prozesse
    - Kein neues Vorgehensmodell, geht aber weg von konventionellen und hin zu 
      agilen Modellen
    - Kultur ist ein Teil, nicht alles
    - DevOps kann unabhängig vom Organigramm eingeführt werden (Ablauf, nicht Aufbauorganisation ist wichtig)
 - Grundsätze:
    - Cycle Time verkürzen: Zeit, bis eine initiale Änderung produktiv gesetzt wird
    - Softwareentwicklung ist keine Einbahnstraße, sondern ein Zyklus oder eine 
      Fließfertigung mit wiederkehrenden Arbeitsschritten
 - Aktivitäten:
    - DevOps deckt den gesamten Lebenszyklus ab
      Schritte des Lebenszyklus werden möglichst weitgehend automatisiert und zyklisch durchlaufen
    - plan - code - build- integrate - test - deploy - operate

 - Automatisierung/DevOps Tools
   - Tools für Entwicklung, Versionskontrolle, Configuration Management, Testing,
     Change Management, Incident- Problem Management, Montitoring
   - Nicht ein Tool sondern eine Toolchain aus vielen ergänzenden Tools
   - Open Source erleichtert die Integration der Tools ineinander

 - Organigramm
   - Teamorientierung und schnelles Lernen stehen im Vordergrung
   - Weitgehende Autonomie
   - Vertrauen
   - Teamzugehörigkeit/Loyalität
   - Möglichkeit zur schnellen Face-to-Face Kommunikation
   - Cross-funktionalität
   führt zu:
   - Starkes Commitment, Kreativität, Innovation, Problemlösungskompetenz, Geschwindigkeit
   - Stream Aligned Teams: Teams sollten an einer Wertschöpfungskette ausgerichtet sein
     Bspw. ein Microservice wird durch ein Team im kompletten Lifecycle betreut
   - Enabling Teams: Unterstützen Stream Aligned Teams und sind "technische Berater"
   - Complicated-Subsystem-Team: Team mit Spezialwissen, das ein Stream-Aligned Team überfordern würde (Bsp. Mathematiker, Statistiker)
   - Platform-Teams: Versorgen die SA Teams mit generellen Services und Infrastruktur
     stellen Self Services Bereit 

