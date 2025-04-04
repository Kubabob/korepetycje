# Projekt 1

Ten projekt będzie podzielony na parę zajęć i na razie będzie obejmował następujące zagadnienia. Z czasem zagadnienia się rozszerzą.

- Ustawienie środowiska jupyter notebook w vs code: https://code.visualstudio.com/docs/datascience/jupyter-notebooks
- Tworzenie struktury projektu przy pomocy [uv](https://docs.astral.sh/uv/getting-started/)
- Tworzenie plików markdown(.md) jako opisów projektu
- Preprocessing danych przy użyciu bibliotek Pandas i Numpy

## Instrukcja

1. uv

- Zainstalować [uv](https://docs.astral.sh/uv/getting-started/)
- Ustawić Python'a w wersji >= 3.12
- Wejść do folderu z korepetycjami
- Użyc komendy do zainstalowania wymaganych bibliotek
```bash 
uv sync 
```
- Zapoznać się z pojęciami z [strony](https://docs.astral.sh/uv/concepts/) dotyczącymi tworzenia projektów z uv

2. Markdown

- Zapoznać się z działaniem [markdown](https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796)
- Stworzyć template do projektu na wzór np. [tego](https://github.com/othneildrew/Best-README-Template); Na razie nie będzie dużo informacji ale warto zacząć

3. Preprocessing danych

- Sprawdzić podstawowe statystyki zbioru danych
- Oczyścić dane z NaN i Null jeśli istnieją
- Usunąć kolumny dla których odchylenie standardowe jest równe 0; Są to kolumny nieinformatywne
- Znormalizować zbiór danych
- Identyfikować i obsługiwać wartości odstające (outliers) np. według reguły 3 sigm

