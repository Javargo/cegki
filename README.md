# cegki

Az occsztest.e-cegjegyzek.hu címen elérhető xml szolgáltatás tesztelése.

1. Töltsd be a [weblapot](https://javargo.github.io/cegki/index.html)
2. Nyomd meg a "Teszt" gombot
3. A szürke keretben megjelennek a szkript futását mutató üzenetek
3. A kívánatos eredmény az, ha a végén szövegesen megjelenik a occsztest.e-cegjegyzek.hu szerver által szolgáltatott XML adatállomány.

Az elvárt eredmény akkor jelenik meg, ha a weboldalt Google Chrome böngészőben a **--user-data-dir="C:\Chrome dev session" --disable-web-security** parancssori kapcsolóval indítjuk el. Ha e kapcsoló nélkül indítjuk a Chrome-ot, akkor nem tölti be az adatállományt. A hibaüzeneteket lásd a böngészőkonzolban. (Ctrl + Shift + I)

