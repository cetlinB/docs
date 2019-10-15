## Scenariusz do przypadku użycia UC3: Abort CT
SP: App User znajduje się w CC
### Scenariusz główny
1. App User wybiera opcję "Abort Computation Task" <<*trigger*>>
2. Launcher pobiera z Library listę CT <<*data*>>
3. Launcher wyświetla listę CT <<*screen*>>
4. App User wybiera aplikację w listy <<*trigger*>>
5. App User wybiera opcję "Abort" <<*trigger*>>
6. Launcher wyświetla okno potwierdzenia przerwania obliczeń <<*screen*>>
7. App User potwierdza przerwanie obliczeń <<*trigger*>>
8. Launcher zleca przerwanie zadania Machine Manager’owi <<*trigger*>>
9. Machine Manager przerywa działanie zadania <<*trigger*>>
10. Machine Manager zwraca status przerwanego zadania <<*data*>>
 
 
### Scenariusz alternatywny I
7. App User anuluje przerwanie obliczeń <<*trigger*>>
8. Launcher wyświetla okno anulowania przerwania obliczeń <<*screen*>>


### Scenariusz alternatywny II
[przerwanie udało się]
11. Launcher usuwa aplikację z listy aplikacji <<*data*>>
12. Launcher wyświetla okno potwierdzenie przerwania obliczeń <<*screen*>>
[powrót do CC]


### Scenariusz alternatywny III
[przerwanie nie udało się]
12. Launcher wyświetla komunikat błędu<<*screen*>>
[powrót do CC]
