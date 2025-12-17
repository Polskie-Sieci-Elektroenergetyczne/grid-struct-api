# Wymiana danych strukturalnych

Poniżej przedstawiono specyfikację zakresu i formatu danych strukturalnych wymienianych przez dedykowany system
informatyczny OSP (kanał B2B). Specyfikacja opiera się na dokumencie „Zakres wymienianych danych dla potrzeb planowania
pracy i prowadzenia ruchu KSE” (TCM - zakres wymienianych danych, opracowany na podstawie art. 40 ust. 5 SO GL) oraz na
IRiESP. Dane wymieniane są pomiędzy OSP, OSD i SGU (znaczących użytkowników sieci) w procesach związanych z zarządzaniem
pracą KSE w zakresie niezbędnym do bilansowania mocy KSE. Dane te są przesyłane w postaci komunikatów elektronicznych o
ściśle określonym formacie.

Wymiana danych strukturalnych odbywać się będzie w oparciu o protokół https i standard REST (komunikacja synchroniczna).
Za pomocą zdefiniowanych komunikatów będzie można zgłaszać dane odpowiednio do wymogów zawartych we wskazanych
dokumentach źródłowych. W ramach komunikacji kanałem B2B będzie zapewniona kontrola przesyłanych komunikatów w zakresie
dopuszczalności ich nadsyłania do operatora systemu przesyłowego, poprawności struktury i formatu.

Korzystanie z kanału wymiany danych B2B wymaga od uczestniczących w wymianie informacji z OSP zarejestrowania się jako
partner biznesowy OSP i uzyskania identyfikatora partnera biznesowego.

## Dokumenty źródłowe

Niniejsze standardy w zakresie wymiany danych strukturalnych opierają się na następujących dokumentach po ich ostatnich
zmianach: \* Dokument TCM „Zakres wymienianych danych dla potrzeb planowania pracy i prowadzenia ruchu KSE” (opracowany
na podstawie art. 40 ust. 5 SO GL), opublikowany dnia 22 października 2025 r. \* Instrukcja Ruchu i Eksploatacji Sieci
Przesyłowej (IRiESP) ze zmianami wynikającymi z Karty aktualizacji nr 3/CK-3/2025 do IRiESP, opublikowanej dnia 22
października 2025 r.

Oprócz tego standardy odnoszą się do dokumentów: \* Umowy przesyłania z OSDp, Wytwórcami i Odbiorcami Końcowymi.e

## Ogólne zestawienie przekazywanych danych strukturalnych

### Zakres obiektów

Zakres obiektów, których dotyczy pozyskiwanie danych strukturalnych w związku z wyżej wymienionymi zmianami dokumentów
źródłowych obejmuje zarówno zasoby generacji i poboru, jak i elementy sieci. Są to:

* Moduły Wytwarzania Energii
* _Turbiny Wiatrowe\*_
* _Moduły PV\*_

* _Inwertery\*_

* Magazyny Energii Elektrycznej
* Zakłady Wytwarzania Energii
* Sumy MWE typu A na węzły
* _Instalacje Odbiorcze \*_
* _Jednostki Odbiorcze \*_
* Stacje,
* Rozdzielnie,
* Szyny,
* Pola wraz z wyposażaniem:
* wyłączniki
* przekładniki
* odłączniki
* uziemniki
* odgromniki
* dławiki wysokich częstotliwości
* Transformatory,* Linie elektroenergetyczne
* Linie wyprowadzenia mocy
* Baterie kondensatorów
* Dławiki kompensacyjne
* Sprzęgła
* Filtry
* _Kompensatory statyczne \*_
* _Kompensatory synchroniczne \*_

### Zakres danych strukturalnych

Poniżej przedstawiono zakres danych strukturalnych przekazywanych poprzez kanał B2B.

Dane strukturalne przekazywane są przez OSDp, Odbiorców końcowych oraz poszczególnych Właścicieli wypełniających
obowiązki SOGL w porządku jak przedstawiono w poniższej tabeli. Zastosowano przy tym następujące nazwy i oznaczenia:

* MWE - Moduł Wytwarzania Energii
* ZWE - Zakład Wytwarzania Energii
* MEE - Magazyn Energii Elektrycznej
* JO - Jednostka Odbiorcza
* IO - Instalacja odbiorcza
* Dławik w.cz. - Dławik wysokich częstotliwości
* SGU - Significant Grid User - Znaczący Użytkownik Sieci
* Właściciel - podmiot należący do znaczących użytkowników sieci (SGU), który jest właścicielem obiektu generacji lub
  poboru. Właściciela może również zastępować jednoznacznie określony inny podmiot, który pełni rolę przedstawiciela
  tego SGU.* OK- Odbiorca końcowy - odbiorca dokonujący zakupu energii elektrycznej na własny użytek. Do własnego użytku
  nie zalicza się energii elektrycznej zakupionej w celu jej magazynowania lub zużycia na potrzeby
  wytwarzania, przesyłania lub dystrybucji energii elektrycznej.

| Nadawca do OSP kanałem B2B                              | Obiekt, którego dotyczy wymiana danych strukturalnych                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Rodzaj przekazywanych danych | Rodzaj  pobieranych danych                                                              | Typy dokumentów                                                                                       |
|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| OSDp                                                    | MWE<br><br>_Turbiny Wiatrowe \*_<br><br>_Moduły PV\*_<br><br>_Inwertery\*_<br><br>MEE<br><br>ZWE<br><br>Suma MWE typu A<br><br>_IO\*_<br><br>_JO\*_<br><br>Stacje<br><br>Rozdzielnie<br><br>Szyny<br><br>Pola wraz z wyposażaniem<br><br>*   wyłączniki<br>*   przekładniki<br>*   odłączniki<br>*   uziemniki<br>*   odgromniki<br><br>Dławiki wysokich częstotliwości<br><br>Transformatory<br><br>Linie elektroenergetyczne<br><br>Linie wyprowadzenia mocy<br><br>Baterie kondensatorów<br><br>Dławiki kompensacyjne<br><br>Sprzęgła<br><br>Filtry<br><br>_Kompensatory statyczne\*_<br><br>_Kompensatory synchroniczne\*_ | Dane rejestracyjne           | Status zgłoszenia<br><br>Wartości słownikowe<br><br>Parametry zarejestrowanych obiektów | Zgłoszenie danych rejestracyjnych<br><br>Zgłoszenie rejestracji Sumy MWE A na węzły                   |
| Dane strukturalne                                       | Zgłoszenie aktualizacji danych strukturalnych<br><br>Zgłoszenie aktualizacji danych rejestracyjnych<br><br>Zgłoszenie aktualizacji Sumy MWE A na węzły                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Właściciel zasobu przyłączonego do sieci dystrybucyjnej | MWE<br><br>_Turbiny Wiatrowe\*_<br><br>_Moduły PV\*_<br><br>_Inwertery\*_<br><br>MEE<br><br>_IO\*_<br><br>_JO\*_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Dane strukturalne            | Status zgłoszenia<br><br>Wartości słownikowe<br><br>Parametry zarejestrowanych obiektów | Zgłoszenie aktualizacji danych strukturalnych<br><br>_Zgłoszenie aktualizacji danych rejestracyjnych_ |
| Właściciel zasobu przyłączonego do sieci przesyłowej    | MWE<br><br>_Turbiny wiatrowe\*_<br><br>_Moduły PV\*_<br><br>_Inwertery\*_<br><br>MEE<br><br>_IO\*_<br><br>_JO\*_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Dane strukturalne            | Status zgłoszenia<br><br>Wartości słownikowe<br><br>Parametry zarejestrowanych obiektów | Zgłoszenie aktualizacji danych strukturalnych<br><br>_Zgłoszenie aktualizacji danych rejestracyjnych_ |
| Odbiorca Końcowy                                        | Stacje<br><br>Rozdzielnie<br><br>Szyny<br><br>Pola wraz z wyposażaniem<br><br>*   wyłączniki<br>*   przekładniki<br>*   odłączniki<br>*   uziemniki<br>*   odgromniki<br><br>Dławiki wysokich częstotliwości<br><br>Transformatory<br><br>Linie elektroenergetyczne<br><br>Linie wyprowadzenia mocy<br><br>Baterie kondensatorów<br><br>Dławiki kompensacyjne<br><br>Sprzęgła<br><br>Filtry<br><br>_Kompensatory statyczne \*_<br><br>_Kompensatory synchroniczne \*_                                                                                                                                                          | Dane rejestracyjne           | Status zgłoszenia<br><br>Wartości słownikowe<br><br>Parametry zarejestrowanych obiektów | Zgłoszenie danych rejestracyjnych                                                                     |
| Dane strukturalne                                       | Zgłoszenie aktualizacji danych rejestracyjnych<br><br>Zgłoszenie aktualizacji danych strukturalnych                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

Rozszerzenie zakresu wymiany danych strukturalnych wskazanych obiektów jest planowane po starcie produkcyjnym kanału
B2B (II etap).

## I Etap

[Zgłoszenie danych rejestracyjnych MWE](mwe/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych MWE](mwe/changeRequest.md)

[Zgłoszenie rejestracji Sumy MWE A w podziale na węzły](mweSum/registrationRequest.md)  
[Zgłoszenie aktualizacji Sumy MWE A w podziale na węzły](mweSum/changeRequest.md)

[Zgłoszenie danych rejestracyjnych MEE](mee/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych MEE](mee/changeRequest.md)

[Zgłoszenie danych rejestracyjnych ZWE](zwe/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych ZWE](zwe/changeRequest.md)

[Zgłoszenie danych rejestracyjnych stacji](substation/registrationRequest.md)  
[Zgłoszenie aktualizacji stacji](substation/changeRequest.md)

[Zgłoszenie danych rejestracyjnych rozdzielni](switchgear/registrationRequest.md)  
[Zgłoszenie aktualizacji rozdzielni](switchgear/changeRequest.md)

[Zgłoszenie danych rejestracyjnych szyny](busbar/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych szyny](busbar/changeRequest.md)

[Zgłoszenie danych rejestracyjnych pola](bay/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych pola](bay/changeRequest.md)

[Zgłoszenie danych rejestracyjnych transformatora](transformer/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych transformatora](transformer/changeRequest.md)

[Zgłoszenie danych rejestracyjnych linii elektroenergetycznych](powerLines/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych linii elektroenergetycznych](powerLines/changeRequest.md)

[Zgłoszenie danych rejestracyjnych linii wyprowadzenia mocy](powerOutputLines/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych linii wyprowadzenia mocy](powerOutputLines/changeRequest.md)

[Zgłoszenie danych rejestracyjnych baterii kondensatora](shuntCapacitor/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych baterii kondensatora](shuntCapacitor/changeRequest.md)

[Zgłoszenie danych rejestracyjnych dławika kompensacyjnego](shuntCompensator/registrationRequest.md)  
[Zgłoszenie aktualizacji dławika kompensacyjnego](shuntCompensator/changeRequest.md)

[Zgłoszenie danych rejestracyjnych sprzęgła](coupler/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych sprzęgła](coupler/changeRequest.md)

[Zgłoszenie danych rejestracyjnych filtra](shuntFilter/registrationRequest.md)  
[Zgłoszenie aktualizacji danych strukturalnych filtra](shuntFilter/changeRequest.md)

## II Etap

[Zgłoszenie danych rejestracyjnych turbiny wiatrowej](phase2/windTurbine/registrationRequest.md)
[Zgłoszenie aktualizacji danych rejestracyjnych turbiny wiatrowej](phase2/windTurbine/changeRequest.md)

[Zgłoszenie danych rejestracyjnych modułu PV](phase2/pvModule/registrationRequest.md)
[Zgłoszenie aktualizacji danych rejestracyjnych_modułu PV](phase2/pvModule/changeRequest.md)

[Zgłoszenie danych rejestracyjnych inwertera](phase2/inverter/registrationRequest.md)
[Zgłoszenie aktualizacji_danych rejestracyjnych inwertera](phase2/inverter/changeRequest.md)

[Zgłoszenie danych rejestracyjnych IO i JO](phase2/ioJo/registrationRequest.md)
[Zgłoszenie aktualizacji_danych rejestracyjnych IO i JO](phase2/ioJo/changeRequest.md)

[Zgłoszenie aktualizacji danych strukturalnych JO](phase2/ioJo/structuralChangeRequest.md)

[Zgłoszenie danych rejestracyjnych kompensatora statycznego](phase2/staticCompensator/registrationRequest.md)
[Zgłoszenie aktualizacji_danych rejestracyjnych kompensatora statycznego](phase2/staticCompensator/changeRequest.md)

[Zgłoszenie danych rejestracyjnych kompensatora synchronicznego](phase2/syncCompensator/registrationRequest.md)
[Zgłoszenie aktualizacji_danych rejestracyjnych kompensatora synchronicznego](phase2/syncCompensator/changeRequest.md)

[Zgłoszenie aktualizacji danych strukturalnych transformatora](phase2/transformer/structuralChangeRequest.md)
[Zgłoszenie aktualizacji danych strukturalnych linii elektroenergetycznej](phase2/powerLines/structuralChangeRequest.md)
[Zgłoszenie aktualizacji danych strukturalnych linii wyprowadzenia mocy](phase2/powerOutputLines/structuralChangeRequest.md)
[Zgłoszenie aktualizacji danych strukturalnych dławika](phase2/shuntCompensator/structuralChangeRequest.md)
[Zgłoszenie aktualizacji danych strukturalnych baterii kondensatorów](phase2/shuntCapacitor/structuralChangeRequest.md)
[Zgłoszenie aktualizacji danych strukturalnych filtra](phase2/shuntFilter/structuralChangeRequest.md)

[Zgłoszenie rejestracji stacji wraz z jej elementami](phase2/substation/registrationRequest.md)
[Zgłoszenie aktualizacji stacji wraz z jej elementami](phase2/substation/changeRequest.md)
