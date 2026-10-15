# Tidy qPCR Data Exercise

This folder tidies the raw qPCR Cq data from the Lecture 3 exercise into a
single long-format table, with one row per well.

## What was done

The original workbook contained two plate-layout sheets (Plate 4 and Plate
7) of Cq values from qPCR on U937 cells with GCN1 knockout, treated for 6
hours with homoharringtonine (HHT) at two concentrations or DMSO. Each
plate sheet was reshaped from its grid layout into a tidy table with one
row per well, using the columns `plate`, `well`, `amplicon`, `sgrna`,
`treatment`, `cq`, and `note`. The two plates were combined into a single
table into a Tidy format. 

## Software used

- Claude was used for the generation of the tidy data. 

## Changelog

- 2026-10-14: Combined Plate 4 and Plate 7 into `tidy_data.csv`; initial version.
