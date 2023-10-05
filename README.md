# TASK 1
## Subtask 1
🔟 punktów
## Subtask 3
Hej 👋, nazywam się Weronika.  W mojej pracy, firma wdrażała system CRM, a ja miałam okazję go testować, zgłaszać defekty oraz porponować usprawnienia. Fakt, że uwielbiam grzebać, analizować, szukać 🕵️‍♀️ i znajdować błędy 🐛 w oprogramowaniu, bardzo ułatwił podjecie decyzji o przebranżowieniu z ubezpieczeń do IT. 

Chcę znaleźć pracę i rozwijać się jako testerka oprogramowania 🧠 📖 💻. Jestem przekonana, że z pomocą Dare IT challange stworzę fajne portfolio 👩‍💻.  

***Werka***

## Subtask 4 - Testy eksploracyjne aplikacji internetowej https://scouts-test.futbolkolektyw.pl/pl 

**Na czym polega ta aplikacja? Do czego służy?**

Aplikacja służy do:
* przeglądania i zapisywania wyników graczy w piłce nożnej,
* sprawdzania i dodawania raportów,
* jest bazą danych graczy
Natomiast głównym celem aplikacji jest zarabianie pieniędzy.
  
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

## Subtask 1 - Krótki kurs podstaw SQL

## Subtask 2 - Konfiguracja środowiska i wgranie bazy danych

## Subtask 3 - Kilka zadań na rozgrzewkę


