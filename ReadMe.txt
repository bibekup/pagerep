﻿ TO DO: 

 - NUM_PROCESSES
 definiert größe der Prozesstabelle, PID muss <= sein Doku updaten! 

 Refactoring: 
 - Alte Typen mit großem Anfangsuchstaben zu kleinem Anfang ändern
 - überflüssige Typen und Funktionen raus (von Sched. und dyn. memory allocation)


 Aufgabe. 
 - Klarstellen, dass prozessverwaltung + Scheduling weggelassen sind. So werden prozesse bei einem Seitenfehler nicht blockiert
 - Page ist ausgelagert, egal pn dirty oder nicht ist nicht optimal, da aber der Inhalt der Seiten nicht mitsimuliert ird, kostet es auch keine Zeit und vereinfsacht die Simulation, does nicht abzuprüfen
