## Etapy pracy nad projektem
1) pobranie składowych pojedynczej opinii do niezależnych zmiennych
2) zapisanie wszystkich składowych pojedynczej opinii do obiektu słownika (dictionary)
3) pobranie wszystkich opinii z pojedynczej strony i zapisanie ich do listy słowników
4) pobranie wszystkich opinii o wskazanym produkcie i zapisanie ich do pliku
5) optymalizacja kodu
    1) zdefiniowanie funkcji do ekstrakcji elementów strony HTML
    2) utworzenie słownika selektorów opisującego pojedynczą opinię
    3) zastąpienie ekstrakcji składowych pojedynczej opinii do niezależnych zmiennych ekstrakcją tych składowych w dictionary comprehension w oparciu o słownik selektorów
6) analiza opinii o wskazanym produkcie
    1) wyliczenie podstawowych statystyk
        1) liczba wszystkich opinii o produkcie
        2) liczba opinii z podaną listą zalet
        3) liczba opinii z podaną listą wad
        4) średnia ocena produktu
    2) narysowanie wykresów
        1) udział poszczególncyh rekomendacji w ogólnej liczbie opinii
        2) histogram częstości wystąpień poszczególnych ocen (liczba gwiazdek)
7)Aktualizaja pliku README.md
8)Przeniesienie zawartości pliku README.md na stronę


-------Użyte Biblioteki---------


json - Służy do wymiany danych, odczytu oraz zapisu ich w przejrzysty sposób.
pandas - Służy do analizy dnych. Można je modyfikowa, wczytywać.
bs4 - Służy do iteracji, wyszukiwania i modyfikacji kodu HTML i XML.
flask - Służy do tworzenia aplikacji webowych.
Markdown - Służy do konwersji formatu R.Markdown na inne formaty do HTML i XHTML.
matplotlib - Służy do tworzenia różnych wykresów, bazujących na podanych danych.
flask - Służy do debugowania oraz jest mikro-frameworkiem da Pythona.
requests - Sluży do obsługi HTTP, wysyła żądania i odbiera odpowiedzi.
numpy - Służy do analzy danych, operacji na macierzach.
