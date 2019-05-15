# Transcription-Factor-Databases

## Current (05/15/2019) Transcription Factor Data Source
1) (1,639) List of ‘All’ Known TFs (Ref 1 & 2)
   Incorpates Following Sources:
	CIS-BP Database: Catalog of Inferred Sequence Binding Preferences
	CISBP-RNA Database: Catalog of Inferred Sequence Binding Preferences of RNA binding proteins
	TRANSFAC motif database
	JASPAR motif database
	HocoMoco motif database
	Uniprobe PBM database
	Vaquerizas et al TF census
	TFCat
	TFClass
	Protein Data Bank (PDB)
	Pfam
	SMART
	Interpro
	Gene Ontology
2) TF Expression Specifity (Ref 1 & 2)
3) Trust v2 DB = (~800) Transcription Factor & Target Binding (8,444)  (Ref 3)
	- Automated literature search then Manually curated literature based TF & Targets
	- 3 Category Types for Targets: Repressive, Activating, Unknown 

## Future To Add or Consider:

1) Harmonizome (Ref 4)
	- Download Datasets: harmonizomedownloader.py
	- 10 entries (http://amp.pharm.mssm.edu/Harmonizome/download) as of 05/15/2019 for Transcription Factors
	- 7 entries (TFs & Targets) are not listed as incorporated in dataset for Transcription Factors used
		- CHEA 
		- MotifMap
		- ENCODE

## Current Folder Structure & Explaination

- Trust V2 data & paper
- TF_Paper_Data = (Ref 1 & 2) raw data
		
### References
1) http://humantfs.ccbr.utoronto.ca/allTFs.php
2) Lambert, S. A., Jolma, A., Campitelli, L. F., Das, P. K., Yin, Y., Albu, M., ... & Weirauch, M. T. (2018). The human transcription factors. Cell, 172(4), 650-665.
3) Han, H., Cho, J. W., Lee, S., Yun, A., Kim, H., Bae, D., ... & Lee, S. (2017). TRRUST v2: an expanded reference database of human and mouse transcriptional regulatory interactions. Nucleic acids research, 46(D1), D380-D386.
4) Rouillard AD, Gundersen GW, Fernandez NF, Wang Z, Monteiro CD, McDermott MG, Ma'ayan A. The harmonizome: a collection of processed datasets gathered to serve and mine knowledge about genes and proteins. Database (Oxford). 2016 Jul 3;2016. pii: baw100.


