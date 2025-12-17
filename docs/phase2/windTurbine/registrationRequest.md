# Zgłoszenie danych rejestracyjnych Typu Turbiny Wiatrowej - II etap B2B

**Nadawca:** OSDp/Wytwórca  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie danych rejestracyjnych Typu Turbiny Wiatrowej dotyczy przekazywania danych i informacji o tych obiektach do
OSP na potrzeby aktualizacji istniejących oraz planowanych do przyłączenia w 5'o letnim horyzoncie planowania MWE typu
D, C i B w kategorii Wiatrowe.

Struktura komunikatu dzieli zakres informacyjny Typu Turbiny Wiatrowej na grupy danych:

* **dane podstawowe** (model, producent, moc znamionowa turbiny, moc pozorna turbiny, napięcie generatora, nazwa typu
  turbiny, krytyczna prędkość wiatru, powyżej której turbina jest wyłączana ze względów bezpieczeństwa)* **dane
  transformatora
  turbiny** (moc
  znamionowa,
  napięcie górne
  SN, napięcie
  dolne nn,
  napięcie
  zwarcia, straty
  w miedzi,
  straty w
  żelazie, prąd
  jałowy, liczba
  zaczepów,
  zakres
  regulacji ΔU,
  skok na zaczep)
* **charakterystyka mocy czynnej w funkcji prędkości wiatru** (moc P, Qpoj, Qind dla prędkości wiatru w zakresie od 0 do
  40 m/s)

Komunikat powinien zawierać wszystkie wymagane parametry w ramach wyszczególnionych grup danych wymagane do rejestracji
obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                            |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie danych rejestracyjnych Typu Turbiny Wiatrowej przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Zarejestrowanie nowego Typu Turbiny Wiatrowej w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Zarejestrowanie nowego Typu Turbiny Wiatrowej  wraz z wprowadzonymi zmianami przez pracownika OSP.**          |
| _Zgłoszenie w korekcie_               | _Zgłoszenie danych rejestracyjnych Typu Turbiny Wiatrowej zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak rejestracji nowego Typu Turbiny Wiatrowej w systemie OSP.**                                              |
