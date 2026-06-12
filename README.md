# Ankieta badawcza (wersja HTML)

Ankieta badawcza dotycząca procesów decyzyjnych, działająca w całości w przeglądarce
jako **pojedynczy plik `ankieta.html`** — bez instalacji, bez serwera, bez połączenia z internetem.
Cała logika (JavaScript) jest wbudowana w plik HTML.

## Czym jest ten program

Interaktywny kwestionariusz prowadzący uczestnika przez 7 kroków:

1. Informacja o badaniu i zgoda,
2. Metryczka (dane demograficzne),
3. Kwestionariusz (21 stwierdzeń, skala 1–7),
4. Test (8 zadań),
5. Scenariusze decyzyjne — **9 zadań losowanych przy każdej sesji** w układzie 3/3/3
   (mało / średnia ilość / dużo informacji),
6. 2 zadania z możliwością dopytania o dodatkowe informacje,
7. Zakończenie i eksport wyników.

Odpowiedzi można wyeksportować do **CSV** oraz **XLSX** (czytelna tabela z pogrubionymi
nagłówkami kolumn, gotowa do analizy).

## Jak uruchomić

### Komputer (Windows / Mac / Linux)
1. Pobierz plik `ankieta.html`.
2. Kliknij go dwukrotnie — otworzy się w domyślnej przeglądarce.
3. Przejdź badanie i na końcu pobierz wyniki (CSV lub XLSX).

### Telefon / tablet (Android, iOS)
- Wyślij sobie plik `ankieta.html` (np. mailem) i otwórz go w przeglądarce (zalecany Chrome).
- Alternatywnie umieść plik na dowolnym hostingu statycznym i udostępnij **link** —
  otwiera się jednym kliknięciem, bez instalacji.

> Uwaga: niektóre komunikatory (Messenger, WhatsApp) blokują pliki `.html`.
> W takim przypadku udostępnij ankietę przez **link**, a nie jako załącznik.

## Rozpoczynanie nowego testu

Postęp jest zapisywany w pamięci przeglądarki (`localStorage`), więc po ponownym otwarciu
pliku badanie wznawia się od ostatniego etapu. Aby zacząć od nowa, użyj przycisku
**„Rozpocznij test od nowa"** widocznego w nagłówku na każdym ekranie
(lub otwórz plik w trybie incognito — ma własną, pustą pamięć).

## Wymagania

Dowolna współczesna przeglądarka (Chrome, Edge, Firefox, Safari). Brak innych zależności.
