# Samples

Free and open source samples I made.

## Strudel

These samples can be imported into [Strudel][strudel] like this:

```javascript
samples('github:AuditeMarlow/samples')

$kick: s("kick!4")
$snare: s("snare").struct("~ x").fast(2)
$fill: s("snare:1").struct("<~ [~!7 [~ x!3]]>").fast(2)
$hihat: s("hihat").struct("~ x ~ x").fast(2)
```

[strudel]: https://strudel.cc
