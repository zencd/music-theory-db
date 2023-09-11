# Music Theory DB

All chords and all scales represented in JSON format.

The things are written using the universal [integer notation][1],
which represents every note as an offset from the primary.

## Chords

[chords.json](chords.json), 26 commonly used ones

[chords-all.json](chords-all.json), 2056 ones

```
{
  "chord UID" : {
    "pitch": notes in the chord [0..23] spanning two octaves
    "name" : ["name"]
    "abbr" : ["abbreviation"]
  }
}
```

## Scales

[scales.json](scales.json), 67 commonly used ones

[scales-ext.json](scales-ext.json), 1490 ones

```
{
  "scale UID" : {
    "pitch": notes in the scale [0..11]
    "name": ["name"]
  }
}
```

[1]: https://en.wikipedia.org/wiki/Pitch_class#Integer_notation
