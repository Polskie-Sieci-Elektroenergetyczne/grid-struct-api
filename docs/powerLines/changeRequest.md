# Zgłoszenie aktualizacji danych strukturalnych Linii elektroenergetycznej

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych Linii elektroenergetycznej dotyczy przekazywania danych i informacji do
OSP o istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania i ich planowanym rozwoju.

Struktura komunikatu dzieli zakres informacyjny Linii elektroenergetycznej na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (nazwa stacji początkowej, nazwa stacji końcowej, nazwa pełna rozdzielni początkowej, nazwa pełna
  rozdzielni końcowej, nazwa pola początkowego, nazwa pola końcowego, napięcie konstrukcyjne linii Un, numer toru, kod,
  właściciel1, właściciel2)
* **dane elektryczne** (rezystancja R, rezystancja R0, reaktancja X, reaktancja zerowa X0, połowa susceptancji B/2,
  połowa susceptancji zerowej B0/2, reaktancja wzajemna Xw, długość linii, najmniejszy przekrój linii, dopuszczalna
  obciążalność linii w okresie letnim, dopuszczalna obciążalność linii w okresie zimowym, dane na 1 km)
* **obciążalność linii** (Charakterystyka obciążalności linii elektroenergetycznej w funkcji temperatury a w przypadku
  jej braku, obciążalności termiczne w sezonie zimowym i w sezonie letnim, Obciążalności termiczne krótkookresowe (
  awaryjne) w funkcji temperatury a w przypadku jej braku, obciążalności termiczne krótkookresowe w sezonie zimowym i w
  sezonie letnim oraz dopuszczalny czas obciążalności termicznej krótkotrwałej wyrażony w minutach* **parametry
                                                                                                    odcinków:** (numer
                                                                                                    odcinka, rodzaj
                                                                                                    przewodu roboczego,
                                                                                                    długość odcinka, typ
                                                                                                    przewodu
                                                                                                    roboczego/kabla,
                                                                                                    przekrój przewodu,
                                                                                                    znacznik
                                                                                                    przynależności, słup
                                                                                                    początkowy, znacznik
                                                                                                    przynależności, słup
                                                                                                    końcowy, seria
                                                                                                    słupów, typ słupów
                                                                                                    przelotowych, ilość
                                                                                                    słupów przelotowych,
                                                                                                    typ słupów
                                                                                                    odporowych/_Dla typu
                                                                                                    przewodu roboczego
                                                                                                    innego niż Kabel/_,
                                                                                                    ilość słupów
                                                                                                    odporowych/_Dla typu
                                                                                                    przewodu roboczego
                                                                                                    innego niż Kabel/_,
                                                                                                    typ przewodu
                                                                                                    odgromowego1, typ
                                                                                                    przewodu
                                                                                                    odgromowego2, linia
                                                                                                    sprzężona, paszport
                                                                                                    liniii - załącznik)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                                            |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych strukturalnych Linii elektroenergetycznej przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych strukturalnych Linii elektroenergetycznej w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych strukturalnych Linii elektroenergetycznej oraz wraz z wprowadzonymi zmianami przez pracownika OSP.**      |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych Linii elektroenergetycznej zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych strukturalnych Linii elektroenergetycznej w systemie OSP.**                                          |
