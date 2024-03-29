# CroP
CroP - Coordinated Panels Visualization Tool

CroP is a data visualization tool that utilizes coordinated multiple views to portray complex networks and multivariate data, in particular time-series. Through dynamic visualization models, CroP aims to highlight and analyze patterns of data, such as relationships between groups of data points, significant shifts in values, and different behaviors over time.

CroP is currently available as an executable jar file, along with sample datasets. To use all of its functionalities, the program requires two datasets: a list of all nodes and their edges (Sample: CSV/human_ppi_network.csv), and a list of the temporal data associated to each node (Sample: CSV/hiv1-gene-expression-time-series.csv).

One file contains a workspace that has already been prepared for a demonstration, which can be loaded by following "Quick Sample Dataset Setup". Alternatively, the two sample CSV files can be loaded by following "CSV Dataset Setup".

---

Quick Sample Dataset Setup:
- The “HIV-1 Infection.txt" contains a PPI network embedded with gene expression time-series of the HIV-1 infection;
- After loading CroP, in the menu under “Data Management” select “Load All” and then the “HIV-1 Infection.txt” file.

---

CSV Dataset Setup:
- After loading CroP, under "Data Management" select "Import Network" -> "Network File (.csv)", then select the file obtained from "CSV/human_ppi_network.csv";
- Then, under "Data Management" select "Import Time-Series" -> "Time-Series File (.csv)", then select the file obtained from "CSV/hiv1-gene-expression-time-series.csv".
