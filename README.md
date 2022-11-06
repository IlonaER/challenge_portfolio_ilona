# TASK 1

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

 1. Mamy możliwość wprowadzenia wieku gracza,który jest nierealny (wiek np.156 ),
 2. Numer telefonu przyjmuje nieprawidłowe wartości ( litery, znaki specjalne, nie ma określonej dlugości ciągu cyfr ani wyboru nr. kierunkowego)
 3. Nierawidłowe wartości dat urodzenia w polu daty urodzenia zawodnika (np. rok 1000 )
 4. W polu imie i nazwisko pole przyjmuje wartości cyfr co także jest błedem.
 5. W polu waga nie ma mamy podanej jednostki wagi, nie wiemy czy wpisujemy kg czy tony, także ilość znaków jakie możemy użyć w tym polu ma za dużo      możliwości.
 6. Pole wzrostu także nie ma jednostki miary w jakiej mamy wpisać podany zwrost zawodnika a pole przyjmuje wszystkie możliwe znaki z klawiatury.
 7. W opcji dodawania akcji podczas meczu możemy zmieniać ilości połów meczu (np.24 połowa meczu) co nie jest prawidłową wartością wg założenia meczu piłki nożnej.
 8. W polu link do FB pole przyjmuje wszelkie dane a powinno być dedykowane dla strony http.
 9. W polu język możemy wpisać dowolny ciąg cyfr lub znaków.
 
 podczas generowania raportów :
 
10. Button SAVE podczas generowania raportu znajduje się w prawym górnym rogu ekranu co nie jest intuicyjne, zazwyczaj szukamy przycisku na dole i w prawym rogu lub poprostu pod spodem wszelkich wprowadzonych danych. 
11. Przycisk cofnij przy meczach nie cofa liczby połów meczu. 
12. Trzykrotne szybkie naciśniecie raportu do pobrania spowodowało bład 404. *e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/events/site 404*

# TASK 2

## Subtask 3
   
   **Przypadki testowe** to kroki, które pozwalają nam zweryfikować czy dana funkcjonalność spełnia określone założenie. Jest to jedne z podstawnych zdań testera. Pisanie przypadków testowych jest po to by dobrze rozplanować to co chcemy przetestować. Nie jest to trudne ale czasem bywa pracochłonne i żmudne. Jednak potrafi pobudzić wyobraźnię. Dobre pokrycie przypadkami testowymi oprogramowania daje nam pewność podczas testów, że nie pominęliśmy żadnej ważnej funkcjonalności. Po zakończeniu testów, na podstawie przypadków testowych możemy budować nasze raporty z wykonanych testów. Dla nowo przyjętych do zespołu ludzi przypadki testowe mogą stać się bardzo dobrym źródłem informacji o niej. 
   
   <!--- Here's my comment --->

<!--- https://www.youtube.com/watch?v=bnXuZiqDCn4 --->

Możemy użyć narzędzi do tego dedykowanych jak Test link czy Azure devops. 

Linki :
Testlink
https://testlink.org/
Azure DevOps
https://www.datadoghq.com
