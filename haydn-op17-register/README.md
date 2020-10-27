# Haydn opus 17 register

This repository contains the Haydn's opus 17 pitch registers data used
in the [research
paper](http://revistamusicatheorica.tema.mus.br/index.php/musica-theorica/article/view/128)
published in [The Musica Theorica
Journal](http://revistamusicatheorica.tema.mus.br/).

## Data structure

The data structure consists of a json document containing 555 objects
with this structure:

- Movement
- Section
- Data type
- Data

The sections are the Sonata Form choices, notated as Exp>T1, Rexp>Tr
and so on.

The data type choices are amplitude, Violin I, Violin II, Viola and
Violoncello. The instrument data are pitch notes represented with MIDI
standards (60 for C4 pitch), and amplitude data is the interval
between the higher and lower pitches in each time point.

## Data example:

```json
{
    'Movement': 'op17n1-01',
    'Section': 'Exp>T1',
    'Data type': 'amplitude',
    'Data': [0.0,
        0.0,
        0.0,

        ...

        0.0,
        0.0,
        0.0
    ]
}
```

