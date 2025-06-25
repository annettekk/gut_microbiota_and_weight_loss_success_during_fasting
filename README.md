# gut_microbiota_and_weight_loss_success_during_fasting
Final project for my MSc Bioinformatics @Birkbeck

Please run Rmd scripts in this order:

1. Finding_2_stepwise_regression
2. Testing_stepwise_regression_model_on_Grundler_dataset
3. Finding_1_Bray_dissimilarity
4. Finding_2_Spearman_R_Ducarmon_Grundler
5. Finding_3_CaZymes_Ducarmon

Data files:

1. Ducarmon_2024_Berlin_ps.RDS -mOTU counts and clinical metadata
2. Grundler_2024_Berlin_ps.RDS -mOTU counts and clinical metadata
3. Mesnage_2023_collated.cazy.combined_rpkm.txt -CaZymes counts for Ducarmon dataset
4. 20230912_sample_metadata_anonymised.xlsx -metadata for CaZymes counts for Ducarmon dataset
5. cazy_classification_fixed_updated_2025.csv -CaZymes subfamilies grouped by FUNCTION_AT_DESTINATION_1 in the file 20250219_Table_S1_incl_dbCAN3_annotations.xlsx
6. 20250219_Table_S1_incl_dbCAN3_annotations.xlsx
7. 3d ds 16S clin data.csv - this one is used by the python script; it is a csv version of CLINICAL_DATA tab from BW-microbiote-clinical-data-13052025-3d-ds.xlsx
8. metadata.csv - this one is used by the python script; it is a csv version of METADATA tab from BW-microbiote-clinical-data-13052025-3d-ds.xlsx
9. BW-microbiote-clinical-data-13052025-3d-ds.xlsx
