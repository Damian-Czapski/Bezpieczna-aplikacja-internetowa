# Bezpieczna-aplikacja-internetowa
Bezpieczna aplikacja z wykorzystaniem Apache2 - w trakcie realizacji.
Celem projektu jest napisanie prostej aplikacji internetowej spełniającej wysokie standardy bezpieczeństwa.
Wymagania:
Napisz aplikację WWW realizującą uwierzytelnianie w oparciu o tajne hasło. Zwróć uwagę na:
- (niezbędne) restrykcyjna weryfikacje danych pochodzących z formularza login-hasło,
- (niezbędne) przechowywanie hasła chronione funkcją hash i solą,
- (niezbędne) możliwość przesłania na serwer pliku o dowolnym rozszerzeniu,
- (niezbędne) możliwość przesłania na serwer fragmentu kodu i wyświetlenie go,
- (niezbędne) zabezpieczenie transmisji poprzez wykorzystanie protokołu https.
- dodatkowa kontrola spójności sesji (przeciw atakom XSRF),
- wielokrotne wykorzystanie funkcji hash, żeby wydłużyć ataki brute-force na hash,
- weryfikacja liczby nieudanych prób logowania,
- dodanie opóźnienia przy weryfikacji hasła w celu wydłużenia ataków zdalnych,
- sprawdzanie jakości hasła (jego entropii),
- możliwość odzyskania dostępu w przypadku utraty hasła,
- dodaj użytkownikowi możliwość zmiany hasła,
- informowanie użytkownika o nowych podłączeniach do jego konta.
