# Zgłoszenie aktualizacji danych strukturalnych Linii wyprowadzenia mocy - II Etap B2B

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych Linii wyprowadzenia mocy dotyczy przekazywania danych i informacji do OSP
o istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania i ich planowanym rozwoju.

Struktura komunikatu dzieli zakres informacyjny Linii wyprowadzenia mocy na grupy danych:

* **istotne daty*** **dane podstawowe**
* **dane elektryczne**
    * **parametry linii*** **obciążalność linii** (Charakterystyka obciążalności linii elektroenergetycznej w funkcji
      temperatury a w przypadku jej braku, obciążalności termiczne w sezonie zimowym i w sezonie
      letnim, Obciążalności termiczne krótkookresowe (awaryjne) w funkcji temperatury a w przypadku
      jej braku, obciążalności termiczne krótkookresowe w sezonie zimowym i w sezonie letnim oraz
      dopuszczalny czas obciążalności termicznej krótkotrwałej wyrażony w minutach* **parametry
      odcinków:**
* lista odcinków
* parametry odcinków
    * konstrukcja
    * parametry elektryczne
    * obciążalność przewodu roboczego
    * dane przewodu roboczego
    * dane słupa

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                                           |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych  strukturalnych Linii wyprowadzenia mocy przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych strukturalnych Linii wyprowadzenia mocy w systemie OSP.**                                                |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych strukturalnych Linii wyprowadzenia mocy oraz wraz z wprowadzonymi zmianami przez pracownika OSP.**       |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych Linii wyprowadzenia mocy zwrócone do OSDp do poprawy i oczekujące na korektę._  |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych strukturalnych Linii wyprowadzenia mocy w systemie OSP.**                                           |
