## Data for [An antigenic atlas of HIV-1 escape from broadly neutralizing antibodies distinguishes functional and structural epitopes](https://research.fhcrc.org/content/dam/stripe/bloom/labfiles/publications/Dingens2019.pdf)

Adam S. Dingens, Dana Arenz, Haidyn Weight, Julie Overbaugh, Jesse D. Bloom

To view the data from [An antigenic atlas of HIV-1 escape from broadly neutralizing antibodies distinguishes functional and structural epitopes](https://research.fhcrc.org/content/dam/stripe/bloom/labfiles/publications/Dingens2019.pdf) using [`dms-view`](dms-view.github.io) you need three files: a [data file](Dingens2019.csv), a [protein structure file](5FYL_AbsRemoved.pdb), and a [metadata file](Dingens2019.md).

### files for [`dms-view`](dms-view.github.io)

- data file: [`HIV_dms-view.csv`](HIV_dms-view.csv)
- protein structure file: [`5fyl_trimer_renumber.pdb`](5fyl_trimer_renumber.pdb) This is the [5fyl pdb file](https://www.rcsb.org/structure/5FYL) (crystal structure of BG505 SOSIP.664 Env bound by PGT122 and 35O22, from Stewart-Jones et al. 2016), with the antibodies removed, viewed as a trimer, and with the 321a insertion moved to 322a such that numbering matches the DMS data.  
- alternate protein structure file: [`5FYL_AbsRemoved.pdb`](5FYL_AbsRemoved.pdb) This is the [5fyl pdb file](https://www.rcsb.org/structure/5FYL) (crystal structure of BG505 SOSIP.664 Env bound by PGT122 and 35O22, from Stewart-Jones et al. 2016), with the antibodies removed and viewed as a monomer.  
- metadata file: [`Dingens2019.md`](Dingens2019.md)

### processing script
- [process_antigenic_atlas.py](process_antigenic_atlas.py): Python script to create the [`Dingens2019.csv`](Dingens2019.csv) data file. This script retrieves the site and mutation data from [EnvsAntigenicAtlas](https://github.com/jbloomlab/EnvsAntigenicAtlas).
