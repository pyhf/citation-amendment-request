# pyhf citation change from ICHEP to JOSS request

## Email Subject

Request for pyhf Citation Amendment in '[PAPER TITLE]' paper

## Email Body

Hi [ALL AUTHORS FIRST NAMES],

We happened to see your recent paper "[PAPER TITLE](HYPERLINK TO PAPER)" on the arXiv and were quite happy to see that you used and cited pyhf in it --- thanks!
However, the citation for pyhf is wrong as it is cites the [ICHEP 2022 proceedings](https://pos.sissa.it/414/245), and not the [Journal of Open Source Software paper](https://joss.theoj.org/papers/10.21105/joss.02823), as given on the [Use and Citations page of the pyhf docs](https://pyhf.readthedocs.io/en/stable/citations.html#citation) and [the citation APIs](https://pyhf.readthedocs.io/en/stable/cli.html#cmdoption-pyhf-cite).
Would you please correct the citation to the JOSS paper?

```
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

We appreciate that ICHEP results might turn up first if people search "pyhf ICHEP" instead of "pyhf", but we've tried to make this clear by noting in the comments for the [corresponding arXiv preprint](https://arxiv.org/abs/2211.15838)

"... If you are looking to cite pyhf as software, please follow the citation instructions at this https URL".

Best,
The pyhf dev team (Lukas, Matthew, and Giordon)
