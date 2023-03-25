# Wybrane Projekty ze Sztucznej Inteligencji i Uczenia Maszynowego 

## [Regresja i klasyfikacja](decision_tree.ipynb)
Implementacja drzew decyzyjnych tworzonych algorytmem ID3 z ograniczeniem maksymalnej głębokości drzewa oraz stworzenia i zbadania jakości klasyfikatorów dla zbioru danych `breast cancer`.

## [Algorytmy ewolucyjne i genetyczne](evolutionary_algorithms.ipynb)
Implementacja algorytmu ewolucyjnego z selekcją ruletkową, krzyżowaniem jednopunktowym, mutacją gaussowską oraz sukcesją generacyjną.
Wykorzystanie implementacji do znalezienia rozwiązanie dające minimalny koszt dla problemu optymalizacyjnego.
Optymalizacja zestawu hiperparametrów dla zadanego problemu i zbadanie jego wpływu na wynik.

## [Modele Bayesowskie](mcmc.ipynb)
Implementacja narzędzia do wnioskowania przy użyciu sieci Bayesa (algorytm MCMC z próbkowaniem Gibbsa) i jego przykładowe użycie.

## [Dwuosobowe gry deterministyczne](min_max_alpha_beta.ipynb)
Implementacja algorytmu min-max z przycinaniem α−β. 
Wykorzystanie implementacji do porównania jakości dla różnych głębokości przeszukiwania dla gry kółko i krzyżyk na planszy N x N. 
W raporcie zostały umieszczone wyniki turnieju w grę kółko i krzyżyk, w którym biorą udział gracze sterowani algorytmem z różnymi głębokościami przeszukiwania.

## [Sztuczne sieci neuronowe](neural_network.ipynb)
Implementacja perceptronu wielowarstwowego oraz algorytmu optymalizacji gradientowej (funkcja aktywacji ReLU) z algorytmem propagacji wstecznej. 
Perceptron wielowarstwowy został wytrenowany do klasyfikacji zbioru danych `wine`.

## [Uczenie się ze wzmocnieniem](reinforcement_learning.ipynb)
Implementacja algorytmu Q-learning oraz stworzenie agenta rozwiązującego problem Taxi.
Problem dostępny jest w pakieciegym `gym`.