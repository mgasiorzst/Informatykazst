model sieciowy osi iso

moel ten zostal stworzony w celu normalizacji zasad komunikacji w sieci
moel ten został przygotowany z myśla o tworzeniu systemu otwartego ktory nie bedzie nalezal do zandej zamknietej sieci. model ten jest modelem poglądowym (teoretycznym) i zostrał podzielony na 7 warstw 
7. warstwa aplikacji - umozliwia komunikacje z uzytkownikiem (strony WWW, poczta elektroniczna) 
6. warstwa prezentacji - zajmuje sie konwersja danych i definiowaniem formatu; odpowiada rozniez za odpowiednie kodowanie danych (szyfrowanie ) na użądzeniu źródłowym i i ch odkodowanie na użądzeniu docelowym 
5. warstwa sesji - zarządza sesjami uzytkownikow korzystajacych np. z stron WWW lub komunikacji video
4. warstwa transportu - głównym zadaniem jest sprawna obsługa komunikacji pomiedzy urzadzeniami.  w warstwie tej dane dzielone sa na mniejsze czesci(segmentowanie) a natepnie opatrywane sa dodatkowymi informacjami, m.in nadawane sa numery porzadkowe, ktore pozwalaja na przydzielenie po właściwej aplikacji 
3. warstwa sieci - segmenty danych sa wzbogacane o nagłówki sieci zawierajace adres IP źródła i celup. w ten sposob tworzy sie pakiety danych. głównym zadaniem warstwy sieciowej jest wybieraniue najlepszej drogi od nadawcy do odbiorcy dla stworzonych w niej pakietow 
2. warstwa łączna danych - głównym zadaniem jest wykrywanie i korygowanie błędów, na jakie narażona jest komunikacja w sieci. Dodatkowo zajmuje się podziałem wysyłanego pakietu na ramki które posuiadają informacje o arhitektórze w sieci
1. warstwa fizyczna - koduje dane do postaci czystych bitów(zer i jedynek) i przesyła je poprzez medium transmisyjne do odpowiednich urządzeń

enkapsulacja - przechodzenie (przemiana) danych z warstwy wyższej do warstwy niższej 


model sieciowy tcp/id

warstwa aplikacji (warstwa sesji + warstwa prezentacji + warstwa aplikacji w modelu iso)  - zajmuje się reprezentacją danych dla użytkownika oraz ich kodowanie 
-warstwa transportowa - (warstwa transportowa modelu iso) - zapewnia komunikację pomiędzy różnymi urządzeniami w sieci 
-warstwa internetu(sieci w modelu iso) - zapewnia najlepszą trasę dla przepływu pakietu
-warstwa dostępu do sieci(łącza danych i fizyczna z modelu iso) - kontroluje urządzenia fizyczne i media 
