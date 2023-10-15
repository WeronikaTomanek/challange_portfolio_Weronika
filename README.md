# TASK 1
## Subtask 1
🔟 punktów
## Subtask 3

Dear Recruiter, 
I encourage you to take a look at my porflio. I created it with the help of the Dare IT (Thank you guys, I enjoyed learning and practicing at the same time!). 

I have 5 years of experience in administrative work and customer service.  As an administration specialist I discovered and started testing software! How is this possible 🤔 ? The company I was working for was implementing a CRM system and I spent 2 years testing the modules of the registration and contracts department. Beta-testing, retesting, reporting bugs, analysing how to make the system more efficient - it is my thing ❤️ !

I've learned ISTQB, basic tools, good testing practices and I'm ready to join the team to work as a junior tester (with ambitions to become an automation tester 🧠 📖 💻 ).

I am looking forward to the first daily meeting as part of the team! 

***Weronika***

## Subtask 4 - Testy eksploracyjne aplikacji internetowej https://scouts-test.futbolkolektyw.pl/pl 

**Na czym polega ta aplikacja? Do czego służy?**

Aplikacja służy do:
* przeglądania i zapisywania wyników graczy w piłce nożnej,
* sprawdzania i dodawania raportów,
* jest bazą danych graczy

Głównym celem aplikacji jest zarabianie pieniędzy.
  
**Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?**

* możliwość dodania gracza ➡️ 💡 Na stronie głównej powinien być innaczej opisany przycisk zamiast "Linki pomocnicze", Dodałabym grafikę z plusem "+" 
* możliwość sprawdzenia wyników wszystkich gracz ➡️ funckja jest intuicyjna
* możliwość pobrania wyników wszystkich graczt ➡️ funckja jest intuicyjna 💡 Proponuję zminić format pobieranego pliku  na xml. Plik pobiera się w formacie CSV, który jest nieczytelny dla użytkownika 
* możliwość dodania wielu informacji odnośnie graczy ➡️ funcja jest intuicyjna
* możliwość dodania raportu z meczu ➡️💡 Funkcja powinna być łatwo dostępna dla użytkownika np. na stronie głównej
* możliwość dodania meczu ➡️ 💡 Funkcja powinna być łatwo dostępna np. na stronie głównej
* możliwość rozpoczęcia meczu ➡️ Funcja nie jest intuicyjna 💡 Warto dodać instrukcję obługi, kóra pokierowałaby krok po kroku jak poruszać się po tej funcjonalności.
* możliwość logowania ➡️ funckja jest intuicyjna
* możliwość resetu hasła ➡️ funckja jest intuicyjna
* możliwość zzamiany języka ➡️ funckja jest intuicyjna

  
**Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

Interfejs aplikacji jest mało czytelny. Moim zdaniem nie jest user friendly ze względu na: 
* brak grafik,
* brak wykresów,
* dużą ilość danych tabeli
* brak podstawowych fukncji tj. dodanie meczu, dodanie raportu na stronie głównej.
  
  
**Czy aplikacja jest intuicyjna?**

* Aplikacja nie jest intuicyjna.
* Przycisk SAVE, na stronie edytowania raportu nie jest dostępny i zaprojektowany zgodnie z dobrymi praktymi User Experience.
* Brak informacji, instrukcji jak posługiwać się opcją "rozpocznij mecz".

* Informacje odnośnie ilości graczy, meczów, raportów, akcji dają złudzenie interaktrywnych przycisków 
 <img width="1182" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/4577cc8f-1b4a-403b-8efe-685f4cf23f8f">



**Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)**

* W okienku logowania system nie przepuszcza użytkownika, jeżeli wkradła się spacja na końcu wpisywania loginu.
* Podczas dodawania gracza, dodałam adres mailowy bez znaku "@", otrzymałam komunikat że gracz nie został dodany jednak brak informacji dlaczego
* Brak możliwości dodania raportu w module "Raporty" - najpierw trzeba wejść w zawodnika, dodać mecz, a dopiero potem można dodać raport
* Po dodaniu gracza strona powinna odsyłać np. do tabeli z graczami
* Po dodaniu gracza nic się dalej nie dzieje na stronie, nie ma żadnego przycisku powrót do strony głównej
* Wchodząc na stronę główną znikają moduły "Gracze" oraz "Raporty" na pasku po lewej stronie
* Exportując plik do CV- brak wszystkich danych z tabeli, wyexportowało tylko kilka pozycji
* Brak listy/tabeli wsystkich raportów z meczów- raporty są tylko odnośnie gracza
* Brak listy/tabeli wszystkich meczów- powinna być taka sama jak lista graczy
* Wszystkie komunikaty, przyciski powinny być w języku polskim np. : submit, clear, save, Scouts Panel.
* Błędy kosmetyczne module "edycja gracza"tj.: 
Waga-> można dodawać wartości ujemne, Wiek -> można dodawać osobę urodzoną wczoraj, dzisiaj oraz w przyszłości, Telefon-> można dodawać litery
* W module "raporty" tylko za pomocą opcji edytuj raport mogę zobaczyć cały raport
* W opcji "dodaj mecz" brak informacji, że należy kliknąć na boisko w celu dodania akcji.
  
# TASK 2

## Subtask 1 ➡️ Pisanie przypadków testowych na podstawie User Story.
📝 https://docs.google.com/spreadsheets/d/1Zp1Z9biPIqosIIFhOafZM8sKMcBh0o2Bgm0FwHzZsxk/edit?usp=drive_link

## Substask 2 ➡️ Pisanie przypadków testowych na podstawie własnych doświadczeń.
📝 https://docs.google.com/spreadsheets/d/1J-nkVVECo8uvTsgKOB_R2ewS4VMu0LWiVm8DK2wnXS8/edit?usp=drive_link

## Subtask 3 ➡️ Po co piszemy test case’y? 

Przypadki testowe (test case) - zbiór warunków wstępnych, danych wejściowych, akcji (w stosownych przypadkach), oczekiwanych rezultatów i warunków końcowych opracowany w oparciu o warunki testowe. 
![image](https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/5b0ec03b-46a3-426a-8065-a914cc91aa21)


🎯 Cele test case'a: 
- wielokrotne uruchamianie tych samych testów na kolejnych wersjach oprogramowania przekłada się na skuteczne i spójne testowanie regresji
- przejrzysta dokumentacja różnych możliwości obsłużenia modułów w tej samej aplikacji
- minimalizacja ryzyka pominięcia ważnej funkcjonalności podczas testów
- pomocna w prowadzeniu raportów z wykonanych testów
- źródło informacji o aplikacji dla nowych członków zespołu


## Subtask 4 ➡️ Pisanie przypadków testowych na podstawie “własnych doświadczeń aplikacja pickup

📝 https://docs.google.com/spreadsheets/d/15VfjP6AsxuIDrHiARE14TpvZYTjIqo8LWIOzHe5AiLE/edit?usp=sharing


# Task 3

## Subtask 1 ➡️ Utworzenie formatki do zgłaszania błędów systemu
📝  https://docs.google.com/spreadsheets/d/10ALEwhpN4zQpzgcwVWldDd-N_220q063KdgfcjrnMm0/edit?usp=sharing

## Subtask 2 ➡️ Testowanie według planów testów i raportowanie błędów
📝  https://docs.google.com/spreadsheets/d/10ALEwhpN4zQpzgcwVWldDd-N_220q063KdgfcjrnMm0/edit?usp=sharing
📝  https://docs.google.com/spreadsheets/d/1J-nkVVECo8uvTsgKOB_R2ewS4VMu0LWiVm8DK2wnXS8/edit#gid=0


## Subtask 3 ➡️ Raport z wykonanych testów
📝  https://docs.google.com/spreadsheets/d/1CFPBfeDIGuUDotiiX03MKVehhM-S0EG5gjzf-5z-3DI/edit?usp=drive_link 

## Subtas 4 ➡️  Dla grupy i chętnych. Sesja testów eksploracyjnych.
📝 https://docs.google.com/spreadsheets/d/1ajBTaI03hbp6EjGXFVksARfjW24qD8FeraD_K8IACrI/edit#gid=0

Testowanie eksploracyjne za pomocą "rajdów" jest kreatywną metodą testowania. Mozna wybrać 6 różnych rajdów:

- Guidebook tour 
- Intellectual Tour 
- Obsessive-Compulsive Tour 
- Landmark Tour 
- Anti social tour
- Money Tour
  
Wcielanie się w konkretną rolę jest bardzo pomocne podczas wykonywania testów eksploracyjnych. Patrząc na aplikację 👀 z perspektywy konkretnej roli lub osoby sprawia że wyłapujemy różne błedy, na które normalnie nie zwrócilibyśmy uwagi. Polecam również wcielić się w rolę cioci/ babci 👵🏻! Chodzi o osobę, która nie jest biegła w komputerach ;) W taki spoób możemy przetestować dostępność naszej aplikacji.

# Taks 4 Testowanie aplikacji mobilnych 

## Subtask 1, 2 - Utworzenie formatki do zgłasza nia błędów systemu oraz testowanie eksploracyjne i raportowanie błędów 


📝 https://docs.google.com/spreadsheets/d/1PdGnuj49Zj73YG2Q62FylDRe15OB2CCj0W9ickUMHO0/edit#gid=1481076662 

## Subtask 3 - Do czego służy ta aplikacja?

Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?

> Aplikacja OLX jest serwisem ogłoszeniowy, który umożliwia zarówno osobom prywatnym, jak i firmom publikowanie ogłoszeń w celu sprzedaży lub znalezienia ofert. Umożliwia użytkownikom kupno, sprzedaż i wymianę różnych produktów i usług.
> Aplikacja oferuje wiele funkcji, które ułatwiają publikowanie ogłoszeń, przeglądanie ofert i nawiązywanie kontaktu między kupującymi a sprzedającymi.


Kto ma być użytkownikiem końcowym aplikacji?

> Użytkownikami końcowymi aplikacji OLX są osoby, które chcą sprzedawać, kupować lub znaleźć oferty produktów i usług.
> - osoby prywatne
> - przedsiębiocy
> - usługodawcy

Czy według Ciebie aplikacja jest user friendly?

> Aplikacja OLX na urządzeniu iPhone 13 ( 17.0.2) jest user friendly, ponieważ  jest czytelna i posiada prosty interfejs użytkownika. 
> Ponadto zawiera zaawansowane narzędzia do filtrownia i wyszukiwania, dzięki czemu łatwo znaleźć odpowiednie ogłoszenie. 
> Aplikacja zawiera bardzo proste oraz intyicyjne przekirowanie do wsparcia technicznego, które jest przydatne w przypadku ewentualnego problemu. 
> Dodanie ogłoszenia jest bardzo proste i bezprobemowe, ponieważ użytkownik jest kierowany krok po kroku jakie dane musi uzupełnić.
> Wszytskie przyciski są opisane co ułatwia rozumienie funkcji.



Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?

> 💡W celu usprawnienia procesu dodawnia ogłoszenia poinformowałabym użytkownika wcześniej o tym, że należy uzupełnić określoną liczbę znaków podczas dodawania tytłu oraz opisu.
> Użytkownik dowiaduje się o tym na końcu procesu dodwania ogłoszenia. Można dodać komunikat który sprawdza ilość znaków i od razu zakreśla tekst na czerwono jeżeli jest niewystarczająca ilość.
>
> 💡 Warto również dodać opcjię dostosowywania interfejsu przez użytkowników na stronie głównej. Taka funcja znajduje się tylko podczas wyszukiwania konkretnego produktu.
> 
> 💡Komentowanie ogłoszeń byłoby przydatną funcjonalnością dla użytkowników. W ten sposób użytkownicy mieliby możliwość wymiany uwag odnośnie produktu lub usługi. 


Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

> Aplikacja internetowa jest to oprogramowanie dostępne z poziomu przeglądarki
> - nie trzeba pobierać oraz instalować na komputerze
> - testowanie zwykle wymaga przeglądarki internetowej i narzędzi do testowania webowego 
>

> Aplikacja natywna to jeden z typów aplikacji mobilnych, które są budowane z przeznaczeniem na tylko 1️⃣ jeden mobilny system operacyjny.
> - wymagają pobrania i instalacji z odpowiednich sklepów z aplikacjami (np. App Store, Google Play). Aktualizacje muszą być pobierane i instalowane osobno przez użytkowników.
> - mają pełen dostęp do funkcji urządzenia, co pozwala na bardziej zaawansowane i zintegrowane funkcje, takie jak dostęp do aparatu, powiadomienia push i lokalizacja.
> 


## Subtask 4 - Dla grupy i chętnych. Testy aplikacji mobilnej i webowej.
![image](https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/8c3e7495-8f80-4dd3-97a3-3b71667e99f1)

# Task 5 SQL part 1

## Subtask 1 & 2 - Krótki kurs podstaw SQL & Konfiguracja środowska

<img width="707" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/3c7bcf52-8e86-43df-bfda-bcfdad2e6819">
<img width="707" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/ad3934b9-9ce6-45fd-9f00-09bd7b0c66b6">
<img width="378" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/13bf5a2a-8e07-4190-8837-b817a845a6f7">



## Subtask 3 - Kilka zadań na rozgrzewkę

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname. 

<img width="580" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/2639a317-9f45-4b64-b1e7-bf8554f96e47">

2. Wyświetl film, który powstał w 2019 roku.
 
<img width="480" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/d41a5459-afab-4689-bcfc-ab545fa1c387">

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

<img width="573" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/4e4b9dea-ec48-44da-a83a-56e5fbafb5af">

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

<img width="572" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/b5e4d51c-4edb-43b4-ac45-3ffecee3e906">

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

<img width="565" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/0e15b3ba-a8d4-4a03-ae6b-431ea507b268">

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

<img width="708" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/9e1917d4-8390-43cc-ad90-f20bc57aa089">

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

<img width="576" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/dac873c9-aef1-4870-910e-7cd5e2dc98f9">

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

<img width="596" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/d7e292e7-54e8-4f7e-8dee-dc52218f4305">

9. Wyświetl dane klienta, który nie ma podanego adresu email.

<img width="533" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/0bd881c1-ad8c-4ade-8ee2-0903d3b5f0c8">

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

<img width="613" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/cbfa302e-4052-4774-82fe-be98c0962bc9">


# Task 6

## Subtask 1 - Krótki kurs podstaw SQL

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈

<img width="879" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/dc5132a1-8f77-4dd2-b12f-514c656fe4bf">

12.  Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.


<img width="939" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/047ebc3d-4e7f-4a10-9ffd-dc35a7554fdf">

13.  Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
<img width="779" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/70a3b82d-0d28-43dc-8bc5-3e3dc0dd5f70">

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

<img width="942" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/bd2066f8-ea9d-49fd-98f8-1eb43808e5fe">

15. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

<img width="729" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/5573010c-f784-49a2-a5df-4e329ff3a748">

16. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

<img width="793" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/a0496eab-d030-4b8c-86d2-7661fa335220">

17. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

<img width="825" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/75f50499-2ec1-4dd6-aae5-3f17d337df23">

18. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

<img width="1100" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/0f03bf63-96e9-47ac-b1f2-a6a1f9fead4c">

19. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

<img width="731" alt="image" src="https://github.com/WeronikaTomanek/challange_portfolio_Weronika/assets/143616151/77f7e4d1-a304-4e01-96f1-207dc58dbc2d">

