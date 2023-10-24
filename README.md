# WOS_bibliometric-analysis
This repository houses the Python code utilized in our recent bibliometric analysis on the literature of Acute Lung Injury (ALI) and Acute Respiratory Distress Syndrome (ARDS) with a specific focus on endothelial cells (ECs). Our code was designed to efficiently extract pivotal attributes from scientific literature, encompassing data like publication years, authors, affiliated institutions, originating countries, specified research areas, journals, references, and distinct author keywords.

Description of each file:
1. ``WOS_bibliometric analysis.ipynb`` is the Python file for performing bibliometric analysis. It provides a detailed explanation of the code's usage and process using markdown syntax.
2. ``WOS_1.txt`` and ``WOS_2.txt`` are the original literature information files exported from the WOS database.
3. ``replacefile_authorkeywords.csv`` is a synonym replacement table for author keywords.
4. ``replacefile_authornames.csv`` is a replacement table for author names.
5. ``replacefile_countrynames.csv`` is a replacement table for country names.
6. Files such as ``01_updated_WOS_1.txt``, ``02_updated_WOS_2.txt``, up to ``05_final_WOS_2.txt`` are txt files generated during the data preprocessing of the original literature information in Python.
7. ``Bubble_fields_data.csv``, ``Bubble_journals_data.csv``, and ``Bubble_keywords_data.csv`` are the raw data tables for creating bubble charts of research areas, journals, and author keywords.
8. Files like ``Data_Author.csv``, ``Data_Country.csv``, up to ``Data_Research_Area.csv`` are the final result tables from Python's bibliometric data analysis of information such as countries, institutions, authors, research areas, and journals.

Primary analytical functionalities incorporated:

Calculation of cumulative publications.
Analysis of total citation frequencies.
Assessment of h-index across diversified spectra: timeframes, author groups, institutional bodies, countries, and distinct research sectors.
An innovative aspect of our study is the utilization of the h-index, traditionally employed to gauge an individual scholar's academic influence. We've broadened its application to evaluate the academic prowess of larger entities, including academic consortiums, institutions, and entire nations.

To offer a more intuitive insight into our findings, our code also facilitates the generation of bubble charts. These diagrams pictorially represent yearly publication trajectories across research domains, journals, and author keywords. Within these graphics, the size of each bubble indicates the dominance of a particular domain, journal, or keyword in that specific year. Concurrently, inscriptions within these bubbles convey the exact number of publications and thematic occurrences.

The objective of making our Python code publicly available is to foster transparency, reproducibility, and further application by the research community. We encourage scholars and data enthusiasts to delve into the code, adapt it, and employ it for similar or broader bibliometric explorations.
