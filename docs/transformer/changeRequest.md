# Zgłoszenie aktualizacji danych rejestracyjnych Transformatora

**Nadawca:** OSDp/Odbiorca Końcowy  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych Transformatora dotyczy przekazywania danych i informacji do OSP o
istniejących oraz nowych inwestycjach w 5'o letnim horyzoncie planowania, ich planowanym rozwoju, a także na potrzeby
rejestracji i aktualizacji miejsca odwzorowania generatora.

Struktura komunikatu dzieli zakres informacyjny Transformatora na grupy danych:

* **istotne daty** (daty: data wprowadzenia do eksploatacji, data zakończenia eksploatacji)
* **dane podstawowe** (nazwa stacji, typ, funkcja, ZWE/dla transformatora blokowego/, liczba uzwojeń, nazwa pełna
  rozdzielni1...4, nazwa pola1...4, znacznik rozdzielni z innej stacji, nr w stacji, nazwa, kod, moc znamionowa,
  właściciel)
* **dane uzwojeń** (układ połączeń, prąd jałowy, straty w żelazie, oznaczenie uzwojenia_/Dla każdego uzwojenia/_,
  napięcie znamionowe uzwojenia _/Dla każdego uzwojenia/_, moc znamionowa uzwojenia _/Dla każdego uzwojenia/,_ dla
  każdej pary uzwojeń: napięcie zwarcia - neutralny zaczep, moc odniesienia do napięcia zwarcia, straty w miedzi -
  neutralny zaczep, straty w miedzi - pierwszy zaczep, straty w miedzi - ostatni zaczep, straty w miedzi każdej pary
  uzwojeń transformatora, moc odniesienia do strat w miedzi)
* **dane elektryczne:**
    * **regulacja** (sposób regulacji napięcia, uzwojenie regulowane - regulacja napięcia, napięcie uzwojenia
      regulowanego, liczba zaczepów aktywnych, oznaczenie Producenta na pierwszy, neutralny i ostatni zaczep, zakres
      zmian modułu napięcia _/Między pierwszym a neutralnym i neutralnym a ostatnim/_, napięcia na zaczepach _/Na
      zaczepie neutralnym/_, sposób regulacji kąta, liczba zaczepów aktywnych, oznaczenie Producenta na pierwszy,
      neutralny i ostatni zaczep, zmiana kąta _/Między pierwszym a neutralnym i neutralnym a ostatnim/_)
* **obciążalność** (czy obciążalność transformatora jest równa jego mocy znamionowej, dla obciążalności różnej od mocy
  znamionowej: obciążalność długotrwała i awaryjna dla trzech zakresów temperatur, moc znamionowa w funkcji temperatury,
  dopuszczalny czas obciążenia awaryjnego ∆ta, współczynnik obciążenia przed wystąpieniem zakłócenia ka= S0(T)/Sd(T),
  wartość temperatury, powyżej, której obowiązuje ograniczenia czasowe ∆ta)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                                |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych strukturalnych Transformatora przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych strukturalnych Transformatora w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych strukturalnych Transformatora wraz z wprowadzonymi zmianami przez pracownika OSP.**           |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych Transformatora zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych strukturalnych Transformatora w systemie OSP.**                                          |
