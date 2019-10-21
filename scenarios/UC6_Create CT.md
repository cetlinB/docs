## Scenariusz do przypadku użycia UC6: Create CT

### Scenariusz główny
1. App User wybiera aplikację z listy w Computation Cockpit <<*trigger*>>
2. Launcher wyświetla szczegóły aplikacji <<*screen*>>
3. App User wybiera opcję "Create CT" <<*trigger*>>
4. Launcher wyświetla formularz tworzenia CT <<*screen*>>
5. App User wypełnia formularz tworzenia CT <<*data*>>
6. App User wybiera opcję "Create" <<*trigger*>>
7. Launcher akceptuje wprowadzone dane <<*validate*>>
8. Launcher tworzy CT <<*action*>>
9. Launcher dodaje CT do listy App Usera <<*action*>>

### Scenariusz alternatywny I
8. Launcher odrzuca wprowadzone dane <<*validate*>>
9. Launcher wyświetla komunikat o niepoprawnych danych <<*screen*>>

### Scenariusz alternatywny II
7. App User wybiera opcję "Anuluj" <<*trigger*>>
8. Launcher wyświetla listę aplikacji <<*screen*>>
