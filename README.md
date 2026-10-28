# Sensor Anomaly Detection

Projekt poświęcony wykrywaniu anomalii w danych czasowych z czujników zamontowanych na ramieniu robotycznym.

## Dane

W projekcie wykorzystano zbiór danych IMAD-DS, zawierający odczyty z trzech rodzajów sensorów:

- Akcelerometr (ACC) — pomiary przyspieszenia wzdłuż trzech osi.
- Żyroskop (GYRO) — pomiary prędkości kątowej wzdłuż trzech osi.
- Mikrofon (MIC) — sygnał akustyczny.

## Zakres projektu

- Wczytywanie i przygotowanie danych - wczytanie danych z plików Parquet oraz metadanych z plików CSV,
- Przetwarzanie sygnałów - podział sygnału na okna czasowe i zastosowanie filtrów dolnoprzepustowych,
- Trening modelu Isolation Forest do wykrywania anomalii oraz dobór jego hiperparametrów,
- Ewaluacja - ocena skuteczności modelu w wykrywaniu anomalii,
- Notebook z eksploracyjną analizą danych.

## Dalsze plany

Implementacja LSTM Autoencodera do wykrywania anomalii oraz zestawienie wyników LSTM Autoencodera z modelem Isolation Forest.
