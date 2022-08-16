# Inputs

Sometimes we need information from a user

input → program → output

## Code using input()

```python
print("What is your name?") # Question on terminal
name = input() # Defines the input
print("Good Morning",name,"What is your PPS number?")
```

"Good Morning",name,"What is your PPS number?"

Orange = Print

Green = Called variable made from input

## Same Program as Above but Shorted

```python
name = input("What is your name?") # Defines the input
print("Good Morning",name,"What is your PPS number?")
```

---

Python always assumes strings, when it comes to input()

## How to convert an input to integer

```python
age = int(input("What is your age?"))
print("I am",age,"years old")
```