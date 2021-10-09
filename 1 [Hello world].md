|1| Hello world (Funkcija printf()):

```c
#include <stdio.h> \\Ovde ukljucujemo biblioteku "stdio" koja nam daje osnovne funkcije.

int main(){ \\ Ovde pocinjemo funkciju "main" sto je glavna funkcija bilo kog koda.
  printf("Hello world\n"); \\Ovde pozivamo funkciju "printf" sa argumentom od niza brojeva. Ova funkcija nam ispisuje bilo sta na ekran.
  return 0; \\Zanemari ovo za sada bice bitno kasnije...
}
```

Glavni deo svakog koda je funkcija ```main()``` ona ce reci kompajleru gde prvo da gleda. Program moze da ima vise funkcija ali mora da ima funkciju ```main()```!!!

```printf``` je jako bitna funkcija u C i ona ispisuje tekst.

Ako pogledamo u kod
``` printf("Hello world\n"); ```
Primeti ce mo da ima \n, to je escape sequence(komande sekvence na srpskom).
\n ima ulogu da nam prebaci u novu liniju tekst.
\n znaci newline.

