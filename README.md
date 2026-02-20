# GSE10072-Lung-Cancer-Transcriptomics
Differential Gene Expression and KEGG Pathway Analysis of Lung Adenocarcinoma (GSE10072)
# Deskripsi Proyek
Analisis ini bertujuan untuk mengidentifikasi gen yang mengalami perubahan ekspresi signifikan antara jaringan paru normal dan jaringan adenokarsinoma paru menggunakan dataset mikroarray GSE10072. Analisis dilakukan dengan pendekatan bioinformatika berbasis bahasa pemrograman R, meliputi:
1. Identifikasi Differentially Expressed Genes (DEGs)
2. Analisis pengayaan Gene Ontology (GO)
3. Analisis pengayaan KEGG Pathway
4. Visualisasi pathway NSCLC (hsa05223) menggunakan Pathview
# DATASET
- Sumber: Gene Expression Omnibus (GEO)
- Accession Number: GSE10072
- Organisme: Homo sapiens
- Platform: Microarray expression profiling
- Perbandingan: Normal lung tissue vs Lung adenocarcinoma
# Analysis Scopes
- R Version: 4.5.2
- Operating System: Windows 11 x64
- Bioconductor Version: 3.22
# Output Analisis
1. Daftar DEG signifikan
2. Visualisasi DEG signifikan
3. Visualisasi Enrichment GO
4. Visualisasi Encirhment KEGG (dotplot & barplot)
5. Diagram pathway NSCLC (hsa05223) dengan pemetaan ekspresi gen (merah = upregulated, biru = downregulated)
# Interpretasi Biologis Singkat
Hasil enrichment menunjukkan keterlibatan jalur utama kanker paru seperti:
- PI3K–Akt signaling pathway
- MAPK signaling pathway
- Cell cycle regulation
- p53 signaling pathway
- Non-small cell lung cancer (hsa05223)
Temuan ini konsisten dengan mekanisme molekuler NSCLC yang melibatkan peningkatan proliferasi, gangguan kontrol siklus sel, serta aktivasi jalur survival dan antiapoptosis.
