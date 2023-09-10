# Music Theory DB

All chords and all scales represented in JSON format.
The things are written using the universal [integer notation][1],
which represents every note as an offset from the primary.

## Chords

[chords.json](chords.json)

- dict key: unique chord id
- dict value:
  - `pitch` - notes in the chord, `[0..23]`, spanning two octaves
  - `name` - human readable names, 1+
  - `abbr` - abbreviations, 1+

## Scales

soon

[1]: https://en.wikipedia.org/wiki/Pitch_class#Integer_notation