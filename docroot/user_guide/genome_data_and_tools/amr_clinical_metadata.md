# Antimicrobial Resistance and Other Clinical Metadata


## Genome-Level Antimicrobial Resistance (AMR)

Genome-level AMR metadata are curated primarily from [sequencing
projects](http://enews.patricbrc.org/niaid-antimicrobial-resistance-sequencing-projects/)
from the NIAID-funded [Genomic Centers for Infectious
Diseases](http://enews.patricbrc.org/niaid-genome-sequencing/). These
data include panel data for antibiotics and chemicals. PATRIC support
for AMR metadata includes:

**Antimicrobial Resistance** metadata field. This field shows genomes
that have been specifically tested against certain antibiotics and the
resulting phenotype from that test. Note that a genome can have multiple
antibiotic phenotypes, such as being resistant to one drug and
susceptible to another. The values included in this field are:

- Resistant
- Susceptible
- Intermediate

**Antimicrobial Resistance Evidence** metadata field. Some of the
genomes included in PATRIC have a specific phenotype that has been
assigned, such as MRSA, and some of the genomes have been screened by
broad, antimicrobial resistant panels (AMR panels). We have created a
new field that identifies which metadata available on the PATRIC website
contains the evidence supporting the resistance category assigned.

-   'Phenotype.' Genomes in this category were assigned their resistance
    category based on phenotype information provided by the sequencing
    center, for instance MRSA or MSSA. This phenotype data is available
    at PATRIC as well.
-   'AMR Panel.' Some genomes have been tested against a panel of
    antibiotics, with the results of the screening reported in a table
    using either a specific designation (such as 'Susceptible,'
    'Resistant,' or 'Intermediate'), or the minimum inhibitory
    concentration (MIC). For genomes in this category, the panel data is
    available for
    [download](ftp://ftp.patricbrc.org/BRC_Mirrors/AMR/PATRIC_genomes_AMR_Dec2014.xlsx).
    In future releases, this data will be more fully integrated on the
    PATRIC website.
-   'Comment.' The basis for the resistance category for these genomes
    can be found in the comment metadata field. This information may
    have come from the comment field at GenBank, or in a comment field
    from data provided by the sequencing center or their sample
    provider. In some cases, the comment has been provided by
    literature-based curation by the PATRIC team; in these cases, a link
    to the corresponding publication is also available.

The Antimicrobial Resistance metadata field and the Antimicrobial
Resistance Evidence metadata field are available as filterable facets on
the Genome list pages, allowing sorting on the terms 'Susceptible',
'Resistant' or 'Intermediate' to locate the genomes tagged with that
information. In addition, filters are available for the source of the
information, which provides the ability, for example, to only include
genomes that have complete AMR panel information and exclude genomes
where there is only a comment.

## Other Clinical Metadata

Some clinical metadata that is available for only a subset of the
genomes available at PATRIC. This includes new typing methods that are
specific to a small number of genomes (such as spa type or wzi type),
but are still important to researchers. These data are stored as a
key-value pairs so that the Global Search can find genomes that contain
any data for that field (e.g., search for 'wzi') or for genomes with
specific values for that field (e.g., search for 'wzi:29')

The Show/Hide capability on Genome lists to expose or hide the new
metadata fields. The information is also available on each Genome
Summary page by selecting clicking on the Summary information. When a
list of genomes is downloaded, all of the new metadata fields are also
included in the list of metadata available.
