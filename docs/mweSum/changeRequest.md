# Zgłoszenie aktualizacji Sumy MWE A na węzły

**Nadawca:** OSDp  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji Sumy MWE A w podziale na węzły dotyczy przekazywania danych i informacji do OSP o łącznej
zagregowanej mocy zainstalowanej MWE typu A przyłączonych do sieci na obszarze sieci OSDp/OSDn,  
z podziałem na grupy źródeł energii pierwotnej tj.: **Cieplne, Wodne, Wiatrowe, Fotowoltaiczne, Biogaz, Magazyn, Inne**
odpowiadające agregatom przyłączonym do tego samego węzła sieci po dolnej stronie transformatora 110 kV/SN.

Komunikat umożliwia Nadawcy przekazanie informacji dotyczących aktualizacji wielkości Sumy mocy MWE A z podziałem na
grupy mocowe w ramach poszczególnych agregatów odpowiadających w\\w kategoriom we wskazanych przez OSDp stacjach.

* Stacja
    * Uzwojenie po dolnej stronie transformatora 110 kV/SN
        * Cieplne
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW
    * Wodne
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW
    * Wiatrowe
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW
    * Fotowoltaiczne
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW
    * Biogaz
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW
    * Inne
        * dla P<= 10 KW
        * 10 kW< P<=50kW
        * 50 kW <P < 200 kW

Komunikat powinien zawierać te sekcje danych, które mają być zaktualizowane, a także mRID aktualizowanej składowej sumy
MWE A (mRID agregatu).

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                          |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji Sumy MWE A na węzły przyjęte w systemie OSP i oczekujące na weryfikację._            |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja Sumy MWE A w podziale na węzły w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja Sumy MWE A w podziale na węzły wraz z wprowadzonymi zmianami przez pracownika OSP.**           |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji Sumy MWE A w podziale na węzły zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji Sumy MWE A w podziale na węzły w systemie OSP.**                                          |
