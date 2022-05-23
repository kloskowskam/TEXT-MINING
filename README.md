# TEXT-MINING
Repozytorium zawierające zadania z text miningu

# Zadanie 1
1.Na stronie https://en.wikipedia.org/wiki/Academy_Award_for_Best_Picture znajduje się
tabela zawierająca listę filmów nominowanych do Nagrody Akademii za Najlepszy Film
(popularnie nazywanej Oskarem). Tytuły filmów umieszczonych w tabeli są interaktywnymi
linkami i prowadzą do stron zawierających szczegółowe informacje o poszczególnych filmach.
2. Korzystając z poznanych modułów i pakietów Pythona napisz skrypt, który pobierze z tej
strony (oraz powiązanych z nią stron poszczególnych filmów) odpowiednie dane i utworzy
dokument tekstowy zawierający dane dotyczące filmów, które otrzymały nagrodę (w tabeli
tytuły tych filmów zostały pogrubione i umieszczone na żółtym tle). Opis każdego filmu
powinien zawierać następujące informacje:
a. tytuł filmu,
b. rok za który otrzymał nagrodę,
c. nazwisko reżysera
d. opis fabuły

# Zadanie 3

Plik superheroes.xlsx zawiera dane dotyczące komiksowych superbohaterek i superbohaterów.
Zadanie polega na zbudowaniu klasyfikatora, który na podstawie historii danej postaci (pole
history_text) oraz opisu jej supermocy (pole powers_text) stwierdzi z jakiego wydawnictwa ona
pochodzi. Dokładniej mówiąc klasyfikator powinien przypisać postać do jednej z trzech klas: Marvel
Comics, DC Comics, inne wydawnictwo (informacja o wydawnictwie znajduje się w polu creator).
1. Podziel dane na zbiór uczący i testowy (w proporcjach 70% - 30%). Zadbaj o odpowiednią
reprezentację wszystkich klas w obu zbiorach.
2. Przekształć dane do postaci nadającej się do analizy.
3. Zbuduj przynajmniej trzy klasyfikatory różnego typu. Dobierz optymalne wartości
parametrów tych klasyfikatorów oraz optymalną reprezentację danych tekstowych.
4. Sprawdź jakość zbudowanych klasyfikatorów na zbiorze testowym, stosując odpowiednie
miary jakości. Porównaj wyniki uzyskane przez te klasyfikatory.
5. Na podstawie zbioru uczącego utwórz listy 30 słów, które mają największy wpływ na
zaklasyfikowanie postaci do danego wydawnictwa (niektóre klasyfikatory pozwalają na
wydobycie takich danych, można też dokonać analizy porównawczej częstości występowania
wyrazów w poszczególnych klasach).
6. Sprawdź, jak wpłynie na jakość klasyfikacji uwzględnienie innych cech postaci (tzn. tych
niepochodzących z pól history_text i powers_text). 
