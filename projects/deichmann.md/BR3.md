# Nieprawidłowy kształt ikony powiększającej grafikę w zakładce Koszyk
 
## Priorytet:
Niski
 
## Środowisko testowe:
macOS Catalina 10.15.3; Google Chrome Wersja 80.0.3987.122
iPhone 7: Oprogramowanie: 13.3.1; Przeglądarka: Safari
 
## Opis:
Ikona w lewym dolnym rogu grafiki artykułu w widoku koszyka ma nieprawidłowy kształt. Po zbadaniu elementu - jego klasa to “enlarge”, bardziej odpowiednią ikoną dla tej klasy jest symbol lupy. Po najechaniu na ikonę “+” kształt kursora ulega zmianie dając błędne przekonanie użytkownikowi że po naciśnięciu ikony wywiąże się akcja, która nie następuje. Najechanie kursorem na ikonę “+” daje ten sam efekt, który jest widoczny po najechaniu na dowolne miejsce grafiki do której jest przypisana. 
 
## Warunki wstępne:
Użytkownik znajduje się na stronie https://www.deichmann.com
W koszyku znajduje się przynajmniej jeden dowolny artykuł.
 
 
## STR:
 
**1.** Kliknij ikonę “koszyk” znajdującą się na górnej belce stronygłównej.
 
**2.** Zwróć uwagę na ikonę “+” w lewym dolnym rogu grafiki artykułu w koszyku.
 
**3.** Najedź kursorem na grafikę artykułu.
 
**4.** Najedź kursorem na ikonę “+” w lewym dolnym rogu artykułu.
 
## Rzeczywisty rezultat:
Ikona “+” daje błędnie przekonanie, że służy do dodawaia większej ilości produktów. W rzeczywistości zwiększa widok grafiki artykułu, ten sam efekt uzyskuje się najeżdżając kursorem na dowolny punkt całej grafiki.
 
## Oczekiwany rezultat:
Ikona służąca powiększaniu zdjęcia ma kształt lupy.
 
## Załączniki:
 
 
[Screen Ikony](https://github.com/KamilaWhite/Projects/blob/master/projects/deichmann.md/screen/Zrzut%20ekranu%202020-05-7%20o%2019.30.02.png)
 
[Screen klasy](https://github.com/KamilaWhite/Projects/blob/master/projects/deichmann.md/screen/Zrzut%20ekranu%202020-05-7%20o%2018.57.21.png)