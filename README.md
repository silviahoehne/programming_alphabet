# Dies ist eine Sammlung von Begriffen der Programmierung

### Niceness (Wert in Prozessen)
Nice ist ein Befehl in Unix- und Linux-Betriebssystemen, der die Anpassung des "Nice"-Wertes von Prozessen ermöglicht. Die Anpassung des "Niceness"-Wertes von Prozessen erlaubt die Einstellung einer empfohlenen CPU-Priorität, die der Scheduler des Kernels verwendet, um zu bestimmen, welche Prozesse mehr oder weniger CPU-Zeit erhalten. Unter Linux kann dieser "Niceness"-Wert vom Scheduler ignoriert werden, andere Unix-Implementierungen können dies jedoch anders behandeln.
Die Möglichkeit, den Niceness-Wert anzupassen, ist in der Regel in zwei Szenarien nützlich.
Das erste ist, wenn Sie einen Prozess haben, der einen Ressourcenkonflikt verursacht oder verursachen könnte; für dieses Szenario würden wir den Niceness-Wert des Prozesses erhöhen.
Das zweite ist, wenn Sie die Ressourcen eines bestimmten Prozesses erhöhen möchten, um die Laufzeit zu verringern oder einem Prozess eine höhere Priorität zu geben. Für dieses Szenario würden wir den Niceness Wert des Prozesses verringern.



### schedule
In der Informatik im Bereich der Betriebssysteme legt Scheduling fest, welche Prozesse wann und wie viel Prozessorzeit erhalten, im Bereich der Datenbanktechnik wird mit dem Scheduling festgelegt, wie parallele Transaktionen ablaufen müssen, ohne die Konsistenz der Datenbank zu verletzen, siehe auch: Scheduler.

## My first fork
author: Silvia Höhne
date: 2021-01-04

