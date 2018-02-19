@title[Python som miniräknare]
## Python som miniräknare
#### Måns Magnusson UVS progläger 2018

---

#### Hur kör man sin pythonkod?

- python i terminalen
- [repl.it](http://repl.it)
- I en IDE (pycharm eller IDLE)

---

Det mesta fungerar som förväntat

### Skriv ut text och tal från ditt program:
```python
>>> print("hejsan")
hejsan
>>> print("10")
10
>>> print(10)
10
```
@[1]
@[1-2]
@[1-4]
@[1-6]

---

Men vissa saker kan vara lite förvirrande

### Text och tal fungerar olika
```python
>>> print(1 + 1)
2
>>> print("hejsan" + "hoppsan")
hejsanhoppsan
>>> print("1" + "1")
11
```
@[1-2]
@[1-3]
@[1-4]
@[1-5]
@[1-6]

---

Det mesta fungerar som förväntat

### Matematiska operatorer:
```python
>>> print(1 + 2)
3
>>> print(5 - 3)
2
>>> print(3 * 2)
6
>>> print(3 / 2)
1.5
>>> print(3 // 2)
1
>>> print(9 ** 2)
81
```
@[1-2]
@[1-4]
@[1-6]
@[1-8]
@[1-10]
@[1-12]

---

### Vi kan skapa variabler

```python
>>> x = 10
>>> y = 5
>>> print(x + y)
15
```
@[1]
@[1-2]
@[1-4]

---

### Input och Output

---

### Programmet "eko"
```python
line = input()
print(line)
```

---

### Exekvering av eko
```python
>>> line = input()
Hejsan
>>> print(line)
Hejsan
```
@[1]
@[1-2]
@[1-4]

---

#### Programmet "multiplicera input med 2."
```python
line = input()
x = int(line)
print(2*x)
```

---


#### Exekvera multiplicera med 2

```python
>>> line = input()
3
>>> x = int(line)
>>> print(2*x)
6
```
@[1]
@[1-2]
@[1-3]
@[1-5]


