### Pole “ Data urodzenia” w rejestracji jest opcjonalna, decydując się na jej podanie klient musi mieć 18 lat#

**Priorytet:** Wysoki

**Środowisko testowe:** macOS Catalina 10.15.3; Google Chrome Wersja 80.0.3987.122

**Opis:** Podczas tworzenia konta nowego użytkownika w formularzy rejestracyjnym, pole “Data urodzenia” nie jest obowiązkowe do wprowadzenia. Decydując  się na jej podanie, rejestracja konta kończy się niepowodzeniem w przypadku wprowadzenia do pola “data urodzenia” rok 2003 i każdy kolejny w górę. Oznacza to że w przypadku wpisania Daty urodzenia osoba rejestrująca się musi mieć 18 lat. W regulaminie sklepu nie ma adnotacji do wieku osoby zakładającej konto. Jeśli taka adnotacja została przypadkowo pominięta w regulaminie to pole “Data urodzenia” podczas rejestracji nie może być opcjonalna.

**Warunki wstępne:** 
Użytkownik znajduje się na stronie https://www.deichmann.com/PL/pl/shop/welcome.html

**STR:**
**1.** W górnej belce strony kliknij “Moje konto”.
**2.** Wypełnij pola wymagane w formularzu “Jestem nowym klientem”.
**3.** W polu “Data urodzenia” wprowadź 01-01-2003. 
**4.** Zaznacz checkbox regulaminu sklepu.
**5.** Kliknij “Zarejestruj teraz”.

**Rzeczywisty rezultat:** Konto użytkownika nie zostaje utworzone, w formularzu pole “Data urodzenia” podświetla się na czerwono z informacją “Sprawdź datę urodzenia”.

**Oczekiwany rezultat:** W przypadku opcjonalnej daty urodzenia aplikacja nie powinna blokować rejestracji użytkownika. Jeśli tylko osoby pełnoletnie mogą być klientami sklepu pole “Data urodzenia” musi być wymagana.

**Załączniki:**
[screen błędu]()
[screen regulaminu]()
