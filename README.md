# Processing side effect and indication data from SIDER 4

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.45521.svg)](http://dx.doi.org/10.5281/zenodo.45521)

[SIDER](http://sideeffects.embl.de/ "SIDER Homepage: Side Effect Resource") is a resource of side effects extracted from drug labels. See the [SIDER 4 publication](https://doi.org/10.1093/nar/gkv1075 "The SIDER database of drugs and side effects") for more information.

This repository extracts data from SIDER 4.1 into user-friendly, tidy TSVs.

[`SIDER4.ipynb`](SIDER4.ipynb) is a single python notebook that performs the analysis.

The `data` directory contains:

+ [`side-effect-terms.tsv`](data/side-effect-terms.tsv): a list of side effect terms and names
+ [`side-effects.tsv`](data/side-effects.tsv): drug side effects mapped to DrugBank compounds
+ [`indications.tsv`](data/indications.tsv): drug indications

## License

SIDER data and their derivatives are licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/ "Attribution-NonCommercial-ShareAlike 4.0 International"). All original content is released as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "Public Domain Dedication").

