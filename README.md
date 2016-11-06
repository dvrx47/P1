Pracownia P1 z przedmiotu Systemy Operacyjne 2016/17: Klasyczny problem synchronizacji procesów

Problem palaczy tytoniu:

Rozważmy system z trzema procesami palaczy i jednym procesem lokaja. Każdy z palaczy, działając w nieskończonej pętli, wypala własnoręcznie przygotowane skręty.Aby jednak to zrobić potrzebuje trzech rzeczy: tytoniu, papieru i zapałek. Lokaj posiada nieograniczony zapas każdej z tych rzeczy, jeden z palaczy posiada nieograniczony zapas tytoniu, drugi - papieru, a trzeci - zapałek. Niepalący lokaj wybiera losowo dwa spośród trzech składników i kładzie je na stole. Następnie palacz posiadający brakujący składnik, tworzy skręta i wypala go, po czym lokaj ponownie kładzie na stole dwa losowe składniki i cykl się powtarza.

Zadanie polega na skoordynowaniu procesów palaczy i lokaja. 
