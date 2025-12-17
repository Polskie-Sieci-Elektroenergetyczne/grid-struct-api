# Zgłoszenie danych rejestracyjnych danych MEE

**Nadawca:** OSDp  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych MEE dotyczy przekazywania danych i informacji do OSP o istniejących oraz planowanych
do przyłączenia w 5'o letnim horyzoncie planowania MEE o łącznej mocy zainstalowanej większej niż 50 kW.

Struktura komunikatu dzieli zakres informacyjny MEE na grupy danych:

* **istotne terminy** (daty: data przyłączenia MEE do sieci)
* **identyfikacja miejsca przyłączenia** (szyna lub pole w zależności od napięcia w miejscu przyłączenia, PPE _/Dla
  każdego miejsca przyłączenia/_) wraz z jego lokalizacją (współrzędne geograficzne)
* **dane identyfikacyjnych MEE** (nazwa, kod, właściciel, dane osoby zgłaszającej, Zakład Wytwarzania Energii)
* **parametry mocowe** (moc maksymalna ładowania, moc maksymalna rozładowania, moc minimalna ładowania, moc minimalna
  rozładowania, moc zainstalowana ładowania, moc zainstalowana rozładowania, moc przyłączeniowa ładowania, moc
  przyłączeniowa rozładowania, sprawność cyklu ładowania, sprawność cyklu rozładowania, pojemność znamionowa, pojemność
  użytkowa, technologia magazynowania energii elektrycznej Magazynu, przypisanie do agregatu/generatora)
* **znaczniki** (autogeneracja)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych, a wymagane do
rejestracji obiekty t.j. szyna i agregat w przypadku MEE przyłączonego do sieci o napięciu <110 kV oraz pole w przypadku
MEE przyłączonego do sieci o napięciu >=110 kV muszą istnieć w systemie OSP.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                       |
|---------------------------------------|--------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie rejestracji MEE przyjęte w systemie OSP i oczekujące na weryfikację._          |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego obiektu MEE w systemie OSP.**                                     |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego obiektu MEE wraz z wprowadzonymi zmianami przez pracownika OSP.** |
| _Zgłoszenie w korekcie_               | _Zgłoszenie rejestracji MEE zwrócone do OSDp do poprawy i oczekujące na korektę._          |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego obiektu MEE w systemie OSP.**                                    |

