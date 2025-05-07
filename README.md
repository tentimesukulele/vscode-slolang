# SloLang Support for Visual Studio Code


Zagotavlja podporo za programski jezik **SloLang** (datoteke s končnico `.slo`) v urejevalniku Visual Studio Code. Ta razširitev omogoča obarvanje skladnje, kar olajša branje in pisanje kode v jeziku SloLang, ki temelji na C++ sintaksi s slovenskimi ključnimi besedami.

## Lastnosti

*   **Obarvanje skladnje (Syntax Highlighting):** Natančno obarvanje za ključne besede, komentarje, nize, števila in druge elemente jezika SloLang, kar izboljša berljivost kode.
*   **(Opcijsko, če si implementiral) Osnovno ujemanje oklepajev in samodejno zapiranje.**
*   **(Opcijsko, če si implementiral) Pravila za komentiranje vrstic/blokov.**
*   **(Opcijsko, če nameravaš dodati) Podpora za odrezke (Snippets) za pogoste konstrukcije.**
*   **(Opcijsko, če nameravaš dodati) Integracija z orodji za gradnjo ali linting (v prihodnosti).**


## Predpogoji

Za polno funkcionalnost prevajanja `.slo` datotek boste potrebovali:
1.  Nameščen **SloLang Transpiler** (`slo_transpiler.exe` ali ekvivalent za vaš sistem).
2.  Nameščen **C++ prevajalnik** (npr. g++, Clang, MinGW za Windows).
3.  (Opcijsko) Knjižnico `slo.cpp` in `slo.h`, če jo vaš projekt uporablja.

Ta VS Code razširitev se osredotoča **samo na podporo urejevalnika** (obarvanje skladnje). Za dejansko prevajanje in zagon kode sledite navodilom za vaš SloLang projekt.

## Namestitev

1.  Odpri **VS Code**.
2.  Pojdi na pogled **Razširitve** (Extensions) s klikom na ikono na stranski vrstici ali s `Ctrl+Shift+X`.
3.  V iskalno polje vpiši `[IME TVOJE RAZŠIRITVE, KO BO OBJAVLJENA, npr. "SloLang Support"]`.
4.  Poišči razširitev na seznamu in klikni **Namesti (Install)**.
5.  (Opcijsko, če še nisi objavil) **Ročna namestitev preko VSIX:**
    *   Prenesi `.vsix` datoteko razširitve.
    *   V VS Code, v pogledu Razširitve, klikni na tri pike (`...`) in izberi `Install from VSIX...`.
    *   Izberi preneseno `.vsix` datoteko.

## Uporaba

Ko je razširitev nameščena, bo VS Code samodejno prepoznal datoteke s končnico `.slo` in uporabil obarvanje skladnje za jezik SloLang.

**(Opcijsko, če si dodal svojo temo ikon datotek):**
Če želite videti specifično ikono za `.slo` datoteke, ki jo prinaša ta razširitev:
1.  Pojdite na `Datoteka > Nastavitve > Tema > Tema ikon datotek` (File > Preferences > Theme > File Icon Theme).
2.  Izberite `[Ime tvoje teme ikon, npr. "Slo File Icons"]` s seznama.
    *Opomba: To bo spremenilo vašo trenutno temo ikon datotek.*

## Ključne besede SloLang (Primer)

Tukaj je nekaj primerov ključnih besed, ki jih podpira obarvanje:

*   Tipi: `celo`, `prazno`, `dvojno`, `znak`, `Niz`, `Seznam`
*   Kontrolne strukture: `če`, `sicer`, `za`, `dokler`, `vrni`
*   Razredi in objekti: `razred`, `javno`, `zasebno`, `novo`, `izbriši`
*   Direktive: `vključi`, `uporabi imenskiprostor`
*   Ostalo: `glavna`, `konst`, `stdk`

## Znane težave

*   [Tukaj navedi morebitne znane težave ali omejitve. Npr. "Obarvanje za napredne predprocesorske makroje morda še ni popolno."]
*   Trenutno ni podpore za IntelliSense ali razhroščevanje neposredno preko te razširitve.

## Načrti za prihodnost (Roadmap)

*   [ ] Izboljšano obarvanje za bolj kompleksne scenarije.
*   [ ] Dodajanje osnovnih odrezkov (snippets) za hitrejše pisanje kode.
*   [ ] Raziskovanje možnosti za osnovno linting podporo.
*   [ ] (Morda) Integracija z gradilnim sistemom preko VS Code opravil (Tasks).

## Prispevanje

Prispevki so dobrodošli! Če imate predloge, poročila o napakah ali želite prispevati kodo, prosimo:
1.  Oddajte "issue" (težavo/predlog) na [GitHub repozitoriju projekta]([POVEZAVA_DO_TVOJEGA_GITHUB_REPOZITORIJA]).
2.  Ali pa naredite "fork" repozitorija in oddajte "pull request".

## Viri

*   [Dokumentacija za ustvarjanje VS Code Razširitev](https://code.visualstudio.com/api)
*   [Slovnice za obarvanje skladnje (TextMate)](https://macromates.com/manual/en/language_grammars)

## Licenca

[TUKAJ NAVEDI LICENCO, npr. MIT]

---

Upam, da vam ta razširitev olajša delo z jezikom SloLang! Vesel bom vaših povratnih informacij.
