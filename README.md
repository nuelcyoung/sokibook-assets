# Soki Book assets

Data files the Soki Book app downloads on demand. Each set is a GitHub release.

## dictionary-1

`dictionary-1.sqlite.gz`: the reader's offline dictionary (gzipped SQLite, 10.3 MB).
Built with `apps/mobile/tool/make_dictionary.py` from:

- **Princeton WordNet 3.0**: definitions, examples, synonyms, irregular forms.
  WordNet 3.0 Copyright 2006 by Princeton University. All rights reserved.
  See `WORDNET-LICENSE.txt`.
- **CMU Pronouncing Dictionary**: pronunciations, converted to IPA.
  Copyright (C) 1993-2015 Carnegie Mellon University. All rights reserved.
  See `CMUDICT-LICENSE.txt`.
