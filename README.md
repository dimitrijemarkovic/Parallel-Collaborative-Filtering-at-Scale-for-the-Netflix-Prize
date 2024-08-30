# Paralelno Kolaborativno Filtriranje Velikih Razmera za Netfliks Nagradu

## Autori
- Dimitrije Marković
- Vuk Stefanović

## Opis Projekta
Ovaj projekat ima za cilj poboljšanje tačnosti predviđanja ocena filmova koristeći napredne tehnike kolaborativnog filtriranja. Početna faza uključivala je obuku i evaluaciju različitih modela, uključujući item-based KNN, SVD i RBM algoritam. Na osnovu rezultata, odlučili smo da implementiramo hibridne modele kako bismo dodatno unapredili tačnost predikcija. Hibridni modeli su koristili dodatne karakteristike kao što su predviđanja iz KNN-a i SVD-a, prosečna ocena filma i korisnika, varijansa ocena, i ukupan broj ocena za filmove i korisnike.

U narednoj fazi, obučili smo Ridge regresiju i XGBoost modele, koji su pokazali značajno poboljšanje u odnosu na prethodne modele. Ovi modeli su omogućili postizanje boljih rezultata u predviđanju ocena filmova, što je bio glavni cilj ovog istraživanja.

## Rezultati
- **Item-based KNN**: RMSE na test skupu = 1.0623
- **SVD**: RMSE na test skupu = 0.9938
- **Ridge Regression**: RMSE na test skupu = 0.7248
- **XGBoost**: RMSE na test skupu = 0.7002

## Podaci
Korišćeni su podaci sa Netflixovog dataseta koji su dostupni na [Kaggle-u](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data).

Svi podaci koje smo obradili i koristili tokom istraživanja mogu se preuzeti sa [Kaggle-a](https://kaggle.com/datasets/2800f75a06869fb37b795745ef175f0262853480969a39d29455d0fa3fe9bd71).

