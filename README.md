# TASK 1

# Testy Eksploracyjne

## Subtask 1

9 punkt贸w 馃槉

## Subtask 3 
Cze艣膰! Zdecydowa艂am sie na udzia艂 w challenge portfolio by stworzy膰 repozytorium i wyr贸偶nia膰 si臋 w艣r贸d kandydat贸w szukajacyh pracy jako tester oprogramowania.

Podj臋艂am decyzj臋 o udziale w projekcie by zmieni膰 obecn膮 prac臋 i uwierzy膰 w siebie. Kieruje mn膮 ch臋膰 nauki i rozwoju. Moim celem jest praca jako tester oprogramowania, wiara we w艂asne mo偶liwo艣ci oraz nabranie pewno艣ci siebie. Oczekuj臋 od projektu interesuj膮cej formy nauczania oraz wsparcia mentorskiego. Obiecuj臋, 偶e gdy w przysz艂o艣ci uda mi si臋 zdoby膰 wymarzon膮 prac臋 podziel臋 si臋 z Tob膮 t膮 informacj膮.   :muscle: :fire:

## _Ilona_

## Subtask 4
* Jest to aplikacja dla skaut贸w pi艂ki no偶nej. Umo偶liwia przegl膮danie wska藕nik贸w, umiej臋tno艣ci i pozycji zawodnik贸w. Aplikacja polega na dodawaniu i zarz膮dzaniu graczami, meczami oraz do tworzenia raport贸w. 
* W aplikacji mamy funkcje dodawania i edycji graczy (imie, nazwisko, pozycja, klub, wojewodztwo, numer telefonu, data urodzenia, wzrost zawodnika). Opcje s膮 bardzo intuicyjne, jednak dobrze gdyby by艂a tak偶e opcja dodania zdj臋cia profilowego gracza. Wizualnie wygl膮da艂oby to atrakcyjniej dla karty gracza. Mamy rownie偶 opcj臋 filtrowania czyli wyszukiwania graczy poprzez selekcj臋 na podstawie np. wieku czy wzrostu. Aplikacja stwarza r贸wnie偶 mo偶liwosci generowania raport贸w oraz relacji z mecz贸w.
* Wygl膮d interfejsu jest do艣膰 prosty i przejrzysty, mimo to nie okre艣la do czego jest ta aplikacja. Przyda艂by si臋 motyw pi艂ki, boiska i kolorystyki zwi膮zanej bli偶ej z tematyk膮 aplikacji. W momencie wybranego klubu, w kt贸rym jest gracz ciekawie gdyby t艂o karty zawodnika przybiera艂o barwy klubu. 艁adne jest logo (Fotbal Kolektyw) z liniami papilarnymi co wi膮偶e si臋 z ide膮 aplikacji czyli tworzeniem ID zawodnika, jednak super gdyby linie papilarnie wprowazi膰 na pi艂k臋. Mieliby艣y obraz/logo, po kt贸rym od razu wida膰 do czego odno艣i si臋 aplikacja.
![obraz](https://user-images.githubusercontent.com/116502803/198896849-d02f7b93-9408-45f3-a6f6-03e812ec0d2d.png)
* Aplikacja jest bardzo intuicyjna je艣li chodzi o opcj臋 dodania gracza. Jesli chodzi o raporty oraz mecze trzeba si臋 chwil臋 zastanowi膰 jaka opcja odnosi si臋 do czego konkretnie. Mo偶na by艂oby urpo艣ci膰 opcje na bardziej intuicyjne. 
* Aplikacja dzia艂a poprawnie w przegl膮darce Chrome, Mozilla, Opera, Microsoft Edge oraz w telefonie Samsung A51, Aipad Air, Samsung Galaxy s8, Iphone XR jednak we wszystkich opcjach po wejsciu w odno艣nik do mecz贸w nale偶y mocno przesuwa膰 w lewo ekran w celu zobaczenia jakie opcje kryj膮 si臋 na ko艅cu w opcjach AKCJE. Galaxy Fold pole akcji do meczu nie mie艣ci si臋 w ekranie.

:warning: 
### Zauwa偶y艂am b艂edy :
przy opcji wprowadzania zawodnika do aplikacji : 

![obraz](https://user-images.githubusercontent.com/116502803/201052623-874b0481-1296-48eb-b478-f83e7253948c.png)


 1. Mamy mo偶liwo艣膰 wprowadzenia wieku gracza,kt贸ry jest nierealny (wiek np.156 ),
 2. Numer telefonu przyjmuje nieprawid艂owe warto艣ci ( litery, znaki specjalne, nie ma okre艣lonej dlugo艣ci ci膮gu cyfr ani wyboru nr. kierunkowego)
 3. Nierawid艂owe warto艣ci dat urodzenia w polu daty urodzenia zawodnika (np. rok 1000 )
 4. W polu imie i nazwisko pole przyjmuje warto艣ci cyfr co tak偶e jest b艂edem.
 5. W polu waga nie ma mamy podanej jednostki wagi, nie wiemy czy wpisujemy kg czy tony, tak偶e ilo艣膰 znak贸w jakie mo偶emy u偶y膰 w tym polu ma za du偶o      mo偶liwo艣ci.
 6. Pole wzrostu tak偶e nie ma jednostki miary w jakiej mamy wpisa膰 podany zwrost zawodnika a pole przyjmuje wszystkie mo偶liwe znaki z klawiatury.
 7. W opcji dodawania akcji podczas meczu mo偶emy zmienia膰 ilo艣ci po艂贸w meczu (np.24 po艂owa meczu) co nie jest prawid艂ow膮 warto艣ci膮 wg za艂o偶enia meczu pi艂ki no偶nej.
 8. W polu link do FB pole przyjmuje wszelkie dane a powinno by膰 dedykowane dla strony http.
 9. W polu j臋zyk mo偶emy wpisa膰 dowolny ci膮g cyfr lub znak贸w.
 10. Nie ma mo偶liwosci skasowania gracza. 
 11. Button " wyczy艣膰" nie powoduje usuni臋cia wszystkich danych z formularza. 
 
 podczas generowania raport贸w :
 
10. Button SAVE podczas generowania raportu znajduje si臋 w prawym g贸rnym rogu ekranu co nie jest intuicyjne, zazwyczaj szukamy przycisku na dole i w prawym rogu lub poprostu pod spodem wszelkich wprowadzonych danych. 
11. Przycisk cofnij przy meczach nie cofa liczby po艂贸w meczu. 
12. Trzykrotne szybkie naci艣niecie raportu do pobrania spowodowa艂o b艂ad 404. *e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/events/site 404*

og贸lne :
1. Brak mo偶liwo艣ci p艂atno艣ci za dane o graczach, brak zak艂adki p艂atno艣ci. 
2. Brak numer贸w raport贸w.
3. Liter贸wki "ostatnio zaaktualizowany gracz"
4. B艂ad w s艂owie "Aktywnos膰". 

![obraz](https://user-images.githubusercontent.com/116502803/201538188-7d65fae8-deb3-44a4-b55a-6a64661ec51c.png)



# TASK 2

# Przypadki Testowe

## Subtask 1

:pencil2: [TEST CASES- Pisanie przypadk贸w testowych na podstawie User Story.](https://docs.google.com/spreadsheets/d/1SQZNn9DFWDLQHjvpZF3Y-jgVg40fRn8WiL9FYvge3Z0/edit#gid=0)


## Subtask 2

鉁忥笍[TEST CASES-Pisanie przypadk贸w testowych na podstawie 鈥渨艂asnych do艣wiadcze艅".](https://docs.google.com/spreadsheets/d/1zVuimNVxVWDsMral14TWLH-uEDZOKgyXpBZP_CxqrSk/edit#gid=0)

## Subtask 3
:question:
_Po co piszemy przypadki testowe?_ 
   
  :point_right: **Przypadki testowe** to kroki, kt贸re pozwalaj膮 nam zweryfikowa膰 czy dana funkcjonalno艣膰 spe艂nia okre艣lone za艂o偶enie. Jest to jedne z podstawnych zda艅 testera. Pisanie przypadk贸w testowych jest po to by dobrze rozplanowa膰 to co chcemy przetestowa膰. Nie jest to trudne ale czasem bywa pracoch艂onne i 偶mudne. Jednak potrafi pobudzi膰 wyobra藕ni臋. Dobre pokrycie przypadkami testowymi oprogramowania daje nam pewno艣膰 podczas test贸w, 偶e nie pomin臋li艣my 偶adnej wa偶nej funkcjonalno艣ci. Po zako艅czeniu test贸w, na podstawie przypadk贸w testowych mo偶emy budowa膰 nasze raporty z wykonanych test贸w. Dla nowo przyj臋tych do zespo艂u ludzi przypadki testowe mog膮 sta膰 si臋 bardzo dobrym 藕r贸d艂em informacji o niej. 
  
  
 :point_down: watch the movie :movie_camera:
 
 [![Watch the video](https://user-images.githubusercontent.com/116502803/200179639-1fc0c994-0d5f-4642-bd9b-957e68567906.png)](https://www.youtube.com/watch?v=bnXuZiqDCn4)



Mo偶emy u偶y膰 program贸w dedykowanych do pisania przypadk贸w testowych :  _Test link czy Azure devops_. :computer: 

Linki do pobrania :
1. Testlink
:flashlight: https://testlink.org/
2. Azure DevOps
:flashlight: https://www.datadoghq.com 

## Subtask 4
馃挜 DLA CH臉TNYCH- Pisanie przypadk贸w testowych na podstawie 鈥渨艂asnych do艣wiadcze艅".

Aplikacja Pick Eat Up

Zadanie wykonane z Anna Ha艂as i Justyna Smo艂kowicz.

:pencil2: [Pisanie przypadk贸w testowych na podstawie 鈥渨艂asnych do艣wiadcze艅".](https://docs.google.com/document/d/1qCHG3Kz0est6oassLm8g_u2Ln6Ugymq7/edit)

# TASK 3

# Raportowanie b艂臋d贸w

## Subtask 1-2

Utworzenie formatki do zg艂aszania b艂臋d贸w systemu i testowanie wed艂ug plan贸w test贸w i raportowanie b艂臋d贸w

馃摑 [Fromatka i plan test贸w](https://docs.google.com/spreadsheets/d/1Cr0C98g_r9e-ox4WsNjSKr46a59KgGHxKRy5ENSyKjk/edit#gid=797795698)

## Subtask 3

:pencil2: [Raport z test贸w](https://docs.google.com/document/d/1YbnCNxyN1HSR4tjZBn0cb0Dio-D4n25yaQ_PC2VSXjU/edit)

![obraz](https://user-images.githubusercontent.com/116502803/201517766-d56cf3d1-790c-4bba-897b-ae7acdfeffef.png)



# TASK 4 

# Testowanie aplikacji mobilnych

![obraz](https://user-images.githubusercontent.com/116502803/202800529-b76b2cc4-310c-47bd-9b95-1d42acbc2052.png)


## Subtask 1-2

Aplikacja Focusly.

:pencil2: [Testowanie eksploracyjne i raportowanie b艂臋d贸w](https://docs.google.com/spreadsheets/d/1fdO8D-vW5-ebooiQZmZp25QEW7fAelsv94ogZbqN-P4/edit#gid=0)

## Subtask 3

# Do czego s艂u偶y ta aplikacja?

![obraz](https://user-images.githubusercontent.com/116502803/202800943-88b3f884-821d-4102-9b9d-c2283f13459e.png)


:grey_question: _1. Do czego s艂u偶y ta aplikacja? Jaki jest cel tej aplikacji?_ 
 
 Focusly to aplikacja wspieraj膮ca rozw贸j osobisty poprzez nagrania psychoedukacyjne, praktyki uwa偶no艣ci i medytacje prowadzone tworzone przez ekspert贸w 鈥? psycholog贸w, terapeut贸w, trener贸w uwa偶no艣ci i nauczycieli medytacji.

:grey_question: _2. Kto ma by膰 u偶ytkownikiem ko艅cowym aplikacji?_
 
 Ko艅cowym u偶ytkownikiem aplikacji zostaje osoba chc膮ca poprawi膰 koncentracj臋, zadba膰 o sw贸j m贸zg, emocje, ukojenie nerw贸w. 
 
 
:grey_question: _3. Czy wed艂ug Ciebie aplikacja jest user friendly?_  
 
 Uwa偶am 偶e aplikacja jest przyjazna dla u偶ytkownika i zach臋ca do medytacji ka偶dego dnia. Przyciski s膮 intuicyjne. 
 
:grey_question:_4. Jak by艣 usprawni艂 aplikacj臋? Co by艣 w niej poprawi艂. Czy masz jaki艣 pomys艂 na dodatkow膮 funkcjonalno艣膰?_

Doda艂abym w aplikacji mo偶liwo艣膰 dodania zdj臋cia profilowego , interakcji miedzy kursantem a nauczycielem w postaci komentarzy pod artyku艂ami , doda艂abym mo偶liwo艣膰 pr臋dko艣ci odtwarzania  w playerze

:grey_question:_5. Jakie dostrzegasz r贸偶nice pomi臋dzy testowaniem aplikacji internetowej, a natywnej?_

Strona internetowa skupia si臋 na przekazie informacji dla osoby odwiedzaj膮cej, proste funkcjonalno艣ci, zazwyczaj nie wymaga uwierzytelniania personalnego.
Aplikacja zaprojektowana jest do interakcji z u偶ytkownikiem, posiada z艂o偶one mechanizmy i funkcje, zazwyczaj wymaga uwierzytelnienia personalnego.

## Subtask 4 :boom: 

:boom: Zadanie dla ch臋tnych. 

## Testy aplikacji mobilnej i webowej.

:boom: Wykonane z Anna Ha艂as i Jowita Ka艂ucka. :boom:

:star: [Jira- test aplikacji SwepTo](https://halas2022.atlassian.net/jira/software/projects/CPP/boards/1?label=WEB%2CMOBILE)

![obraz](https://user-images.githubusercontent.com/116502803/204475920-838daa4f-8f62-4d2d-b823-398c546f8aef.png)

 

# TASK 5

# SQL part 1

## Subtask 1

W tym zadaniu dowiedzia艂am si臋 czym jest j臋zyk SQL i jakie s膮 zapytania : SELECT,	FROM,	WHERE,GROUP BY,ORDER BY. 

_SQL to j臋zyk komputerowy przeznaczony do pracy ze zbiorami fakt贸w i relacjami mi臋dzy nimi._


## Subtask 2 

ZROBIONE!!! :D 鉁旓笍
![obraz](https://user-images.githubusercontent.com/116502803/204156654-31ef9e61-989d-4980-91ab-b598444e1865.png)


## Subtask 3

1. Wy艣wietl tabel臋 actors w kolejno艣ci alfabetycznej sortuj膮c po kolumnie surname.

![obraz](https://user-images.githubusercontent.com/116502803/204158047-b9c7f1d6-e59f-49a4-bf2a-81dc588cdbae.png)


2. Wy艣wietl film, kt贸ry powsta艂 w 2019 roku.
![obraz](https://user-images.githubusercontent.com/116502803/204158058-e78e0cf2-b454-4b27-a78b-88c2a95463f8.png)



3. Wy艣wietl wszystkie filmy, kt贸re powsta艂y mi臋dzy 1900, a 1999 rokiem.

![obraz](https://user-images.githubusercontent.com/116502803/204158067-a5cbe0ab-24c6-4089-aa5a-7c4174aefa7e.png)




4. Wy艣wietl JEDYNIE tytu艂 i cen臋 film贸w, kt贸re kosztuj膮 poni偶ej 7$ 

![obraz](https://user-images.githubusercontent.com/116502803/204158072-2b3b9592-200c-4302-bde5-cd5195453693.png)



5. U偶yj operatora logicznego AND, aby wy艣wietli膰 aktor贸w o actor_id pomi臋dzy 4-7 (4 i 7 powinny si臋 wy艣wietla膰). NIE U呕YWAJ operatora BETWEEN.

![obraz](https://user-images.githubusercontent.com/116502803/204158083-c7aeffc5-239c-48c0-a7ff-a0d07a8f4552.png)



6. Wy艣wietl klient贸w o id 2,4,6 wykorzystaj do tego warunek logiczny. 

![obraz](https://user-images.githubusercontent.com/116502803/204158090-2607be4c-6428-42ca-b4b2-1508bde8cb28.png)


7. Wy艣wietl klient贸w o id 1,3,5 wykorzystaj do tego operator IN. 

![obraz](https://user-images.githubusercontent.com/116502803/204158099-f0484c07-2271-437d-9bc1-f18bcda1c45e.png)



8. Wy艣wietl dane wszystkich os贸b z tabeli 鈥榓ctors鈥?, kt贸rych imi臋 zaczyna si臋 od ci膮gu 鈥淎n鈥?.
![obraz](https://user-images.githubusercontent.com/116502803/204158106-6cfa4a4e-776d-4942-9c37-e3371d264157.png)



9. Wy艣wietl dane klienta, kt贸ry nie ma podanego adresu email.
![obraz](https://user-images.githubusercontent.com/116502803/204158114-8229b615-6bed-4d30-9735-4133d95a78fb.png)



10. Wy艣wietl wszystkie filmy, kt贸rych cena wynosi powy偶ej 9$ oraz ich ID mie艣ci si臋 pomi臋dzy 2 i 8 movie_id.
![obraz](https://user-images.githubusercontent.com/116502803/204158123-f010899e-8e1c-4aef-b2af-5890f92b3655.png)

# TASK 6

# SQL part 2

## Subtask 1

 Kr贸tki kurs podstaw SQL
 
 11. Pope艂ni艂am b艂膮d wpisuj膮c nazwisko Ani Miler 鈥? wpisa艂am Muler. Znajd藕 i zastosuj funkcj臋, kt贸ra poprawi m贸j karko艂omny b艂膮d 馃檲
 
 ![obraz](https://user-images.githubusercontent.com/116502803/205507146-471072de-bc99-47e2-8880-ff87daf9a032.png)


12. Pobra艂am za du偶o pieni臋dzy od klienta, kt贸ry kupi艂 w ostatnim czasie film o id 4. Korzystaj膮c z funkcji join sprawd藕, jak ma na imi臋 klient i jakiego ma maila. W celu napisania mu wiadomo艣ci o pomy艂ce fantastycznej szefowej.

![obraz](https://user-images.githubusercontent.com/116502803/205512453-abd413b0-71cb-4d6f-aed3-67e7befdd8a0.png)


13. Na pewno zauwa偶y艂_艣, 偶e sprzedawca zapomnia艂 wpisa膰 emaila klientce Patrycji. Uzupe艂nij ten brak wpisuj膮c: [pati@mail.com](mailto:pati@mail.com)

![obraz](https://user-images.githubusercontent.com/116502803/205624644-e5e9fb3f-c998-4ac8-9b74-905bc9c94186.png)


14. Dla ka偶dego zakupu wy艣wietl, imi臋 i nazwisko klienta, kt贸ry dokona艂 wypo偶yczenia oraz tytu艂 wypo偶yczonego filmu. (wykorzystaj do tego funkcj臋 inner join, zastan贸w si臋 wcze艣niej, kt贸re tabele Ci si臋 przydadz膮 do wykonania 膰wiczenia).

![obraz](https://user-images.githubusercontent.com/116502803/205743957-1d59c5f3-d2da-45ac-8796-5571441bf64d.png)


15. W celu anonimizacji danych, chcesz stworzy膰 pseudonimy swoich klient贸w. - Dodaj kolumn臋 o nazwie 鈥榩seudonym鈥? do tabeli customer,- Wype艂nij kolumn臋 w taki spos贸b, aby pseudonim stworzy艂 si臋 z dw贸ch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling 鈫? Nag

16. Wy艣wietl tytu艂y film贸w, kt贸re zosta艂y zakupione, wy艣wietl tabel臋 w taki spos贸b, aby tytu艂y si臋 nie powtarza艂y.

17. Wy艣wietl wsp贸ln膮 list臋 imion wszystkich aktor贸w i klient贸w, a wynik uporz膮dkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

![obraz](https://user-images.githubusercontent.com/116502803/205507165-fd98125c-2697-4489-ae22-15a3af2a17e0.png)


18. Polsk臋 opanowa艂a inflacja i nasz sklepik z filmami r贸wnie偶 dotkn膮艂 ten problem. Podnie艣 cen臋 wszystkich film贸w wyprodukowanych po 2000 roku o 2,5 $ (Pami臋taj, 偶e dolar to domy艣lna jednostka- nie u偶ywaj jej nigdzie).

![obraz](https://user-images.githubusercontent.com/116502803/205615062-9d654719-1ddb-4a75-b7a4-1d71877b06e3.png)


19. Wy艣wietl imi臋 i nazwisko aktora o id 4 i tytu艂 filmu, w kt贸rym zagra艂

20. A gdzie nasza HONIA!? Dodaj do tabeli customers now膮 krotk臋, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = [honia@mail.com](mailto:honia@mail.com) oraz pseudonym = Hoa

![obraz](https://user-images.githubusercontent.com/116502803/205618960-f243a54f-ec7a-4ed8-85d3-acf89cc05d59.png)





## Subtask 2

Sprawd藕 swoj膮 wiedz臋 z zakresu testowania oprogramowania:

Poziom podstawowy

:large_blue_circle: cyan-15

:white_circle: alabastrowy-15

:purple_circle: indygo-14

:brown_circle: heban-13

## Subtask 3

Tworzymy portfolio

# ABOUT ME : 


 :star: [UPDATE](https://github.com/IlonaER/IlonaRadecka-Update)



