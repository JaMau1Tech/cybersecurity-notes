# Data Encoding Notes

## Objective

Understand how computers represent text using character encoding standards.

---

# Character Encoding

Encoding maps numbers to readable characters.

Computers store numbers.

Encoding tells the computer which character each number represents.

---

# ASCII

ASCII stands for:

American Standard Code for Information Interchange

Features:

- Created in 1963
- Uses 7 bits
- Supports 128 characters
- English letters
- Numbers
- Punctuation
- Control characters

Examples:

```
65 = A
66 = B
97 = a
48 = 0
```

Limitations:

- English only
- No emojis
- No Asian languages
- Limited special characters

---

# Unicode

Unicode solves the limitations of ASCII.

Every character receives a unique code point.

Examples:

```
U+0041 = A

U+03A9 = Ω

U+3042 = あ

U+1F60A = 😊
```

Unicode supports:

- All major languages
- Symbols
- Emojis
- Historical writing systems

---

# UTF Formats

UTF defines how Unicode characters are stored.

## UTF-8

- 1–4 bytes
- Most efficient
- Web standard
- ASCII compatible

---

## UTF-16

- 2–4 bytes
- Common on Windows

---

## UTF-32

- Always 4 bytes
- Simplest format
- Highest memory usage

---

# Comparison

ASCII

↓

English only

↓

Unicode

↓

Universal character set

↓

UTF

↓

Storage format

UTF-8
UTF-16
UTF-32

---

# Key Takeaways

- Computers store characters as numbers.
- Encodings map numbers to characters.
- ASCII supports English text only.
- Unicode supports nearly every written language.
- UTF defines how Unicode is stored.
- UTF-8 is the most common encoding on modern systems.