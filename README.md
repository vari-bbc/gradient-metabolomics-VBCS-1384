# gradient-metabolomics-VBCS-1384
A shareable code space between Hannah Damico (VAI BBC) + Richard Cassidy (VAI Fondufe-Mittendorf Lab)

# libs_opts.R
- Either run this file directly before running any other files OR source this file at the top of markdowns
- If running file directly in script, comment out the source(libs_opt.R) at the top of .Rmd files unless using correct file path
  
# init_process_widegradientmetab_20250217.Rmd
- must run libs_opts.R file OR source("libs_opts.R") to run this file

# widegradmetab_DEG_20250307.Rmd
- Workflow for limma + eBayes methods to find differentially expressed genes from Metabolomics data
- *requires vsn_metab.rds file created in line 470 of init_process_widegradientmetab_20250217.Rmd file*
- Search "FIND DATA - VSN_METAB" in *init_process_widegradientmetab_20250217.Rmd* to locate this line in line number doesn't equate
- Limma methods: https://www.bioconductor.org/packages/devel/bioc/vignettes/limma/inst/doc/usersguide.pdf
- duplicateCorrelation() information for Limma model: https://rdrr.io/bioc/limma/man/dupcor.html
- Empirical Bayes methods: https://rdrr.io/bioc/limma/man/ebayes.html
