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

## Subtask 2 ➡️ Testowanie według planów testów i raportowanie błędów

## Subtask 3 ➡️ Raport z wykonanych testów

## Subtask 4 ➡️ Dla grupy i chętnych. Sesja testów eksploracyjnych.
  
