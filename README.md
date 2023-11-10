# Dzielnice polskich miast w formacie topoJSON gotowe do Power BI
Pliki .json (topoJSON) sformatowane oraz osobiście przetestowane pod kątem użytku w programie Power BI.

### Warunki użytkowania:
Wszystkie te dane są publicznie dostępne a moja praca polegała wyłącznie na dostosowaniu pliku.<br>
Bierz i korzystaj ku chwale ojczyzny :)<br>
Będzie mi miło jeśli oznaczysz źródło, ale nie jest to wymagane.<br>

## Spis treści:
* [Jak używać](#jak-używać)
* [Dzielnice Gdańska](#dzielnice-gdańska-json-gotowe-do-power-bi)
* [Dzielnice Warszawy](#dzielnice-warszawy-json-gotowe-do-power-bi)

# Jak używać?
1. Pobierz wybrany plik.
2. Upewnij się, że Twoje dane zawierają kolumnę z nazwami dzielnic (do pobrania np. z Wikipedii przez Power Query).
3. Utwórz nową wizualizację "shape map" używając danych z tej właśnie kolumny.
4. Pojawi się mapa USA. Nie przejmuj się :)
5. Zaznacz mapę, w panelu "Format" przejdź do "Map settings" i rozwiń listę pod "Map type".
6. Na samym dole listy znajduje się pozycja "Custom map".
7. Po wybraniu tej opcji poniżej pojawi się pole "add a map type" z opcją załadowania pliku.
8. Załaduj plik pobrany na początku.
9. Upewnij się, że nazwy dzielnic są w polu "Location" (czasem automatycznie ładują się jako "Legend").
10. Voila!
11. W panelu "Build visual" pojawi się pole "Color saturation", którego możesz użyć by zróżnicować kolory dzielnic.

<i>Jeżeli jakaś dzielnica nie wyświetla się poprawnie (np. nie pokazuje koloru) sprawdź pisownię nazwy dzielnicy zwracając szczególną uwagę na wszystkie kropki, spacje i myślniki (np. Piecki Migowo vs Piecki-Migowo).<br>
Jeśli masz wątpliwość, jak nazwane są dzielnice w pliku JSON - otwórz go w notatniku i zjedź na sam koniec, tam znajdziesz nazwy dzielnic zakodowane w mapie.</i><br>

# Dzielnice Gdańska JSON gotowe do Power BI
POBIERZ 
Źródło: https://dane.gov.pl/pl/dataset/1821,granice-dzielnic-w-gdansku/resource/22145/table<br>
Data dostępu: 08.11.2023

# Dzielnice Warszawy JSON gotowe do Power BI
POBIERZ
Źródło: https://gis-support.pl/baza-wiedzy-2/dane-do-pobrania/granice-administracyjne/<br>
Data dostępu: 10.11.2023

# Uwagi
Choć zakładam, że zamieszczone dane są poprawne, szczególnie że opieram się na źródłach rządowych, nie odpowiadam za ich zgodność ze stanem rzeczywistym.
