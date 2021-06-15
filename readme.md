# CS50’s Introduction to Artificial Intelligence with Python
# Project 2: Uncertainty: Heredity

Aim: Write an AI to assess the likelihood that a person will have a particular genetic trait.

Description: Mutated versions of the GJB2 gene are one of the leading causes of hearing impairment in newborns. 
Each person carries two versions of the gene, so each person has the potential to possess either 0, 1, or 2 copies 
of the hearing impairment version GJB2. Unless a person undergoes genetic testing, though, it’s not so easy to 
know how many copies of mutated GJB2 a person has. This program will calculate the probabily of the children inheriting
the trait given the trait status on their family.

See full description here: https://cs50.harvard.edu/ai/2020/projects/2/heredity/

Usage: python heredity.py [data.csv]

```
Example:
$ python heredity.py data/family0.csv
Harry:
  Gene:
    2: 0.0092
    1: 0.4557
    0: 0.5351
  Trait:
    True: 0.2665
    False: 0.7335
James:
  Gene:
    2: 0.1976
    1: 0.5106
    0: 0.2918
  Trait:
    True: 1.0000
    False: 0.0000
Lily:
  Gene:
    2: 0.0036
    1: 0.0136
    0: 0.9827
  Trait:
    True: 0.0000
    False: 1.0000
```
