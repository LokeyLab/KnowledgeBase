# Design Rules & Library Design

Considerations for designing peptide libraries, particularly for MS/MS sequencing workflows.

## Benefits of Sequencing

- Reduce LC-MS runs by running mixtures of compounds.
- Deconvolute peptides if they share a mass.

## Requirements for Sequencing

### Correlating with Other Data

- If correlating with another data set, MS2 data must be collected with the same chromatographic parameters so that retention times can be matched.

### Cyclic Libraries

- Because each single cyclic peptide's fragments contain no information on the order of the residues present, avoid putting several variable positions which have the same (or nearly the same) contents in a row.
- Only fragments which contain (alone or in combination) a unique neighbor to a variable position can give solid sequencing data.
- The more locations with non-unique neighbors that exist, the better the MS2 data must be to accurately sequence the peptide.

### Linear Libraries

- Much easier to sequence because there is a beginning and end of the peptide, with a separate series of ions starting from each end.
- Unique neighbor positions are less important, but still make sequencing easier/possible with lower MS2 data quality.

## Chromatographic Considerations

- The main limiter on sublibrary size is the ability to resolve peptides of the same mass from each other.
- The larger your sublibrary or the more mass-redundant it is, the more separation you will need.

!!! example "Separation example"
    A 150-member sublibrary with an average of ~5 compounds per mass resolves 80% on a 2.1 x 250 mm C18 column with a ~33 minute run length at 0.5 mL/min.

## Isotopic Labeling

- Can be used to distinguish stereochemistry by mass.
- Remember that the size of your molecule will influence its C13 mass envelope profile. For example, a cyclic hexapeptide will generally have a fairly strong peak at [M+H+1].
- As a consequence, labeled residues should be at least 2 mass units different from their unlabeled counterpart in order to avoid potentially significant mass overlap with compounds at nearby masses.

!!! tip
    When in doubt, consult Chad.
