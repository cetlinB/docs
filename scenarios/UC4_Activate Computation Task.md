## Scenariusz do przypadku użycia UC3: Activate CT
SP: App User znajduje się w CC
### Scenariusz główny
1. App User wybiera opcję "Activate Computation Task" <<*trigger*>>
2. Launcher pobiera z Library listę stworzonych CT App Usera <<*data*>>
3. Launcher wyświetla listę stworzonych CT <<*screen*>>
4. App User wybiera aplikację z listy stworzonych CT <<*trigger*>>
5. App User wybiera opcję "Activate" <<*trigger*>>
6. Launcher wyświetla okno potwierdzenia aktywacji obliczeń <<*screen*>>
7. App User potwierdza aktywację obliczeń <<*trigger*>>
8. Launcher zleca aktywację zadania Machine Manager’owi <<*trigger*>>
9. Machine Manager aktywuje działanie zadania <<*trigger*>>
10. Machine Manager zwraca status aktywacji zadania <<*data*>>
 
 
### Scenariusz alternatywny I
7. App User anuluje aktywacje obliczeń <<*trigger*>>
8. Launcher wyświetla okno anulowania aktywacji obliczeń <<*screen*>>
[powrót do CC]
 
 
### Scenariusz alternatywny II
[aktywacja udało się]
11. Launcher wyświetla okno potwierdzenie aktywacji obliczeń <<*screen*>>
[powrót do CC]
 
 
### Scenariusz alternatywny III
[aktywacja nie udała się]
11. Launcher wyświetla komunikat błędu <<*screen*>>
[powrót do CC]