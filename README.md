# AI_Workshop

# Autorzy

- Kacper Cygan (@decan33)
- Krzysztof Klimczyk (@bxo11)
- Krzysztof Kubit (@KrzQbt)

## Klasyfikacja materiałów jako izolator, ~~półprzewodnik~~, lub przewodnik bez użycia cechy "band gap"

### Realizacja Celów Projektowych

1. **Definicja Celów Projektu**  
    Głównym celem tego projektu jest stworzenie modelu sztucznej inteligencji, który może przewidywać, czy dany materiał jest izolatorem, półprzewodnikiem, czy przewodnikiem na podstawie dostępnych danych strukturalnych i chemicznych, bez bezpośredniego uwzględnienia wartości przerwy energetycznej (band gap). Celem jest przyspieszenie procesu identyfikacji właściwości materiałów.

2. **Określenie Wskaźników Sukcesu**  
    - Dokładność modelu w klasyfikowaniu materiałów jako izolatory, półprzewodniki lub przewodniki.  
    - Zdolność modelu do generalizacji na materiały nieobecne w danych treningowych.

3. **Wyznaczenie Zakresu Projektu**  
   - Zbieranie i przygotowanie danych z Materials Project.  
   - Rozwój i trening modelu AI do przewidywania właściwości materiałów.  
   - Walidacja i testowanie modelu na niezależnym zbiorze danych.  
   - Optymalizacja modelu dla lepszej wydajności i dokładności.

4. **Określenie Korzyści z Realizacji**  
   - Przyspieszenie charakteryzacji nowych materiałów.  
   - Zmniejszenie potrzeby eksperymentów fizycznych dzięki wstępnym przewidywaniom AI.
  
### Użyte technologie

- Python
- `pandas`
- `matplotlib`
- `sklearn`
- TBA

### Obejrzenie danych oraz ustalenie celow projektowych
1. Sposób użycia danych będzie polegał na sprecyzowaniu wzoru chemicznego "composition" na podstawie którego model określi band gap materiału.
2. Z istniejących rozwiązań dostępnych jest niewiele prostych przykładów, które określają band gap na podstawie struktury materiału. Poza tym istnieje narzędzie "automatminer" - https://hackingmaterials.lbl.gov/automatminer/, które automatycznie dobiera cechy i tworzy model uczenia maszynowego do określania wybranej cechy.


   

# Zbiór danych

https://next-gen.materialsproject.org/
