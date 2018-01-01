# 2k18 - 1 zimlich n:icecream:e Sprache

**2k18** ist eine an [2k16](https://github.com/HerrLevin/2k16-spec) angelehnte Programmiersprache. Sie wurde grundlegend bei der Entwicklung des Vongpiler überarbeitet.

## Danksagung

Vieleng Dang an [Herr Levin](https://github.com/HerrLevin), welcher die ursprüngliche Sprache entworfen hat!

## Compiler

### Vongpiler

Der **Vongpiler** ist ein in Java geschriebenen Compiler, welcher Maschinencode generiert, der in der **VVM** (**Vong Virtual Machine**) ausgeführt werden kann.

Der **Vongpiler** wie auch die **VVM** können in folgendem Projekt heruntergeladen werden:

[https://github.com/MastersOfDesaster/VongPiler](https://github.com/MastersOfDesaster/VongPiler)

## Programmaufbau

ERSTER ENTWURF &mdash; ERSTER ERSTER ZWEITAUSENDACHTZEHN
*Dieses Dokument dient zur Festlegung der Grundsätzlichen Struktur von 2k18. Bitte beachtet: Da das nur ein Entwurf ist, können sich große Bestandteile dieser "Sprache" noch gurndlegend abändern. Wenn ihr so verrückt seid, 2k18 zu nutzen, seid ihr selbst schuld. Wenn was nicht funktioniert, macht uns nicht dafür verantwortlich!*

gez. Das Vongpiler Team.

---

```2k18
was ist das fuer 1 code?
    [code]
1 nicer!!!
```

## Halo Wörlt (AAL)

Um das Hello World Beispiel möglichst kurz zu gestalten, hat 2k18 die Funktion integriert.

Beispiel

```2k18
was ist das fuer 1 code?
    halo i bims!!! :X gibt Hello World aus!
1 nicer!!!
```

## Kommentare

> Ein einzeiliger Kommentar wird mit einem :X eingeleitet.

```2k18
[code] :X Das ist 1 nicer komentar!
```

## Variablen

> Variablen beginnen immer mit einem Buchstaben und bestehen anschließend aus Buchstaben und/oder Zahlen enthalten. Variablen müssen immer initialisiert werden.

```2k18
i bims 1 [name] vong [type] goenn dir [value]!!!
```

### Typen

| Code   | Typ                                  |
| ------ | ------------------------------------ |
| `word` | String                               |
| `zal`  | Number                               |
| `isso` | Boolean (yup: True, nope: False)     |

### Beispiel

Die Variable `lauch` wird als Number mit einem Wert von `15` definiert.

```2k18
i bims 1 lauch vong zal her goenn dir 15!!!
```

## Kontrollstrukturen

```2k18
bist du [bool]? yup
    [code wenn bool == true]
real rap
bist du [bool]? nope
    [code wenn bool == false]
real rap
```

Zeilen, bei denen [bool] zu true evaluieren muss, enden mit [yup]. Umgekehrt mit [nope]. Else gibts also nicht direkt. Else-if ergibt sich durch mehrere "bist du ..."

## GOTO

> Um ein Label zu setzen wird der Lattenzaun (auch Hashtag genannt) verwendet. Darauf folgt der Name des Labels.

```2k18
[label]
[irgendwelcher kot]
g zu [label] du larry!!!
```

Beispiel Endlosschleife

```2k18
#lauch
g zu #lauch du larry!!!
```

## Ausgabe

Gib Variablenname auf stdout aus.

```2k18
gieb [variable]
```

## Arithmetische und Logische Operationen

Operationen können wie folgt aufgerufen werden. Die Anzahl der Argumente kann beliebig groß sein.

```2k18
was ist das fuer 1 [operation] vong [arg1] + [arg2] + [argn] her?
```

|Operation  |Beschreibung           |
|-----------|-----------------------|
|sume       |Addition(+)            |
|abziehung  |Subtraktion(-)         |
|mahl       |Multiplikation(*)      |
|teilung    |Division(/)            |
|räst       |Modulo(%)              |
|ismär      |Größer als(>)          |
|isweniga   |Kleiner als(<)         |
|same       |Und(&&)                |

Beispiel

Berechne die Summe (30 + 12)

```2k18
was ist das fuer 1 sume vong 30 + 12 her?
```

Berechne die Summe (30 + 12) und weise das Ergebnis der Variable [lauch] zu.

```2k18
i bims 1 zal lauch goenn dir 0!!!

lauch goenn dir was ist das fuer 1 sume vong 30 + 12 her?
```
