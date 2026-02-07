# Coordinates

A SUBIT coordinate is a single 6‑bit address that can be read in three synchronized forms:

- binary address (six polarities)
- bigram address (WHO / WHERE / WHEN)
- trigram address (inner tension × outer color)

All three representations describe the same point in the SUBIT‑64 lattice.

---

## Binary Coordinates (6 bits)

Each element has a unique 6‑bit code:

b1 b2  |  b3 b4  |  b5 b6  
WHO    | WHERE   | WHEN

- first two bits — subject (ME / WE / YOU / THEY)  
- next two bits — direction (EAST / SOUTH / WEST / NORTH)  
- last two bits — season (SPRING / SUMMER / AUTUMN / WINTER)

---

## Bigram Coordinates (WHO / WHERE / WHEN)

Each bigram has four possible states:

10, 11, 01, 00

### WHO
10 = ME  
11 = WE  
01 = YOU  
00 = THEY  

### WHERE
10 = EAST  
11 = SOUTH  
01 = WEST  
00 = NORTH  

### WHEN
10 = SPRING  
11 = SUMMER  
01 = AUTUMN  
00 = WINTER  

SUBIT = 4 WHO × 4 WHERE × 4 WHEN = 64 coordinates

---

## Trigram Coordinates (inner × outer)

The same six bits can be read as two trigrams:

inner = b1 b3 b5  
outer = b2 b4 b6

### Inner (tension)
S, V, F, M, T, C, D, N

### Outer (color)
Bl, Gr, Lm, Yl, Or, Rd, Bg, Pu

A trigram coordinate is written as:

TensionColor  
(e.g., MOr, FBl, DPu)

---

## Unified Coordinate

A SUBIT coordinate is the intersection of all three readings:

Binary:   101011  
Bigram:   ME · EAST · SUMMER  
Trigram:  SOr

All three refer to the same archetype.

---

## Coordinate Space

The SUBIT space is simultaneously:

- a 6‑bit cube  
- a 3‑axis bigram grid  
- an 8×8 trigram crystal  

These structures are isomorphic.

---

## Examples

### Example 1
Binary:   000000  
Bigram:   THEY · NORTH · WINTER  
Trigram:  NBg

### Example 2
Binary:   101010  
Bigram:   ME · EAST · SPRING  
Trigram:  FLm

### Example 3
Binary:   110111  
Bigram:   WE · WEST · SUMMER  
Trigram:  TRd

---

## Summary

A SUBIT coordinate is:

- 6 bits  
- 3 bigrams  
- 2 trigrams  
- 1 archetype

It is a universal address in the SUBIT‑64 system, readable in three synchronized semantic languages.
