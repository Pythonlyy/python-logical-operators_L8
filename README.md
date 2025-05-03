# 🧠 Logical Operators in Python

Logical operators let you combine multiple conditions using `and`, `or`, and `not`.
These always return `True` or `False` and are used often in decision-making with `if` statements.

---

## 💡 Logical Operators

| Operator | Meaning                          | Example         | Result  |
| -------- | -------------------------------- | --------------- | ------- |
| `and`    | True if both conditions are true | `True and True` | `True`  |
| `or`     | True if at least one is true     | `True or False` | `True`  |
| `not`    | Flips the result                 | `not True`      | `False` |

---

## 💻 Example with Explanation

```python
is_raining = True
has_umbrella = False

print(is_raining and has_umbrella)   # False
print(is_raining or has_umbrella)    # True
print(not is_raining)                # False
```

### 🔈 Output

```
False
True
False
```

---

### 📌 Key Notes

* Use `and` when **both** things must be true
* Use `or` when **at least one** thing should be true
* Use `not` to **reverse** a condition (True → False)

These are commonly used inside `if` statements:

```python
if is_raining and has_umbrella:
    print("You’ll stay dry!")
else:
    print("Uh oh. Wet socks.")
```

---

## 🧪 Try It Yourself

```python
sunny = True
warm = False

print("Go outside?", sunny and warm)
print("Maybe go outside?", sunny or warm)
print("Is it not sunny?", not sunny)
```

### 🔈 Expected Output

```
Go outside? False
Maybe go outside? True
Is it not sunny? False
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **@Pythonly** for more.

---


