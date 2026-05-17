# Drakkar_Coregonus
notes for White Fish metagenomics data processing with Drakkar

Using ERDA fileshare links with http works, although Drakkar must copy the data to Mjolnir. 
First step is to run preprocessing and cataloging.

## Technology Comparison

Test run on 12 samples from Havgajavri lake designed for technology comparison. Samples will be assembled individually. Objective is to assess similarity between corresponding BGI and Illumina samples

### Preprocessing

drakkar preprocessing -f samples_tech_control_2.tsv -o /maps/projects/alberdilab/people/pgk128/drakkar_output -r https://sid.erda.dk/share_redirect/P668viwaMO/Whitefish_analysis_BGI/Coregonus_sp_ref_genome/GCA_902810595.1_AWG_v2_genomic.fna.gz --fraction --nonpareil

### Cataloging

drakkar cataloging -f samples_tech_control_2.tsv -o /maps/projects/alberdilab/people/pgk128/drakkar_output -m individual

## Actual Run

If no technology bias is found previously, preprocessing and cataloging will be run on all shotgun metagenomics samples, with coassembly by lake.

### Preprocessing

### Cataloging
