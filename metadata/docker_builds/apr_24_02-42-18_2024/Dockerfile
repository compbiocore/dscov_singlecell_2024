FROM ghcr.io/compbiocore/dscov_singlecell_2024:latest

RUN R -e "install.packages('devtools')"
RUN R -e "devtools::install_github('immunogenomics/presto')"
