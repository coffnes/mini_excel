# mini_excel

The idea is to implement a program that can accept a csv file that looks like this:
```CSV
A,      B
1,      2
3,      4
=A1+B1, =A2+B2
```

And outputs:
```CSV
A,      B
1,      2
3,      4
3,      7
```

Basically a simple Excel engine without UI