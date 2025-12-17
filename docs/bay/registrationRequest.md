# Zgłoszenie danych rejestracyjnych Pola z jego wyposażeniem

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Pola wraz z jego wyposażeniem dotyczy przekazywania danych i informacji do OSP o
istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania, a także na potrzeby rejestracji i aktualizacji
istniejących, oraz planowanych do przyłączenia w 5'o letnim horyzoncie planowania MWE typu D, C, B, A, a także MEE o
łącznej mocy zainstalowanej > 50 kW.

Struktura komunikatu dzieli zakres informacyjny Pola z wyposażeniem na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (nazwa, nazwa stacji, nazwa pełna rozdzielni, nr pola, kod, typ, nazwa szyny (1....6) lub mostek (
  1...2), właściciel)
* **wyposażenie pola:**
    * **Wyłączniki** (typ, napięcie znamionowe, prąd znamionowy ciągły, prąd znamionowy wyłączalny dla zwarć na
      zaciskach, prąd znamionowy 1-sekundowy, czas własny wyłącznika)
* **Przekładniki**
    * **prądowy** (typ, napięcie znamionowe, dopuszczalne trwałe przeciążenie strony pierwotnej przekładnika X\*ln,
      prądy znamionowe uzwojeń pierwotnych, prądy znamionowe uzwojeń wtórnych, wskazanie wartości nastawionej prądu
      znamionowego uzwojeń pierwotnych  
      i wtórnych, rdzenie strony wtórnej: nr uzwojenia pierwotnego, nr uzwojenia wtórnego, moc, klasa dokładności
      rdzenia, liczba przetężeniowa)
    * **napięciowy** (typ, napięcie znamionowe pierwotne, dzielnik napięcia znamionowego pierwotnego, napięcie
      znamionowe uzwojenia wtórnego, dzielnik napięcia znamionowego wtórnego, moc uzwojenia wtórnego, dzielnik mocy
      uzwojenia wtórnego, klasa dokładności uzwojenia wtórnego _/Można dodać maksymalnie dziesięć zestawów danych
      uzwojenia wtórnego/_)
    * **kombinowany** (połączenie parametrów przekładników prądowych i napięciowych)
* **Odłączniki** (typ, napięcie znamionowe, prąd znamionowy ciągły, zintegrowany uziemnik, dopuszczalny prąd zwarciowy)
* **Uziemniki** (typ)
* **Odgromniki** (typ)
* **Dławiki w.cz.** (typ, napięcie znamionowe, prąd znamionowy ciągły)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                       |
|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji Pola z wyposażeniem przyjęte w systemie OSP i oczekujące na weryfikację._          |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu Pole z wyposażeniem w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu Pole z wyposażeniem wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji Pola z wyposażeniem zwrócone do OSDp do poprawy i oczekujące na korektę._          |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu Pole z wyposażeniem w systemie OSP.**                                    |
