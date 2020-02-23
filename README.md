# Demo z 2 spotkania PyData Bydgoszcz - Python współbieżnie (Paweł Kmiecik) - 18.02.2020

## Przygotowanie
Sklonuj to repozytorium.
```
virtualenv -p python3 pydata_concurrent
source pydata_concurrent/bin/activate```
następnie w katalogu repozytorium:
```
pip install -r requirements.txt
```
## Praca z demo

Upewnij się, że wirtualne środowisko pydata_concurrent jest aktywne
Poszczególne dema uruchamiaj komendami:
```
python -m io_bound.demo_sequential
python -m io_bound.demo_futures_threads
python -m io_bound.demo_asyncio
python -m cpu_bound.demo_process_pool
python -m cpu_bound.demo_sequential
``` 
