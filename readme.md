
# Credit Risk Analysis (Predykcja ryzyka kredytowego)

## 📊 Opis projektu

Projekt analizuje dane klientów banku oraz buduje model predykcyjny,
który przewiduje, czy klient spłaci pożyczkę, czy istnieje ryzyko niewypłacalności.

Projekt łączy analizę danych, uczenie maszynowe oraz wizualizację w Power BI.

---

## 🎯 Cel projektu

Celem projektu jest:
- analiza zachowań finansowych klientów
- identyfikacja czynników wpływających na niespłacenie kredytu
- budowa modelu predykcyjnego ryzyka kredytowego
- prezentacja wyników w dashboardzie

---

## 🛠 Technologie

- Python (Pandas, NumPy, scikit-learn)
- Analiza danych
- Machine Learning
- Power BI (dashboard)
- Wizualizacja danych

---

## 📈 Zakres projektu

- czyszczenie i przygotowanie danych
- eksploracyjna analiza danych (EDA)
- selekcja zmiennych
- budowa modelu predykcyjnego (niespłacenie kredytu)
- wizualizacja wyników w Power BI

---

## 🧠 Model

Model przewiduje prawdopodobieństwo niespłacenia kredytu przez klienta
na podstawie danych historycznych.

Może być wykorzystany do:
- oceny ryzyka kredytowego
- wsparcia decyzji biznesowych
- identyfikacji klientów wysokiego ryzyka


## 📂 Struktura projektu


## 📸 Wizualizacje

### Dashboard Power BI

dashboard_credit_risk.png (Image: dashboard klientów banku z KPI i zadłużeniem)

Dashboard przedstawia analizę klientów banku, w tym:
- liczba klientów
- liczba spłaconych i niespłaconych pożyczek
- poziom zadłużenia
- procent klientów zalegających ze spłatą

Pozwala to na szybkie zrozumienie sytuacji finansowej klientów
oraz skali ryzyka kredytowego.

---

### 🧠 Model – ocena skuteczności

model_evaluation-Logistic Regression.png (Image: krzywa ROC i macierz pomyłek modelu)

Model predykcyjny przewiduje, czy klient spłaci pożyczkę.

Zastosowane metryki:
- krzywa ROC (AUC ≈ 0.62)
- macierz pomyłek
- accuracy, precision, recall

Wyniki wskazują, że model jest w stanie wykrywać część klientów zagrożonych niespłaceniem (recall ~53%),
jednak kosztem większej liczby fałszywych alarmów (niska precision).

Model może być użyteczny jako narzędzie wspierające decyzje,
ale wymaga dalszej optymalizacji.
