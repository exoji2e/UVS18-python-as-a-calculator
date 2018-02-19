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

#### Skriv ut text från ditt program:
```python
>>> print(10)
10
```
@[1]
@[1-2]

---

Det mesta fungerar som förväntat

#### Matematiska operatorer:
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

#### Vi kan skapa variabler

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

#### Programmet "multiplicera input med 2."
```python
line = input()
x = int(line)
print(2*x)
```
@[1-2]
<!--
Vi vill typiskt inte räkna ut exakt samma sak varje gång vi kör vårt program.
Vi kan modifera vad vårt program för genom att ge det olika input.
-->

---

### Input och Output

#### Exekvering av programmet

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


