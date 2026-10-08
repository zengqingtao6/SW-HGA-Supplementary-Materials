# SW-HGA Experimental Results

This directory contains the experimental material used in the paper.

| Folder | Paper scope | Contents |
|---|---|---|
| 01_Main_Benchmark | Sections 4.2-4.3 | 344 OP and 240 PCTSP instances, 20 runs per instance. |
| 02_Published_Reference_Data | Sections 4.2-4.3 | Published HGA and recent-method reference values used for cross-study comparisons. |
| 03_Seven_Configuration_Component_Study | Section 5.1 and Appendix C | 3,920 run-level records, instance summaries, and average ranks for seven configurations. |
| 04_Initialization_and_Construction_Rule_Controls | Section 5.2 | Ten-run initialization and R/RR/RS controls, raw records, and paper-level statistics. |
| 05_Rollback_and_Switch_Diagnostics | Section 5.3 and Appendix C | Operator counters, endpoint diagnostics, and weak rl-family checks. |
| 06_Population_Diversity | Appendix C | HGA and SW-HGA diversity trajectories on 16 OP instances. |
| 07_K_Means_Cluster_Scale_Sensitivity | Appendix C | K0.5 and K1.5 runs; K1 is available in the main benchmark data. |
| 08_Supporting_Ablations | Appendix C | Archived instance-level initialization and route-neighborhood summaries. |

The main cross-study benchmark comparisons should not be interpreted as same-platform runtime comparisons. Positive signed differences are oriented as described in the paper. OP is maximized and PCTSP is minimized.

Top-level folders and curated files use the terminology of the paper. Machine-generated raw filenames retain the original run-mode tokens (for example, `mixed_initial` and `rollback_ratio`) so that logs remain traceable to the supplied runner; local absolute paths inside logs and workbooks have been replaced by portable record identifiers.

Files named `VALIDATION.txt`, `FILE_MANIFEST.csv`, and workbook `Data_Dictionary` sheets document completeness and interpretation.
