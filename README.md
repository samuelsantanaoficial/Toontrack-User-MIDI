# EZbass User MIDI
## Exemplo de código

```
ChordList {
    Chord {
        Note 0 0 0 
        Time 0 4 
        ChordParts
    }
}
```

### Como usar

* Note
* Time
* ChordParts

Nome       | Função     | Valores
-----------|------------|-------------------------------------
Note       | Note 0 0 0 | Baixo(0-11) Acorde(0-11) Tipo(0-1)
Time       | Time 0 4   | Tempo inical(beat) Tempo Final(beat)
ChordParts ||

### Valores de nota
Número | Nota
-------|-----
0      | C
1      | C#
2      | D
3      | D#
4      | E
5      | F
6      | F#
7      | G
8      | G#
9      | A
10     | A#
11     | B

### tipos de acordes
Número | Tipo
-------|-------------
0      | Acorde Maior
1      | Acorde Menor

## EXEMPLOS: 

```
| C | G | Am | F |
```

```
ChordList {
    Chord {
        Note 1 1 0
        Time 0 4
        ChordParts
    }
}
ChordList {
    Chord {
        Note 7 7 1
        Time 4 8
        ChordParts
    }
}
ChordList {
    Chord {
        Note 9 9 1
        Time 8 12
        ChordParts
    }
}
ChordList {
    Chord {
        Note 5 5 0
        Time 12 16
        ChordParts
    }
}
```

```
| C#m C#m/Bb | A          |
```

```
ChordList {
    Chord {
        Note 1 1 1
        Time 0 2
        ChordParts
    }
}
ChordList {
    Chord {
        Note 10 1 1
        Time 2 4
        ChordParts
    }
}
ChordList {
    Chord {
        Note 9 9 0
        Time 4 8
        ChordParts
    }
}
```
