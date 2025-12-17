# Zgłoszenie rejestracji Stacji wraz z jej elementami - II etap B2B

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Stacji wraz z jej elementami dotyczy przekazywania danych i informacji do OSP o
istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania.

Struktura komunikatu dzieli zakres informacyjny Stacji i jej elementów na grupy danych:

* **istotne daty** (data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane stacji** (nazwa, typ, kod, właściciel, ODM, OSDp, OSDn, szerokość i długość geograficzna)
* **rozdzielnie**
* **lista rozdzielni** (napięcie, kod, nazwa pełna rozdzielni, budowa)_/Dla każdej z rozdzielni w zgłoszeniu_
* **dane rozdzielni** (nazwa pełna rozdzielni) _/Dla każdej rozdzielni w zgłoszeniu_
    * **dane rozdzielni** (napięcie, kod, krótki opis rozdzielni, nazwa pełna rozdzielni, właściciel, plik ze schematem
      i układem pracy rozdzielni, ODM, OSDp1, OSDp2, OSDn, szerokość i długość geograficzna)
    * **skład rozdzielni***   **szyny _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
    * **pola z wyposażeniem _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
    * **baterie kondensatorów _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
    * **dławiki kompensacyjne _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
    * **filtry _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
    * **sprzęgła _/Zgodnie z zakresem danych rejestracyjnych obiektu_**
* **transformatory _/Zgodnie z zakresem danych rejestracyjnych obiektu_**

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                         |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji Stacji wraz z jej elementami przyjęte w systemie OSP i oczekujące na weryfikację._   |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu Stacja wraz z jej elementami w systemie OSP.**                              |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu Stacja wraz z jej elementami wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji Stacji wraz z jej elementami zwrócone do OSDp do poprawy i oczekujące na korektę._   |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu Stacja wraz z jej elementami w systemie OSP.**                             |
