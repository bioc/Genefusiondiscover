# ALKfusiondiscover
DESCRIPTION
Package: ALKfusiondiscover
Title: Identification of EML4-ALK variants using paired-end sequencing
Version: 0.0.1.1
Authors@R: 
    person("Christoffer Trier", "Maansson", , "ctm@clin.au.dk", role = c("aut", "cre"),
           comment = c(ORCID = "0000-0002-3071-3437"))
Description: Paired-end sequencing of cfDNA generated BAM files can be used as input to
  discover EML4-ALK variants. This package was developed using position deduplicated BAM
  files generated with the AVENIO Oncology Analysis Software. These files are made using
  the AVENIO ctDNA surveillance kit and Illumina Nextseq 500 sequencing. This is a targeted 
  hybridization NGS approach and includes ALK-specific but not EML4-specific probes. 
License: `use_mit_license()`, `use_gpl3_license()` or friends to pick a
    license
Encoding: UTF-8
Roxygen: list(markdown = TRUE)
RoxygenNote: 7.2.0
Import: GenomicRanges,
        Rsamtools,
        dplyr,
        bamsignals
        
See vignettes for details