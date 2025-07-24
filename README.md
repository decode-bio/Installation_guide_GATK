# GATK: Genome Analysis Toolkit (GATK)
* Definition

GATK stands for Genome Analysis Toolkit. It is a collection of command-line tools developed by the Broad Institute’s Data Sciences Platform for analyzing high-throughput sequencing data, with a primary focus on variant discovery and genotyping.

* Key Features

Comprehensive suite for variant calling (SNPs, indels), filtration, and annotation.


Implements best-practice workflows: duplicate marking, base-quality recalibration, joint genotyping.


High-performance engine supporting single-node, HPC clusters, and Apache Spark–based cloud execution.


Fully open source under the Apache 2.0 license with an active user community and forums for support.


# Create a directory
Create a directory named GATK under your Tools directory. Can make it as new directory, the choice is yours.
Then write the following code
```
wget  https://github.com/broadinstitute/gatk/releases/download/4.6.2.0/gatk-4.6.2.0.zip
```
OUTPUT
<img width="1914" height="664" alt="image" src="https://github.com/user-attachments/assets/0a4376cd-6232-4ff1-b91f-b6a25a1f8417" />

# Unzip
You can now see zipped file into your directory, now unzip it.
```
unzip gatk-4.6.2.0.zip
```
OUTPUT
<img width="1875" height="813" alt="image" src="https://github.com/user-attachments/assets/7604e023-b4e0-431b-9bd5-9fa0b342900f" />

Now once unzip is complete, we can now see the following contents under the directory
<img width="1504" height="82" alt="image" src="https://github.com/user-attachments/assets/df62cf73-f8d2-49ee-b80f-9a7ec050ecd3" />
# GATK
Now have to export the path into your .bashrc file at the end like below
<img width="900" height="744" alt="image" src="https://github.com/user-attachments/assets/0a586933-6896-4311-94d8-83b7ef808d3f" />
Save the changes and run the script by using the following command
```
source ~./bashrc
```
<img width="934" height="145" alt="image" src="https://github.com/user-attachments/assets/65bab393-5d96-4989-a794-13d3b3bacf10" />

Even after my setup not showing response against gatk command.So, I am using the alternative command to check for gatk installation

```
python3 ~/Tools/gatk-4.6.2.0/gatk
```
<img width="1437" height="489" alt="image" src="https://github.com/user-attachments/assets/6535e373-6b82-4638-b7f4-91c948181b4d" />
Now I will be using the above command to use the gatk tools for the variant analysis.



---
Thanks and happy decoding.
