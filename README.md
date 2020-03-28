# HIV deep mutational scanning data sets visualized by `dms-view`

## Data sets

### ENV

- Antibody escape mutations of HIV BG505 ENV from a panel of monoclonal antibodies measured by [Dingens _et al._, 2019](https://linkinghub.elsevier.com/retrieve/pii/S107476131830565X). [See here](https://dms-view.github.io/?markdown-url=https%3A%2F%2Fraw.githubusercontent.com%2Fdms-view%2FHIV%2Fmaster%2Fdingens2019antigenic%2Fdingens2019antigenic.md&pdb-url=https%3A%2F%2Fraw.githubusercontent.com%2Fdms-view%2FHIV%2Fmaster%2Fdingens2019antigenic%2F5FYL_AbsRemoved.pdb&data-url=https%3A%2F%2Fraw.githubusercontent.com%2Fdms-view%2FHIV%2Fmaster%2Fdingens2019antigenic%2FHIV_dms-view.csv&condition=PGT121&site_metric=site_avgfracsurvive+%28median+of+reps%29&mutation_metric=mut_excess+frac+survive+%28median+of+reps%29&selected_sites=323%2C324%2C325%2C326%2C327%2C328%2C329%2C330%2C331%2C332%2C333%2C334%2C415%2C416%2C417%2C441) for a interactive `dms-view` visualization that shows escape from the antibody PGT121.
The raw data are [here](data/Env/Dingens2019).


## Adding data sets

1. Make a new branch or a fork of this repository.

2. Navigate to the [./data/](data) directory and create a subdirectory for the appropriate protein and study.
Data are organized first by protein and then by study, with studies named by the first author and year, such as [./data/Env/Dingens2019/](data/Env/Dingens2019).

3. Within that subdirectory, add the three input files that are needed to visualize the data.
As described in the [`dms-view` docs](https://dms-view.github.io/docs/), these are a CSV file of the data, a protein structure PDB file, and a Markdown metadata file.
In general, you should name these with the CSV data file named according to the study name (e.g., [./data/Env/Dingens2019/Dingens2019.csv](data/Env/Dingens2019/Dingens2019.csv)), the PDB file simply being the PDB (e.g., [./data/Env/Dingens2019/5FYL_AbsRemoved.pdb](./data/Env/Dingens2019/5FYL_AbsRemoved.pdb)), and the Markdown metadata file also named according to the study name (e.g. [./data/Env/Dingens2019/Dingens2019.md](data/HA/Dingens2019/Dingens2019.md)).
In addition, you should add a README within the subdirectory explaining the origin of the files (e.g., [./data/Env/Dingens2019/README.md](./data/Env/Dingens2019/README.md)).
In some cases (such as if the same data is mapped to multiple protein structures) you may need to extend or modify this naming scheme.
If you need to process other rawer forms of the data (e.g., from paper supplements) into the final data file for `dms-view`, then include those rawer data and the processing scripts if possible, explaining in the subdirectory repo.

4. Make a pull request for your branch or fork to add the data.

5. In [this top-level README file](README.md) add a **short** description of the study and a link to an appropriate [dms-view](https://dms-view.github.io) view of the dataset.

6. Make a pull request for your branch or fork to add the link.
