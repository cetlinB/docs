## Scenariusz do przypadku użycia UC9: "Signal own status"

### Scenariusz główny
1. **Computation Resource** sygnalizuje zmianę w obliczeniach. <<*trigger*>>
2. **Computation Occurrance** przechwytuje informację o zmianie w obliczeniach. <<*data*>>
3. **Computation Occurrance** aktualizuje stan obliczeń. <<*data*>>
4. **Computation Occurrance** wysyła stan obliczeń. <<*trigger*>>
5. **Cluster Node** odbiera stan obliczeń. <<*data*>>
6. **Cluster Node** potwierdza odbiór stanu obliczeń. <<*trigger*>>

### Scenariusz aleterantywny I
5. **Cluste Node** nie odbiera stanu obliczeń.
6. **Computation Occurrance** ponawia próbę wysłania stanu obliczeń. <<*trigger*>>

