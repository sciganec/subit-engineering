# Mappings

SUBIT‑64 is a system of synchronized correspondences.  
Every element has three perfectly aligned identities:

- binary (6 bits)  
- bigram (WHO / WHERE / WHEN)  
- trigram (inner tension × outer color)

Mappings describe how these identities translate into one another.

---

## Binary → Bigram Mapping

The 6‑bit code splits into three bigrams:

b1 b2  |  b3 b4  |  b5 b6  
 WHO   | WHERE   | WHEN

### WHO mapping
10 → ME  
11 → WE  
01 → YOU  
00 → THEY  

### WHERE mapping
10 → EAST  
11 → SOUTH  
01 → WEST  
00 → NORTH  

### WHEN mapping
10 → SPRING  
11 → SUMMER  
01 → AUTUMN  
00 → WINTER  

This mapping defines the 4×4×4 subjectivity cube.

---

## Binary → Trigram Mapping

The same six bits can be read as two interleaved trigrams:

inner = b1 b3 b5  
outer = b2 b4 b6

### Inner (tension)
100 → S  
101 → V  
110 → F  
111 → M  
011 → T  
010 → C  
001 → D  
000 → N  

### Outer (color)
100 → Bl  
101 → Gr  
110 → Lm  
111 → Yl  
011 → Or  
010 → Rd  
001 → Bg  
000 → Pu  

This mapping defines the 8×8 SUBIT crystal.

---

## Bigram → Trigram Mapping

Each bigram triple (WHO, WHERE, WHEN) corresponds to a unique pair of trigrams.

### Example
WHO = ME = 10  
WHERE = EAST = 10  
WHEN = SPRING = 10  

Binary = 10 10 10  
Inner = 1 1 1 = M  
Outer = 0 0 0 = Pu  

Trigram = MPu

This mapping is bijective: every bigram triple has exactly one trigram pair.

---

## Trigram → Bigram Mapping

Given a trigram pair:

Inner = X  
Outer = Y  

Convert each trigram to its 3‑bit form, interleave the bits, and decode:

inner bits:  i1 i2 i3  
outer bits:  o1 o2 o3  

Binary = i1 o1  i2 o2  i3 o3  
Then decode WHO / WHERE / WHEN.

### Example
Tension = F = 110  
Color = Gr = 101  

Binary = 1 1  1 0  0 1 = 111001  
WHO = 11 = WE  
WHERE = 10 = EAST  
WHEN = 01 = AUTUMN  

Bigram = WE · EAST · AUTUMN

---

## Archetype Mapping (64‑element identity)

Each archetype has:

- 1 binary coordinate  
- 1 bigram coordinate  
- 1 trigram code  
- 1 canonical name  

### Example
Binary:   000000  
Bigram:   THEY · NORTH · WINTER  
Trigram:  NBg  
Name:     Dim  

These four identities always refer to the same element.

---

## Mapping Table Structure

A complete mapping table contains:

- binary → bigram  
- binary → trigram  
- trigram → name  
- bigram → name  

This produces a 64‑row canonical mapping.

---

## Summary

Mappings define the internal equivalence of SUBIT‑64:

- 6 bits ↔ 3 bigrams ↔ 2 trigrams ↔ 1 archetype  
- all transformations preserve identity  
- all coordinate systems are synchronized  

This is the core isomorphism that makes SUBIT a unified semantic lattice.
