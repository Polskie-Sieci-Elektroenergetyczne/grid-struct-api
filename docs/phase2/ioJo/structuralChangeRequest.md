# Zgłoszenie aktualizacji danych strukturalnych JO - II etap B2B

**Nadawca:** OSDp  
**Odbiorca:** Operator Systemu Przesyłowego

## Charakterystyka komunikatu:

Zgłoszenie aktualizacji danych strukturalnych Jednostki Odbiorczej dotyczy przekazywania danych i informacji do OSP o
istniejących oraz planowanych do przyłączenia IO/JO w przypadku przystąpienia instalacji odbiorczej (IO) wraz z jej
jednostką/ami odbiorczymi (JO) do procesu kwalifikacji jej zasobów, celem świadczenia usług bilansujących. Dane są
przekazywane przed rozpoczęciem procesu kwalifikacji.

Struktura komunikatu dzieli zakres informacyjny JO na grupy danych:

* **praca w zaniżeniu**
* **praca w przeciążeniu**
* **obciążenie Bazowe (EB) i Rezerwa RR**

* **rezerwa FCR**

* **rezerwa aFRR**

* **rezerwa mFRRd**

Komunikat powinien zawierać wszystkie wymagane parametry w ramach grup danych, które mają być zaktualizowane, a także
mRID aktualizowanego obiektu.

## Status obsługi zgłoszenia:

| Status zgłoszenia                     | Opis                                                                                                    |
|---------------------------------------|---------------------------------------------------------------------------------------------------------|
| _Zgłoszenie przesłane do akceptacji_  | _Zgłoszenie aktualizacji danych strukturalnych JO przyjęte w systemie OSP i oczekujące na weryfikację._ |
| **Zgłoszenie zatwierdzone**           | **Aktualizacja danych strukturalnych JO w systemie OSP.**                                               |
| **Zgłoszenie zatwierdzone ze zmianą** | **Aktualizacja danych strukturalnych JO wraz z wprowadzonymi zmianami przez pracownika OSP.**           |
| _Zgłoszenie w korekcie_               | _Zgłoszenie aktualizacji danych strukturalnych JO zwrócone do OSDp do poprawy i oczekujące na korektę._ |
| **Zgłoszenie odrzucone**              | **Brak aktualizacji danych strukturalnych JO w systemie OSP.**                                          |
