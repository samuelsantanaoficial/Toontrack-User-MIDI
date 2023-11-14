# EZbass User MIDI
## Como usar

Criar arquivo de txt com o mesmo nome do arquivo midi e colocar na mesma pasta, e salvar o arquivo de texto como .midchordinfo

### Exemplo:
* verso_1.mid
* verso_1.midchordinfo

```
ChordList {
    Chord {
        Note 0 0 0 
        Time 0 4 
        ChordParts
    }
}
```

## Documentação

* Note
* Time
* ChordParts

Nome       | Função     | Valores
-----------|------------|-------------------------------------
Note       | Note 0 0 0 | Baixo(0-11) Acorde(0-11) Tipo(0-1)
Time       | Time 0 4   | Tempo inical(beat) Tempo Final(beat)
ChordParts ||

### Valores de nota
Número | Nota            | Grau
-------|-----------------|---------
0      | Tônica          | 1º Grau
1      | #/b             |
2      | Supertônica     | 2º Grau
3      | #/b             |
4      | Mediante        | 3º Grau
5      | Subdominante    | 4º Grau
6      | #/b             |
7      | Dominante       | 5º Grau
8      | #/b             |
9      | Sobredominante  | 6º Grau
10     | #/b             |
11     | Sensível        | 7º Grau

### tipos de acordes
Número | Tipo
-------|-------------
0      | Acorde Maior
1      | Acorde Menor

## EXEMPLOS: 
### Tom: C

```
| C | G | Am | F |
```

```
ChordList {
    Chord {
        Note 0 0 0
        Time 0 4
        ChordParts
    }
}
ChordList {
    Chord {
        Note 7 7 0
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

### Tom: E
```
| C#m C#m/Bb | A          | E          |
```

```
ChordList {
    Chord {
        Note 9 9 1
        Time 0 2
        ChordParts
    }
}
ChordList {
    Chord {
        Note 7 7 1
        Time 2 4
        ChordParts
    }
}
ChordList {
    Chord {
        Note 5 5 0
        Time 4 8
        ChordParts
    }
}
ChordList {
    Chord {
        Note 0 0 0
        Time 8 12
        ChordParts
    }
}
```

# EZkey User MIDI
## Como usar

Criar arquivo de txt com o mesmo nome do arquivo midi e colocar na mesma pasta, e salvar o arquivo de texto como .midchordinfo

### Exemplo:
* verso_1.mid
* verso_1.midchordinfo

```
ChordList {
    Chord {
        Note 0 0 0 
        Time 0 4 
        ChordParts
    }
}
```
