# Zgłoszenie danych rejestracyjnych Kompensatora statycznego - II Etap B2B

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Kompensatora statycznego dotyczy przekazywania danych i informacji do OSP o
istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania.

Struktura komunikatu dzieli zakres informacyjny Kompensatora statycznego na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (kod, nazwa, nazwa stacji, nazwa pełna rozdzielni, nazwa pola, typ, właściciel, moc znamionowa,
  napięcie znamionowe, wartość mocy biernej indukcyjnej, wartość mocy biernej pojemnościowej, pobór mocy czynnej)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                         |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji Kompensatora statycznego przyjęte w systemie OSP i oczekujące na weryfikację._       |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu Kompensator statyczny w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu Kompensator statyczny wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji Kompensatora statycznego zwrócone do OSDp do poprawy i oczekujące na korektę._       |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu Kompensator statyczny w systemie OSP.**                                    |
