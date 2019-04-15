# VCF-DART_example_exomes
A few example exomes in vcf format for testing the VCF-DART annotation and reporting tool.

Four exomes derived from publicly available data have been deposited in this repository for review and testing purposes. They may be uploaded to the VCF-DART instance and run through the annotation tool, and then viewed in the VCF-DART Viewer tool.

**NB:** Example gene lists have also been deposited here to use for review/testing purposes only.

## Notes to reviewers:

* There are two exomes (and associated dummy coverage stats files) assigned to each reviewer, this is signified in the file names.
* This repository can be downloaded/cloned to a local machine and then vcf and text files uploaded to the VCF-DART webserver.
* When entering the required details into VCF-DART please follow this example (using `HG103_GBR_exome_Reviewer_01.vcf.gz` in this example):
  * in the **Sample ID** field use `HG103`
  * in the **Label** field use `01`
  * dummy gene lists are also provided, these can be uploaded using the file selection tools in VCF-DART
  * the fields **User Name** and **Run ID** can be set as anything the user desires
  * the **Output Directory Name** requires the inclusion of the supplied **Sample ID** at least, and it is good practice to include the label and date, i.e. `HG103_01_20190415`
  * the **Genome Build** must be set as hg19 (default), the hg38 version is still in development

Please don't hesitate to contact the authors with issues or queries.