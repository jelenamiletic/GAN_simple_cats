<h1 align="center">GAN generisanje slika mačaka 🐱</h1>
Generativna adverzala mreza koja generise jednostavne crteze macaka zasnovanih na Google **Quick, Draw**! dataset-u. 

## Problem koji se resava
Generisanje novih crteza macaka iz odredjenog skupa podataka. 

## Nacin resavanja problema
Za resavanje ovog problema je koriscena Generativna adverzala mreza (GAN). Generativne adverzalne mreže se sastoje iz dve neuronske mreže koje se “takmiče” jedna sa drugom. Zbog toga se zovu adverzalne mreže. Prva mreža je generatorna koja pokušava da ulazni nasumični šum napravi što sličniji pravim podacima.

## Skup podataka koji se koristi
Na sledecem [linku](https://console.cloud.google.com/storage/quickdraw_dataset/full/numpy_bitmap) se moze naci skup podataka koji se koristi za treniranje.

## Biblioteke koje su koriscene 
- numpy
- tqdm 
- matplotlib
- scikit-learn
- keras
```
pip install numpy
pip install tqdm
pip install matplotlib
pip install -U scikit-learn
pip install keras
```
---
Prvo je potrebno instalirati biblioteke koriscenjem komande _pip_.
Ulaskom u lokalni direktorijum gde se nalazi main.py pokrenuti aplikaciju iz terminala uz pomoc komande:

```
python3 main.py
```
