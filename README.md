# Embedded Study

[English version](./README.en.md)

Este repositorio es mi espacio para estudiar sistemas embebidos con calma, ir guardando recursos y dejar por escrito lo que voy aprendiendo en el camino.

No quiero llevar este proceso con prisa ni saltandome bases. La idea es aprender bien, entender de verdad lo que estoy viendo y poco a poco ir construyendo una base solida.

## Que quiero hacer aqui

Quiero usar este repo como una especie de bitacora de estudio. Aqui voy a ir juntando:

- libros y recursos
- notas
- ejemplos
- practicas
- cosas que me parezcan importantes para revisar despues

## Recursos

### C

- [C Programming Absolute Beginner's Guide](./C/C_Programming_Absolute_Beginner%E2%80%99s_Guide_by_Greg_Perry_Dean_Miller.pdf)

  Este es el recurso que voy a usar ahora para C. Me parece mejor punto de partida para llevar el aprendizaje con mas orden y desde una base mas clara, asi que por ahora este sera el libro principal que voy a seguir.

## Notas del camino

- Me instale GCC para poder empezar a compilar ejemplos de C desde la terminal.
- La version que instale fue `gcc 15.2.0`.
- Lo instale usando `winget`, con el paquete `BrechtSanders.WinLibs.POSIX.UCRT`.
- Construí mi primer "Hola mundo". Tenia que hacerlo; es casi un ritual entre programadores. Aunque ya sepa programar en otros lenguajes, esto se siente como un nuevo comienzo con C y ese ritual no se podia saltar.
- Para compilar uno de los ejemplos use este comando:

```bash
gcc -std=c2x -Wall -lm -o getting-started getting-started.c
```

## Estado actual

Voy empezando y por ahora estoy organizando recursos y definiendo como quiero llevar el estudio.
