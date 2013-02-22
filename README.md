# Marcin Ścibisz

m.scibisz@wz.pw.edu.pl  
pok. NT46 / NT2

electurer.edu.pl - > hasło: popro

1. Program
2. Regulamin
3. Wykład PDF
4. Przykłady wejściówek

## Zaliczenie

Laboratorium (60pkt)

* 20pkt 5x4pkt Wejściówka
* 15pkt I kolokwium
* 15pkt II kolokwium
* 10pkt Projekt

Wykład (40pkt)

kolkokwia poprawkowe na ostatnich zajęciach  
zerówka na ostatnim wykładzie

Zaliczenie: teoria i pisanie kodu  
Wejściówki: fragmet kodu na kartce  
Kolokwia: Piszemy program

## Wykład 1

### Wprowadzenie

1. Definicja Progrmowania
2. Program Komputerowy
  * Kompilacja i Interpretacja
3. Język programowania
  * syntaktyka - rodzaje dostępnych symboli, reguły budowy zdań  
  (notacja BNF, diagramy syntaktyczne)
  * semantyka - logika języka, przeznaczenie identyfikatorów
4. Najpopularniejsze języki programowania (www.tiobe.com)
  * Java
  * C
  * C++
  * Python
  * PHP
  * C# -> specjalność (informatyka..)
  * Visual Basic
  * Objective-C
  * JavaScript
  * Perl
5. Klasyfikacja języków programowania:
  * paradygmat (wzorzec) programowania  
  Programowanie proceduralne (np. C)  
  strukturalne
  funkcyjne
  Programowanie obiektowe (np. C++, Java)  
  logiczne
  * generacja  
    1. Języki maszynowe (01010101001)
    2. Języki symboliczne (asemblery)
    3. Języki wysokiego poziomu  
    Pierwszym był ALGOL. Potem np.  
    niestrukturalne: BASIC,  
    strukturalne: Pascal, C, FORTRAN, COBOL  
    zorientowane obiektowo: C++, Java
    4. Języki bardzo wysokiego poziomu (np. SQL)
    5. Języki sztucznej inteligencji (p. PROLOG)
  * sposób kontroli typów
    1. typowanie statyczne, polegające na okreslaniu typów zminnych  
    i stałłych podczas kompilacji programu.  
    1 możliwość dobrej optymalizacji kodu wynikowego  
    1 możliwość wykrycia większości błędów związanych z określaniem typów danych.  
    0 konieczność precyzyjnego opisywania typów danych w programie  
  * sposób wykonania  
    1. kompilacja - kod źródłowy jest do postaci kodu maszynowego przed uruchomieniem programu. języki tego typu to tzw. kompilowane języki programowania.  
    kod wykgenerowany na drodze kompilacji jest ziązany ze sprzętową architekturą.
    2. Interpretacja - kod źródłowy jest na bierząco tłumaczony i wykonywany przez dodatkowy program zwany interpreterem. Języki tego typu to tzw. języki interpretowane  
    kod jest wiloplatformowy

### Java

**Literatura**

Hortsmann C.S. Cornell G. - *Java Podstawy*, Wydawnictwo Helion, Gliwice 2008  
Eckel B. - *Thinking in Java*, Wydawnictwo Helion, Gliwice 2006  
Schildt H. - *Java. Kompedium programisty*, Wydawnictwo Helion, Gliwice 2005  
Marcin Lis - *???*, ???, ???

**Wprowadzenie**

Java to obiektowy język programowania stworzony przez grupę roboczą pod kierunkiem Jamesa Goslinga z firmy Sun Microsystems.  
Java jest językiem tworzenia programów źródłowych kompilowanych do kodu pośredniego (bajtowego), wykonywanego przez maszynę wirtualną  
Witrualna maszyna Javy dospępna jest na wielu platformach sprzętowych i dla wielu systemów operacyjnych  
Podstawowe koncepcje jezykwa Jaca zostały zaczerpnięte z języka Smalltalk (maszyna wirtualna, zadządzanie pamięcią) oraz z jęzuka C++ (składnia, słowa kluczowe, silne typowanie)

**Język Java - edycje**

Java Standard Edition (Java SE) - edycja języka zawierająca podstawową funkcjonalność pozwalającą na twodzenie aplikacji działających na komputerach osobistych, serwerach oraz środowisku czasu rzeczywistego  
Java Enterprise Edition (Java EE) - zawiera biblioteki rozszerzające możliwości Java SE w sapekcie tworzenia zaawansowanego oprogramowania dla dużych i bardzo dużych organizacji  
Java Micro Edition (Java ME) - edycja funkcjonalnie ograniczona w stosunku do Java SE

**Język Java - dystrybucje**

Java Development Kit (JDK) - darmowe środowisko niezbędne do programowania w języku Java. Zawiera poniższe narzędzia programistyczne:

* javac - kompilator
* jar - archiwizator
* javadoc - generator dokumentacji
* javah - generator plików nagłówkowych
* javap - deasembler
* jdb - debugger

Java Runtime Environment (JRE) - środowisko uruchomieniowe dla skomplikowanych programw napisanych w jezyku Java. Zawiera wirtualną maszynę Java oraz bibliotekę klas podstawowych.

**Pierwszy program w języku Java**

Kod źródłowy zapisujemy w plikach `.java`  
nazwa tego pliku musi być zgodna z nazwą publicznej klasy zdefiniowanej w pliku

Kompilację kodu źródłowego, otrzymujemy plik `.class`

Uruchamiamy za pomocą wirtualnej maszyny Java z pakietu JRE: `java nazwa.class`

**Przykładowy program:**

`code`  

**Komentarze**

`// To jest komentarz jednowierszowy`

`/* To jest 
   komentarz wielowierszowy */`

`/* kilka */ /* komentarzy */ /* w wierszu */`

**Typy Danych**

Typy danych w języku Java są podzielone na dwie kategorie:

* typy pierwotne
* typy referencyjne

Typy pierwotne to grupa ośmiu typów zawierających wartości proste:

* typy całkowitoliczbowe: `byte, short, int, long`  
  typy są zgodne z kodem uzupełnień do 2  
  klasy osłonowe: `Byte, Short, Int, Long`
* typy zmiennopozycyjne: `float, double`  
  format zgodny ze specyfikacją standardu ANSI/IEEE 754  
  klasy osłonowe: `Float, Double`
* typ znakowy: `char`
* wartości logiczne `boolean`

zaczynamy od slajdu 2.11
