# <p align="center"> MDP REPRESENTATION </p>

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.
  1. Text representation
  2. Graphical representation
  3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description:
The problem is to develop a Reinforcement Learning model for product detection in a manufacturing factory. The model should determine whether a product is ready to be exported or faulty based on its features. The goal is to optimize the production process and reduce the number of faulty products while maximizing the number of products ready for export.

### State Space:
{F,J,E} -> {0,1,2}

where,
- F -> Faulty
- J-Juction(decision making state)
- E -> Export

### Sample State:
Dimensions: (Length, Width, Height) = (10 cm, 5 cm, 2 cm).
Weight: 100 grams.
Color: Blue.

### Action Space:
{F,E} -> {0,1}
 where,
  "E->Export" ,
  "F->Mark as Faulty"

### Sample Action:
E-> 1<br>
product is ready for Export.

### Reward Function:
R = { +10 for correctly exporting a ready product,
-10 for exporting a faulty product}

### Graphical Representation:
![20240312_143623](https://github.com/Venkatigi/mdp-representation/assets/94154252/e201c4d7-462b-43c1-b1dc-7c48a44c2a38)

## PYTHON REPRESENTATION:
```
Name: Venkatesh E
Register Number: 212221230119
```

![Screenshot 2024-03-12 112409](https://github.com/Venkatigi/mdp-representation/assets/94154252/cc8b0ffa-e3a9-4055-9822-c4325708b6e4)

## OUTPUT:
![Screenshot 2024-03-12 112420](https://github.com/Venkatigi/mdp-representation/assets/94154252/cd6a7b51-f8c3-420a-bf0f-6be7af6d85c5)


## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.
  1. Text representation
  2. Graphical representation
  3. Python - Dictonary representation

