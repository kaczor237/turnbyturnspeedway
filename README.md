# Turn by Turn Speedway

Turowa gra o żużlu w przeglądarce (telefon i komputer). Jeden plik `index.html`, bez bibliotek, bez serwera, bez zbierania danych.

## Jak się gra
- Mecz ma 15 biegów po 4 okrążenia, za bieg punkty 3-2-1-0. Biegi 14 i 15 są nominowane.
- Jedziesz czerwonym i niebieskim zawodnikiem. Na łuku wybierasz każdemu tor: krawężnik, środek albo bandę. Na prostej: środek albo bandę.
- Ten sam tor co inny zawodnik oznacza walkę o pozycję. Na torze są koleiny i miejsca z lepszą przyczepnością, ale nie widać gdzie.
- Rezerwa taktyczna dostępna, gdy przegrywasz o co najmniej 6 punktów.
- Tor się zużywa i jest równany po biegach 4, 8 i 12.
- Zdarzają się upadki (czerwone światło, powtórka biegu) i defekty (zawodnik zjeżdża na trawę).

## Uruchomienie lokalnie
Otwórz `index.html` w przeglądarce.

## Publikacja na GitHub Pages
1. Utwórz repozytorium i wgraj `index.html` oraz `README.md` do gałęzi `main`.
2. W repozytorium: Settings, Pages, Source: Deploy from a branch, Branch: `main`, folder `/ (root)`.
3. Po chwili gra jest dostępna pod adresem `https://TWOJ-LOGIN.github.io/NAZWA-REPO/`.

## Uwagi
- Zawodnicy i drużyny są fikcyjni. Karta biegów jest uproszczona i nie odpowiada oficjalnemu regulaminowi żadnej ligi.
- Gra nie używa cookies, localStorage, analityki ani zewnętrznych zasobów.
