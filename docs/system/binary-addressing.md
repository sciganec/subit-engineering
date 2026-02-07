# Binary Addressing

Binary addressing in SUBIT defines the 6‑bit coordinate that encodes subjectivity.  
Every semantic act receives a unique binary signature composed of three bigrams:

- WHO (2 bits)  
- WHERE (2 bits)  
- WHEN (2 bits)

This creates 64 possible subjectivity states, each combinable with any of the 64 semantic elements.

---

## Structure of the 6‑bit Address

The binary address is always ordered as:

- bits 1–2 → WHO  
- bits 3–4 → WHERE  
- bits 5–6 → WHEN  

Example:  
`10 01 11` → WHO=ME, WHERE=WEST, WHEN=SUMMER

---

## WHO Bigram (2 bits)

Represents the subject perspective.

| Bits | WHO  |
|------|------|
| 10   | ME   |
| 01   | YOU  |
| 11   | WE   |
| 00   | THEY |

WHO defines who is the center of the semantic frame.

---

## WHERE Bigram (2 bits)

Represents spatial orientation.

| Bits | WHERE |
|------|--------|
| 10   | EAST   |
| 11   | SOUTH  |
| 01   | WEST   |
| 00   | NORTH  |

WHERE defines the directional stance of the semantic act.

---

## WHEN Bigram (2 bits)

Represents temporal mode.

| Bits | WHEN   |
|------|---------|
| 10   | SPRING  |
| 11   | SUMMER  |
| 01   | AUTUMN  |
| 00   | WINTER  |

WHEN defines the temporal setting of the semantic act.

---

## Subjectivity Coordinate

A subjectivity coordinate is the decoded form of the 6‑bit address.  
It specifies:

- WHO (perspective)  
- WHERE (orientation)  
- WHEN (temporal mode)

Example:

Binary: `11 10 00`  
Decoded: WE / EAST / WINTER

This coordinate can be attached to any SUBIT‑64 element (inner tension + outer color), producing a fully specified semantic state.

---

## Role in the SUBIT System

Binary addressing provides:

- a finite set of 64 subjectivity states  
- a universal encoding for semantic context  
- a stable coordinate layer beneath all semantic elements  
- compatibility with computational and symbolic systems  

Together with SUBIT‑8 (valences) and SUBIT‑64 (archetypes), binary addressing completes the semantic coordinate system used in Semantic Engineering.
