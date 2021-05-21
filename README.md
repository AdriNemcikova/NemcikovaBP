# NemcikovaBP
Metódy hlbokého učenia pre analýzu dát z oblasti zákrytových premenných hviezd

Úloha je rozdelená do viacerých skriptov, a to:
  1. vizualizácia syntetických a observačných svetelných kriviek - skript data_visualization.ipynb
  2. morfologická klasifikácia kriviek za použitia 1D CNN architektúry; model trénovaný na 1. datasete syntetických kriviek, vyhodnotený na observačných krivkách -     skript 1DCNN_allCurves.ipynb
  3. morfologická klasifikácia kriviek za použitia 1D CNN architektúry; model trénovaný na 2. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript 1DCNN_NoSpottyCurves.ipynb
  4. morfologická klasifikácia kriviek za použitia LSTM architektúry; model trénovaný na 1. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript LSTM_allCurves.ipynb
  5. morfologická klasifikácia kriviek za použitia LSTM architektúry; model trénovaný na 2. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript LSTM_NoSpottyCurves.ipynb
  6. morfologická klasifikácia kriviek za použitia GRU architektúry; model trénovaný na 1. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript GRU_allCurves.ipynb
  7. morfologická klasifikácia kriviek za použitia GRU architektúry; model trénovaný na 2. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript GRU_NoSpottyCurves.ipynb
  8. morfologická klasifikácia kriviek za použitia 1D CNN + LSTM architektúry; model trénovaný na 1. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript 1DCNN_LSTM_allCurves.ipynb
  9. morfologická klasifikácia kriviek za použitia 1D CNN + LSTM architektúry; model trénovaný na 2. datasete syntetických kriviek, vyhodnotený na observačných krivkách - skript 1DCNN_LSTM_NoSpottyCurves.ipynb
  10. klasifikácia oddelených kriviek na základe škvrnitosti za použitia 1D CNN architektúry; model trénovaný na 3. datasete syntetických kriviek, vyhodnotený na syntetických krivkách - skript 1DCNN_detachedCurves.ipynb
  11. klasifikácia dotykových kriviek na základe škvrnitosti za použitia 1D CNN architektúry; model trénovaný na 4. datasete syntetických kriviek, vyhodnotený na syntetických krivkách - skript 1DCNN_overcontactCurves.ipynb
  12. hierarchická klasifikácia dotykových kriviek za použitia modelov natrénovaných v skriptoch 8., 10. a 11.; vyhodnotená na syntetických krivkách - skript Spotty_Classification.ipynb
  13. viactriedna klasifikácia dotykových kriviek za použitia 1D CNN + LSTM ar-chitektúry; model trénovaný na upravenom 1. datasete syntetických kriviek,vyhodnotený na syntetických krivkách - skript Multiclass_model.ipynb

Dataset **syntetických** kriviek: https://mega.nz/file/jYxVWQgK#FVfqyz57jNGxHOPG6XI3PXyohjLsJDZ_9lDqHJ-AMkg

Dataset **observačných** kriviek: observed_lc.csv

Adriana Nemcikova, Bakalarska praca, HI, KKUI, FEI TUKE
