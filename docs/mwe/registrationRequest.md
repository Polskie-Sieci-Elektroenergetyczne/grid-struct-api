# Zgłoszenie danych rejestracyjnych MWE

**Nadawca:** OSDp  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych MWE dotyczy przekazywania danych i informacji do OSP o istniejących oraz planowanych
do przyłączenia w 5'o letnim horyzoncie planowania MWE typu D, C i B, a także MWE typu A dla mocy zainstalowanej w
zakresie od 50 - 200 kW.

Struktura komunikatu dzieli zakres informacyjny MWE na grupy danych:

* **istotne terminy** (daty: pierwszego wprowadzenia mocy do sieci, podania napięcia, przekazania do eksploatacji),
* **znaczniki** (typ, rodzaj, autogeneracja, status relacji OS z właścicielem zakładu),
* **dane identyfikacyjnych MWE** (nazwa, kod, właściciel, dane osoby zgłaszającej, Zakład Wytwarzania Energii),
* **identyfikacja miejsca przyłączenia** (szyna lub pole w zależności od napięcia w miejscu przyłączenia, kod PPE_/Na
  miejsce przyłączenia/_) wraz z jego lokalizacją (współrzędne geograficzne)
* **parametry mocowe** (współczynnik netto/brutto dla mocy PminWspółczynnik netto/brutto dla 85% mocy PmaxWspółczynnik
  netto/brutto dla Pmax, technologia Wytwarzania Energii, przypisanie do generatora/agregatu, PPE_/Na kategorię dla MWE
  MIX (min 2 kategorie w tym możliwy magazyn/;_
* **Parametry źródeł energii pierwotnej wchodzących w skład MWE:** (kategoria, moc zainstalowana brutto, źródło
  podstawowe, źródło dodatkowe, moc maksymalna w kier. Generacji, moc minimalna w kier. Generacji, moc osiągalna w kier.
  Generacji, minimum techniczne w kier. Generacji, moc maksymalna w kier. Pompowania, moc minimalna w kier. Pompowania,
  moc osiągalna w kier. Pompowania, minimum techniczne w kier. pompowania)
* **Parametry mocowe Magazynu**(moc zainstalowana rozładowania, rodzaj Magazynu, pojemność znamionowa, sprawność cyklu
  ładowania, sprawność cyklu rozładowania, moc maksymalna rozładowania, moc maksymalna ładowania)
* **Parametry mocowe MWE**: (moc przyłączeniowa, moc maksymalna netto, moc minimalna netto, moc bierna pojemnościowa,
  moc osiągalna brutto, minimum techniczne brutto, moc bierna indukcyjna)

Dodatkowo w przypadku MWE typu D, gdzie rodzaj MWE to moduły synchroniczne zgłoszenie danych rejestracyjnych MWE będzie
zawierało grupę:

* **generatory** (dane identyfikacyjne oraz parametry mocowe).

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych, a wymagane do
rejestracji obiekty t.j. szyna, pole, agregat w przypadku MWE A, B, C muszą istnieć w systemie OSP.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                       |
|---------------------------------------|--------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji MWE przyjęte w systemie OSP i oczekujące na weryfikację._          |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu MWE w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu MWE wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji MWE zwrócone do OSDp do poprawy i oczekujące na korektę._          |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu MWE w systemie OSP.**                                    |
