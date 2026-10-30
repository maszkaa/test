# Matma po kolei

Polskojęzyczna aplikacja do podstaw logiki, tautologii, kresów zbiorów i przekształceń algebraicznych. Cztery krótkie lekcje, osiem pytań, stopniowe podpowiedzi i interaktywna implikacja. Zakres według opisu użytkowniczki; sylabus UMK nie został zweryfikowany.

## Lokalnie

W katalogu repozytorium uruchom `python3 -m http.server 8000 --bind 127.0.0.1`. Otwórz stronę serwera w przeglądarce. Nie potrzeba instalacji zależności ani kompilacji.

## GitHub Pages

Po przesłaniu plików do gałęzi `main`, wybierz w repozytorium **Settings → Pages → Source → GitHub Actions**. Workflow `.github/workflows/pages.yml` publikuje stronę. Docelowy adres: https://maszkaa.github.io/test/ (dopiero po udanym wdrożeniu).

Postępy są lokalne dla przeglądarki. Eksport i import JSON umożliwia ręczne przeniesienie między urządzeniami. Statystyka opanowania mierzy ukończenie lekcji, nie poziom wiedzy; trafność mierzy pierwsze próby każdego kroku przy każdej powtórce. Aplikacja nie używa AI ani zewnętrznych usług.
