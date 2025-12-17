# Zgłoszenie aktualizacji danych rejestracyjnych Szyny

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych Szyny dotyczy przekazywania danych i informacji do OSP o istniejących oraz
nowych inwestycjach w 5'o letnim horyzoncie planowania, ich planowanym rozwoju, a także na potrzeby rejestracji i
aktualizacji istniejących, oraz planowanych do przyłączenia w 5'o letnim horyzoncie planowania MWE typu D, C, B, A, a
także MEE o łącznej mocy zainstalowanej > 50 kW.

Struktura komunikatu dzieli zakres informacyjny Szyny na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (nazwa stacji, nazwa pełna rozdzielni, nazwa, kod, typ, system, sekcja, właściciel)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                       |
|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych strukturalnych Szyny przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych strukturalnych Szyny w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych  strukturalnych Szyny wraz z wprowadzonymi zmianami przez pracownika OSP.**          |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych Szyny zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych strukturalnych Szyny w systemie OSP.**                                          |
