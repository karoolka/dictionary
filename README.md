# dictionary

1. Charakterystyka oprogramowania
Nazwa skrócona: Dictionary
Pełna nazwa: Dictionary App with API
Krótki opis: Aplikacja słownika wykorzystująca REST API. Jest w języku angielskim, po wpisaniu słowa w wyszukiwarkę pokazuje nam się pełne wyjaśnienie oraz użycie w zdaniu, antonimy i synonimy danego słowa. Można również odsłuchać poprawną wymowę po kliknięciu w ikonę głośnika.
 
 2. Prawa autorskie
Uznanie Autorstwa 4.0 Międzynarodowe (CC by 4.0) – pozwala na kopiowanie, zmienianie, rozprowadzanie, przedstawianie i wykonywanie utworu jedynie pod warunkiem oznaczenia autorstwa.
Projekt stworzony na podstawie tutoriali:
How to Make a Clean Architecture Dictionary App (WITH CACHING!) - Android Stu...
3. Specyfikacja wymagań
  Id
Nazwa
Opis
Priorytet
1.
Wyszukiwarka słówek
Po wpisaniu konkretnego słowa wyszukanie w zewnętrznym API fragmentu w kodzie
1
2.
Pobieranie danych z API
Użycie danych poprzez zwracany plik Json.
1
3.
Wyświetlanie danych z API
Wyświetlanie odpowiedniego tekstu w odpowiednich miejscach
2
4.
Przycisk głośnika
Po kliknięciu wydobywa się poprawna wymowa słowa po angielsku
3
          1 - wymagane, 2 - przydatne, 3 - opcjonalne
Wymagania funkcjonalne:
● wyświetlanie słowa fonetycznie
● wyświetlanie opisu oraz przykładu użycia w zdaniu danego słowa
● wyświetlanie synonimów
● wyświetlanie antonimów
● wyświetlanie jaka to część mowy
Wymagania niefunkcjonalne:
● kompatybilność z urządzeniami z systemem Android
● prosty i przejrzysty interfejs
● mały rozmiar
● łatwy dostęp

● JAVA
● Android Studio
● Free Dictionary API
4. Architektura oprogramowania
5. Testy
Id
Wymagania
Opis
Wynik
1.
Możliwość wpisania słowa
Po dodaniu buttona oraz odpowiedniego kodu powinna wyskoczyć nam klawiatura i możliwość wpisania zapytania
pozytywny
2.
Poprawna wymowa słówka
Po dodaniu OnClick ze znaczkiem głośnika oraz odpowiedniego kodu będziemy słyszeć poprawną wymowę
pozytywny
3.
Wpisanie innego słówka
Po kliknięciu krzyżyka na buttonie zniknięcie tekstu i pojawienie się pustego pola
pozytywny
