# tribolium-synteny-project
Beginning bioinformatics course code 
Arend Vischer - 1002393685 - BIOL-5340-001
Compares chromosome structure across four Tribolium species using protein-based reciprocal best hits and a custom syntenic-block finder:

T. castaneum (Tcas), assembly icTriCast1.1 (NCBI RefSeq GCF_031307605.1), used as the reference for chromosome labels
T. madens (Tmad)
T. freemani (Tfre)
T. confusum (Tcon)


All six species pairs are analyzed with identical thresholds, so results are directly comparable. The project status is a draft: the pipeline has been run on all four genomes, and downstream validation and gene loss/duplication analyses are still to do (see Project status).

Repo contents
Path	Description
Tribolium_AllVsAll_Synteny_v4_icTriCast1_1.ipynb	Main Google Colab notebook containing the whole pipeline
README.md	This file
figures/	Dot plots and ribbon diagrams, one of each per species pair (12 images)
results/	Small summary tables exported from the notebook (see below)
requirements.txt	Tool and package versions (to be added)
LICENSE

Usage
Open the notebook in Google Colab (File → Open notebook → GitHub, or upload the .ipynb).
Upload the eight input files to /content.
Check the genome overview cell (Section 1) to confirm the kept sequences are the chromosomes you expect.
Run all cells. Outputs go to /content/processed_v3/, and figures to processed_v3/pairs/<A>_<B>/.
Download the output folder before the Colab session ends.
