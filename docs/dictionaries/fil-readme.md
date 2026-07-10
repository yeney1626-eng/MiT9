# Filipino Dictionary (fil.txt)

Place this file in: `docs/dictionaries/fil-readme.md`

## Source
This is a hand-curated starter word list (~300 common Filipino/Tagalog words:
pronouns, numbers, days, months, family terms, food, and everyday vocabulary),
compiled for the MiTi9 keyboard. It is **not** a comprehensive corpus — TT9's
other bundled languages typically ship with 100k–1.6M words sourced from
proper linguistic corpora (e.g. Wiktionary word-frequency dumps, hunspell
dictionaries, or OpenSubtitles frequency lists).

## License
The word list itself (common everyday vocabulary) is not subject to
copyright. No third-party corpus was copied into this file.

## Recommended next step
For production-quality predictive text, replace/extend this file with a
proper frequency-ranked Filipino corpus, for example:
- Tagalog Wiktionary frequency list
- FrequencyWords project (https://github.com/hermitdave/FrequencyWords) — Filipino/Tagalog list, if available
- A Filipino Hunspell dictionary word list

When you add a bigger list, keep the same constraints as the starter file:
- one word per line, no duplicates, no digits, only letters defined in
  `Filipino.yml`'s `layout` (a–z plus ñ).
- optionally switch to the CSV word+frequency format (`word<TAB>frequency`)
  for better prediction ranking once you have real frequency data.
