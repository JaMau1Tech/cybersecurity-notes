# Data Representation Notes

## Objective

Understand how computers represent colors and numbers using binary and hexadecimal notation.

---

# Colors

Computers create colors using RGB.

RGB consists of:

- Red
- Green
- Blue

Each color channel uses:

- 8 bits
- 1 byte

Total:

```
24 bits
```

This allows:

```
16,777,216 colors
```

---

# Binary

Computers only understand:

```
0
1
```

Each position represents a power of two.

|Bit|Value|
|---|---|
|7|128|
|6|64|
|5|32|
|4|16|
|3|8|
|2|4|
|1|2|
|0|1|

Example:

```
11001010

128
64
  8
  2

= 202
```

---

# Decimal

Humans use Base-10.

Computers use Base-2.

Binary values increase using powers of two.

---

# Hexadecimal

Hexadecimal uses Base-16.

Digits:

```
0-9

A
B
C
D
E
F
```

Example:

```
FF

=

11111111
```

Each hexadecimal digit represents:

```
4 bits
```

---

# RGB Hex Colors

Example:

```
#3BC81E
```

Each pair represents one color channel.

```
3B

C8

1E
```

Red

Green

Blue

---

# Key Takeaways

- Computers store everything as binary.
- Binary uses powers of two.
- Hexadecimal simplifies binary.
- RGB colors use 24 bits.
- Every hexadecimal digit equals four binary bits.