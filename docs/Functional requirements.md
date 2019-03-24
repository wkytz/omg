# Functional Requirements
## Input
A valid expression file has a three-column TAB-separated plain text file. the first is gene_id,and then is ControlSample (control sample) and KnockOutSample (treatment sample).

## out put
it will display a table and a scatter plot given a gene expression file,the X-axis is Control, and Y-axis is Treatment,the up-regulated genes are shown in red dots, and down-regulated genes are shown in blue.And it will give a table contains a list of differentially expressed genes.