# SUBIT‑3 Bigrams

SUBIT‑3 defines the three binary bigrams that encode subjectivity in the SUBIT semantic system. Each bigram represents a fundamental axis of situational meaning: WHO, WHERE, and WHEN. Together they form a 6‑bit coordinate that situates every semantic act within a discrete subjectivity state.

---

## Structure of SUBIT‑3

SUBIT‑3 consists of three independent 2‑bit bigrams:

- WHO — subject perspective  
- WHERE — spatial orientation  
- WHEN — temporal mode  

Each bigram has four possible states, producing 4 × 4 × 4 = 64 subjectivity coordinates.

---

## Binary Encoding

Each bigram is encoded as a 2‑bit pair:

- **10**  
- **11**  
- **01**  
- **00**

These four states map to the four modes of each axis.

The full 6‑bit address is structured as:

- bits 1–2: WHO  
- bits 3–4: WHERE  
- bits 5–6: WHEN  

Example:  
**10 01 11** → WHO=ME, WHERE=WEST, WHEN=SUMMER

---

## WHO Bigram

Represents the subject perspective of the semantic act.

| Bits | WHO  |
|------|------|
| 10   | ME   |
| 11   | WE   |
| 01   | YOU  |
| 00   | THEY |

WHO defines **who** is the center of the semantic frame.

---

## WHERE Bigram

Represents the spatial orientation of the semantic act.

| Bits | WHERE |
|------|--------|
| 10   | EAST   |
| 11   | SOUTH  |
| 01   | WEST   |
| 00   | NORTH  |

WHERE defines **where** the semantic act is oriented.

---

## WHEN Bigram

Represents the temporal mode of the semantic act.

| Bits | WHEN   |
|------|---------|
| 10   | SPRING  |
| 11   | SUMMER  |
| 01   | AUTUMN  |
| 00   | WINTER  |

WHEN defines **when** the semantic act is situated.

---

## Subjectivity Coordinate

A subjectivity coordinate is the combination of:

- WHO (2 bits)  
- WHERE (2 bits)  
- WHEN (2 bits)  

Example:

- Binary: **11 10 00**  
- WHO = WE  
- WHERE = EAST  
- WHEN = WINTER  

This coordinate can be attached to any semantic element (inner tension + outer color), producing a fully specified semantic state.

---

## Role in SUBIT

SUBIT‑3 provides:

- the subjectivity layer of the semantic lattice  
- the binary addressing scheme for all 64 elements  
- the situational context for semantic operations  

Together with SUBIT‑8 (valences) and SUBIT‑64 (elements), SUBIT‑3 completes the coordinate system of Semantic Engineering.
