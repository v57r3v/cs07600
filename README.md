java c
„Numerische Methoden II“
Wintersemester 2023/2024
Aufgabe 0 – Template: Nichtlineare Gleichungen
Der kontinuierliche Rührkesselreaktor (CSTR) wird in vielen chemischen Prozessen eingesetzt da er im stationären Beharrungszustand betrieben werden kann. Der stationäre Beharrungszustand ist durch die Schnittpunkte von Reaktionskurve und Transportgeraden charakterisiert (vgl. CRT1 – Kapitel 7.6.1).
In dieser Aufgabe soll der stationäre Beharrungszustand eines adiabaten Rührkesselreaktors in Abhängigkeit der Temperatur T und des Zulaufvolumenstroms V+ bestimmt werden. Die modifizierte Energiebilanz in dimensionsloser Form. lautet:

mit den Koeffizienten

Hierbei sind
• R = 8,314 J mol-1 K-1 die universelle Gaskonstante
• VR = 1 m3 das Reaktorvolumen
• V + der Zulaufvolumenstrom in m³ s-1
• T die Temperatur in K
• T+ = 298 K die Zulauftemperatur
• k0 = 2.85 s-1 die Reaktionsgeschwindigkeitskonstante
• E = 21059.362 J mol-1 die Aktivierungsenergie
• ρ = 1000 kg m-3 die Dichte
• cp = 4 kJ kg-1 K-1 die spezifische Wärmekapazität
• cA+ = 10 mol m-3 die Zulaufkonzentration
• ∆hR = -119200 kJ mol-1 die Reaktionsenthalpie
Programmieraufgabe
Schreiben Sie ein allgemeines Programm zur Lösung der Energiebilanz, indem Sie zur Lösung der nichtlinearen代 写Numerische Methoden II Wintersemester 2023/2024 Aufgabe 0 – Template: Nichtlineare GleichungenC/C++
代做程序编程语言 Gleichung f(T*) = 0 Newton-Klasse aus der Library
Das Programm soll:
• unabhängig von den Stoffdaten implementiert werden, d.h. die Stoffdaten sollen aus einer Datei eingelesen werden
• den Verlauf von T/T+ über a0 tabellarisch ausgeben
• den Verlauf T/T+ über a0 grafisch darstellen. Für diese Aufgabe können Sie gnuplot verwenden
Auswertung
1.) Testen Sie ihr Programm für einen Zulaufvolumenstrom   V + im Bereich [0.009, 0.011] m³ s-1. Wählen Sie einen sinnvollen Startwert für die Temperatur T/T+.
2.) Variieren Sie den Startwert für die Temperatur T/T+ und untersuchen Sie die Konvergenz der Lösung.
Hinweise
Diese Aufgabe setzt den Wissensstand aus der Vorlesung „Numerische Methoden 1“ voraus. Im Folgenden werden die Mindestvoraussetzungen und die optimale Lösung der Aufgabe erläutert:
Mindestvoraussetzungen:
• Kenntnisse von Numerische Methoden I: Algorithmen zur Lösung linearer Gleichungen und Ausgleichsproblemen, nichtlinearer Gleichungen, Integration (Euler, Runge-Kutta) von gewöhnlichen Differentialgleichungen und Extrapolationsverfahren.
Optimale Lösung dieser Aufgabe:
• Sie lösen die Aufgabe indem Sie ihre Funktionen in die Dateien main.cpp, function.cpp, f_read.cpp und f_out.cpp unterteilen.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
