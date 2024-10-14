# **Mathematical Operators in Python and C#**

### Arithmetic Operators
- `+` : Addition (Python ✅, C# ✅)
- `-` : Subtraction (Python ✅, C# ✅)
- `*` : Multiplication (Python ✅, C# ✅)
- `/` : Division (floating-point result) (Python ✅, C# ✅)
- `//` : Floor division (Python ✅, C# 🚫)
- `%` : Modulus (Python ✅, C# ✅)
- `**` : Exponentiation (Python ✅, C# 🚫 — Use `Math.Pow()` in C#)
- `^` : Bitwise XOR in both; for exponentiation in C#, use `Math.Pow()`

### Comparison Operators
- `==` : Equality (Python ✅, C# ✅)
- `!=` : Inequality (Python ✅, C# ✅)
- `<` : Less than (Python ✅, C# ✅)
- `<=` : Less than or equal to (Python ✅, C# ✅)
- `>` : Greater than (Python ✅, C# ✅)
- `>=` : Greater than or equal to (Python ✅, C# ✅)

### Assignment Operators
- `=` : Assigns a value to a variable (Python ✅, C# ✅)
- `+=` : Adds and assigns (Python ✅, C# ✅)
- `-=` : Subtracts and assigns (Python ✅, C# ✅)
- `*=` : Multiplies and assigns (Python ✅, C# ✅)
- `/=` : Divides and assigns (Python ✅, C# ✅)
- `//=` : Floor division and assigns (Python ✅, C# 🚫)
- `**=` : Exponentiation and assigns (Python ✅, C# 🚫)
- `%=` : Modulus and assigns (Python ✅, C# ✅)

### Logical Operators
- `and` : Logical AND (Python ✅, C# use `&&`)
- `or` : Logical OR (Python ✅, C# use `||`)
- `not` : Logical NOT (Python ✅, C# use `!`)
- `&&` : Logical AND in C# (Python 🚫, C# ✅)
- `||` : Logical OR in C# (Python 🚫, C# ✅)
- `!` : Logical NOT in C# (Python 🚫, C# ✅)

### Bitwise Operators
- `&` : Bitwise AND (Python ✅, C# ✅)
- `|` : Bitwise OR (Python ✅, C# ✅)
- `^` : Bitwise XOR (Python ✅, C# ✅)
- `~` : Bitwise NOT (Python ✅, C# ✅)
- `<<` : Bitwise left shift (Python ✅, C# ✅)
- `>>` : Bitwise right shift (Python ✅, C# ✅)

### Python-Only Operators
- `is` : Checks if two variables point to the same object
- `is not` : Checks if two variables point to different objects
- `in` : Checks if a value is present in a sequence
- `not in` : Checks if a value is not in a sequence

### Special Operators in C# (not in Python)
- **Null-coalescing operator** (`??`): Returns the left-hand operand if it’s not null; otherwise, returns the right operand.
  ```csharp
  string name = null;
  string displayName = name ?? "Guest";  // Returns "Guest"
```
