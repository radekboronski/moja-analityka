# moja-analityka

Prywatne narzędzie analityczne do własnego użytku, korzystające z Allegro REST API.

- Właściciel: radekboronski (konto Allegro tego samego użytkownika)
- Cel: analiza publicznych ofert w wybranych kategoriach oraz własnych ofert i zamówień, na potrzeby własnej sprzedaży.
- Ruch: pojedynczy Client ID, tempo ograniczone znacznie poniżej limitu 9000 zapytań na minutę, obsługa odpowiedzi 429 (zatrzymanie i wznowienie z mniejszym tempem).
- Identyfikacja: każde zapytanie zawiera nagłówek User-Agent zgodny z nazwą zarejestrowanej aplikacji (`moja-analityka`).
- Aplikacja nie jest udostępniana innym użytkownikom ani sprzedawcom.
- Kontakt: radek.boronski@gmail.com
