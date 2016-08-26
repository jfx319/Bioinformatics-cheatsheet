
# Bioinformatics-cheatsheet
A cheat sheet for Bioinformatians.
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents  

- [Biological Concepts](#biological-concepts)
  - [Basics](#basics)
  - [Interaction/Regulation/Association](#interactionregulationassociation)
  - [Biological Processes](#biological-processes)
- [Databases Collecting Basic Elements](#databases-collecting-basic-elements)
  - [Gene/Genome Databases](#genegenome-databases)
  - [Protein/Protein Domain Databases](#proteinprotein-domain-databases)
  - [Transcription Factor Databases](#transcription-factor-databases)
  - [Enhancer Databases](#enhancer-databases)
  - [Drug/Small Molecule Database](#drugsmall-molecule-database)
  - [Other Databases](#other-databases)
- [Databases of Biological interactions/Regulations/Associations](#databases-of-biological-interactionsregulationsassociations)
  - [TFBS/TF Binding Motif/TF Target Databases](#tfbstf-binding-motiftf-target-databases)
  - [Protein-Protein Interaction Databases](#protein-protein-interaction-databases)
  - [Protein-Chemical/Small Molecule Interaction Databases](#protein-chemicalsmall-molecule-interaction-databases)
  - [Pathway Databases](#pathway-databases)
  - [Other Databases](#other-databases-1)
- [Experimental Techniques](#experimental-techniques)
  - [Next Generate Sequencing](#next-generate-sequencing)
  - [Uncategorized](#uncategorized)
- [NGS Data Repositories](#ngs-data-repositories)
- [NGS Data Analysis](#ngs-data-analysis)
  - [Variants Calling](#variants-calling)
    - [SNP Calling](#snp-calling)
- [Variant Databases](#variant-databases)
- [File Formats](#file-formats)
  - [Formats](#formats)
  - [Tools](#tools)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Biological Concepts
### Basics
- **CNV**: The chromosome now has two copies of this section of DNA, rather than one. Copy number variation (CNVs) is a relatively new field in genomics and it is defined as a phenomenon in which sections of the genome are repeated and the number of repeats in the genome varies between individuals in the human population. [@Wiki](https://en.wikipedia.org/wiki/Copy-number_variation)
- **DNA**: Deoxyribonucleic acid is a molecule that carries the genetic instructions used in the growth, development, functioning and reproduction of all known living organisms and many viruses. [@Wiki](https://en.wikipedia.org/wiki/DNA), [@NIH](https://www.genome.gov/25520880/deoxyribonucleic-acid-dna-fact-sheet/)
- **Enhancer**: In genetics, an enhancer is a short (50-1500 bp) region of DNA that can be bound by proteins (activators) to increase the likelihood that transcription of a particular gene will occur. These proteins are usually referred to as transcription factors. [@Wiki](https://en.wikipedia.org/wiki/Enhancer_(genetics))
- **Gene**: A gene is a locus (or region) of DNA which is made up of nucleotides and is the molecular unit of heredity. [@Wiki](https://en.wikipedia.org/wiki/Gene), [@NIH](https://ghr.nlm.nih.gov/primer/basics/gene)
- **Promoter**: In genetics, a promoter is a region of DNA that initiates transcription of a particular gene. Promoters are located near the transcription start sites of genes, on the same strand and upstream on the DNA (towards the 5' region of the sense strand). [@Wiki](https://en.wikipedia.org/wiki/Promoter_(genetics))
- **Protein**: Proteins are large biomolecules, or macromolecules, consisting of one or more long chains of amino acid residues. [@Wiki](https://en.wikipedia.org/wiki/Protein)
- **RNA**: Ribonucleic acid (RNA) is a polymeric molecule implicated in various biological roles in coding, decoding, regulation, and expression of genes. [@Wiki](https://en.wikipedia.org/wiki/RNA)
- **SNP**: A single nucleotide polymorphism, often abbreviated to SNP (pronounced snip; plural snips), is a variation in a single nucleotide that occurs at a specific position in the genome, where each variation is present to some appreciable degree within a population (e.g. >1%). [@Wiki](https://en.wikipedia.org/wiki/Single-nucleotide_polymorphism), [@NIH](https://ghr.nlm.nih.gov/primer/genomicresearch/snp)
- **Super Enhancer**: In genetics, a super-enhancer is a region of the mammalian genome comprising multiple enhancers that is collectively bound by an array of transcription factor proteins to drive transcription of genes involved in cell identity. [@Wiki](https://en.wikipedia.org/wiki/Super-enhancer), [@Nature Genetics](http://www.nature.com/ng/journal/v47/n1/full/ng.3167.html)
- **TF - Transcription Factor**: Transcription factors are proteins that control which genes are turned on or off in the genome. They do so by binding to DNA and other proteins. [@Wiki](https://en.wikipedia.org/wiki/Transcription_factor), [@BroadInstitute](https://www.broadinstitute.org/education/glossary/transcription-factor), [@Scitable](http://www.nature.com/scitable/definition/general-transcription-factor-transcription-factor-167)

### Interactions/Regulations/Associations
- **DNA Sequence Motif**: Sequence motifs are short, recurring patterns in DNA that are presumed to have a biological function. [@Nature Biotechnology](http://www.nature.com/nbt/journal/v24/n4/full/nbt0406-423.html), [@Wiki](https://en.wikipedia.org/wiki/Sequence_motif)
- **PPI - Protein-Protein Interaction**: Protein–protein interactions (PPIs) refer to lasting or ephemeral physical contacts of high specificity established between two or more protein molecules as a result of biochemical events steered by electrostatic forces including the hydrophobic effect. [@Wiki](https://en.wikipedia.org/wiki/Protein–protein_interaction)
- **PWM - Position Weight Matrix/PSWM/PSSM**: A position weight matrix (PWM), also known as a position-specific weight matrix (PSWM) or position-specific scoring matrix (PSSM), is a commonly used representation of motifs (patterns) in biological sequences. [@Wiki](https://en.wikipedia.org/wiki/Position_weight_matrix)
- **TFBS - Transcription Factor Binding Site/DNA Binding Site**: DNA binding sites are a type of binding site found in DNA where other molecules may bind. [@Wiki](https://en.wikipedia.org/wiki/DNA_binding_site)

### Biological Processes
- **Expression (Gene expression)**: Gene expression is the process by which information from a gene is used in the synthesis of a functional gene product. These products are often proteins, but in non-protein coding genes such as transfer RNA (tRNA) or small nuclear RNA (snRNA) genes, the product is a functional RNA. [@Wiki](https://en.wikipedia.org/wiki/Gene_expression), [@Scitable](http://www.nature.com/scitable/topicpage/gene-expression-14121669)
- **Pathway (Biological pathway)**: A biological pathway is a series of actions among molecules in a cell that leads to a certain product or a change in a cell. Such a pathway can trigger the assembly of new molecules, such as a fat or protein. Pathways can also turn genes on and off, or spur a cell to move. [@Wiki](https://en.wikipedia.org/wiki/Biological_pathway), [@NIH](https://www.genome.gov/27530687/biological-pathways-fact-sheet/)
- **Transcription**: Transcription is the first step of gene expression, in which a particular segment of DNA is copied into RNA (mRNA) by the enzyme RNA polymerase. [@Wiki](https://en.wikipedia.org/wiki/Transcription_(genetics))
- **Translation**: In molecular biology and genetics, translation is the process in which cellular ribosomes create proteins. In translation, messenger RNA (mRNA)—produced by transcription from DNA—is decoded by a ribosome to produce a specific amino acid chain, or polypeptide. [@Wiki](https://en.wikipedia.org/wiki/Translation_(biology))

## Databases Collecting Basic Elements
### Gene/Genome Databases
- **[CADgene](http://www.bioguo.org/CADgene)**: Coronary Artery Disease Gene Database.
- **[Candida Genome Database](www.candidagenome.org/)**: Resource for genomic sequence data and gene and protein information for Candida albicans.
- **[Ensembl genome browser](www.ensembl.org/)**: Ensembl is a joint project between EMBL - EBI and the Sanger Institute to develop a software system which produces and maintains automatic annotation on selected eukaryotic genomes.
- **[GenAge](http://genomics.senescence.info/genes)**: GenAge: The Ageing Gene Database.
- **[GeneCards](www.genecards.org/)**: GeneCards is a searchable, integrated, database of human genes that provides concise genomic related information, on all known and predicted human genes.
- **[H-InvDB](http://www.h-invitational.jp)**: H-Invitational Database (H-InvDB) is an integrated database of human genes and transcripts.
- **[FlyBase](http://flybase.org)**: FlyBase: a database of Drosophila Genes & Genomes.
- **[HGNC](http://www.genenames.org/)**: HGNC is responsible for approving unique symbols and names for human loci, including protein coding genes, ncRNA genes and pseudogenes, to allow unambiguous scientific communication.
- **[KEGG GENES](http://www.genome.jp/kegg/genes.html)**: KEGG GENES is a collection of gene catalogs for all complete genomes generated from publicly available resources, mostly NCBI RefSeq and GenBank.
- **[MGI - Mouse Genome Informatics](http://www.informatics.jax.org/)**: MGI is the international database resource for the laboratory mouse, providing integrated genetic, genomic, and biological data to facilitate the study of human health and disease. 
- **[NCBI Gene](www.ncbi.nlm.nih.gov/gene)**: A portal to gene-specific content based on NCBI's RefSeq project, information from model organism databases, and links to other resources.
- **[RGD - Rat Genome Database](rgd.mcw.edu/)**: The Rat Genome Database (RGD) is the premier site for genetic, genomic, phenotype, and disease data generated from rat research.
- **[Saccharomyces Genome Database](www.yeastgenome.org/)**: The Saccharomyces Genome Database (SGD) provides comprehensive integrated biological information for the budding yeast Saccharomyces cerevisiae.
- **[WormBase](http://www.wormbase.org)**: Worm Base.

### Protein/Protein Domain Databases
- **[iPfam](http://ipfam.sanger.ac.uk)**: Protein families database of alignments and HMMs.
- **[iProClass](http://pir.georgetown.edu/pirwww/dbinfo/iproclass.shtml)**: The iProClass database provides value-added information reports for UniProtKB and unique NCBI Entrez protein sequences in UniParc, with links to over 160 biological databases, including databases for protein families, functions and pathways, interactions, structures and structural classifications, genes and genomes, ontologies, literature, and taxonomy.
- **[MiST](http://mistdb.com)**: The Microbial Signal Transduction database contains the signal transduction proteins for bacterial and archaeal genomes.
- **[ModBase](http://modbase.compbio.ucsf.edu/modbase-cgi/index.cgi)**: ModBase is a database of comparative protein structure models, calculated by modeling pipeline [ModPipe](http://salilab.org/modpipe).
- **[PepBank](http://pepbank.mgh.harvard.edu)**: PepBank is a database of peptides based on sequence text mining and public peptide data sources.
- **[PROFESS](http://cse.unl.edu/~profess)**: PROFESS is a biology database system that integrates databases describing PROtein Functions, Evolution, Structures and Sequences.
- **[ProtCID](http://dunbrack2.fccc.edu/protcid)**: PROTein Common Interfaces Database.
- **[SUBA3](http://suba.plantenergy.uwa.edu.au)**: The SUBcellular localization database for Arabidopsis proteins.
- **[SynSysNet](http://bioinformatics.charite.de/synsysnet)**: Synaptic Proteins Database.

### Transcription Factor Databases
- **[AnimalTFDB](http://bioinfo.life.hust.edu.cn/AnimalTFDB/)**: AnimalTFDB is a comprehensive database including classification and annotation of genome-wide transcription factors (TFs), transcription co-factors and chromatin remodeling factors in 65 animal genomes. 
- **[DBD](www.transcriptionfactor.org/)**: DBD is a database of predicted transcription factors in completely sequenced genomes.
- **[PlantTFDB](http://planttfdb.cbi.pku.edu.cn/)**: Plant transcription factor database, a portal for the functional and evolutionary study of plant transcription factors.
- **[TFCat](www.tfcat.ca/)**: TFCat: The curated catalog of mouse and human transcription factors.
- **[TFdb](http://genome.gsc.riken.jp/TFdb/)**: The Mouse transcription factor database (TFdb) is a database containing mouse transcription factor genes and their related genes.

### Enhancer Databases
- **[VISTA Enhancer Browser](enhancer.lbl.gov/)**: The VISTA Enhancer Browser is a central resource for experimentally validated human and mouse noncoding fragments with gene enhancer activity as assessed in transgenic mice.  
- **[DENdb](http://www.cbrc.kaust.edu.sa/dendb/)**: DENdb is a centralized on-line repository of predicted enhancers derived from multiple human cell-lines.
- **[dbSUPER](http://bioinfo.au.tsinghua.edu.cn/dbsuper/)**: dbSUPER is the first integrated and interactive database of super-enhancers.
- **[SEA](http://sea.edbc.org/)**: a super-enhancer archive.
- **[EI](http://www.dcode.org/EI/)**: Database of EI candidate tissue-specific enhancers: Predicting Tissue-Specific Enhancers in the Human Genome. [@Paper](http://www.genome.org/cgi/reprint/17/2/201)

### Drug/Small Molecule Database
- **[AHD2.0](http://ahd.cbi.pku.edu.cn)**: The aim of the Arabidopsis hormone database is to provide a systematic and comprehensive view of morphological phenotypes regulated by plant hormones, as well as regulatory genes participating in numerous plant hormone responses.
- **[DrugBank](http://www.drugbank.ca/)**: The DrugBank database is a unique bioinformatics and cheminformatics resource that combines detailed drug (i.e. chemical, pharmacological and pharmaceutical) data with comprehensive drug target (i.e. sequence, structure, and pathway) information.
- **[TTD - Therapeutic Target Database](http://bidd.nus.edu.sg/BIDD-Databases/TTD/TTD.asp)**: A database to provide information about the known and explored therapeutic protein and nucleic acid targets, the targeted disease, pathway information and the corresponding drugs directed at each of these targets.

### Other Databases
- **[ASD](http://mdl.shsmu.edu.cn/ASD)**: Allosteric Database.

## Databases of Biological interactions/Regulations/Associations
### TFBS/TF Binding Motif/TF Target Databases
- **[Cistrome DB](http://dc2.cistrome.org/)**: Cistrome DB is a comprehensive resource of hg38 and mm10 ChIP-seq data collection. Here is a brief introduction about the workflow of [ChiLin](http://cistrome.org/chilin/).
- **[CollecTF](http://www.collectf.org/browse/home/)**: CollecTF is a database of transcription factor binding sites (TFBS) in the Bacteria domain.
- **[CTCFBSDB](http://insulatordb.uthsc.edu/)**: A database for CTCF binding sites and genome organization.
- **[FactorBook](http://www.factorbook.org/)**: This website organizes the analysis results of ENCODE TF ChIP-seq data, integrated with other ENCODE data such as ChIP-seq of histone marks and nucleosome occupancy.
- **[footprintDB](http://floresta.eead.csic.es/footprintdb/index.php)**: footprintDB is a web server for assigning putative cis DNA motifs to input transcription factors (TFs) and conversely for predicting which TFs that might recognize input DNA motifs.
- **[hmChIP](http://jilab.biostat.jhsph.edu/database/cgi-bin/hmChIP.pl)**: hmChIP is a database of genome-wide chromatin immu-noprecipitation (ChIP) data in human and mouse.
- **[HOCOMOCO](http://hocomoco.autosome.ru/)**: HOmo sapiens COmprehensive MOdel COllection (HOCOMOCO) contains transcription factor (TF) binding models represented as classic Position Weight Matrices (PWMs, also known as Position-Specific Scoring Matrices, PSSMs) and precalculated score thresholds.
- **[HOMER Motif Database](http://homer.salk.edu/homer/motif/motifDatabase.html)**: This database is maintained as part of HOMER and is mostly based on the analysis of public ChIP-Seq data sets.
- **[hPDI](http://bioinfo.wilmer.jhu.edu/PDI/)**: The hPDI database holds experimental protein-DNA interaction data for humans identified by protein microarray assays.
- **[HTRIdb](http://www.lbbc.ibb.unesp.br/htri)**: Human Transcriptional Regulation Interaction Database.
- **[JASPAR](jaspar.binf.ku.dk/)**: The high-quality transcription factor binding profile database.
- **[MAPPER](http://genome.ufl.edu/mapper/)**: MAPPER is a platform for the computational identification of transcription factor binding sites (TFBSs) in multiple genomes, that combines TRANSFAC® and JASPAR data with the search power of profile hidden Markov models (HMMs).
- **[MotifMap](http://motifmap.ics.uci.edu/)**: The MotifMap system provides comprehensive maps of candidate regulatory elements encoded in the genomes of model species using databases of transcription factor binding motifs, refined genome alignments, and a comparative genomic statistical approach - Bayesian Branch Length Score.
- **[oPOSSUM](http://opossum.cisreg.ca/oPOSSUM3/)**: oPOSSUM is a web-based system for the detection of over-represented conserved transcription factor binding sites and binding site combinations in sets of genes or sequences.
- **[SwissRegulon](http://swissregulon.unibas.ch/fcgi/sr/swissregulon)**: Swissregulon Database contains genome-wide annotations of regulatory sites.
- **[TFBSshape](http://rohslab.cmb.usc.edu/TFBSshape/)**: TFBSshape provides DNA shape features for transcription factor binding sites (TFBSs) that in addtion to sequence features, usually in the form of position weight matrices (PWMs), characterize DNA binding specificities of transcription factors (TFs) from 23 different species.
- **[TRANSFAC](http://www.biobase-international.com/product/transcription-factor-binding-sites)**: TRANSFAC® is a unique knowledge-base containing published data on eukaryotic transcription factors and miRNAs, their experimentally-proven binding sites, and regulated genes.
- **[UniPROBE](http://the_brain.bwh.harvard.edu/uniprobe/index.php)**: The UniPROBE (Universal PBM Resource for Oligonucleotide Binding Evaluation) database hosts data generated by universal protein binding microarray (PBM) technology on the in vitro DNA binding specificities of proteins. 

### Protein-Protein Interaction Databases
- **[2P2Idb](http://2p2idb.cnrs-mrs.fr)**: 2P2I<sub>DB</sub> is a hand-curated database dedicated to the structure of protein-protein complexes with known small molecule inhibitors.
- **[3D-Interologs](http://3d-interologs.life.nctu.edu.tw/index.php)**: The 3D-Interologs is a cross-species interacting database inferring from three-dimensional (3D) protein structure complexes and a novel scoring function by using 3D-domain interologs.
- **[3DID](http://3did.irbbarcelona.org)**: The database of three-dimensional interacting domains (3did) is a collection of high-resolution three-dimensional structural templates for domain-domain interactions.
- **[ANAP](http://gmdd.shgmo.org/Computational-Biology/ANAP)**: Arabidopsis Network Analysis Pipeline.
- **[AntiJen](http://www.ddg-pharmfac.net/antijen/AntiJen/antijenhomepage.htm)**: AntiJen v2.0, is a database containing quantitative binding data for peptides binding to MHC Ligand, TCR-MHC Complexes, T Cell Epitope, TAP , B Cell Epitope molecules and immunological Protein-Protein interactions.
- **[APID](http://cicblade.dep.usal.es:8080/APID/init.action)**: APID (Agile Protein Interactomes DataServer) provides a comprehensive collection of protein interactomes for more than 400 organisms based in the integration of known experimentally validated protein-protein physical interactions (PPIs).
- **[ASPD](http://wwwmgs.bionet.nsc.ru/mgs/gnw/aspd)**: ASPD (Artificial Selected Proteins/Peptides Database) is a curated database on selected from randomized pools proteins and peptides.
- **[ATDB](http://protchem.hunnu.edu.cn/toxin/index.jsp)**:ATDB mainly focuses on construct a globe-scale animal toxin-channel interaction network based on literatures and database annotations.
- **[AtPID](http://www.megabionet.org/atpid/webfile)**: Arabidopsis thaliana Protein Interactome Database.
- **[Bacteriome.org](http://128.100.134.188/bacteriome)**: Bacterial Protein Interaction Database for Escherichia Coli.
- **[BIANA](http://sbi.imim.es/web/index.php/research/servers/biana?page=biana.server)**: Biologic Interaction and Network Analysis.
- **[BID](http://tsailab.chem.pacific.edu/wikiBID/index.php/Main_Page)**: Binding Interface Database.
- **[BioGRID](thebiogrid.org/)**: BioGRID Is An Online Interaction Respository With Data Compiled Through Comprehensive Curation Efforts.
- **[BISC](http://bisc.cse.ucsc.edu)**: BISC(BInary SubComplex Database) is a new protein-protein interaction (PPI) database intending to bridge between the two communities most active in their characterisation: structural biology and functional genomics researchers.
- **[CCSB Interactome Database](http://interactome.dfci.harvard.edu)**: Center for Cancer Systems Biology Interactome Database.
- **[ComSim](http://antares.protres.ru/comsin)**: Database of protein structures in bound (Complex) and unbound (Single) states.
- **[CORUM](http://mips.helmholtz-muenchen.de/genre/proj/corum/index.html)**: Comprehensive resource of mammalian protein complexes.
- **[CTDB](http://calcium.uhnres.utoronto.ca/ctdb/flash.htm)**: Calmodulin Target Database.
- **[CutDB](http://cutdb.burnham.org)**: CutDB: Proteolytic Event Database.
- **[DeathDomain](http://www.deathdomain.org)**: A manually curated database of protein-protein interactions for Death Domain Superfamily.
- **[DIMA](http://webclu.bio.wzw.tum.de/dima/index.jsp)**: DIMA is a Domain Interaction MAp and aims at becoming a comprehensive resource for functional and physical interactions among conserved protein-domains.
- **[DIP](http://dip.doe-mbi.ucla.edu/)**: The DIP<sup>TM</sup> database catalogs experimentally determined interactions between proteins.
- **[DOMINE](http://domine.utdallas.edu/cgi-bin/Domine)**: DOMINE is a database of known and predicted protein domain (domain-domain) interactions.
- **[DOMINO](http://mint.bio.uniroma2.it/domino)**: DOMINO is an open-access database comprising more than 3900 annotated experiments describing interactions mediated by protein-interaction domains.
- **[DOMMINO](http://orion.rnet.missouri.edu/~nz953/DOMMINO)**: Database of MacroMolecular Interactions .
- **[DroID](http://www.droidb.org/)**: DroID is a comprehensive gene and protein interactions (interactome) database designed specifically for the model organism Drosophila.
- **[DroPNet](http://dropnet.isima.fr/DroPNet_project/index.faces)**: Drosophila Protein Network.
- **[EciD](http://ecid.bioinfo.cnio.es)**: E. coli Interaction Database.
- **[FunCoup](http://funcoup.sbc.su.se)**: FunCoup is a framework to infer genome-wide functional couplings in 11 model organisms.
- **[Gene3D](http://gene3d.biochem.ucl.ac.uk)**: Gene3D takes CATH domain families (from PDB structures) and assigns them to the millions protein sequences (using Hidden Markov models generated from HMMER) with no PDB structures.
- **[gpDB](http://biophysics.biol.uoa.gr/gpDB/index.jsp)**: a database of GPCRs, G-proteins, Effectors and their interactions.
- **[GWIDD](http://gwidd.bioinformatics.ku.edu)**: Genome-WIde protein Docking Database.
- **[HCPIN](http://nesg.org:9090/HCPIN)**: Human Cancer Protein Interaction Network.
- **[HCVpro](http://cbrc.kaust.edu.sa/hcvpro)**: Hepatitus C Virus Protein Interaction Database.
- **[HINT](http://hint.yulab.org)**:HINT (High-quality INTeractomes) is a database of high-quality protein-protein interactions in different organisms.
- **[HitPredict](http://hintdb.hgc.jp/htp)**: HitPredict is a resource of experimentally determined protein-protein interactions with reliability scores.
- **[HIV-1 Human Interaction Database](http://www.ncbi.nlm.nih.gov/RefSeq/HIVInteractions)**: The HIV-1, human interactions project collates published reports of two types of interactions - protein interactions, and human gene knock-downs that affect virus replication and infectivity (reported as 'replication interactions').
- **[HIVMID](http://www.hiv.lanl.gov/content/immunology)**: HIV Molecular Immunology Database.
- **[HotRegion](http://prism.ccbb.ku.edu.tr/hotregion)**: A Database of Cooperative Hotspots.
- **[HP-DPI](http://dpi.nhri.org.tw)**: Helicobacter pylori Database of Protein Interactomes.
- **[HPID](http://www.hpid.org)**: Human Protein Interaction Database.
- **[HPIDB](http://agbase.msstate.edu/hpi/main.html)**: Host-Pathogen Interaction Database.
- **[HPRD](http://www.hprd.org/)**: The Human Protein Reference Database represents a centralized platform to visually depict and integrate information pertaining to domain architecture, post-translational modifications, interaction networks and disease association for each protein in the human proteome.
- **[Human-gpDB](http://bioinformatics.biol.uoa.gr/human_gpdb)**: A database of human GPCRs, G-proteins, Effectors and their interactions.
- **[HumanPSD](http://www.proteome.com/control/researchproducts/insilico/proteome/details)**: Human Proteome Survey Database .
- **[HuPI](http://hupi.ircm.qc.ca/hupi)**: database of the Human Proteotheque Initiative.
- **[I2D](http://ophid.utoronto.ca)**: Interologous Interaction Database.
- **[IBIS](http://www.ncbi.nlm.nih.gov/Structure/ibis/ibis.cgi)**: Inferred Biomolecular Interactions (protein-protein, protein-small molecule, protein nucleic acids and protein-ion interactions) Server.
- **[ICBS](http://icbs.ics.uci.edu)**: A database of protein-protein interactions mediated by interchain ß-sheet formation.
- **[IMEx](http://www.imexconsortium.org)**: The International Molecular Exchange Consortium.
- **[iMOTdb](http://caps.ncbs.res.in/imotdb)**: Interacting motifs in proteins database.
- **[InnateDB](http://www.innatedb.ca)**: A Knowledge Resource for Innate Immunity Interactions and Pathways.
- **[INstruct](http://instruct.yulab.org)**: a database of 3D protein interactome networks with structural resolution.
- **[IntAct](www.ebi.ac.uk/intact/)**: IntAct provides a freely available, open source database system and analysis tools for molecular interaction data.
- **[Interactome](http://interactome-cmp.ucsf.edu/)**: Krogan Lab Interactome Database.
- **[InterDom](http://interdom.i2r.a-star.edu.sg)**: InterDom is a database of putative interacting protein domains derived from multiple sources, ranging from domain fusions (Rosetta Stone), protein interactions (DIP and BIND), protein complexes (PDB), to scientific literature (MEDLINE). 
- **[InterEvol](http://biodev.cea.fr/interevol)**: InterEvol database is designed for the analysis of co-evolution events at the interface of known structures of hetero- and homo-oligomers.
- **[Interfaces](http://home.ku.edu.tr/~okeskin/INTERFACE/INTERFACES.html)**: DATASET OF PROTEIN-PROTEIN INTERFACES.
- **[Interolog](http://interolog.gersteinlab.org)**: Interolog/Regulog Database.
- **[InteroPorc](http://biodev.extra.cea.fr/interoporc)**: InteroPorc is an automatic prediction tool to infer protein-protein interaction networks.
- **[iRefIndex](http://irefindex.org/wiki/index.php?title=iRefIndex)**: iRefIndex provides an index of protein interactions available in a number of primary interaction databases including BIND, BioGRID, CORUM, DIP, HPRD, InnateDB, IntAct, MatrixDB, MINT, MPact, MPIDB and MPPI.
- **[iRefWeb](http://wodaklab.org/iRefWeb)**: Interaction Reference Index Web Interface.
- **[IRView](http://ir.hgc.jp)**: a database and viewer of interacting regions (IRs) in protein sequences.
- **[MatrixDB](http://matrixdb.univ-lyon1.fr/)**: MatrixDB stores experimental data established by full-length proteins, matricryptins, glycosaminoglycans, lipids and cations.
- **[MINT](http://mint.bio.uniroma2.it/)**: MINT focuses on experimentally verified protein-protein interactions mined from the scientific literature by expert curators.
- **[MIPS-MPPI](http://mips.helmholtz-muenchen.de/proj/ppi)**: MIPS Mammalian Protein-Protein Interaction Database.
- **[MPI-LIT](http://www.jcvi.org/mpidb/interaction.php?dbsource=MPI-LIT)**: the microbial protein interaction database.
- **[MPID](http://bioinformatics.cau.edu.cn/cgi-bin/zzd-cgi/ppi/mpid.pl)**: Magnaporthe grisea Protein-protein Interaction Database.
- **[MPID-T](http://variome.bic.nus.edu.sg/mpidt/index.html)**: MHC-Peptide Interaction Database.
- **[MPIDB](http://www.jcvi.org/mpidb/about.php)**: Microbial Protein Interaction Database.
- **[NCG](http://bio.ieo.eu/ncg2)**: NCG collects information on duplicability, orthology, evolutionary appearance and protein interactions network (PIN) properties of 736 cancer genes.
- **[NCPI](http://protein.cau.edu.cn/ncpi)**: Neurospora Crassa Protein Interactome Database.
- **[Negatome](http://mips.helmholtz-muenchen.de/proj/ppi/negatome)**: The Negatome is a collection of protein and domain pairs which are unlikely engaged in direct physical interactions.
- **[PRISM](http://cosbi.ku.edu.tr/prism/)**: Protein Interactions by Structural Matching.
- **[PCRPi-DB](http://www.bioinsilico.org/cgi-bin/PCRPIDB/htmlPCRPI/home)**: PCRPi-DB is a database of computationally annotated hot spots in protein interfaces.
- **[PDZBase](http://icb.med.cornell.edu/services/pdz/start)**: PDZBase is a manually curated protein-protein interaction database developed specifically for interactions involving PDZ domains.
- **[PICCOLO](http://www-cryst.bioc.cam.ac.uk/~richard/piccolo/about.php)**: PICCOLO is a comprehensive database of structurally-characterized protein-protein interactions described at atomic level.
- **[PIPs](http://www.compbio.dundee.ac.uk/www-pips/)**: PIPs is a database of predicted human protein-protein interactions. 
- **[PiSITE](http://pisite.hgc.jp)**: PiSITE is a web-based database of protein interaction sites.
- **[PPIRA](http://protein.cau.edu.cn/ppira)**: Protein-Protein Interactions between Ralstonia solanacearum and Arabidopsis thaliana.
- **[PDBePISA](http://www.ebi.ac.uk/pdbe/pisa/)**: PDBePISA is an interactive tool for the exploration of macromolecular interfaces.
- **[PRIN](http://bis.zju.edu.cn/prin)**: Predicted Rice Interactome Database.
- **[RKD](http://rkd.ucdavis.edu/interactome.shtml)**: Rice Kinase Database.
- **[SCOPPI](http://scoppi.biotec.tu-dresden.de/scoppi/index.html)**: Structural classification of protein-protein interfaces.
- **[SCOWLP](http://www.scowlp.org/scowlp)**: structural classification of protein binding reasons for atomic comparative analysis of protein interactions.
- **[SNAPPI-DB](http://www.compbio.dundee.ac.uk/SNAPPI)**: Structures, iNterfaces and Alignments for Protein-Protein Interactions.
- **[STRING](string-db.org/)**: functional protein association networks.
- **[Struct2Net](http://groups.csail.mit.edu/cb/struct2net/webserver)**: Structure-based Computational Predictions of Protein-Protein Interactions.
- **[SYFPEITHI](http://www.syfpeithi.de)**: Database of MHC Ligands and Peptide Motifs.
- **[TissueNet](http://netbio.bgu.ac.il/tissuenet)**: The Database of Human Tissue Protein-Protein Interactions.
- **[TRIP](http://www.trpchannel.org)**: a manually curated database of protein-protein interactions for mammalian TRP channels.
- **[Wiki-Pi](http://severus.dbmi.pitt.edu/wiki-pi)**: Wiki-Pi: a wiki resource centred on human protein-protein interactions.
- **[XooNET](http://bioportal.kobic.re.kr/XooNET)**: Integrated Protein-Protein Interaction database of Xanthomonas oryzae pathovar oryzae KACC1031.

### Protein-Chemical/Small Molecule Interaction Databases
- **[ChemProt](http://potentia.cbs.dtu.dk/ChemProt/)**: The ChemProt 3.0 server is a ressource of annotated and predicted chemical-protein interactions. 

### Pathway Databases
- **[ConsensusPathDB](http://consensuspathdb.org/)**: ConsensusPathDB is a database that integrates different types of functional interactions between physical entities in the cell like genes, RNA, proteins, protein complexes and metabolites in order to assemble a more complete and a less biased picture of cellular biology.
- **[KEGG PATHWAY](www.genome.jp/kegg/pathway.html)**: KEGG PATHWAY is a collection of manually drawn pathway maps representing our knowledge on the molecular interaction and reaction networks for different aspects.
- **[MetaCyc](http://metacyc.org/)**: MetaCyc is a curated database of experimentally elucidated metabolic pathways from all domains of life.
- **[MouseCyc](http://www.informatics.jax.org/pathways.shtml)**: MouseCyc is a database of curated biochemical pathways data for the laboratory mouse that can be integrated with functional and phenotypic data from MGI.
- **[PANTHER Pathway](http://www.pantherdb.org/pathway/)**: PANTHER Pathway consists of over 177, primarily signaling, pathways, each with subfamilies and protein sequences mapped to individual pathway components. 
- **[Pathway Commons](http://pathwaycommons.org/)**: Pathway Commons aims to store and disseminate knowledge about biological pathways. Information is sourced from public pathway databases and is readily searched, visualized, and downloaded.
- **[Reactome](http://reactome.org/)**: Reactome is a free, open-source, curated and peer reviewed pathway database.
- **[PLANTCYC](http://www.plantcyc.org/)**: PlantCyc is a metabolic pathway reference database containing more than 800 pathways and their catalytic enzymes and genes, as well as compounds from over 350 plant species. It includes: [AraCyc](http://www.plantcyc.org/databases/aracyc/14.0)(Arabidopsis thaliana col), [BarleyCyc](http://www.plantcyc.org/databases/barleycyc/4.0)(Hordeum vulgare), [BrachypodiumCyc](http://www.plantcyc.org/databases/brachypodiumcyc/4.0)(Brachypodium distachyon), [CassavaCyc](http://www.plantcyc.org/databases/cassavacyc/6.0)(Manihot esculenta esculenta), [ChineseCabbageCyc](http://www.plantcyc.org/databases/chinesecabbagecyc/4.0)(Brassica rapa ssp. pekinensis), [ChlamyCyc](http://www.plantcyc.org/databases/chlamycyc/6.0)(Chlamydomonas reinhardtii), [CornCyc](http://www.plantcyc.org/databases/corncyc/7.0)(Zea	mays mays), [GrapeCyc](http://www.plantcyc.org/databases/grapecyc/6.0)(Vitis vinifera), [MossCyc](http://www.plantcyc.org/databases/mosscyc/5.0)(Physcomitrella patens), [OryzaCyc](http://www.plantcyc.org/databases/oryzacyc/4.0)(Oryza sativa japonica group), [PapayaCyc](http://www.plantcyc.org/databases/papayacyc/5.0)(Carica papaya), [PoplarCyc](http://www.plantcyc.org/databases/poplarcyc/9.0)(Populus trichocarpa, other Populus species and hybrids), [PotatoCyc](http://www.plantcyc.org/databases/potatocyc/3.0)(Solanum tuberosum), [SelaginellaCyc](http://www.plantcyc.org/databases/selaginellacyc/5.0)(Selaginella moellendorffii), [SetariaCyc](http://www.plantcyc.org/databases/setariacyc/4.0)(Setaria italica), [SorghumBicolorCyc](http://www.plantcyc.org/databases/sorghumbicolorcyc/4.0)(Sorghum bicolor), [SoyCyc](http://www.plantcyc.org/databases/soycyc/7.0)(Glycine max), [SpirodelaCyc](http://www.plantcyc.org/databases/spirodelacyc/2.0)(Spirodela polyrhiza), [SwitchgrassCyc](http://www.plantcyc.org/databases/switchgrasscyc/4.0)(Panicum virgatum), [TomatoCyc](http://www.plantcyc.org/databases/tomatocyc/2.0)(Solanum lycopersicum), [WheatACyc](http://www.plantcyc.org/databases/wheatacyc/2.0)(Triticum urartu), [WheatDCyc](http://www.plantcyc.org/databases/wheatdcyc/2.0)(Aegilops tauschii)
- **[SignaLink](http://signalink.org/)**: An integrated resource to analyze signaling pathway cross-talks, transcription factors, miRNAs and regulatory enzymes.
- **[SMPDB](http://smpdb.ca/)**: SMPDB (The Small Molecule Pathway Database) is an interactive, visual database containing more than 618 small molecule pathways found in humans. More than 70% of these pathways (>433) are not found in any other pathway database.
- **[Yeast Pathways Database](http://pathway.yeastgenome.org/)**: The Yeast Pathways Database is a collection of manually curated metabolic pathways and enzymes of Saccharomyces cerevisiae.

### Other Databases
- **[CORNET](https://cornet.psb.ugent.be)**: CORrelation NETworks.
- **[GeneMANIA](http://www.genemania.org)**: GeneMANIA finds other genes that are related to a set of input genes, using a very large set of functional association data.

## Experimental Techniques
### PPI Detection
- **[CoIP - Co-immunoprecipitation](https://en.wikipedia.org/wiki/Co-immunoprecipitation)**: is considered to be the gold standard assay for protein–protein interactions, especially when it is performed with endogenous (not overexpressed and not [tagged](https://en.wikipedia.org/wiki/Epitope#Epitope_tags)) proteins. The protein of interest is isolated with a specific antibody. Interaction partners which stick to this protein are subsequently identified by [Western blotting](https://en.wikipedia.org/wiki/Western_blotting). Interactions detected by this approach are considered to be real. 
- **[Bimolecular fluorescence complementation](https://en.wikipedia.org/wiki/Bimolecular_fluorescence_complementation)**: (BiFC) is a new technique in observing the interactions of proteins. Combining with other new techniques, this method can be used to screen protein–protein interactions and their modulators, [DERB](https://en.wikipedia.org/wiki/DERB).
- **[Affinity electrophoresis](https://en.wikipedia.org/wiki/Affinity_electrophoresis)**: as used for estimation of [binding constant](https://en.wikipedia.org/wiki/binding_constant)s, as for instance in [lectin](https://en.wikipedia.org/wiki/lectin) affinity electrophoresis or characterization of molecules with specific features like [glycan](https://en.wikipedia.org/wiki/glycan) content or [ligand](https://en.wikipedia.org/wiki/ligand) binding.
- **Pull-down assays**: are a common variation of [immunoprecipitation](https://en.wikipedia.org/wiki/immunoprecipitation) and [immunoelectrophoresis](https://en.wikipedia.org/wiki/immunoelectrophoresis) and are used identically, although this approach is more amenable to an initial screen for interacting proteins.
- **[Label transfer](https://en.wikipedia.org/wiki/Label_transfer)**: can be used for screening or confirmation of protein interactions and can provide information about the interface where the interaction takes place. Label transfer can also detect weak or transient interactions that are difficult to capture using other ''in vitro'' detection strategies. In a label transfer reaction, a known protein is tagged with a detectable label. The label is then passed to an interacting protein, which can then be identified by the presence of the label.
- **[Y2H - Yeast Two-Hybrid](https://en.wikipedia.org/wiki/yeast_two-hybrid)**: Y2H screen investigates the interaction between artificial fusion proteins inside the nucleus of yeast. This approach can identify binding partners of a protein in an unbiased manner.
- **[Phage display](https://en.wikipedia.org/wiki/Phage_display)**: used for the high-throughput screening of protein interactions
- **[TAP - Tandem Affinity Purification](https://en.wikipedia.org/wiki/Tandem_affinity_purification)**: (TAP) method allows high throughput identification of protein interactions. In contrast to yeast two-hybrid approach the accuracy of the method can be compared to those of small-scale experiments and the interactions are detected within the correct cellular environment as by [co-immunoprecipitation](https://en.wikipedia.org/wiki/co-immunoprecipitation). However, the TAP tag method requires two successive steps of protein purification and consequently it can not readily detect transient protein–protein interactions. 
- **[Cross-link/Chemical cross-linking](https://en.wikipedia.org/wiki/cross-link|Chemical_cross-linking)**: is often used to "fix" protein interactions in place before trying to isolate/identify interacting proteins. Common crosslinkers for this application include the non-cleavable [NHS](https://en.wikipedia.org/wiki/N-Hydroxysuccinimide)-ester cross-linker, [bissulfosuccinimidyl suberate](https://en.wikipedia.org/wiki/bissulfosuccinimidyl_suberate) (BS3); a cleavable version of BS3, [dithiobis(sulfosuccinimidyl propionate)](https://en.wikipedia.org/wiki/dithiobis(sulfosuccinimidyl_propionate)) (DTSSP); and the [imidoester](https://en.wikipedia.org/wiki/imidoester) cross-linker [dimethyl dithiobispropionimidate](https://en.wikipedia.org/wiki/dimethyl_dithiobispropionimidate) (DTBP) that is popular for fixing interactions in [ChIP](https://en.wikipedia.org/wiki/ChIP) assays.
- **[SPINE](https://en.wikipedia.org/wiki/SPINE_(molecular_biology))**: (Strepprotein interaction experiment) uses a combination of reversible crosslinking with formaldehyde and an incorporation of an affinity tag to detect interaction partners ''in vivo''.
- **[Quantitative immunoprecipitation combined with knock-down](https://en.wikipedia.org/wiki/Quantitative_immunoprecipitation_combined_with_knock-down)**: (QUICK) relies on co-immunoprecipitation, quantitative [mass spectrometry](https://en.wikipedia.org/wiki/mass_spectrometry) ([SILAC](https://en.wikipedia.org/wiki/SILAC)) and [RNA interference](https://en.wikipedia.org/wiki/RNA_interference) (RNAi). This method detects interactions among endogenous non-tagged proteins. Thus, it has the same high confidence as co-immunoprecipitation. However, this method also depends on the availability of suitable antibodies.
- **[Proximity ligation assay](https://en.wikipedia.org/wiki/Proximity_ligation_assay)**: (PLA) in situ is an immunohistochemical method utilizing so called PLA probes for detection of proteins, protein interactions and modifications.


### Next Generate Sequencing
- **DNA-seq**: DNA sequencing is the process of determining the precise order of nucleotides within a DNA molecule. [@Wiki](https://en.wikipedia.org/wiki/DNA_sequencing)
- **RNA-seq**: RNA-seq (RNA sequencing), also called whole transcriptome shotgun sequencing[1] (WTSS), uses next-generation sequencing (NGS) to reveal the presence and quantity of RNA in a biological sample at a given moment in time. [@Wiki](https://en.wikipedia.org/wiki/RNA-Seq)
- **ChIP-seq**: ChIP-sequencing, also known as ChIP-seq, is a method used to analyze protein interactions with DNA. ChIP-seq combines chromatin immunoprecipitation (ChIP) with massively parallel DNA sequencing to identify the binding sites of DNA-associated proteins. [@Wiki](https://en.wikipedia.org/wiki/ChIP-sequencing)
- **CLIP-Seq**: [@Wiki](https://en.wikipedia.org/wiki/CLIP)
- **FAIRE-seq**: [@Wiki](https://en.wikipedia.org/wiki/FAIRE-Seq)
- **DNase-Seq**: [@Wiki](https://en.wikipedia.org/wiki/DNase-Seq)
- **CAGE**: [@Wiki](https://en.wikipedia.org/wiki/Cap_analysis_gene_expression)
- **ChIA-PET**: [@Wiki](https://en.wikipedia.org/wiki/Chia_Pet)
- **5C/Hi-C**: [@Wiki](https://en.wikipedia.org/wiki/Chromosome_conformation_capture) 

### Uncategorized
- **ChIP**: Chromatin Immunoprecipitation (ChIP) is a type of immunoprecipitation experimental technique used to investigate the interaction between proteins and DNA in the cell. [@Wiki](https://en.wikipedia.org/wiki/Chromatin_immunoprecipitation)
- **ChIP-chip**: ChIP-chip (also known as ChIP-on-chip) is a technology that combines chromatin immunoprecipitation ('ChIP') with DNA microarray ("chip"). Like regular ChIP, ChIP-on-chip is used to investigate interactions between proteins and DNA in vivo. [@Wiki](https://en.wikipedia.org/wiki/ChIP-on-chip)

## NGS Data Repositories
- **[1000 Genomes Project](http://www.1000genomes.org/)**: The 1000 Genomes Project ran between 2008 and 2015, creating the largest public catalogue of human variation and genotype data.
- **[Array Express](http://www.ebi.ac.uk/arrayexpress/)**: an NIH-funded database at the European Molecular Biology Laboratory -European Bioinformatics Institute that collects and disseminates microarray-based gene-expression data.
- **[DDBJ](http://www.ddbj.nig.ac.jp/)**: DNA Data Bank of Japan (DDBJ) is a data bank organized by the National Institute of Genetics in Japan that collects sequence data.
- **[ENCODE](https://www.encodeproject.org/)**: The goal of ENCODE is to build a comprehensive parts list of functional elements in the human genome, including elements that act at the protein and RNA levels, and regulatory elements that control cells and circumstances in which a gene is active.
- **[GEO](http://www.ncbi.nlm.nih.gov/geo/)**: GEO is a public functional genomics data repository supporting MIAME-compliant data submissions. Array- and sequence-based data are accepted.
- **[GermOnline](http://www.germonline.org/index.html)**: The GermOnline 4.0 gateway is a cross-species microarray expression database focusing on germline development, meiosis and gametogenesis as well as the mitotic cell cycle.
- **[Roadmap Epigenomics Project](http://www.roadmapepigenomics.org/)**: The NIH Roadmap Epigenomics Mapping Consortium was launched with the goal of producing a public resource of human epigenomic data to catalyze basic biology and disease-oriented research.
- **[TCGA](http://cancergenome.nih.gov/)**: The Cancer Genome Atlas (TCGA) is a collaboration between the National Cancer Institute (NCI) and the National Human Genome Research Institute (NHGRI) that has generated comprehensive, multi-dimensional maps of the key genomic changes in 33 types of cancer. 

## NGS Data Analysis
### Variants Calling
#### SNP Calling
- **[GATK](https://software.broadinstitute.org/gatk/)**: Genome Analysis Toolkit offers a wide variety of tools with a primary focus on variant discovery and genotyping.

## Variant Databases
- **[COSMIC](http://cancer.sanger.ac.uk/)**: COSMIC is an online database of somatically acquired mutations found in human cancer.
- **[dbSNP](http://www.ncbi.nlm.nih.gov/SNP/)**: The Single Nucleotide Polymorphism Database (dbSNP) is a free public archive for genetic variation within and across different species developed and hosted by the National Center for Biotechnology Information (NCBI) in collaboration with the National Human Genome Research Institute (NHGRI).
- **[GWASdb](http://jjwanglab.org/gwasdb)**: GWASdb is an online bioinformatics database combines collections of GVs from GWAS and their comprehensive functional annotations, as well as disease classifications.

## File Formats
### Formats
- **BAM**: BAM is the compressed binary version of the Sequence Alignment/Map (SAM) format, a compact and index-able representation of nucleotide sequence alignments.
- **BED**: The BED format consists of one line per feature, each containing 3-12 columns of data, plus optional track definition lines. [@UCSC](https://genome.ucsc.edu/FAQ/FAQformat.html#format1), [@bedtools](http://bedtools.readthedocs.io/en/latest/content/general-usage.html), [@Ensembl](http://useast.ensembl.org/info/website/upload/bed.html)
- **BigWig**: The BigWig format is designed for dense, continuous data that is intended to be displayed as a graph. Files can be created from WIG or BedGraph files using the appropriate utility program. [@UCSC](http://genome.ucsc.edu/goldenPath/help/bigWig.html)
- **GFF**: The GFF (General Feature Format) format consists of one line per feature, each containing 9 columns of data, plus optional track definition lines. [@UCSC](https://genome.ucsc.edu/FAQ/FAQformat.html#format3), [@Ensembl](http://useast.ensembl.org/info/website/upload/gff.html), [GTF(GFFv2)@GMOD](http://gmod.org/wiki/GFF2), [@Wiki](https://en.wikipedia.org/wiki/General_feature_format)
- **WIG**: The WIG (wiggle) format is designed for display of dense continuous data such as probability scores. Wiggle data elements must be equally sized; if you need to display continuous data that is sparse or contains elements of varying size, use the BedGraph format instead. [@UCSC](https://genome.ucsc.edu/goldenpath/help/wiggle.html), [@Ensembl](http://useast.ensembl.org/info/website/upload/wig.html)
- **[SAM](http://samtools.github.io/hts-specs/SAMv1.pdf)**: The SAM Format is a text format for storing sequence data in a series of tab delimited ASCII columns. [@Wiki](http://genome.sph.umich.edu/wiki/SAM)
- **VCF**: The Variant Call Format (VCF) specifies the format of a text file used in bioinformatics for storing gene sequence variations. [v4.0@1000genomes](http://www.1000genomes.org/wiki/Analysis/Variant%20Call%20Format/vcf-variant-call-format-version-40), [@Wiki](https://en.wikipedia.org/wiki/Variant_Call_Format)

### Tools
- **[BEDOPS](https://bedops.readthedocs.io/en/latest/)**: the fast, highly scalable and easily-parallelizable genome analysis toolkit.
- **[bedtools](https://github.com/arq5x/bedtools2)**: Collectively, the bedtools utilities are a swiss-army knife of tools for a wide-range of genomics analysis tasks.
- **[bwtool](https://github.com/CRG-Barcelona/bwtool)**: bwtool is a command-line utility for bigWig files.
- **[sambamba](https://github.com/lomereiter/sambamba)**: samtools functions with multi-threading support.
- **[samtools](https://github.com/samtools/samtools)**: SAM Tools provide various utilities for manipulating alignments in the SAM/BAM format, including sorting, merging, indexing and generating alignments in a per-position format.
- **[VCFtools](https://vcftools.github.io/index.html)**: A set of tools written in Perl and C++ for working with VCF files.


