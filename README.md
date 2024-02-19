# Statistical Analysis for Detecting Depression
This repository holds the source code for my final year project at Aston University.

Statistical Analysis for Detecting Depression is a research project that focuses on a dataset collected on a set of people who have depressive symptoms. It includes data collected from those people with depression and a control set of people without depression.

## Dataset
The dataset used for this project was from a public domain called Simula (<a href="https://datasets.simula.no/depresjon/">https://datasets.simula.no/depresjon/</a>) published by Garcia-Ceja, et al. (2018).

## Ethics
This project has received ethical approval since it contains data of human participants, and it is anonymised.

### Terms & Conditions of Use
The website where the secondary dataset is publicly available states: "In all documents and papers that report experimental results based on the Depresjon Dataset, a reference to this study should be included".
<br><br>
The paper by Garcia-Ceja, et al. (2018) also states that the intention of the dataset is for it to be used by research community for developing statistical methods to analyse the dataset. It also states the contribution is a "completely open dataset" for researchers to use.

### Risk
The original study in which the dataset was collected (Berle et al., 2010): <a href="https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-3-149">https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-3-149</a>
<br><br>
From this study: “The study protocol was approved by the local ethics committee (REK III, Health-West, Norway)”

## Tools/Technology
* Jupyter Notebook (Integrated Development Environment (IDE) via Anaconda Navigator)
* Python (Programming Language)

## Files
* <code>Statistical Analysis Experiment for Depression.ipynb</code> - develops the statistics of the days, madrs1 and madrs2 columns of the <code>scores.csv</code> file using descriptive analysis (central tendency and variability)
* <code>Machine Learning Experiment - Depression or Non-Depression Classification.ipynb</code> - develops the machine learning experiment that classify patients as depressed or non-depressed using a new dataset based on features extracted from each patient's activity data from the actigraph watch

## References
Berle, J. O., Hauge, E. R., Oedegaard, K. J., Holsten, F. and Fasmer, O. B. (2010) 'Actigraphic registration of motor activity reveals a more structured behavioural pattern in schizophrenia than in major depression', <i>BMC Research Notes</i>, 3, article number 149. Available at: <a href="https://doi.org/10.1186/1756-0500-3-149">https://doi.org/10.1186/1756-0500-3-149</a> (Accessed: 6 November 2023).
<br><br>
Garcia-Ceja, E., Riegler, M., Jakobsen, P., Tøressen, J., Nordgreen, T., Oedegaard, K. J. and Fasmer O. B. (2018) 'Depresjon: a motor activity database of depression episodes in unipolar and bipolar patients', <i>MMSys '18: Proceedings of the 9th ACM Multimedia Systems Conference</i>, Amsterdam, Netherlands, 12-15 June 2018. New York: Association for Computing Machinery, pp. 472-477. Available at: <a href="https://doi.org/10.1145/3204949.3208125">https://doi.org/10.1145/3204949.3208125</a> (Accessed: 10 November 2023).
<br><br>
Simula (no date) <i>Simula Datasets - Depresjon</i>. Available at: <a href="https://datasets.simula.no/depresjon/">https://datasets.simula.no/depresjon/</a> (Accessed: 6 November 2023).
