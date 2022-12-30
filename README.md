Rotation of 3D solid in gnuplot
-

**Build**: 
```
mkdir build
cmake -S . -B build
cmake --build build -t Rotacja3D
```

**run**: `./build/Rotacja3D {.dat file}` 

**example**: 
```
./build/Rotacja3D pr1.dat pr5.dat
c
Twoj wybor? (m - menu):**o**
Podaj sekwencje oznaczen osi oraz katy obrotu w stopniach: **x 90 y 270 .**
Podaj ilosc powtorzen podanej powyzej sekwencji: **1**
Podaj numer figury ktora chcesz obrocic:**1**

Twoj wybor? (m - menu): **p 50 0 0**
Podaj numer figury ktora chcesz obrocic:**2**

Twoj wybor? (m - menu): **k**
```

Ten program mozna uruchomic tylko w srodowisku sytemu Linux lub Unix.
Wymaga wczesniejszej instalacji programu gnuplot.
Program gnuplot dostepny jest w standardowych pakietach kazdej
dystrybucji Linuksa.
