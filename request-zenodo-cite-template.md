# pyhf citation Zenodo extension request

## Email Subject

Request for pyhf Citation Amendment in '[PAPER TITLE]' paper

## Email Body

Hi [ALL AUTHORS FIRST NAMES],

We happened to see your recent paper "[PAPER TITLE](HYPERLINK TO PAPER)" on the arXiv and were quite happy to see that you used and cited pyhf in it --- thanks!
Would you mind extending the citation of pyhf through, so that in addition to the JOSS paper citation that you have in there now the Zenodo DOI citation would be added (as given on the [Use and Citations page of the pyhf docs](https://pyhf.readthedocs.io/en/stable/citations.html#citation) and [the citation APIs](https://pyhf.readthedocs.io/en/stable/cli.html#cmdoption-pyhf-cite)).

Example for pyhf v0.7.6:

```
@software{pyhf,
  author = {Lukas Heinrich and Matthew Feickert and Giordon Stark},
  title = "{pyhf: v0.7.6}",
  version = {0.7.6},
  doi = {10.5281/zenodo.1169739},
  url = {https://doi.org/10.5281/zenodo.1169739},
  note = {https://github.com/scikit-hep/pyhf/releases/tag/v0.7.6}
}

@article{pyhf_joss,
  doi = {10.21105/joss.02823},
  url = {https://doi.org/10.21105/joss.02823},
  year = {2021},
  publisher = {The Open Journal},
  volume = {6},
  number = {58},
  pages = {2823},
  author = {Lukas Heinrich and Matthew Feickert and Giordon Stark and Kyle Cranmer},
  title = {pyhf: pure-Python implementation of HistFactory statistical models},
  journal = {Journal of Open Source Software}
}
```

Would you mind submitting an extended citation to arXiv? It is important for pyhf's future as a project that we're able to show use citations for it, and having both the Zenodo and JOSS citations help.

Best,
The pyhf dev team (Lukas, Matthew, and Giordon)
