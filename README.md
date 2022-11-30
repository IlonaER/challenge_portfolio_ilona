# TASK 1

# Testy Eksploracyjne

## Subtask 1

9 punktów 😊

## Subtask 3 
Cześć! Zdecydowałam sie na udział w challenge portfolio by stworzyć repozytorium i wyróżniać się wśród kandydatów szukajacyh pracy jako tester oprogramowania.

Podjęłam decyzję o udziale w projekcie by zmienić obecną pracę i uwierzyć w siebie. Kieruje mną chęć nauki i rozwoju. Moim celem jest praca jako tester oprogramowania, wiara we własne możliwości oraz nabranie pewności siebie. Oczekuję od projektu interesującej formy nauczania oraz wsparcia mentorskiego. Obiecuję, że gdy w przyszłości uda mi się zdobyć wymarzoną pracę podzielę się z Tobą tą informacją.   :muscle: :fire:

## _Ilona_

## Subtask 4
* Jest to aplikacja dla skautów piłki nożnej. Umożliwia przeglądanie wskaźników, umiejętności i pozycji zawodników. Aplikacja polega na dodawaniu i zarządzaniu graczami, meczami oraz do tworzenia raportów. 
* W aplikacji mamy funkcje dodawania i edycji graczy (imie, nazwisko, pozycja, klub, wojewodztwo, numer telefonu, data urodzenia, wzrost zawodnika). Opcje są bardzo intuicyjne, jednak dobrze gdyby była także opcja dodania zdjęcia profilowego gracza. Wizualnie wyglądałoby to atrakcyjniej dla karty gracza. Mamy rownież opcję filtrowania czyli wyszukiwania graczy poprzez selekcję na podstawie np. wieku czy wzrostu. Aplikacja stwarza również możliwosci generowania raportów oraz relacji z meczów.
* Wygląd interfejsu jest dość prosty i przejrzysty, mimo to nie określa do czego jest ta aplikacja. Przydałby się motyw piłki, boiska i kolorystyki związanej bliżej z tematyką aplikacji. W momencie wybranego klubu, w którym jest gracz ciekawie gdyby tło karty zawodnika przybierało barwy klubu. Ładne jest logo (Fotbal Kolektyw) z liniami papilarnymi co wiąże się z ideą aplikacji czyli tworzeniem ID zawodnika, jednak super gdyby linie papilarnie wprowazić na piłkę. Mielibyśy obraz/logo, po którym od razu widać do czego odnośi się aplikacja.
![obraz](https://user-images.githubusercontent.com/116502803/198896849-d02f7b93-9408-45f3-a6f6-03e812ec0d2d.png)
* Aplikacja jest bardzo intuicyjna jeśli chodzi o opcję dodania gracza. Jesli chodzi o raporty oraz mecze trzeba się chwilę zastanowić jaka opcja odnosi się do czego konkretnie. Można byłoby urpościć opcje na bardziej intuicyjne. 
* Aplikacja działa poprawnie w przeglądarce Chrome, Mozilla, Opera, Microsoft Edge oraz w telefonie Samsung A51, Aipad Air, Samsung Galaxy s8, Iphone XR jednak we wszystkich opcjach po wejsciu w odnośnik do meczów należy mocno przesuwać w lewo ekran w celu zobaczenia jakie opcje kryją się na końcu w opcjach AKCJE. Galaxy Fold pole akcji do meczu nie mieści się w ekranie.

:warning: 
### Zauważyłam błedy :
przy opcji wprowadzania zawodnika do aplikacji : 

![obraz](https://user-images.githubusercontent.com/116502803/201052623-874b0481-1296-48eb-b478-f83e7253948c.png)


 1. Mamy możliwość wprowadzenia wieku gracza,który jest nierealny (wiek np.156 ),
 2. Numer telefonu przyjmuje nieprawidłowe wartości ( litery, znaki specjalne, nie ma określonej dlugości ciągu cyfr ani wyboru nr. kierunkowego)
 3. Nierawidłowe wartości dat urodzenia w polu daty urodzenia zawodnika (np. rok 1000 )
 4. W polu imie i nazwisko pole przyjmuje wartości cyfr co także jest błedem.
 5. W polu waga nie ma mamy podanej jednostki wagi, nie wiemy czy wpisujemy kg czy tony, także ilość znaków jakie możemy użyć w tym polu ma za dużo      możliwości.
 6. Pole wzrostu także nie ma jednostki miary w jakiej mamy wpisać podany zwrost zawodnika a pole przyjmuje wszystkie możliwe znaki z klawiatury.
 7. W opcji dodawania akcji podczas meczu możemy zmieniać ilości połów meczu (np.24 połowa meczu) co nie jest prawidłową wartością wg założenia meczu piłki nożnej.
 8. W polu link do FB pole przyjmuje wszelkie dane a powinno być dedykowane dla strony http.
 9. W polu język możemy wpisać dowolny ciąg cyfr lub znaków.
 10. Nie ma możliwosci skasowania gracza. 
 11. Button " wyczyść" nie powoduje usunięcia wszystkich danych z formularza. 
 
 podczas generowania raportów :
 
10. Button SAVE podczas generowania raportu znajduje się w prawym górnym rogu ekranu co nie jest intuicyjne, zazwyczaj szukamy przycisku na dole i w prawym rogu lub poprostu pod spodem wszelkich wprowadzonych danych. 
11. Przycisk cofnij przy meczach nie cofa liczby połów meczu. 
12. Trzykrotne szybkie naciśniecie raportu do pobrania spowodowało bład 404. *e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/events/site 404*

ogólne :
1. Brak możliwości płatności za dane o graczach, brak zakładki płatności. 
2. Brak numerów raportów.
3. Literówki "ostatnio zaaktualizowany gracz"
4. Bład w słowie "Aktywnosć". 

![obraz](https://user-images.githubusercontent.com/116502803/201538188-7d65fae8-deb3-44a4-b55a-6a64661ec51c.png)



# TASK 2

# Przypadki Testowe

## Subtask 1

:pencil2: [TEST CASES](https://docs.google.com/spreadsheets/d/1SQZNn9DFWDLQHjvpZF3Y-jgVg40fRn8WiL9FYvge3Z0/edit#gid=0)
0

## Subtask 2

✏️[TEST CASES](https://docs.google.com/spreadsheets/d/1zVuimNVxVWDsMral14TWLH-uEDZOKgyXpBZP_CxqrSk/edit#gid=0)

## Subtask 3
:question:
_Po co piszemy przypadki testowe?_ 
   
  :point_right: **Przypadki testowe** to kroki, które pozwalają nam zweryfikować czy dana funkcjonalność spełnia określone założenie. Jest to jedne z podstawnych zdań testera. Pisanie przypadków testowych jest po to by dobrze rozplanować to co chcemy przetestować. Nie jest to trudne ale czasem bywa pracochłonne i żmudne. Jednak potrafi pobudzić wyobraźnię. Dobre pokrycie przypadkami testowymi oprogramowania daje nam pewność podczas testów, że nie pominęliśmy żadnej ważnej funkcjonalności. Po zakończeniu testów, na podstawie przypadków testowych możemy budować nasze raporty z wykonanych testów. Dla nowo przyjętych do zespołu ludzi przypadki testowe mogą stać się bardzo dobrym źródłem informacji o niej. 
  
  
 :point_down: watch the movie :movie_camera:
 
 [![Watch the video](https://user-images.githubusercontent.com/116502803/200179639-1fc0c994-0d5f-4642-bd9b-957e68567906.png)](https://www.youtube.com/watch?v=bnXuZiqDCn4)




Możemy użyć programów dedykowanych do pisania przypadków testowych :  _Test link czy Azure devops_. :computer: 

Linki do pobrania :
1. Testlink
:flashlight: https://testlink.org/
2. Azure DevOps
:flashlight: https://www.datadoghq.com 

## Subtask 4

:pencil2: https://docs.google.com/document/d/1qCHG3Kz0est6oassLm8g_u2Ln6Ugymq7/edit

# TASK 3

# Raportowanie błędów

## Subtask 1-3

_LINK DO FOLDERU Z ZADANIAMI 1-3_

:pencil2: https://drive.google.com/drive/u/0/folders/1v1DXEawc7s8jlVrfs7ysKHICE9BBL8R3

![obraz](https://user-images.githubusercontent.com/116502803/201517766-d56cf3d1-790c-4bba-897b-ae7acdfeffef.png)



# TASK 4 

# Testowanie aplikacji mobilnych

![obraz](https://user-images.githubusercontent.com/116502803/202800529-b76b2cc4-310c-47bd-9b95-1d42acbc2052.png)


## Subtask 1-2
:pencil2: https://docs.google.com/spreadsheets/d/1fdO8D-vW5-ebooiQZmZp25QEW7fAelsv94ogZbqN-P4/edit#gid=0

## Subtask 3

# Do czego służy ta aplikacja?

![obraz](https://user-images.githubusercontent.com/116502803/202800943-88b3f884-821d-4102-9b9d-c2283f13459e.png)


:grey_question: _1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?_ 
 
 Focusly to aplikacja wspierająca rozwój osobisty poprzez nagrania psychoedukacyjne, praktyki uważności i medytacje prowadzone tworzone przez ekspertów – psychologów, terapeutów, trenerów uważności i nauczycieli medytacji.

:grey_question: _2. Kto ma być użytkownikiem końcowym aplikacji?_
 
 Końcowym użytkownikiem aplikacji zostaje osoba chcąca poprawić koncentrację, zadbać o swój mózg, emocje, ukojenie nerwów. 
 
 
:grey_question: _3. Czy według Ciebie aplikacja jest user friendly?_  
 
 Uważam że aplikacja jest przyjazna dla użytkownika i zachęca do medytacji każdego dnia. Przyciski są intuicyjne. 
 
:grey_question:_4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?_

Dodałabym w aplikacji możliwość dodania zdjęcia profilowego , interakcji miedzy kursantem a nauczycielem w postaci komentarzy pod artykułami , dodałabym możliwość prędkości odtwarzania  w playerze

:grey_question:_5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?_

Strona internetowa skupia się na przekazie informacji dla osoby odwiedzającej, proste funkcjonalności, zazwyczaj nie wymaga uwierzytelniania personalnego.
Aplikacja zaprojektowana jest do interakcji z użytkownikiem, posiada złożone mechanizmy i funkcje, zazwyczaj wymaga uwierzytelnienia personalnego.

## Subtask 4 :boom: 

:boom: Zadanie dla chętnych. 
## Testy aplikacji mobilnej i webowej.
:boom: Wykonane z Anna Hałas i Jowita Kałucka.  :boom:
:star: [Jira- test aplikacji SwepTo](https://halas2022.atlassian.net/jira/software/projects/CPP/boards/1?label=WEB%2CMOBILE)

![obraz](https://user-images.githubusercontent.com/116502803/204475920-838daa4f-8f62-4d2d-b823-398c546f8aef.png)

 

# TASK 5

# SQL part 1

## Subtask 1

W tym zadaniu dowiedziałam się czym jest język SQL i jakie są zapytania : SELECT,	FROM,	WHERE,GROUP BY,ORDER BY. 

_SQL to język komputerowy przeznaczony do pracy ze zbiorami faktów i relacjami między nimi._


## Subtask 2 

ZROBIONE!!! :D ✔️
![obraz](https://user-images.githubusercontent.com/116502803/204156654-31ef9e61-989d-4980-91ab-b598444e1865.png)


## Subtask 3

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

![obraz](https://user-images.githubusercontent.com/116502803/204158047-b9c7f1d6-e59f-49a4-bf2a-81dc588cdbae.png)


2. Wyświetl film, który powstał w 2019 roku.
![obraz](https://user-images.githubusercontent.com/116502803/204158058-e78e0cf2-b454-4b27-a78b-88c2a95463f8.png)



3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

![obraz](https://user-images.githubusercontent.com/116502803/204158067-a5cbe0ab-24c6-4089-aa5a-7c4174aefa7e.png)




4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 

![obraz](https://user-images.githubusercontent.com/116502803/204158072-2b3b9592-200c-4302-bde5-cd5195453693.png)



5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

![obraz](https://user-images.githubusercontent.com/116502803/204158083-c7aeffc5-239c-48c0-a7ff-a0d07a8f4552.png)



6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 

![obraz](https://user-images.githubusercontent.com/116502803/204158090-2607be4c-6428-42ca-b4b2-1508bde8cb28.png)


7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 

![obraz](https://user-images.githubusercontent.com/116502803/204158099-f0484c07-2271-437d-9bc1-f18bcda1c45e.png)



8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![obraz](https://user-images.githubusercontent.com/116502803/204158106-6cfa4a4e-776d-4942-9c37-e3371d264157.png)



9. Wyświetl dane klienta, który nie ma podanego adresu email.
![obraz](https://user-images.githubusercontent.com/116502803/204158114-8229b615-6bed-4d30-9735-4133d95a78fb.png)



10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
![obraz](https://user-images.githubusercontent.com/116502803/204158123-f010899e-8e1c-4aef-b2af-5890f92b3655.png)



