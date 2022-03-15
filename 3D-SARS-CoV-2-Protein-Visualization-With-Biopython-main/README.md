# 3D SARS-CoV-2 Spike (S) Protein Visualization Using Biopython

## Table of Contents

1. [Overview](#overview)
2. [Getting Started](#getting-started)
    1. [Data Source](#data-source)
    2. [Dependencies](#dependencies)
	3. [Installation](#installation)
3. [Project Motivation](#project-motivation)
4. [Modeling](#modeling)
5. [Results](#results)
6. [Author](#author)
7. [Licensing](#licensing)

## Overview <a name="overview"></a>

We will use Biopython to handle biological sequence data stored in FASTA & PDB (Protein Data Bank) and XML format. Using this sequence data, we will explore and create an interactive three-dimensional (3D) representation of SARS-CoV-2 (Coronavirus) protein structures.

## Getting Started  <a name="getting-started"></a>

### Data Source <a name="data-source"></a>

Data contains the genetic information in FASTA file format, downloaded from from [NCBI (National Center for Biotechnology Information)](https://www.ncbi.nlm.nih.gov/nuccore/MN908947.3?report=fasta).

### Dependencies <a name="dependencies"></a>
* Python 3.*
* Libraries: Biopython, Pylab, Pandas, urllib, nglview
* Jupyter Notebook

### Installation <a name="installation"></a>

* Datasets: The complete set of files is publicly available and can be downloaded from the [NCBI (National Center for Biotechnology Information)](https://www.ncbi.nlm.nih.gov/nuccore/MN908947.3?report=fasta).. Alternatively, you can find the folder (titled _SARS-CoV-2-spike-protein-visualization_) in my Github repository [here](https://github.com/madison-freeman/SARS-CoV-2-spike-protein-visualization).
* Others: The code can be run in [JupyterLab](https://jupyter.org/try) as an Interactive Python Notebook (ipynb). No additional installation is required.
    - JupyterLab allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer (other than a browser).

## Project Motivation <a name="project-motivation"></a>

In the fields of Bioinformatics, Health and Medical Technology & Biotechnology, there is now a widespread need for visualization tools to present the 3D structure of proteins. There are only a few examples of protein function. A remarkable fact is that all tasks they can perform are based on a common principle, the twenty amino acids that can form a protein. That is the reason why studying proteins, their composition, structure, dynamics and function, is so important.

We must understand how these molecules fold, how they assemble into complexes, how they function if we wish to answer questions such as why we have cancer, why we grow old, why we get sick, how can we find cures for many diseases, why life as we know it has evolved in this way and on this planet and not anywhere else, at least for the moment. 
 
 All proteins functions are dependent on their structure, which, in turn, depends on physical and chemical parameters. This is another important fact on studying these molecules; classical biological, physical, chemical, mathematical and informatics sciences have been working together in a new area known as bioinformatics to allow a new level of knowledge about life organization. To understand structural biology, visualization of complex macromolecular structure (like proteins) is essential and macromolecular structure visualization is also now one of the primary steps in the process of drug design and discovery and docking studies. These studies are done virtually thus reducing animal trials and manpower.

## Modeling <a name="modeling"></a>

<https://raw.githubusercontent.com/madison-freeman/SARS-CoV-2-spike-protein-visualization/master/3D-SARS-CoV-2-Protein-Visualization-With-Biopython-main/Data%20%26%20Images/1.png>

<https://raw.githubusercontent.com/madison-freeman/SARS-CoV-2-spike-protein-visualization/master/3D-SARS-CoV-2-Protein-Visualization-With-Biopython-main/Data%20%26%20Images/2.png>

<https://raw.githubusercontent.com/madison-freeman/SARS-CoV-2-spike-protein-visualization/master/3D-SARS-CoV-2-Protein-Visualization-With-Biopython-main/Data%20%26%20Images/3.png>

<https://raw.githubusercontent.com/madison-freeman/SARS-CoV-2-spike-protein-visualization/master/3D-SARS-CoV-2-Protein-Visualization-With-Biopython-main/Data%20%26%20Images/5.png>

<https://raw.githubusercontent.com/madison-freeman/SARS-CoV-2-spike-protein-visualization/master/3D-SARS-CoV-2-Protein-Visualization-With-Biopython-main/Data%20%26%20Images/6.png>

## Results <a name="results"></a>

* Sequence length: 29,903 base pairs
* GC content: 37.97%
* Protein content has high Leucine L and Serine S.
* The largest protein is of length 2,701 amino acid.
* Largest protein BLAST results corresponds to SARS-CoV-19 6YYT.
* Protein 6YYT has 8 chains & a RNA binding domain.

## Author<a name="author"></a>
* [Madison F.](https://github.com/madison-freeman)

## Licensing<a name="licensing"></a>

* The dataset is available under the Open Database License [ODbL](http://opendatacommons.org/licenses/odbl/1.0/).
* Any rights in individual contents of the database are licensed under the [Database Contents License](http://opendatacommons.org/licenses/dbcl/1.0/).
