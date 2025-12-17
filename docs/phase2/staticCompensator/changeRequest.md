# Zgłoszenie aktualizacji danych rejestracyjnych Kompensatora statycznego - II Etap B2B

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Kompensatora statycznego dotyczy przekazywania danych i informacji do OSP o
istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania oraz ich planowanym rozwoju.

Struktura komunikatu dzieli zakres informacyjny Kompensatora statycznego na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (kod, nazwa, nazwa stacji, nazwa pełna rozdzielni, nazwa pola, typ, właściciel, moc znamionowa,
  napięcie znamionowe, wartość mocy biernej indukcyjnej, wartość mocy biernej pojemnościowej, pobór mocy czynnej)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                                           |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych rejestracyjnych Kompensatora statycznego przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych rejestracyjnych Kompensatora statycznego w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych rejestracyjnych Kompensatora statycznego wraz z wprowadzonymi zmianami przez pracownika OSP.**           |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych rejestracyjnych Kompensatora statycznego zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych rejestracyjnych Kompensatora statycznego w systemie OSP.**                                          |
