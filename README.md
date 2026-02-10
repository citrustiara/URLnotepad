# URL Notepad

Minimalistyczny notatnik, który zapisuje całą treść bezpośrednio w adresie URL. Bez serwera, bez bazy danych – wystarczy skopiować link, żeby zachować notatkę.

## Jak to działa

Tekst wpisany w edytor jest kompresowany za pomocą [LZString](https://github.com/pieroxy/lz-string) i zapisywany w hashu URL. Dzięki temu cały stan notatki jest zawarty w samym linku – można go wysłać komuś lub zapisać jako zakładkę.

## Funkcje

- Automatyczny zapis do URL przy każdej zmianie tekstu
- Kompresja LZString (nawet ~10× mniejszy rozmiar)
- Przyciski do kopiowania URL i tekstu
- Całość działa w przeglądarce (client-side only)

## Technologie

- JavaScript (vanilla)
- LZString – kompresja tekstu
- History API – aktualizacja URL bez przeładowania strony

