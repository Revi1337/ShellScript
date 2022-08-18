#  Pack (Packing Data Utility)

## Usage
```bash
$pack
./Usage STRINGS [MODE] [ARCH]

[MODE]
--little : data sort with little-endian (DEFUALT)
--big    : data sort with big-endian

[ARCH]
--64 : pack data 64bit (DEFAULT)
--32 : pack data 32bit
```

<br>
<br>

## OUTPUT

```bash
$pack howto?
INPUT
howto?

FORMAT
64bit Little-Endian

OUTPUT
0x3f6f74776f68
```

```bash
$pack howto? --big
INPUT
howto?

FORMAT
64bit Big-Endian

OUTPUT
0x686f77746f3f
```

