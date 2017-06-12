Lista zagadnień - obowiązuje tylko materiał omawiany na ćwiczeniach (notebooki, zadania domowe, wzory na tablicy itp.):
1. Znajomość API podstawowych klas z Pythonowych pakietów użytkowanych w kontekście Uczenia Maszynowego: matplotlib, numpy, scikit-learn.
2. Różnica pomiędzy modelem dyskryminatywnym i generatywnym.
3. Funkcja likelihood, funkcja loglikelihood.
4. Maximum Likelihood, Maximum a Posteriori. Definicje, porównanie tych dwóch metod.
5. Jednowymiarowy rozkład Gaussa. Wzór.
6. Prawdopodobieństwo warunkowe, wzór Bayesa: postać, zastosowanie. Dwa sposoby interpretacji prawdopodobieństwa: jako cecha obiektu, jako wiedza o świecie. Związek z wzorem Bayesa.
7. Wnioskowanie Bayesowskie na podstawie obserwacji rzutów monetą: estymacja prawdopodobieństwa wypadnięcia orła.
8. Wnioskowanie Bayesowskie o danych pochodzących z rozkładu Gaussa: estymacja średniej rozkładu przy stałej wariancji.
9. Regresja liniowa z błędem gaussowskim. Wzór, parametry regresji liniowej.
10. Zmiana zmiennych w regresji liniowej, funkcje bazowe. Wzór. Dlaczego używamy zmiany zmiennych.
11. Estymator ML regresji liniowej (także w wersji ze zmianą zmiennych). Wzór, wyprowadzenie wzoru.
12. Estymator MAP regresji liniowej. Na czym jest rozkład a priori, jak interpretujemy ten rozkład. Założenie gaussowskiego rozkładu a priori. Wzór (bez wyprowadzenia). Działanie parametru sigma, działanie parametru lambda.
13. Założenie i.i.d. Definicja, wytłumaczenie.
14. Random train-test split, Cross Validation, Leave One Out. Opisy algorytmów.
15. Model selection. Model evaluation. Parametry vs hiperparametry. Konieczność automatyzacji doboru hiperparametrów. Strategie poprawnej ewaluacji.
16. Model selection i model evaluation za pomocą podwójnej cross validacji. Opis algorytmu.
17. Pojęcia bias/variance dowolnego estymatora (np. estymatora średniej zmiennej losowej).
18. Bias-variance tradeoff. Definicja bias i variance modelu uczonego na zbiorze treningowym o rozmiarze N, na czym polega tradeoff.
19. Bias-variance tradeoff. Definicja bias i variance estymatora używanego w model evaluation (estymujemy skuteczność modelu m uczonego na zbiorze treningowym o rozmiarze N), na czym polega tradeoff.
20. Dekompozycja bias/variance/noise błędu MSE. Wzór (bez wyprowadzenia).
21. Regularyzacja. Związek z podejściem Bayesowskim w modelu liniowym, równoważność funkcji kosztu. Hiperparametry, które kontrolują bias/variance w modelach omawianych na zajęciach (sieci neuronowe, k-NN, regresja logistyczna).
22. Poprawna ewaluacja modelu uczonego na augmentowanych danych.
23. Podstawowe metryki w klasyfikacji: accuracy, precision oraz recall. Interpretacja jako prawdopodobieństwa warunkowe.
24. Zbalansowane metryki w klasyfikacji: F1, balanced accuracy. Wpływ przewagi klasy pozytywnej na metryki. Sposoby zbalansowania klasyfikatora: wagi przykładów oraz zamiana progu. Wzory (bez wyprowadzenia).
25. Definicja krzywej precision-recall. Jakie dodatkowe informacje można zdobyć analizując tę krzywą.
26. Wzór (bez wyprowadzenia) na prawdopobieństwo predykcji modelów: regresja logistyczna, Naive Bayes. Różnice między klasyfikatorem Naive Bayes oraz regresją logistyczną: m.in. dyskryminatywność modelu oraz założenia o niezależności (problem “double counting”).
27. Ensemble modeli. Definicja, przykładowe strategie obliczania ostatecznej predykcji dla problemu klasyfikacji (głosowanie, głosowanie ważone) i problemu regresji (średnia arytmetyczna, średnia ważona).
28. Bagging. Definicja, własności, wady i zalety.
29. Boosting. Definicja, własności, wady i zalety.
30. Gradient boosting. Nieróżniczkowalne modele - niemożliwość stosowania gradient descent, jak ten problem rozwiązuje gradient boosting: wzór na aproksymowaną pochodną, metoda aproksymacji, update rule.
31. Wielowarstwowa sieć neuronowa. Definicja. Zapis regresji logistycznej jako sieci neuronowej.
32. SGD i Momentum. Wzory, update rule. Co oznacza "Stochastic" w SGD.
33. Pochodna cząstkowa. Własności: siła wpływu parametrów na wartość funkcji, gradient jako kierunek najefektywniejszego wpływu.
34. Backpropagation. Zasada działania: sieć neuronowa jako wielokrotne złożenie funkcji, chain-rule przy liczeniu pochodnej. Algorytm forward pass. Algorytm backward pass.
35. Warstwy: ReLU, Sigmoid, Dense. Definicja, wzór na forward pass, wzór na backward pass.
36. MSE, Entropia krzyżowa. Definicja, wzór na forward pass, wzór na backward pass.
37. Funkcja kosztu vs metryka. Dlaczego nie wystarczy sama metryka (problem nieróżniczkowalności), dlaczego funkcja kosztu może zastąpić metrykę (aproksymacja metryki).
38. Cel uczenia reprezentacji. Maximum likelihood danych treningowych vs. znajdowanie dobrych semantycznie cech.
39. Autoenkoder. Zasada działania. Równoważność liniowego autoenkodera oraz PCA. Zapis autoenkodera jako sieci neuronowej.
40. Wady PCA: założenie o globalnej strukturze Euklidesowej, założenie o pochodzeniu z rozkładu normalnego.
41. Isomap. Zasada działania. Których wad PCA nie ma isomap.
42. t-SNE. Zasada działania. Zastosowanie, rola parametru perplexity.
43. Odwracalność modeli. Które modele z: t-SNE, isomap, liniowy autoenkoder, nieliniowy autoenkoder są odwracalne.

Zagadnienia nieobowiązkowe - wszystkie zagadnienia, które nie są obowiązkowe, w tym m.in.:
1. Całka po rozkładzie a posteriori (Posterior Predictive Distribution).
2. Monte Carlo
3. Wielowymiarowy rozkład Gaussa
4. Macierze dodatnio określone
5. Rozkład produktowy, brzegowy
6. Centralne twierdzenie graniczne
7. Odwracanie macierzy
8. Szeregi czasowe
9. Optymalizacja Bayesowska
10. Drzewo decyzyjne.
11. Random Forest
12. xgboost
13. SVM
14. Feature engineering
15. Vanishing gradient
