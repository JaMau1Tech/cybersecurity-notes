# TryHackMe - Data Encoding

## Room Information

| Item | Value |
|------|-------|
| Platform | TryHackMe |
| Module | Software Basics |
| Room | Data Encoding |
| Difficulty | Easy |
| Status | Completed |

---

## Objective

Learn how computers encode text using ASCII and Unicode while understanding how UTF encodings store Unicode characters.

---

## Topics Covered

- Character Encoding
- ASCII
- Extended ASCII
- Unicode
- UTF-8
- UTF-16
- UTF-32
- Emoji Encoding

---

## Key Concepts

### Character Encoding

Character encoding maps numeric values to readable characters so computers can store and display text.

---

### ASCII

- Created in 1963
- Supports 128 characters
- Designed for English text
- Uses 7-bit values

Examples:

```
65 = A
97 = a
48 = 0
```

---

### Unicode

Unicode provides a universal character set capable of representing virtually every written language along with symbols and emojis.

Examples:

```
U+0041 = A
U+03A9 = Ω
U+3042 = あ
U+1F60A = 😊
```

---

### UTF Encoding

UTF specifies how Unicode characters are stored.

#### UTF-8

- Variable length
- 1–4 bytes
- Web standard
- Backward compatible with ASCII

#### UTF-16

- Uses 2–4 bytes
- Common on Windows

#### UTF-32

- Fixed 4-byte encoding
- Simplest representation
- Uses the most memory

---

## Skills Learned

- Character encoding fundamentals
- ASCII lookup
- Unicode code points
- UTF encoding formats
- Text compatibility
- Understanding encoding mismatches

---

## Files

```
README.md
task-notes.md
images/
```