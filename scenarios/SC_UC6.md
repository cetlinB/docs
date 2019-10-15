## Scenariusz do przypadku użycia UC6: Create CT

### Scenariusz główny
1. App User wybiera opcję "Create Computation Task" <<*trigger*>>
2. Launcher pobiera z Library listę danych aplikacji App Usera <<*data*>>
3. Launcher wyświetla listę aplikacji <<*screen*>>
4. App User wybiera aplikację w listy <<*trigger*>>
5. Launcher wyświetla widok tworzenia CT <<*screen*>>
6. App User wypełnia dane CT
7. App User wybiera opcję "Create" <<*trigger*>>
8. Launcher akceptuje wprowadzone dane
9. Launcher tworzy i dodaje CT do listy App Usera

### Scenariusz alternatywny I
8. Launcher odrzuca wprowadzone dane
9. Launcher wyświetla komunikat o niepoprawnych danych <<*screen*>>

### Scenariusz alternatywny II
7. App User wybiera opcję "Anuluj" <<*trigger*>>
8. Launcher wyświetla listę aplikacji <<*screen*>>