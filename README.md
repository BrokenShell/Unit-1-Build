# Data Pattern: Broken’s Angle
#### Principle Feature Focus Technique for Monstrous Data With a Peculiar Pattern
Lambda Data Science Unit 1 Build Project

-Robert Sharp, March 2020


<br>


## Research Question
**Is it possible to produce a tighter distribution of data by combining features with simple math?**
> TL;DR: Yes, but...


### [Monster Blog - Public View](https://sharpdesigndigital.com/monster-data/)
Public facing report with interactive graphs.


### [Monster Notebook - Academic View](https://colab.research.google.com/drive/1veaih8LUZ7zBbKixNUI2hAynqQpurAC9)
Academic details of the data and my findings.


## Monster Data Source
One million random monsters built with MonsterFactory.py -> 28MB CSV file.


#### [MonsterFactory.py | Python Monster Generator](https://pypi.org/project/MonsterFactory/)
MonsterFactory.py is a small library for generating random monsters.
This is part of a larger project known as Dungeon Lib. Dungeon Lib can generate a
full career spanning campaign setting with dungeons, settlements and wilderness areas.
Built on Fortuna.


#### [Fortuna | Cython RNG Toolkit](https://pypi.org/project/Fortuna/)
Fortuna features a collection of abstractions for creating custom random generators in Python. Built on Storm.
- RandomValue: Higher-order random value generator.
- TruffleShuffle: Wide distribution generator.
- WeightedChoice: Programmable rarity.
- QuantumMonty: Collection of predefined distributions.
- FlexCat: Multi-dimensional random value generator for matrices.


#### [Storm | C++ RNG Engine](https://github.com/BrokenShell/Storm)
Storm is a high performance random number engine based a custom implementation of the Mersenne Twister Algorithm. 
- Functional style header-only wrapper for the C++ random library.
- Low level distributions.
