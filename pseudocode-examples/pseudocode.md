## Kasta en tärning tre gånger och räkna ihop det totala värdet

### Version 1

```
START
    Sätt variabel summa till 0
    Kasta tärning och returnera resultat
    Sätt summa till resultat
    Kasta tärning och returnera resultat
    Sätt summa till summa + resultat
    Kasta tärning och returnera resultat
    Sätt summa till summa + resultat
    Skriv ut summa // Visa på skärmen
SLUT
```

### Version 2

```
START
    Sätt variabel summa till 0
    Iterera 3 gånger:
        Kasta tärning och returnera resultat
        Sätt summa till summa + resultat
    Skriv ut summa
SLUT

```

## Fizzbuzz

På 100 tal så:

Om talet är delbart med 3: skriv "Fizz"

Om talet är delbart med 5: skriv "Buzz"

Om talet är delbart med både 3 och 5: skriv "FizzBuzz"

Annars: skriv ut talet

### Exempel

**Exempel output**

```
1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, FizzBuzz, 16, 17, Fizz, 19, Buzz, Fizz, 22, 23, Fizz, Buzz, 26, Fizz, 28, 29, Fizz Buzz, 31, 32, Fizz, 34, Buzz, Fizz, ...
```

```
För tal från 1 till 100:
    Om talet modulo (%) 3 är lika med 0 **och** talet modulo (%) 5 är lika med 0
        Skriv ut FizzBuzz
    Om talet modulo (%) 3 är lika med 0
        Skriv ut Fizz
    Om talet modulo (%) 5 är lika med 0
        Skriv ut Buzz
    Annars
        Skriv ut talet
```
