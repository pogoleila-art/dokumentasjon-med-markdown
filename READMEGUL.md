#### Programmeringspråk sammenligning
| språk | styrke | svakhet |
|:-------|:--------:|---------:|
|Javascript|har none|har alt|
|Python|bra nybegynner språk|har noen|

#### Kodeblokk med syntax highlighting
```python
print("1. Add | 2. Subtract | 3. Multiply | 4. Divide")
choice = input("Choose (1/2/3/4): ")

num1 = float(input("First number: "))
num2 = float(input("Second number: "))

if choice == "1":
    print("Result:", num1 + num2)
elif choice == "2":
    print("Result:", num1 - num2)
elif choice == "3":
    print("Result:", num1 * num2)
elif choice == "4":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Cannot divide by zero")
else:
```
#### Sjekkliste
- [x] jobbe med skoleoppgave
- [ ] dra på jobb
- [x] kjøpe flybillet til Oslo
- [ ] overleve

# Oppgave 4 – Mini-README

## Værsjekk

Et lite kommandolinjeprogram som viser gjeldende værmelding for en valgt by.

### Installasjon

1. Klon repoet: `git clone https://github.com/bruker/vaersjekk.git`
2. Gå inn i mappen: `cd vaersjekk`
3. Installer avhengigheter: `npm install`
4. Start programmet: `npm start`

### Funksjoner

- Viser temperatur og værtype for valgt by
- Støtter flere byer samtidig
- Lagrer favorittby lokalt
- Oppdaterer automatisk hver time

#### \*