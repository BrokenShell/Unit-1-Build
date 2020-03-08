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
Not only did I build the dataset for this project, I also built all the tools used to build the dataset.


#### [MonsterFactory.py | Monster Generator](https://pypi.org/project/MonsterFactory/)
MonsterFactory.py is a small library for generating random monsters.
This is part of a larger project known as Dungeon Lib. Dungeon Lib can generate 
full career spanning campaign settings with dungeons, settlements and wilderness areas.


#### [Fortuna | Python RNG Toolkit](https://pypi.org/project/Fortuna/)
Fortuna is an abstraction toolkit for creating random generators in Python. Built on Storm.
- RandomValue: Higher-order random value generator.
- TruffleShuffle: Wide distribution generator.
- WeightedChoice: Programmable rarity.
- QuantumMonty: Predefined distributions.
- FlexCat: Multi-dimensional random value generator for matrices.


#### [Storm | C++ RNG Engine](https://github.com/BrokenShell/Storm)
Storm is a high performance random number engine based on the Mersenne Twister Algorithm. 
- Functional header-only, wrapper for the C++ random library.
- Hardware seeding only.
- Low level distribution functions.
