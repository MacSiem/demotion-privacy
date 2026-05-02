# DeMotion — Polityka prywatności

**Data wejścia w życie:** 2026-05-02
**Deweloper:** Maciej Siemiński (jednoosobowa działalność gospodarcza)
**Kontakt:** maciek.sieminski@gmail.com

DeMotion to aplikacja mobilna, która usuwa komponent wideo z Live Photo (iOS) i Motion Photo (Android) ze zdjęć w bibliotece Twojego urządzenia, edytując je w miejscu. Ten dokument opisuje, jakie dane DeMotion przetwarza, w jaki sposób i dlaczego.

## Krótkie podsumowanie

- **DeMotion nigdy nie wysyła Twoich zdjęć nigdzie.** Całe przetwarzanie odbywa się na Twoim urządzeniu.
- **DeMotion nie zbiera danych osobowych.** Brak kont, brak analityki, brak śledzenia przez nas.
- **DeMotion używa Google AdMob** do wyświetlania reklam w wersji darmowej. AdMob może zbierać identyfikator reklamowy urządzenia oraz dane interakcji z reklamą zgodnie ze swoją polityką.
- **DeMotion używa zakupów w aplikacji Apple App Store / Google Play** do opcjonalnego ulepszenia Premium. Apple/Google obsługują płatność; my otrzymujemy tylko informację o statusie (Premium tak/nie).

## Jakie dane DeMotion ma dostęp na Twoim urządzeniu

| Dane | Po co | Zostaje na urządzeniu | Wychodzi gdziekolwiek |
|---|---|---|---|
| Twoje zdjęcia w bibliotece | Aby znaleźć Live/Motion Photos i usunąć komponent wideo | Tak | Nie |
| Metadane zdjęć (data, lokalizacja, EXIF) | Zachowane bez zmian podczas edycji w miejscu | Tak | Nie |
| Preferencje motywu/języka/Premium | Zapisane w lokalnej pamięci aplikacji | Tak | Nie |
| Identyfikator reklamowy (IDFA na iOS, AAID na Android) | Wysyłany do AdMob, jeśli udzielisz zgody na śledzenie | Nie (wysyłany do AdMob) | Tak — tylko AdMob |
| Paragon zakupu w aplikacji | Weryfikowany lokalnie; status Premium zapisywany | Tak | Nie (Apple/Google obsługują weryfikację serwerową) |

## DeMotion NIE

- nie wysyła, nie kopiuje, nie przesyła Twoich zdjęć na żaden serwer, nigdy;
- nie zbiera Twojego imienia, e-maila, adresu, telefonu, danych biometrycznych, zdrowotnych, finansowych ani kontaktów;
- nie używa raportowania awarii w tej wersji (możemy rozważyć w przyszłej wersji z wyraźnym wcześniejszym powiadomieniem);
- nie używa analityki w tej wersji (możemy rozważyć w przyszłej wersji z wyraźnym wcześniejszym powiadomieniem);
- nie śledzi Cię w innych aplikacjach ani witrynach poza tym, co AdMob robi w celu reklamowym.

## Usługi zewnętrzne

DeMotion używa następujących usług zewnętrznych:

### Google AdMob
- Cel: wyświetlanie banerów i reklam pełnoekranowych w wersji darmowej.
- Dane udostępniane AdMob: identyfikator reklamowy, typ urządzenia, wersja systemu, zdarzenia interakcji z reklamą.
- Polityka prywatności AdMob: https://policies.google.com/privacy
- Rezygnacja: włącz Premium (zakup usuwa reklamy) lub cofnij zgodę na śledzenie w ustawieniach urządzenia (iOS: Ustawienia → Prywatność → Śledzenie; Android: Ustawienia → Prywatność → Reklamy → Resetuj identyfikator reklamowy / Usuń identyfikator reklamowy).

### Apple App Store / Google Play (zakupy w aplikacji)
- Cel: obsługa opcjonalnych zakupów Premium (subskrypcja roczna, dożywotnia, napiwek).
- Dane udostępniane: w całości obsługiwane przez Apple/Google; my otrzymujemy tylko status aktywnego Premium.
- Polityka Apple: https://www.apple.com/legal/privacy/
- Polityka Google: https://policies.google.com/privacy

## Uprawnienia, o które prosi DeMotion

| Uprawnienie | Po co | Wymagane? |
|---|---|---|
| Biblioteka zdjęć (odczyt + zapis) | Główna funkcja: znaleźć Live Photos i edytować je w miejscu. Bez tego aplikacja nie może działać. | Tak |
| App Tracking Transparency (iOS) | Wymagane przez Apple dla spersonalizowanych reklam AdMob. Możesz odmówić; reklamy będą niespersonalizowane. | Nie |
| Zarządzanie mediami (Android 11+) | Opcjonalne. Jeśli zostanie udzielone, Motion Photos mogą być edytowane w batchu bez potwierdzenia per zdjęcie. Jeśli odmówisz, aplikacja zapyta o potwierdzenie przy każdym zdjęciu. | Nie |

## Twoje prawa

- **Możesz przestać używać DeMotion w dowolnym momencie.** Odinstalowanie usuwa wszystkie lokalne dane aplikacji.
- **Możesz zażądać informacji o danych, które przechowujemy.** Ponieważ DeMotion nie zbiera danych osobowych na serwerze, nie mamy żadnych danych użytkownika do dostarczenia. Twoje lokalne dane na urządzeniu należą tylko do Ciebie.
- **Możesz cofnąć dostęp do biblioteki zdjęć** w ustawieniach prywatności urządzenia w dowolnym momencie.
- **Użytkownicy UE (RODO):** Maciej Siemiński jest administratorem danych w odniesieniu do DeMotion. Ponieważ DeMotion przetwarza dane tylko na Twoim urządzeniu, podstawą prawną jest Twoja zgoda (wyraziłeś ją instalując aplikację i udzielając uprawnień). Możesz ją wycofać w każdej chwili odinstalowując aplikację lub cofając uprawnienia.
- **Użytkownicy California (CCPA):** DeMotion nie sprzedaje Twoich danych osobowych, kropka.
- **Dzieci:** DeMotion nie jest skierowany do dzieci poniżej 13 roku życia. Świadomie nie przetwarzamy danych od dzieci poniżej 13 lat.

## Zmiany w polityce

Jeśli zmienimy coś istotnego (np. dodamy analitykę lub raportowanie awarii), nowa polityka zostanie opublikowana pod tym samym URL z nową datą wejścia w życie. Istotne zmiany odnotujemy w informacjach o wydaniu w aplikacji.

## Kontakt

W sprawach prywatności pisz na maciek.sieminski@gmail.com.
