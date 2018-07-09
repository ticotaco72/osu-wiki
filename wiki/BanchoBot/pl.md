# BanchoBot

![BanchoBot's player card](BanchoBot.jpg "BanchoBot's player card")

BanchoBot to bot internetowy (czyli zestaw komend i zautomatyzowanych odpowiedzi), który pomaga graczom na czacie poprzez wyświetlanie pewnych informacji zażądanych przez użytkownika oraz ogłaszanie informacji związanych z grą. Zostal zaprogramowany przez [Echo49](/users/431). Jest takze hostem [serwera Bancho IRC](/wiki/Internet_Relay_Chat). Posiada swoj wlasny [profil osu!](/users/3) oraz swoje [konto na twiterze](https://twitter.com/banchoboat)!

## Komendy

*Aby poznac liste komend w kliencie gry, zobacz [Czat](/wiki/Chat_Console)*

Komendy BanchoBota zaczynaja sie od '!' i nastepujacym po wykrzykniku poleceniu. Komendy te dzialaja w grze oraz zewnetrznych klientach IRC. Moga byc one uzyte czacie trybu multiplayer oraz zakladce z rozmowa prywatna z BanchoBotem. Jezeli normalny uzytkownik napisze komende BanchoBota na publicznym kanale, inne osoby nie beda mogly jej zobaczyc, a odpowiedz BanchoBota zostanie wyswietlona w zakladce rozmowy prywatnej z BanchoBotem.

## !help

-   Otwiera zakładkę BanchoBota w okienku czatu. Wyświetli ci listę komend podanych poniżej.
    -   Jeśli masz otwartą zakładkę BanchoBot, jakakolwiek użyta komenda pojawi się w tym okienku niezależnie na którym okienku byłeś gdy wydawałeś komendę (nie wliczając w to moderatorów)
    -   Jeżeli wyślesz komendę bez znaku „!", Banchobot przyjmie to tak samo jakby została użyta z /bb
-   Nie da się użyć komendy bazowanej na znaku "!" w okienkach wiadomości prywatnych innych niż okienko BanchoBota

#### Standardowe komendy (!KOMENDA lub /bb KOMENDA)

| Komenda | Efekt | Przykład | Odpowiedź BanchoBota |
| ------- | ----- | -------- | -------------------- |
| WHERE (nick) | Pokazuje lokalizację danego gracza | !where John | John is in USA |
| STATS (nick) | Pokazuje status danego gracza (bazując na karcie gracza) | !stats John | Stats for John is Idle. Score:00 (#0). Plays:2 (lvl 4). Accuracy:0.00%. |
| FAQ (L.code)(wyraz kluczowy) (list) | Różna użyteczność. [list] Lista komend. | !faq wiki / !faq ru:wiki | The osu! Wiki - Make it awesome! / Примите участие в заполнении вики! |
| REPORT (powód) | Wzywa moderatora | !report Thomas offending comments | Chat moderators has been alerted. Thanks for your help. |
| REQUEST (list) | Pokazuje losowe i najnowsze zapytanie o zmodowanie. [list] Pokazuje 5 losowych i najnowszych zapytań o zmodowanie. | !request | Seether - Fake It by [Dellirium] |
| ROLL (liczba) | Rzuca (wirtualną) kostką i podaje losowy rezultat od 1 do (numer) (domyślnie 100) | !roll 9000 | John rolls 1337 point(s) |
