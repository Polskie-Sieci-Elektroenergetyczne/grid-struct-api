# Zgłoszenie danych rejestracyjnych Baterii kondensatorów

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Baterii kondensatorów dotyczy przekazywania danych i informacji do OSP o istniejących
oraz nowych inwestycjach w 5'o letnim horyzoncie planowania.

Struktura komunikatu dzieli zakres informacyjny Baterii kondensatorów na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (nazwa stacji, nazwa pełna rozdzielni, numer baterii w stacji, nazwa pola, transformator,
  właściciel, moc znamionowa baterii kondensatorów, napięcie znamionowe)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                         |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji Baterii kondensatorów przyjęte w systemie OSP i oczekujące na weryfikację._          |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu Bateria kondensatorów w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu Bateria kondensatorów wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji Baterii kondensatorów zwrócone do OSDp do poprawy i oczekujące na korektę._          |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu Bateria kondensatorów w systemie OSP.**                                    |
