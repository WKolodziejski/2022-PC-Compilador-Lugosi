## Preparar
```
mkdir build && cd build
```

## Compilar
Precisa do Java 17
```
javacc ../Lugosi.jj && javac *.java
```

## Executar
```
java Lugosi <file.lug> && java.c <file.java> && java <file>
```

## Exemplos
Ex1: calcula o fibonacci de n iterativa e recursivamente e verifica se ambos são iguais

Ex2: calcula o fatorial de n recursivamente
