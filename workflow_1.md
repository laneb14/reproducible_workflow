reproducible_workflow_1
================
Scott Klasek
2024-05-16

# Large header

## Another header

**make bold text like this**

*italic text*

<https://happygitwithr.com/big-picture>.

There can be text here like this

``` r
2+2
```

    ## [1] 4

``` r
library(phyloseq)

### phyloseq objects across all sites
its.all.ps <- readRDS(file = "/Users/klas0061/Desktop/UMN/phyloseqs/all_obj1_by_site/all.ITS.ps")

its.all.ps # this is the phyloseq object of the ITS data
```

    ## phyloseq-class experiment-level object
    ## otu_table()   OTU Table:         [ 33085 taxa and 2878 samples ]
    ## sample_data() Sample Data:       [ 2878 samples by 21 sample variables ]
    ## tax_table()   Taxonomy Table:    [ 33085 taxa by 7 taxonomic ranks ]
    ## refseq()      DNAStringSet:      [ 33085 reference sequences ]

``` r
cat("this object contains ", ntaxa(its.all.ps), "ASVs")
```

    ## this object contains  33085 ASVs

This dataset contains 33k taxa and 2800 sample.
