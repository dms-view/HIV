
# High-resolution mapping of the neutralizing and binding specificities of polyclonal rabbit serum elicited by HIV trimer immunization 
Adam S. Dingens, Payal Pratap, Keara Malone, Sarah K. Hilton, Thomas Ketas, Christopher Cottrell, P.J Klasse, John Moore, Andrew Ward, Jesse D. Bloom (and likely others, author list is not final)

We performed mutational antigenic profiling of BG505 SOSIP trimer vaccinated rabbit serum, provided by John Moore and PJ Klasse. 

Here, we used BG505.T332N mutant Env libraries, first described and characterized in [Haddox, Dingens et al 2018](https://elifesciences.org/articles/34420). Note that this is matched to the BG505 immunogens, enabling profiling of autologous responses.

## Data plotted here

The _differential selection_ statistic used in this analysis is explained in detail [here](https://jbloomlab.github.io/dms_tools2/diffsel.html).

For each rabbit sera, you can view the median (across biological replicates) site- and mutation-level differential selection metrics.

The site-metrics (dot plot) include:

- **positive diffsel**: The sum of all positive differential selection values at a site (site level). This gives a sense to the total amount of escape/selective pressure at each site.
- **negative diffsel**: The sum of all negative differential selection values at a site (site level). This gives a sense for mutations that are depleted, rather than enriched, during serum selection relative to a non-selected control library. It is intriguing that many of these potential serum sensitizing mutations cluster and are consistent across sera.
- **max diffsel**: The value of the largest effect mutation (largest mutation differential selection) at each site (site level).
- **min diffsel**: The value of the smallest effect mutation (smalled mutation differential selection) at each site.
- **abs diffsel**: The absolute value of all mutation differential selection values at each site.


The mutation-metrics (logo plot) include

- **diffsel**: All mutation differential selection values, including negative values, are plotted. 
- **pos diffsel**: Only the mutations with positive differential selection values. 


Additionally,

- The frequency at which each amino acid is found in nature (**Natural Frequencies**), accessed from [LANL's filtered web alignment](https://www.hiv.lanl.gov/content/sequence/NEWALIGN/align.html]) (2017 version).
- The BG505 amino-acid preferences (**DMS preferences**), determined using the same BG505.T332N mutant virus libraries in [Haddox, Dingens et al 2018](https://elifesciences.org/articles/34420). Here, the height of each amino acid is proportional to how well that virus replicates in cell culture. This statistic can crudely be used to examine what mutations are viable and in our mutant virus libraries before serum selection.

Data is currently plotted on a BG505 SOSIP.664 Env monomer structure ([5FYL](https://www.rcsb.org/structure/5FYL)).
