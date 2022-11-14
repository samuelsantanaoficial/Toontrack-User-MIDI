# EZbass User MIDI
## ex:

ChordList {
    Chord {
        Note 0 0 0 //Baixo 0-11 semitom - Acorde 0-11 semitom - Tipo | 0 = maior 1 = menor | 
        Time 0 4 //Tempo inical - Tempo final | BEAT | 
        ChordParts //?
    }
}

0  = C
1  = C#
2  = D
3  = D#
4  = E
5  = F
6  = F#
7  = G
8  = G#
9  = A
10 = A#
11 = B

## ex: | C#m C#m/Bb | A |

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