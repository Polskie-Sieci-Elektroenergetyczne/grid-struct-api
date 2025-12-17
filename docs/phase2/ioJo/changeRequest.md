# Zgłoszenie aktualizacji danych rejestracyjnych IO/JO - II etap B2B

**Nadawca:** OSDp  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych rejestracyjnych Instalacji Odbiorczej wraz z Jednostkami Odbiorczymi dotyczy
przekazywania danych i informacji do OSP o istniejących oraz planowanych do przyłączenia IO/JO w przypadku przystąpienia
instalacji odbiorczej (IO) wraz z jej jednostką/ami odbiorczymi (JO) do procesu kwalifikacji jej zasobów, celem
świadczenia usług bilansujących. Dane są przekazywane przed rozpoczęciem procesu kwalifikacji.

Struktura komunikatu dzieli zakres informacyjny IO/JO na grupy danych:

* **istotne terminy** (daty: data przyłączenia do systemu, data przekazania zasobu odbiorczego do eksploatacji, data
  zakończenia eksploatacji),
* **dane podstawowe IO**(nazwa, kod, właściciel, dane osoby zgłaszającej)
* **dane podstawowe JO** (nazwa, kod**,** sterowany odbiór)
* **parametry mocowe JO** (moc minimalna, moc maksymalna, moc przyłączeniowa, moc osiągalna, średni współczynnik energii
  brutto/netto)
* **miejsce przyłączenia JO** (szyna lub pole w zależności od napięcia w miejscu przyłączenia, kod PPE_/Dla każdego
  miejsca przyłączenia/_) wraz z jego lokalizacją (współrzędne geograficzne)
* **parametry mocowe IO** (moc przyłączeniowa, moc minimalna, moc maksymalna, moc osiągalna, średni współczynnik energii
  brutto/netto)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                        |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych rejestracyjnych IO/JO przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych rejestracyjnych IO/JO w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych rejestracyjnych IO/JO wraz z wprowadzonymi zmianami przez pracownika OSP.**           |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych rejestracyjnych IO/JO zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych rejestracyjnych IO/JO w systemie OSP.**                                          |
