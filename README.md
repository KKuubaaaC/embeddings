# my-project-embeddings

Projekt zbudowany z użyciem [uv](https://docs.astral.sh/uv/).

## Środowisko

- Python: 3.13 (z `.python-version`)
- Menadżer pakietów: uv

## Komendy

```bash
# Aktywacja venv (opcjonalnie – uv run używa go automatycznie)
source .venv/bin/activate   # macOS/Linux

# Instalacja zależności / tworzenie venv
uv sync

# Dodawanie zależności
uv add <pakiet>
uv add --dev <pakiet>   # zależności deweloperskie

# Uruchomienie skryptu
uv run python main.py
# lub
uv run main.py
```

## Struktura

- `main.py` – punkt wejścia
- `pyproject.toml` – konfiguracja projektu i zależności
- `uv.lock` – zablokowane wersje (po `uv sync`)
