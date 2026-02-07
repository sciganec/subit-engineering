# Coordinates

SUBIT‑координата — це єдина 6‑бітна адреса, яку можна читати у трьох синхронних формах:

- **бінарна адреса** (6 полярностей)
- **біграмна адреса** (WHO / WHERE / WHEN)
- **триграмна адреса** (inner tension × outer color)

Усі три форми описують один і той самий стан у SUBIT‑64.

---

## Binary Coordinates (6 bits)

Кожен елемент SUBIT має унікальний 6‑бітний код:

```
b1 b2  |  b3 b4  |  b5 b6
 WHO   | WHERE   | WHEN
```

- перші два біти — суб’єкт (ME / WE / YOU / THEY)
- наступні два — напрям (EAST / SOUTH / WEST / NORTH)
- останні два — сезон (SPRING / SUMMER / AUTUMN / WINTER)

---

## Bigram Coordinates (WHO / WHERE / WHEN)

Кожен біграм має 4 можливі стани:

```
10, 11, 01, 00
```

Відповідності:

### WHO
- 10 = ME  
- 11 = WE  
- 01 = YOU  
- 00 = THEY  

### WHERE
- 10 = EAST  
- 11 = SOUTH  
- 01 = WEST  
- 00 = NORTH  

### WHEN
- 10 = SPRING  
- 11 = SUMMER  
- 01 = AUTUMN  
- 00 = WINTER  

Таким чином:

```
SUBIT = {4 WHO} × {4 WHERE} × {4 WHEN} = 64 координати
```

---

## Trigram Coordinates (inner × outer)

Ті самі 6 біт можна читати як дві триграми:

```
inner = b1 b3 b5
outer = b2 b4 b6
```

### Inner (tension)
S, V, F, M, T, C, D, N

### Outer (color)
Bl, Gr, Lm, Yl, Or, Rd, Bg, Pu

Кожна координата має вигляд:

```
TensionColor  (наприклад: MOr, FBl, DPu)
```

---

## Unified Coordinate

SUBIT‑координата — це три одночасні читання:

```
Binary:   101011
Bigram:   ME · EAST · SUMMER
Trigram:  SOr
```

Усі три записи — це один і той самий елемент SUBIT‑64.

---

## Coordinate Space

SUBIT‑простір — це:

- 6‑бітний куб  
- 3‑вимірна решітка біграмів  
- 8×8 кристал триграм  

Усі три структури ізоморфні.

---

## Examples

### Example 1
```
Binary:   000000
Bigram:   THEY · NORTH · WINTER
Trigram:  NBg
```

### Example 2
```
Binary:   101010
Bigram:   ME · EAST · SPRING
Trigram:  FLm
```

### Example 3
```
Binary:   110111
Bigram:   WE · WEST · SUMMER
Trigram:  TRd
```

---

## Summary

SUBIT‑координата — це:

- **6 біт**  
- **3 біграми**  
- **2 триграми**  
- **1 архетип**

Це універсальна адреса у SUBIT‑64, яку можна читати у трьох формах без втрати інформації.
