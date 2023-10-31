We provide the allele age annotations computed on each of the 26 populations from the 1,000 Genome Project data set separately and then aggregated per supergroup (AFR, AMR, EUR, SAS, EAS) as described in the paper. We also combined age estimates from all 26 populations (see paper for more details).

We computed allele age annotations on each of the 26 populations from the 1,000 Genome Project data set separately. We then aggregated the allele age annotations per supergroups (AFR, AMR, EUR, SAS, EAS) and across all 26 populations as described in the paper. We provide here the aggregated allele age annotations for each supergroup and across all populations.

Files are provided in compressed text format, where each row refers to a different variant. See below for a description of the columns.

- chromosome
- rsid
- start(bp): start position in basepairs
- end(bp): end position in basepairs
- reference_state
- alternate_state
- ancestral_state: If available, ancestral state inferred from Ensembl multiple alignments (human assembly GRCh37) using Ortheus in the Enredo-Pecan–Ortheus (EPO) pipeline (Paten et al. 2008). If not, the ancestral state is assumed to be the same as the reference state.
- {population_name}_AF: alternate allele frequency
- {population_name}_AF_derived: derived allele frequency
- lower_age: lower age estimate
- upper_age: upper age estimate (-1 means estimate could not be derived)
- age_estimate: age estimate (-1 means estimate could not be derived)
- QS: Quality Score (ratio of number of concordant and discordant pairs before filtering over the same number after filtering)
