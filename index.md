# HEADER LEVEL 1

### HERE IS AN IMAGE OF A CAT FROM WIKIPEDIA
![WIKIPEDIA CAT IMAGE](https://upload.wikimedia.org/wikipedia/commons/1/15/Cat_August_2010-4.jpg)

### HERE IS CODE YOU SHOULD NOT RUN IN PYTHON:

```python
def numbers():
  with open("./numbers.txt", "r") as f:
    for i in range(100000):
      with open("./numbers.txt", "w") as ff:
        ff.write(f.read())
  return
```
