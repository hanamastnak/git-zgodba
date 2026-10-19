# Nadaljnja navodila

1. Sedaj imate lokalno kopijo repozitorija.
2. Poženite skripto, da boste lahko preigrali zgodbo:
   v ukazno vrstico napišete `./hook-install.sh` in stisnite vnašalko.
3. Uredite to datoteko (`navodila.md`) tako, da bo v njej nekje
   zapisan odgovor na življenje, vesolje in sploh vse (tj. `42`).
4. Z `git status` preverite, da ste res spremenili vsebino datoteke.
5. Gitu povejte, da ste spremenili datoteko: `git add navodila.md`.
6. Poglejte, kako se je spremenilo stanje repozitorija: `git status`.
   Zeleno so obarvane datoteke, ki ste jih dodali z `git add`, rdeče pa tiste,
   ki jih še niste. Sedaj napišite `git commit -m "Moj prvi vnos"` in
   s tem spremembo zabeležite kot vnos v repozitorij.
7. Glejte ukazno vrstico za nadaljnja navodila.
   Spremembe zabeležite v ukazni vrstici, ne z gumbom _Commit_ v VSCode, sicer sporočil zgodbe ne boste videli.
   Če se ob ukazu `git commit` ni izpisalo nič drugega kot običajno, ste izpustili 2. korak: poženite skripto in `git commit` ponovite.
   42

<!-- inhibit-stiridva -->
8. Pošljite svoje delo na GitHub z naslednjimi ukazi:
   - `git add navodila.md`
   - `git commit -m "Tik pred shranjevanjem na strežnik"`
   - `git push origin master`
9. Počakajte kakšno minuto, nato si na GitHubu oglejte svojo kopijo repozitorija.
    Ali so se v datoteki `navodila.md` pojavila dodatna navodila?
    Če se tudi po nekaj minutah ne pojavijo, preverite, ali ste v 2. koraku navodil v `README.md` vklopili _Actions_.
