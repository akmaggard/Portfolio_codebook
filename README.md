# Portfolio_codebook

## About this assignment
This assignment was intended to test my ability to create a codebook more or less similar to those provided for "real life" datasets.   

## Research Topic
I developed my codebook to complement an as-yet hypothetical analysis of data concerning public procurement contracts awarded by Russian defense industry entities to private contractors for the supply of foreign-manufactured precision machine tools. 

## The Data
I employ 44-FZ contract metadata derived from zakupki.gov.ru, an official Russian government database of public procurement records. These records include 
contracts awarded by Russian defense industry entities. 

## My Approach
My main priority was to create a new variable differentiating Russian state-owned defense industry contract customers from other Russian government contract customers. I achieved this using R's mutate() and recode() functions. I also revamped OKPD codes (basically a system for classifying goods and services) using mutate() and recode(). I also cleaned the data by imposing a unitary NULL classification system. Finally, I rearranged the existing columns into a "neater", more logical format.
