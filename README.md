# Warsztaty ***"Jeden, by wszystkimi rządzić" - czyli eRowy toolbox analityka danych.***
## Konferencja Ekonometryk - zawód przyszłości
## 2016-04-20 

### Wymagania wstępne:

- Podstawowa znajomość R i Rstudio.
- Zainstalowana najnowsza wersja R (3.2.4) i Rstudio (przynajmniej w wersji 0.99.878).
- Uruchomić w R poniższy kod (pobranie i instalacja wszystkich potrzebnych pakietów):

```r
if(!require(pacman, quietly = TRUE))
{
  install.packages("pacman")
  library(pacman)
}

p_load("rmarkdown", "knitr", "dplyr",
        "devtools", "whisker", "quantmod", "PerformanceAnalytics")
p_load_gh("eRkaKrakow/erkaSupport")

```


#### Użytkownicy Windowsa:

- Należy pobrać i zainstalować Rtools 3.3 (https://cran.r-project.org/bin/windows/Rtools/).

#### Użytkownicy Linuxa

- Tutaj wszystko powinno być gotowe.


