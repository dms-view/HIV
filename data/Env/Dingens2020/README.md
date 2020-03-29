## Data for Comprehensive, residue-level mapping of polyclonal neutralizing antibody responses in BG505 SOSIP trimer vaccinated rabbits
Adam S. Dingens, Payal Pratap, Keara Malone, Thomas Ketas, P.J Klasse, John Moore, Andrew Ward, Jesse D. Bloom (and likely others)

To view the data using [`dms-view`](dms-view.github.io) you need three files: a [data file](Dingens2020.csv), a [protein structure file](5FYL_AbsRemoved.pdb), and a [metadata file](Dingens2020.md).

### files for [`dms-view`](dms-view.github.io)

- data file: [`Dingens2020.csv`](Dingens2020.csv)
- protein structure file: [`5FYL_AbsRemoved.pdb`](5FYL_AbsRemoved.pdb)([pdb entry](https://www.rcsb.org/structure/5FYL))
- metadata file: [`Dingens2020.md`](Dingens2020.md)

### raw data files

- `summary_*_median*diffsel.csv`: differential selection files for both the site and mutation level from Adam.
- [`LANL_NatFreq_dropIndelsRelBG505.csv`](LANL_NatFreq_dropIndelsRelBG505): natural frequencies file (in prefs format) from Adam.
- [`BG505-avg-rescaled-prefs_ADrealigned.csv`](BG505-avg-rescaled-prefs_ADrealigned.csv): BG505 preferences file from Adam.

### processing script
- [build_data.ipynb](build_data.ipynb): Jupyter notebook to create the [`Dingens2020.csv`](Dingens2020.csv) data file.
