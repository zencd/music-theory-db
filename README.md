# Music Theory DB

All chords and all scales represented in JSON format.

The things are written using the universal [integer notation][1],
which represents every note as an offset from the primary.

## Chords

[chords.json](chords.json), 26 ones

- dict key: unique chord id
- dict value:
  - `pitch` - notes in the chord, `[0..23]`, spanning two octaves
  - `name` - human readable names, starting with the most popular
  - `abbr` - abbreviations, 1+

## Scales

[scales.json](scales.json), 67 ones

- dict key: unique scale id
- dict value:
  - `pitch` - notes in the scale, `[0..11]`
  - `name` - human-readable names, starting with the most popular


[1]: https://en.wikipedia.org/wiki/Pitch_class#Integer_notation