# Protein Families

PATRIC provides computed protein families at 3 levels:
[FIGfams](http://www.nmpdr.org/FIG/wiki/view.cgi/FIG/FigFam),
genus-specific protein families
([PLfams](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4744870/)) and
cross-genera protein families (PGfams). These protein families cover
almost all of the proteins in the current public genomes (\~100% protein
coverage) to support more comprehensive comparative analysis.

The protein families are computed using the procedure described below:

-   All the proteins from public genomes currently available in PATRIC
    are assigned function based on the most recent signature k-mers. For
    all the proteins with identical functions, a similarity matrix is
    computed based on the number of signature k-mers they have in
    common, divided by average protein length for every pair of
    proteins. This k-mer similarity matrix is then processed using MCL
    algorithm, which forms one or more protein clusters based on
    similarity among the members.
-   The genus-specific protein families are computed using only proteins
    within a genus and more stringent criteria (MCL inflation = 3.0).
    This provides higher sequence similarity and better specificity
    while performing within-genus/species or close strain comparisons.
-   The cross-genera protein families are computed by clustering
    representative proteins from the genus-specific families with
    slightly relaxed criteria (MCL inflation = 1.1). This allows
    cross-genera or distant homologs to cluster together, which is
    necessary to support cross-genera comparative analysis across all
    microbial genomes.

The new protein families are accessible through the Genome and Gene
Overview webpages and through the Protein Family Sorter tool. The
Protein Family Sorter now allows users to perform comparative analysis
using PLfams, PGfams, or FIGfams.
