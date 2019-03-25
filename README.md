# whw2019_snow_modeling

### Waterhackweek 2019

Slack channel: [#whw2019_snow_modeling] (https://waterhackweek2019.slack.com/messages/CH9CULM2Q/details/)

Binder URL: https://mybinder.org/v2/gh/bartnijssen/hydroshare-pangeo-notebooks/binder

---

### Collaborators:
* Andrew Bennett (Project Lead)
* Deena Hannoun-Giffen
* Andrew Hedrick
* Anne Heggli
* Steven Pestana

---

### The Problem:
*

---

### Data:

* Col du Porte, France - 6 water years
---

### Specific Questions/Goals:
* How are different model configurations sensitive to forcing data?
* Impact of layer thickness - Loop through different formulations of layer thicknesses and numbers.
* Derive albedo parameter distribution informed by Bayesian analysis of outputs.

### Broader Impacts and Applications:
* Multiple water years (i.e. different climatologies) will have different effects on model parameterizations.
* Different snow regimes will display varying sensitivities to changes in parameterizations.
...


---

### Existing Methods/Tools and Prior Work:
* https://github.com/arbennett/col-de-port_1994-2010_summa
* https://github.com/arbennett/cues_2016_summa_setup


---

### Proposed Methods/Tools:
* [pysumma](https://github.com/arbennett/pysumma/tree/feature/ensemble) - This links to a specific version of @arbennett's code which has support for running ensembles of SUMMA runs.

---

### Background Reading:
* [Essery et al 2012: A comparison of 1701 snow models using observations from an alpine site](https://depts.washington.edu/mtnhydr/snowschool/Essery_2013.pdf)
* [Clark et al 2015a: A unified approach for process-based hydrologic modeling: 1. Modeling concept](https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1002/2015WR017198)
* [Clark et al 2015b: A unified approach for process-based hydrologic modeling: 2. Model implementation and case studies](https://agupubs.onlinelibrary.wiley.com/doi/10.1002/2015WR017200)

=======
