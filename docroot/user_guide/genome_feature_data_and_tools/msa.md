# Multiple Sequence Alignment

## Accessing the Multiple Sequence Alignment Viewer on the PATRIC Website 

This tool may be accessed from the MSA Tools button in the light blue
Table Toolbar at the top of PATRIC tables, including the Table Toolbar
within your Workspace. From within the Protein Family Sorter you may
chose to access MSA via the Table Toolbar or to conduct MSA for **ALL**
protein members on any FIGfam details page by clicking “For All XX
Members” link under "Integrated Protein Tree and Alignment**"** in the
upper right corner of the page. For more details on the Protein Family
Sorter please see [Protein Family Sorter FAQs](/content/Protein_Family_Sorter).

## Multiple Sequence Alignment Viewer Overview

The multiple sequence alignment viewer is an interactive tool that
displays multiple sequence alignment and a family tree side-by-side and
allows the user to examine details of selected protein families,
including the overall quality of the alignment as well as more specific
details such as particular regions or motifs of interest.

## Alignment Program and Source Data

The protein sequences from each family are aligned using MUSCLE (v 3.6)
and ambiguous portions of the alignment are removed using Gblocks (v 0.91b).
The input data for the multiple sequence alignments are the protein
sequences that have been grouped together in a FIGfam. When the user
selects a FIGfam from the protein family sorter, all members of that
FIGfam from the set of genomes being examined are included.

## Multiple Sequence Alignment Viewer Features and Functionality

-   The Family Tree, displayed on the left side of the screen, may be
    collapsed or expanded in order to co-locate sequences of interest.

-   A scroll bar, located at the bottom of the alignment, allows for
    visualization of specific regions throughout the amino acid
    sequences.

-   The Family Tree display can be switched between phylogram and
    cladogram views. In phylogram view, the tree branches are drawn with
    lengths based upon the branch lengths in the tree. In cladogram
    view, the tree branch lengths are disregarded and branches are drawn
    so all branch labels line up on the right side of the Family Tree.
    Phylogram view conveys additional information about the evolutionary
    divergence, while the cladogram view allows better visual resolution
    of the branching pattern for very closely related taxa (where the
    branch lengths are too small to allow the branching pattern to be
    distinguished in phylogram view). Cladogram view also shows branch
    support values, which are calculated by
    [FastTree.](http://www.microbesonline.org/fasttree/)

-   You may chose to label the Family Tree with locus tags or genome
    names. In either view, you may momentarily see both the locus tag
    and genome name identifiers by placing your mouse over a specific
    branch label in the tree.

-   Within the alignment, columns highlighted in black are considered
    conserved. You may adjust the conservation sensitivity with the
    slidebar located at the top of the alignment.

-   Clicking within the alignment will highlight the selected amino acid
    column in blue and show the numerical position designator for that
    column along the top of the alignment. It will also automatically
    highlight the coinciding genome branches in the Family Tree with the
    same colors as their respective amino acids in the alignment.

-   Both the alignment and the Family Tree are printable by clicking on
    “Printable Alignment” and “Prinatble Tree” respectively at that top
    of the table. Note: The Family Tree may be printed in either
    phylogram or cladogram view.