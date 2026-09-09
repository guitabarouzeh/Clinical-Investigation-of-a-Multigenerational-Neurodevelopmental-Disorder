# Clinical Investigation of a Multigenerational Neurodevelopmental Disorder

## Targeted Sequencing Panel Analysis and Candidate Gene Prioritization

## Overview

This repository presents a case-based variant prioritization analysis performed using a Variant Call Format (VCF) file generated from a targeted sequencing panel.

The investigated family includes multiple individuals affected by a neurodevelopmental phenotype characterized by severe intellectual disability and developmental delay. The available genomic data belonged to one affected individual selected as the proband.

The objective of this project was to systematically prioritize candidate variants and genes by integrating:

- Variant annotation and classification
- Zygosity
- Gene–disease association
- Reported mode of inheritance
- Available clinical phenotype
- Family history and pedigree
- Evidence from ClinVar, OMIM, PubMed, and scientific literature

This analysis represents an exploratory, case-based variant prioritization workflow. Due to limited clinical information, the absence of segregation analysis, and the lack of molecular data from other family members, the findings should not be interpreted as a definitive molecular diagnosis.

## Repository Structure

The repository contains the following materials:

- `REPORT.md` — Detailed case-based variant prioritization report
- `README.md` — Project overview and repository information
- Analysis outputs and supporting materials, where applicable

Only anonymized and non-identifying information is included in the public repository.

## Privacy and Data Protection

All potentially identifiable patient and family information has been excluded from this repository.

The original VCF file and detailed identifying pedigree information are not publicly shared. Only anonymized information relevant to the genetic analysis and variant prioritization workflow is presented.

# 1. Clinical Features

The available clinical information indicated that multiple individuals in the family were affected by a severe neurodevelopmental phenotype.

Reported features included:

- Severe intellectual disability
- Developmental delay
- Significant impairment in educational functioning

Detailed clinical information was not available for most affected individuals.

The following information was unavailable or insufficiently documented:

- Neurological examination
- Brain imaging
- Metabolic findings
- Plasma amino acid analysis
- Renal function
- Ophthalmological examination
- Cardiac evaluation
- Muscle involvement
- Dysmorphic features
- Newborn screening history

One affected individual was selected as the proband, and a VCF file generated from a targeted sequencing panel was available for analysis.

# 2. Family History and Pedigree

The parents of the affected siblings were reported to be clinically unaffected and non-consanguineous.

The couple had:

- Two affected sons
- Two affected daughters
- Two unaffected daughters
- One unaffected son

The proband was one of the affected daughters.

## Maternal Family History

The mother was reported to have:

- One affected brother
- Two unaffected brothers
- Two unaffected sisters

The maternal grandparents were reported to have a consanguineous marriage.

## Paternal Family History

The father was reported to have:

- Two affected sisters
- Two unaffected brothers

One affected paternal aunt had:

- One affected daughter
- One unaffected daughter
- Two unaffected sons

Another affected paternal aunt had:

- One affected son
- Multiple unaffected sons and daughters

The pedigree therefore suggests affected individuals across multiple generations and in both sexes.

However, interpretation of the inheritance pattern is limited because:

- Segregation analysis has not been performed.
- Genomic data from other affected family members are unavailable.
- Detailed clinical phenotyping is unavailable.
- The molecular status of unaffected relatives is unknown.

The observed pedigree does not immediately fit a simple classical autosomal dominant or autosomal recessive model. Variable expressivity, incomplete penetrance, X-linked mechanisms, or other complex inheritance models may be considered as hypotheses, but none can be established from the available data.

# 3. Available Genomic Data

A VCF file generated from a targeted sequencing panel was available for one affected individual.

The analysis focused on variants annotated in the available VCF file.

No molecular data were available for:

- Parents
- Affected siblings
- Unaffected siblings
- Other affected relatives

Therefore, the following analyses could not be performed:

- Segregation analysis
- Determination of parental origin
- Confirmation of de novo variants
- Confirmation of compound heterozygosity
- Phasing of multiple variants
- Determination of cis/trans relationships

# 4. Variant Filtering and Prioritization Workflow

## 4.1 Initial Variant Filtering

A stepwise variant prioritization strategy was applied to the available VCF data.

### Step 1 — Deprioritization of Benign and Likely Benign Variants

Variants annotated as:

- Benign
- Likely benign

in the available ACMG-based and/or ClinVar annotation fields were deprioritized during the initial filtering process.

Variants without clinically relevant pathogenicity annotations in the available dataset were also not prioritized during the initial screening stage.

This was an initial prioritization step rather than a definitive exclusion of every variant lacking a pathogenic classification.

### Step 2 — Selection of Exonic Variants

The initial analysis focused primarily on variants annotated as exonic in the available `Func.refGene` annotation.

This approach was selected to prioritize variants with a direct potential effect on protein sequence.

### Step 3 — Removal of Synonymous Variants

Variants annotated as synonymous in the `ExonicFunc.refGene` annotation were initially removed.

The remaining candidates primarily included:

- Missense variants
- Stop-gain variants
- Other non-synonymous coding variants

This filtering strategy was used for initial prioritization and did not imply that synonymous variants are always biologically irrelevant.

### Step 4 — Prioritization of Clinically Relevant Variants

A total of 22 candidate variants remained following the initial filtering process.

Among these 22 variants, six variants were selected for initial detailed investigation because they were reported as Pathogenic or Likely Pathogenic in at least one of the available ACMG-based or ClinVar annotation fields.

These classifications were treated as existing database or annotation evidence rather than as independent clinical classifications performed as part of this project.

### Step 5 — Gene and Phenotype Review

The prioritized variants and genes were investigated using:

- ClinVar
- OMIM
- PubMed
- Scientific literature

The following factors were considered:

- Gene–disease association
- Variant classification
- Zygosity
- Mode of inheritance
- Phenotype compatibility
- Presence of additional variants in the same gene
- Possibility of a second disease-associated allele
- Family pedigree

## 4.2 Secondary Candidate Analysis

Following the initial prioritization, additional variants were reviewed in selected candidate genes.

This included:

- Additional exonic variants
- Synonymous variants
- Intronic variants
- Potential splice-region variants

Particular attention was given to autosomal recessive genes in which only one potentially relevant variant had initially been identified.

Variants near canonical splice sites were considered particularly important because disruption of normal RNA splicing can cause disease even when a variant does not alter the encoded amino acid sequence.

Canonical splice positions generally include:

- -1
- -2
- +1
- +2

relative to an exon–intron boundary.

Nearby non-canonical positions, such as +3 or -3, may also affect splicing depending on the gene, sequence context, and available functional evidence.

# 5. Candidate Gene Prioritization

Three genes were selected for detailed discussion:

1. **PAH** — Leading candidate
2. **SLC25A5** — Alternative candidate
3. **SLC4A4** — Alternative candidate

These genes were prioritized based on the currently available genomic, clinical, inheritance, and literature evidence.

None of the candidates can currently be considered definitively causative.

# 6. PAH — Leading Candidate

## 6.1 Gene Function

The **PAH** gene encodes phenylalanine hydroxylase, an enzyme responsible for the conversion of phenylalanine to tyrosine.

Deficiency of phenylalanine hydroxylase results in impaired phenylalanine metabolism and can lead to elevated blood phenylalanine concentrations.

Pathogenic variants in PAH are associated with a spectrum of phenylalanine hydroxylase deficiency, including:

- Phenylketonuria (PKU)
- Mild hyperphenylalaninemia
- Mild forms of PKU

PAH-related disorders are inherited in an autosomal recessive manner.

## 6.2 Clinical Relevance

Untreated or inadequately treated phenylalanine hydroxylase deficiency can cause neurological complications.

Depending on disease severity and metabolic control, phenylalanine hydroxylase deficiency may be associated with:

- Developmental delay
- Intellectual disability
- Neurocognitive impairment
- Behavioral abnormalities

Because severe intellectual disability and developmental delay were reported in multiple affected family members, PAH was considered particularly relevant during phenotype-based prioritization.

However, the absence of biochemical information such as plasma phenylalanine measurements and newborn screening records prevents direct confirmation of a phenylalanine metabolism disorder in this family.

## 6.3 Identified Variant

The primary PAH variant identified in the proband was:

**NM_000277.3(PAH):c.688G>A (p.Val230Ile)**

The variant was:

- Missense
- Heterozygous (0/1)
- Located in PAH
- Associated with PAH-related disease in ClinVar

The condition-specific ClinVar record for phenylketonuria classifies this variant as **Likely Pathogenic**, with review by the **ClinGen PAH Variant Curation Expert Panel**. The expert panel applied PAH-specific ACMG/AMP criteria and reported evidence including observations in affected individuals in homozygous or compound heterozygous states [1].

Importantly, classification of a variant as Pathogenic or Likely Pathogenic does not by itself establish that the heterozygous variant is sufficient to cause disease in this individual, because PAH-related disease is autosomal recessive.

## 6.4 Functional and Clinical Evidence

The p.Val230Ile variant has been reported in individuals with mild hyperphenylalaninemia and mild phenylketonuria, including individuals carrying the variant in homozygous or compound heterozygous states [1].

ClinVar records also include clinical and experimental evidence supporting its involvement in PAH deficiency. One clinical submission reports residual mutant enzyme activity of approximately 63% of normal, consistent with a variant associated with a milder biochemical phenotype [1].

Therefore, the variant has substantial evidence supporting disease association in the context of PAH-related disorders, but the patient's heterozygous status means that an additional disease-associated allele would need to be investigated.

## 6.5 Investigation of a Potential Second PAH Allele

Because PAH-related disease is autosomal recessive, a single heterozygous disease-associated variant is not sufficient to establish PAH as the molecular cause of the phenotype.

Additional PAH variants were therefore investigated.

One variant of particular interest was:

**NM_000277.3(PAH):c.735G>A (p.Val245=)**

This variant is synonymous and does not change the encoded amino acid.

The current ClinVar record classifies c.735G>A itself as **Benign**, with multiple submitters and no conflicts for the relevant record [2].

However, the same variant has also been reported as part of the combined haplotype:

**NM_000277.1:c.[722delG;c.735G>A]**

This combined haplotype is classified as **Likely Pathogenic** in ClinVar [3].

Therefore, c.735G>A should not be interpreted as a confirmed pathogenic second allele on its own.

Instead, this observation highlights the importance of determining whether:

- An additional pathogenic PAH variant is present.
- The c.735G>A variant is part of a disease-associated haplotype.
- c.735G>A occurs in cis with another PAH variant.
- A pathogenic allele exists in trans.
- Additional PAH variants are present outside the initially prioritized exonic variants.

The phase of the identified PAH variants is currently unknown [2,3].

## 6.6 Why PAH Was Prioritized

PAH was considered the leading candidate because:

- PAH is a well-established disease gene.
- The identified c.688G>A variant has substantial disease-specific clinical evidence [1].
- Phenylalanine hydroxylase deficiency can produce severe neurodevelopmental consequences when untreated or inadequately controlled.
- Additional PAH variation was identified and requires further investigation.
- The inheritance pattern of the family makes investigation of a recessive mechanism relevant, although the pedigree is not sufficient to establish one.

## 6.7 Limitations of the PAH Interpretation

Several important limitations remain:

- The primary disease-associated variant is heterozygous.
- A confirmed second pathogenic PAH allele has not been identified.
- Phasing information is unavailable.
- Segregation analysis has not been performed.
- Plasma phenylalanine data are unavailable.
- Newborn screening information is unavailable.
- The available phenotype is insufficient to establish a metabolic diagnosis.

Therefore, PAH is currently considered the leading candidate gene, but the available evidence is insufficient to establish it as the definitive molecular diagnosis.

# 7. SLC25A5 — Alternative Candidate

## 7.1 Identified Variant

The following variant was identified:

**NM_001152:c.662C>G (p.Thr221Ser)**

The variant was:

- Missense
- Located on the X chromosome
- Identified in the proband
- Not identified in ClinVar during the initial review

## 7.2 Gene–Disease Relevance

SLC25A5 encodes a mitochondrial solute carrier involved in ADP/ATP exchange.

Vandewalle et al. investigated overlapping Xq24 microdeletions in three unrelated families with non-syndromic intellectual disability. The smallest region of overlap contained **SLC25A5** and **SLC25A43**. Based on additional evidence, the authors proposed SLC25A5 as a novel candidate gene for non-syndromic intellectual disability [4].

The study also reported high expression of SLC25A5 in the cerebral cortex and hippocampus and proposed a role in mitochondrial ADP/ATP exchange and cognitive processes [4].

This study provides candidate-gene and biological evidence supporting further investigation of SLC25A5. However, it does not establish SLC25A5 as a definitively disease-causing gene for the phenotype, nor does it establish the specific p.Thr221Ser variant as pathogenic.

## 7.3 Pedigree Considerations

The presence of affected males and females makes the family pattern more complex than a typical X-linked recessive pedigree.

Potential mechanisms that could contribute to variable expression in females include:

- Skewed X-chromosome inactivation
- Variable expressivity
- Differences in genetic background

However, these mechanisms remain hypotheses in the present case.

The available family data are insufficient to establish that the identified SLC25A5 variant follows an X-linked inheritance pattern.

## 7.4 Required Investigation

The p.Thr221Ser variant requires additional evaluation using:

- Population frequency data such as gnomAD
- Conservation analysis
- Appropriate in silico pathogenicity prediction
- Literature review for the specific variant
- Segregation analysis

Testing additional family members would be particularly informative.

Important questions include:

- Is the variant present in affected males?
- Is the variant present in affected females?
- Is the variant absent in unaffected relatives?
- Was the variant inherited from the mother?
- Does the variant segregate with the phenotype?

## 7.5 Interpretation

SLC25A5 remains an interesting alternative candidate because:

- The gene has been proposed as a candidate for non-syndromic intellectual disability [4].
- The gene has a biologically relevant mitochondrial function.
- The identified variant is located on the X chromosome.
- The reported phenotype is compatible at the gene level.

However:

- Variant-level evidence for p.Thr221Ser remains limited.
- No ClinVar classification was identified for the specific p.Thr221Ser variant during the initial review.
- Segregation data are unavailable.
- The X-linked interpretation remains unconfirmed.

Therefore, SLC25A5 should currently be interpreted as an alternative candidate requiring further investigation.

# 8. SLC4A4 — Alternative Candidate

## 8.1 Identified Variant

The following variant was identified:

**SLC4A4:c.1942G>A**

The variant was:

- Missense
- Heterozygous (0/1)
- Reported with conflicting clinical interpretations

Available classifications included:

- Variant of uncertain significance
- Benign
- Likely benign

Therefore, the identified coding variant alone does not provide sufficient evidence to establish disease causation.

## 8.2 Gene–Disease Association

SLC4A4 is associated with autosomal recessive proximal renal tubular acidosis with ocular abnormalities.

Reported manifestations may include:

- Proximal renal tubular acidosis
- Metabolic acidosis
- Developmental delay
- Intellectual disability
- Glaucoma
- Cataract
- Band keratopathy
- Growth abnormalities

The possibility of intellectual disability and developmental delay makes the gene relevant to the available phenotype [5,6].

However, the absence of renal and ophthalmological clinical information in the present family substantially limits phenotype-based evaluation.

## 8.3 Evidence From Splice-Region Variants

A published case report described compound heterozygous SLC4A4 variants located in exon–intron boundary regions:

- c.1076+3A>C
- c.1772-2A>T

The affected individual presented with severe proximal renal tubular acidosis, glaucoma, and intellectual disability. The variants were inherited from different parents, and the study reported that the SLC4A4 transcript was almost undetectable, supporting a functional effect on gene expression and splicing [5].

Another study investigated the canonical splice-site variant c.1499+1G>A in SLC4A4. The study used a minigene assay and demonstrated aberrant RNA splicing associated with this variant [6].

These studies demonstrate why intronic and splice-region variants should not automatically be excluded during candidate-gene analysis.

## 8.4 Intronic Variant Investigation

The intronic variants identified in the available VCF require transcript-level annotation before clinical interpretation.

Each variant should be evaluated according to:

1. Genomic position
2. Reference genome assembly
3. Relevant transcript
4. Distance from the nearest exon
5. HGVS nomenclature
6. ClinVar classification
7. Population frequency
8. Splice prediction
9. Available functional evidence
10. Published literature

Variants closest to exon–intron boundaries should generally receive higher priority.

Canonical splice-site variants include positions:

- +1
- +2
- -1
- -2

Additional nearby variants such as +3 or -3 may also affect splicing depending on the gene and local sequence context [5].

## 8.5 Interpretation

SLC4A4 remains an alternative candidate because:

- The associated disease can include intellectual disability and developmental delay [5,6].
- SLC4A4-related disease follows an autosomal recessive inheritance pattern.
- Published evidence supports pathogenic splice-region variants [5,6].
- Multiple intronic variants remain to be systematically evaluated.

However:

- The currently identified coding variant has conflicting interpretations.
- A second pathogenic allele has not been confirmed.
- Renal clinical data are unavailable.
- Ophthalmological clinical data are unavailable.

Therefore, SLC4A4 remains a candidate requiring further investigation, particularly through systematic analysis of intronic and splice-region variants.

# 9. Summary of Additional Candidate Genes Evaluated

| Gene | Main Disease Association | Variant(s) / Genetic Context | Preliminary Interpretation |
|---|---|---|---|
| **TYR** | Oculocutaneous albinism type 1 | Two heterozygous missense variants, c.575C>A and c.1205G>A | Possible relevance requires phase determination; no clear albinism phenotype reported |
| **DYSF** | Muscular dystrophy | Two variants identified | Potential biallelic mechanism requires phase and phenotype assessment; no convincing neuromuscular phenotype available |
| **GHR** | Laron syndrome | Non-synonymous variant; ACMG-based annotation Pathogenic but ClinVar VUS | Autosomal recessive disease and phenotype were not strongly compatible |
| **FAM83H** | Primarily amelogenesis imperfecta | c.601C>T (p.Gln201*) | ClinVar Pathogenic but ACMG-based annotation VUS; main disease association does not explain the reported neurological phenotype |
| **MYH7** | Cardiomyopathy and myopathy | c.4817G>A (p.Arg1606His) | ClinVar Likely Pathogenic; no reported cardiac or muscular phenotype |
| **NQO1** | Drug-response and other associations | c.343C>T | No convincing relationship with the investigated phenotype |
| **F5** | Coagulation and thrombophilia-related disorders | c.1601A>G (p.Gln534Arg), homozygous | Poor phenotype compatibility |
| **ABCC2** | Dubin–Johnson syndrome | c.3379G>A, homozygous | No compatible liver phenotype reported |
| **HSPG2** | Skeletal disorders / Schwartz–Jampel syndrome | Rare coding variant | No convincing phenotype match; literature linking rare HSPG2 variation to familial idiopathic scoliosis does not establish causality for the present neurodevelopmental phenotype [7] |
| **TNNT2** | Cardiomyopathy | c.416G>A, heterozygous | No reported cardiac phenotype |
| **LRPPRC** | Mitochondrial complex IV deficiency | c.1928A>G, heterozygous | Conflicting interpretation and no confirmed second allele |
| **TIA1** | ALS / frontotemporal dementia / distal myopathy | c.842A>G, heterozygous | Insufficient phenotype and variant-level evidence |
| **IFT140** | Ciliopathies, renal, skeletal and retinal disorders | Variant with conflicting interpretations | No convincing phenotype match |
| **MPI** | Congenital disorder of glycosylation type Ib | c.1337T>C, heterozygous | No confirmed second pathogenic allele or compatible phenotype |
| **CCDC88C** | Hydrocephalus / spinocerebellar ataxia | c.590G>A, heterozygous | Variant and phenotype evidence insufficient |
| **TGM1** | Congenital ichthyosis | c.1762G>A (p.Ala588Thr), heterozygous | No compatible skin phenotype reported |
| **LAMA2** | Muscular dystrophy | c.922G>A (p.Glu308Lys), heterozygous | Conflicting/benign-leaning evidence and no convincing muscular phenotype |
| **GCKR** | Metabolic quantitative traits | c.1337T>C, heterozygous | Reported as benign; not relevant to the investigated phenotype |

The genes listed above were evaluated based on the currently available information and should not be considered permanently excluded.

Additional clinical, genetic, segregation, or functional evidence may change their prioritization.

# 10. Final Candidate Prioritization

## 10.1 PAH — Leading Candidate

### Strengths

- Established disease gene
- Strong disease-specific clinical evidence for c.688G>A [1]
- Biological relevance to neurodevelopmental impairment
- Additional PAH variation identified and requiring further investigation
- Autosomal recessive inheritance provides a plausible framework for investigating a second allele

### Limitations

- Only one disease-associated allele is currently confirmed
- A second pathogenic allele has not been established
- Phase is unknown
- No segregation analysis is available
- No plasma phenylalanine data are available
- Newborn screening information is unavailable

## 10.2 SLC25A5 — Alternative Candidate

### Strengths

- Proposed association with non-syndromic intellectual disability [4]
- Relevant mitochondrial biological function
- Located on the X chromosome
- Family includes affected males and females

### Limitations

- Limited variant-level evidence
- No ClinVar evidence for the specific p.Thr221Ser variant identified during the initial review
- No segregation data
- X-linked interpretation remains unconfirmed

## 10.3 SLC4A4 — Alternative Candidate

### Strengths

- Associated disease can include intellectual disability and developmental delay [5,6]
- Autosomal recessive inheritance
- Published evidence supports pathogenic splice-region variants [5,6]
- Multiple intronic variants remain to be investigated

### Limitations

- Coding variant has conflicting interpretations
- No confirmed second pathogenic allele
- No renal phenotype information
- No ophthalmological phenotype information

# 11. Limitations

## Limited Clinical Information

Detailed clinical phenotyping was unavailable.

This limited the ability to perform phenotype-driven variant prioritization and to determine whether specific candidate genes have compatible extra-neurological manifestations.

## Lack of Segregation Analysis

The absence of molecular data from additional family members prevented:

- Segregation analysis
- Confirmation of parental origin
- Phasing
- Confirmation of compound heterozygosity
- Determination of cis/trans relationships

## Single-Proband Analysis

Only one affected individual's VCF file was available.

Given the multigenerational family structure, sequencing additional affected and unaffected relatives would substantially improve candidate prioritization.

## Initial Exonic Filtering

The initial workflow focused primarily on exonic non-synonymous variants.

Although useful for initial prioritization, this strategy may miss:

- Splice variants
- Deep intronic variants
- Synonymous variants affecting splicing
- Regulatory variants
- Structural variants not represented in the available VCF

The subsequent review of selected intronic and synonymous variants partially addressed this limitation but did not constitute a comprehensive genome-wide analysis of all non-coding variation.

# 12. Recommended Next Steps

## PAH

- Measure plasma phenylalanine.
- Measure plasma tyrosine.
- Review newborn screening records.
- Review metabolic and dietary history.
- Perform segregation analysis.
- Determine the phase of PAH variants.
- Investigate additional coding and non-coding PAH variants.
- Determine whether a disease-associated PAH haplotype is present.
- Evaluate whether an additional pathogenic allele exists in trans.

## SLC25A5

- Check population frequency in gnomAD.
- Evaluate amino acid conservation.
- Perform appropriate in silico pathogenicity prediction.
- Search the literature for p.Thr221Ser.
- Perform segregation analysis.
- Investigate affected and unaffected relatives.
- Determine whether the variant is maternally inherited.
- Consider X-chromosome inactivation studies if biologically justified.

## SLC4A4

- Convert genomic coordinates to transcript-level HGVS nomenclature.
- Determine the distance of intronic variants from exon boundaries.
- Prioritize canonical and near-canonical splice variants.
- Perform splice prediction analysis.
- Review population frequency.
- Review ClinVar.
- Obtain renal clinical data.
- Obtain ophthalmological clinical data.
- Perform segregation analysis.
- Consider RNA-based functional testing for high-priority splice variants where clinically and technically feasible.

## Additional Family-Based Analysis

If samples are available, sequencing additional affected and unaffected relatives would be highly informative.

Family-based analysis could help determine:

- Whether candidate variants segregate with the phenotype
- Whether variants are inherited or de novo
- Whether multiple variants are in cis or trans
- Whether a recessive model is supported
- Whether an X-linked candidate segregates with affected males and females

# 13. Conclusion

This project demonstrates a case-based approach to variant prioritization using a targeted sequencing panel VCF file from an affected individual in a multigenerational family with a neurodevelopmental phenotype.

A stepwise filtering workflow reduced the candidate set and enabled detailed investigation of multiple disease-associated genes.

Based on the currently available evidence, **PAH was prioritized as the leading candidate gene**.

The identification of PAH:c.688G>A (p.Val230Ile) is supported by substantial disease-specific clinical evidence [1]. The biological compatibility between phenylalanine hydroxylase deficiency and neurodevelopmental impairment further supports continued investigation of this gene.

However, the variant is heterozygous, PAH-related disease is autosomal recessive, and a confirmed second pathogenic allele has not yet been identified. Therefore, the current evidence is insufficient to establish PAH as the definitive molecular diagnosis.

**SLC25A5** and **SLC4A4** were retained as alternative candidate genes.

SLC25A5 is supported by candidate-gene literature concerning non-syndromic intellectual disability, but the specific p.Thr221Ser variant requires additional variant-level and segregation evidence [4]. The available literature provides a rationale for further investigation but does not establish the specific variant as pathogenic.

SLC4A4 is relevant because its associated autosomal recessive disorder can include intellectual disability and ocular and renal manifestations, and published studies demonstrate the importance of splice-region variants in this gene [5,6]. Nevertheless, the currently identified coding variant has conflicting interpretations and a second pathogenic allele has not been established.

Overall, the analysis should be interpreted as a **candidate gene and variant prioritization study rather than a definitive molecular diagnosis**.

Further clinical phenotyping, biochemical testing, segregation analysis, phasing, and additional genomic or functional investigations would be required to determine the molecular basis of the family's neurodevelopmental phenotype.

# 14. Training Context

This project was completed as part of an **International Research Fellowship in Genomics** provided by the **Helix Institute for Medical and Biological Sciences (US)** in collaboration with the **Genomics Laboratory (Iran)**.

The training covered genomic data analysis and interpretation, including:

- FASTA and FASTQ formats
- BAM and VCF files
- NGS quality control
- Read processing and alignment
- Variant detection
- Variant annotation
- Clinical variant interpretation
- ACMG-based variant classification
- Gene–disease databases and resources including ClinVar, OMIM, NCBI, and PubMed

This project was developed for educational and research portfolio purposes and does not represent a clinical diagnostic report.

# References

1. ClinVar. **NM_000277.3(PAH):c.688G>A (p.Val230Ile) and Phenylketonuria.** ClinGen PAH Variant Curation Expert Panel; Likely Pathogenic; reviewed by expert panel. ClinVar Variation ID: VCV000102784.  
   [https://www.ncbi.nlm.nih.gov/clinvar/variation/102784/](https://www.ncbi.nlm.nih.gov/clinvar/variation/102784/)

2. ClinVar. **NM_000277.3(PAH):c.735G>A (p.Val245=).** Germline classification: Benign; multiple submitters, no conflicts. ClinVar RCV000078529.  
   [https://www.ncbi.nlm.nih.gov/clinvar/RCV000078529/](https://www.ncbi.nlm.nih.gov/clinvar/RCV000078529/)

3. ClinVar. **NM_000277.1:c.[722delG;c.735G>A].** Germline classification: Likely Pathogenic. ClinVar Variation ID: VCV000402236.  
   [https://www.ncbi.nlm.nih.gov/clinvar/variation/VCV000402236.1](https://www.ncbi.nlm.nih.gov/clinvar/variation/VCV000402236.1)

4. Vandewalle J, Bauters M, Van Esch H, et al. The mitochondrial solute carrier SLC25A5 at Xq24 is a novel candidate gene for non-syndromic intellectual disability. *Human Genetics*. 2013;132(10):1177–1185.  
   [https://doi.org/10.1007/s00439-013-1322-3](https://doi.org/10.1007/s00439-013-1322-3)

5. Horita S, Simsek E, Simsek T, et al. SLC4A4 compound heterozygous mutations in exon-intron boundary regions presenting with severe proximal renal tubular acidosis and extrarenal symptoms coexisting with Turner’s syndrome: a case report. *BMC Medical Genetics*. 2018;19(1):103.  
   [https://doi.org/10.1186/s12881-018-0612-y](https://doi.org/10.1186/s12881-018-0612-y)

6. Liu Y, Sheng W, Wu J, et al. Case report: Altered pre-mRNA splicing caused by intronic variant c.1499+1G>A in the SLC4A4 gene. *Frontiers in Pediatrics*. 2022;10:890147.  
   [https://doi.org/10.3389/fped.2022.890147](https://doi.org/10.3389/fped.2022.890147)

7. Baschal EA, Wethey CI, Swindle K, et al. Exome sequencing identifies a rare HSPG2 variant associated with familial idiopathic scoliosis. *G3: Genes, Genomes, Genetics*. 2015;5(2):167–174.  
   [https://doi.org/10.1534/g3.114.015669](https://doi.org/10.1534/g3.114.015669)

# Databases and Resources

The following databases and resources were used for variant and gene investigation:

- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)
- [OMIM](https://www.omim.org/)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/)
- [NCBI Gene](https://www.ncbi.nlm.nih.gov/gene/)
- Scientific literature and published case reports

# Disclaimer

This repository is intended for educational and research purposes.

All clinical and family information has been anonymized.

The findings presented here represent exploratory variant prioritization and candidate gene analysis. They should not be considered a definitive clinical diagnosis or used as a substitute for clinical genetic evaluation.
