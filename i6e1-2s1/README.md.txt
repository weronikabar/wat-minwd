# Metody i narzędzia wspomagania decyzji LAB 1

autor: Weronika Bar, I6E2S1

## Instalacja biblioteki joptimizer 5.0

https://mvnrepository.com/artifact/com.joptimizer/joptimizer/5.0.0

Za pomocą <dependencies> zainstalować bibliotekę mavena JOptimizer 5.0.

## Opis biblioteki

http://www.joptimizer.com/ (strona obecnie nie działa)

JOptimizer to biblioteka umożliwiająca rozwiązywanie ogólnych problemów optymalizacji takich jak linear programming, quadratic programming, semidefinite programming itp. 
Przykładowe metody wykorzystane z powyższej biblioteki to LinearMultivariateRealFunction, czyli f(x) = q.x + r, OptimalizationRequest jako problem optymalizacyjny,

## Przykład użycia

Wytypowaliśmy dwa zestawy liczb, które chcemy obstawić na najbliższym losowaniu lotto. Zależy nam na zminimalizowaniu kosztów losów przy jednoczesnym założeniu, że odpowiednio cena kupionych liczby obu losów będzie większa lub równa konkretnej wartości, nie chcemy bowiem schodzić poniżej konkretnej ilości.
Y - rozwiązanie optymalne
x1 oraz x2 to odpowiednio ilość kupionych szans na dany zestaw
min(25x1+3x2)
x1*5+x2*2>=10
x1*2+x2*9>=11
x1*1+x2*3>=6

## Kompilacja i uruchomienie

Projekt załadować do InteliJ'a i uruchomić. 

Oczekiwany rezultat:
X1: 0	X2: 5
Y =15.0
