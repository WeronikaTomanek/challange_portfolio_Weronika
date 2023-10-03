# TASK 1
## Subtask 1
🔟 punktów
## Subtask 3
Hej 👋, nazywam się Weronika.  W mojej pracy, firma wdrażała system CRM, a ja miałam okazję go testować, zgłaszać defekty oraz porponować usprawnienia. Fakt, że uwielbiam grzebać, analizować, szukać 🕵️‍♀️ i znajdować błędy 🐛 w oprogramowaniu, bardzo ułatwił podjecie decyzji o przebranżowieniu z ubezpieczeń do IT. 

Chcę znaleźć pracę i rozwijać się jako testerka oprogramowania 🧠 📖 💻. Jestem przekonana, że z pomocą Dare IT challange stworzę fajne portfolio 👩‍💻.  

***Werka***

## Subtask 4

**Na czym polega ta aplikacja? Do czego służy?**

Aplikacja służy do:
* przeglądania i zapisywania wyników graczy w piłce nożnej,
* sprawdzania i dodawania raportów,
* jest bazą danych graczy


Głównym celem aplikacji jest zarabianie pieniędzy.
  
**Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)**

* możliwość dodania gracza - Na stronie głównej powinien być innaczej opisany przycisk zamiast "Linki pomocnicze", Dodałabym grafikę z plusem "+" 
* możliwość sprawdzenia wyników wszystkich gracz - to jest intuicyjne
* możliwość pobrania tych wyników - to jest intuicyjne ale plik pobiera się w formacie CSV, a większość osób nie ma wiedzy jak odtworzyć plik w tym formacie.
* możliwość dodania wielu informacji odnośnie graczy- to jest intuicyjne. Cały panel powinien być w języku Polskim.
* możliwość dodania raportu z meczu- taka funkcja powinna być łatwo dostępna np. na stronie głównej
* możliwość dodania meczu - taka funkcja powinna być łatwo dostępna np. na stronie głównej
* możliwość rozpoczęcia meczu- dużo czasu mi zajeło zrozumienie tej funcji brak informacji, żeby kliknć na boisko aby dodać akcje zawodnika.
* możliwość logowania - intuicyjne
* możliwość resetu hasła - intuicyjne
* możliwość zzamiany języka - intuicyjne

  
**Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

NIE:
* brak grafik,
* brak wykresów,
* duża ilość danych tabeli
* brak podstawowych fukncji tj. dodanie meczu, dodanie raportu na stronie głównej.
  
  
**Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).**

* Nie jest intuicyjna- szukałam jak mam zapisać edytowany raport, gdzie znajdę listę wszystkich raportów, dlaczego nie zapisało mi gracza, brak informacji jak posługiwać się opcją "rozpocznij mecz".



**Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)**

* W okienku logowania system nie przepuszcza użytkownika, jeżeli wkradła się spacja na końcu wpisywania loginu
* Podczas dodawania gracza, dodałam adres mailowy bez znaku "@", otrzymałam komunikat że gracz nie został dodany jednak brak informacji dlaczego
* Brak możliwości dodania raportu w module "Raporty" - najpierw trzeba wejść w zawodnika, dodać mecz, a dopiero potem można dodać raport
* Po dodaniu gracza strona powinna odsyłać np. do tabeli z graczami
* Po dodaniu gracza nic się dalej nie dzieje na stronie, nie ma żadnego przycisku powrót do strony głównej
* Wchodząc na stronę główną znikają moduły "Gracze" oraz "Raporty" na pasku po lewej stronie
* Exportując plik do CV- brak wszystkich danych z tabeli, wyexportowało tylko kilka pozycji
* Brak listy/tabeli wsystkich raportów z meczów- raporty są tylko odnośnie gracza
* Brak takiej listy/tabeli wszystkich meczów- powinna być taka sama jak lista graczy
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

Czy według Ciebie aplikacja jest user friendly? (Przyjazna dla użytkownika- np. wchodzisz do aplikacji i szybko łapiesz do czego służą przyciski. 



Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? (Żeby nie było: nie jest to aplikacja przy której pracuję, takie pytania pojawiają się na rozmowach rekrutacyjnych dlatego dobrze jest to przećwiczyć :D )

Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

## Subtask 4 - Dla grupy i chętnych. Testy aplikacji mobilnej i webowej.
