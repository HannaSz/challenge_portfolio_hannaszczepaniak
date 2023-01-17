
####  

<div align="center">challenge_portfolio_hannaszczepaniak</div>

# Spis treści

*[Subtask 1](#Subtask 1)

*[Subtask 2](#Subtask 2)

*[Subtask 3](#Subtask 3)

*[Subtask 4](#Subtask 4)

 
 ###
<div align="center">Task 1</div>


##### Subtask 1

6/10

##### Subtask 3



Cześć :smiley: Mam na imię Hania i zdecydowałam się na udział w challenge portfolio aby zwiększyć swoje szanse na otrzymanie stażu jako tester. Mam nadzieje, że będzie to również dobry sprawdzian dla mnie czy w ogóle nadaję się na testera. Po długiej przerwie w aktywności zawodowej postanowiłam zmienić branżę i ktoś podpowiedział mi abym spróbowała zostać testerem. Jako mama dwójki chłopców w końcu mam szansę pomyśleć w końcu o sobie i po zakończeniu kursu szukam wszelkich możliwości aby móc się rozwijać :smiley: Moc jest ze mną :smiley:

#### Subtask 4

 Nazwa testowanej aplikacji: .[https://scouts-test.futbolkolektyw.pl/pl](https://scouts-test.futbolkolektyw.pl/pl) – automatic! [Scouts Panel](https://scouts-test.futbolkolektyw.pl/pl).
 Głównym celem aplikacji dodawaniu piłkarzy do zbioru danych, zarządzania graczami, meczami i tworzeniem raportów.



Z aplikacji będą korzystać osoby zajmujące się wyszukiwaniem najlepszych graczy do swoich zespołów. Użytkownik będzie miał wyspecyfikowane wymagania co do gracza. 
Domyślam się, że z aplikacji będą również korzystać trenerzy zespołów piłkarskich, publikując dane swoich zawodników oraz ich osiągniecia. 
 Aplikacja działa zarówno na stronie stacjonarniej jak i na urządzeniach mobilnych. Nie posiada możliwości utworzenia nowego użytkownika. Nie występuje podział na użytkownika i administratora. Tylko zalogowany użytkownik ma możliwość wyświetlenia listy piłkarzy. Zarówno logowanie jak i wylogowanie z aplikacji przebiega sprawnie.
Użytkownik może podjąć na aplikacji akcje takie jak: 
1. zalogowanie do systemu
2. dodatnie gracza
 Tworząc profil piłkarza :
*Wymagane dane: imię, nazwisko, data urodzenia, pozycja na boisku.*
3. dodanie meczy, w których wystąpił

  Profil gracza można rozszerzyć o informacje nt. rozegranych meczy.
 
    *Wymagane dane do dodania rozegranego meczu: drużyna zawodnika, drużyna przeciwna, zdobyte gole, stracone gole, data meczu.*

4. Dla utworzonego meczu można utworzyć raport dla zawodnika oraz wprowadzić wykonane akcje w dowolnym momencie meczu.
5. Wyświetlenie listy dodanych graczy
6. Wyszukanie graczy stosując wybrane filtry
7. wyświetlić ostatnie akcje w aplikacji
8. zmienić język aplikacji 
9. wyświetlić liczbę dodanych graczy, meczy, raportów i akcji
10. edytować profil gracza, dodane raporty i mecze
11. wylogować się. 

 Aplikacja musi współpracować z innymi platformami:
  * facebook.com
  * youtube.com
  * laczynaspilka.pl
  * 90minut.pl.
  
# Błędy, które znalazłam w aplikacji.

| utworzenie profilu gracza | - imię i nazwisko można wyrazić cyframi - można dodać datę urodzenia, która się dopiero odbędzie lub baaardzo baardzo odległą - można dodać niezliczoną liczbę kont o takich samych danych - wagę, wzrost i numer telefonu można dodać ze znakiem (-) - waga musi być zaokrąglona do jedności - po zmianie języka na angielski zmieniają się nazwy województw [?]                                                                                                                                                                                      |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| utworzenie meczu          | - można utworzyć wynik meczu w dacie, która się dopiero odbędzie - mecz może odbyć się pomiędzy tą samą drużyną - mecz można wyłączyć w dowolnej chwili, nie ma możliwości do powrotu do edycji meczu - czas meczu można wyrazić ze znakiem (-),  - czas meczu można edytować w każdej chwili, zarówno minuty jak i sekundy nie mają ograniczeń - liczba "połów" meczów jest nieskończona i ich liczba jest zmienialna w każdej chwili - można rozegrać ujemną liczbę "połów" - akcje w meczu można cofnąć, ale nie można ich przywrócić z powrotem    |
| wygenerowanie raportu     | - można wygenerować pusty raport - aby wygenerować raport z meczu należy dodać województwo do profilu gracza, a nie była to wymagana informacja - można ocenić gracza w raporcie na skali wypełniających się kolorem gwiazdek , zarówno w połowie jak i w całości a legenda do tej oceny zawiera tylko wyjaśnienia do pełnych gwiazdek -                                                                                                                                                                                                               |
| edycja profilu gracza     | - Wszystkie dane gracza są edytowalne - nie można usunąć informacji z profilu - przycisk 'clear' nie działa - nie można usunąć profilu gracza                                                                                                                                                                                                                                                                                                                                                                                                          |
| wyszukiwanie gracza       | - po usunięciu nie interesujących mnie tabel w wyszukiwarce , przełączając strony użytkowników dodają się tabele z wiekiem i recenzją -                                                                                                                                                                                                                                                                                                                                                                                                                |
| działanie strony          | - bardzo powolne przechodzenie ze strony głównej do listy graczy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

