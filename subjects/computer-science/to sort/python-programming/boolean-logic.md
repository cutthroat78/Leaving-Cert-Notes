# Boolean Logic

Invented George Boole (Cork 19th Century)

Boolean was useless until the advent of computers

[Boolean Symbol](Boolean%20Lo%20062ae/Boolean%20Sy%20a82a7.csv)

## Boolean Logic Given

True or False

```python
true=True
print(true)
```

```python
Megan = 16
Cathal = 16
Iustina = 17
Matthew = 17
Aine = 35
print(Aine > Cathal)
print(Megan < Aine)
print(Matthew > Iustina)
print(Matthew >= Iustina)
print(Cathal != Megan)
```

---

event a

event b

## and

a and b

True + True = True

## or

a or b

True + False = True

False + True = True

## not

a and not b

True + False = True

b and not a

False + True = True

```python
Megan = 16
Cathal = 16
Iustina = 17
Matthew = 17
Aine = 35
one = (Cathal > Aine) #False
two = (Aine > Cathal) #this answer is True
three = (Matthew > Iustina) #False
four = (Matthew >= Iustina) #True

print(one and two)
print(two or three)
print(four and not two)
print(two and four)
print(two and not three)
print(one and two and three)
print(one or two or four)
print(three or not one)
```