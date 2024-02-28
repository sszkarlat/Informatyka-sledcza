# Informatyka-sledcza

Podczas drugiego semestru na kierunku Cyberbezpieczeństwo na AGH w Krakowie jednym z moich przedmiotów była Informatyka śledcza. Repozytrium to stanowi podsumowanie wszystkich laboratoriów jakie udało mi się wykonać w ramach zajęć z przedmiotu Informatyka śledcza.

## Tematy poszczególnych laboratoriów
- lab 1: Pozyskiwanie informacji z obrazów (tworzenie kopii binarnej nośnika, analiza obrazu)
- lab 2: Narzędzia EwfTools+Rarcrack (analiza metadanych zdjęć (zmiana metadanych), łamanie haseł metodą brute force)
- lab 3: Base64/ASCII (kodowanie/odkodowywanie plików, narzędzie GHex - analiza sygnatur, usuwanie danych - narzędzie dd)
- lab4: Odzyskiwanie plików oraz data carving; analiza rejestrów systemu Windows (tworzenie kopii binarnej nośnika, narzędzia Foremost, Recoverjpeg, Scalpel, Bulk_Extractor służące do odzyskiwania danych usuniętych z nośnika)
- lab 5: Analiza ruchu sieciowego (skanowanie sieci Nmap, anliza ruchu sieciowego TCPdump, Wireshark, analiza malwere)
- lab 6: Analiza pamięci operacyjnej (tworzenie zrzutu pamięci RAM - FTK Imager, tworzenie zrzutu Linux - avml, wykorzystanie Volatility jako narzędzia do analizy pamięci operacyjnej)
- lab 7: Analiza dużego obrazu (sqlite, SQL, analiza iOS, Androida)

## Projekt
Projekt miał na celu wykorzystanie w praktyce poznanych narzędzi znajdujących się w "otwartym kodzie" do potencjalnej analizy śledczej. Analiza systemu Windows przy pomocy narzędzia do analizy śledczej, tj. Autopsy. Analiza ta stanowiła dużą część projektu. Dodatkowo przeprowadzenie analizy polegającej na:
1. Zrzucie pamięci RAM oraz jej analizy (działania w ramach systemu Linux).
2. Wyciągnięciu danych ze smartfona (IOS lub Android) lub pobranie gotowego obrazu
systemu mobilnego do analizy (obraz udostępniony na platformie MS Teams). Analiza
plików (PLIST i SQLite).
3. Wykorzystaniu narzędzia ExifTool do wyciągnięcia metadanych z plików graficznych
oraz przedstawienia metod odzyskiwania straconych danych (Foremost, Scalpel,
RecoverJPEG).
4. Utworzeniu kopii binarnej nośnika (np. DD, DCFLDD, DC3DD, itp.) zawierającego dane
nadające się do analizy oraz pozyskanie informacji o samym obrazie (mmls, fls,
img_stat, ewftools, itp.).
5. Własny pomysł (np. analiza ruchu „NetFlow”, konfiguracji urządzenia sieciowego
lub inną formę analizy omówioną na wykładzie).