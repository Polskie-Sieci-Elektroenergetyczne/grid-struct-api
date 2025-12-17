# Zgłoszenie aktualizacji danych strukturalnych MEE

**Nadawca:** OSDp/Wytwórca  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych MEE dotyczy przekazywania danych i informacji do OSP o istniejących oraz
planowanych do przyłączenia w 5'o letnim horyzoncie planowania MEE o łącznej mocy zainstalowanej większej niż 50 kW.

Struktura komunikatu dzieli zakres informacyjny aktualizowanego MEE na grupy danych:

* Istotne terminy
* Identyfikacja miejsca przyłączenia
* Dane identyfikacyjne MEE
* Parametry mocowe
* Znaczniki
* Obciążenie Bazowe (EB) i Rezerwa RR
* Generacja
* Pobór
* Rezerwa FCR
    * Generacja
* Pobór* Rezerwa aFRR
* Generacja
* Pobór* Rezerwa mFRRd
* Generacja
* Pobór* Regulacja napięcia i mocy biernej
* Tryby regulacji
* Charakterystyka Q=f(U)
* Charakterystyka P=f(U)
* Charakterystyka Q=f(P)* Charakterystyka statyczna U=f(Q/P)
* LFSM
* Generacja
* Pobór
* Parametry ruchowe
* Redukcja mocy czynnej
* Zdalne sterowanie Q U cos φ
* Układy regulacji
* Redysponowanie* Obrona i odbudowa
* Postój
* Rozruch autonomiczny
* Praca w układach wyspowych
* Warunki uruchomienia
* Charakterystyki zwarciowe i napięciowe
* LVFRT
* HVFRT
* I=f(U)
* Zabezpieczenia U
* Podnapięciowe miejsca przyłączenia * Nadnapięciowe miejsca przyłączenia
* Podnapięciowe MEE * Nadnapięciowe MEE* Zabezpieczenia f
* Podczęstotliwościowe miejsca przyłączenia
* Nadczęstotliwościowe miejsca przyłączenia
* Podczęstotliwościowe MEE
* NadczęstotliwościoweMEE
* df/dt* Dane telemetryczne _/Dla MEE, które nie są modelowane indywidualnie/_
* Schemat wyprowadzenia mocy
* _Parametry modeli matematycznych (?)_

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                                 |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych strukturalnych MEE przyjęte w systemie OSP i oczekujące na weryfikację._             |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych rejestracyjnych i/lub strukturalnych MEE w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych rejestracyjnych i/lub strukturalnych MEE wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych MEE zwrócone do OSDp do poprawy i oczekujące na korektę._             |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych rejestracyjnych i/lub strukturalnych MEE w systemie OSP.**                                |
