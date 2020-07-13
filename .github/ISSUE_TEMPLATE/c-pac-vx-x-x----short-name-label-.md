---
name: C-PAC vX.X.X - [short name/label]
about: Submit run information for a completed or attempted C-PAC pipeline.
title: ''
labels: ''
assignees: ''

---

<!-- 
Toggle between the 'write' and 'preview' tabs for markdown rendering.
-->


## Resource info table    

|                     |                                                                                         |
| :------------------ | :-------------------------------------------------------------------------------------- |
| **Version**            | replace this with the C-PAC version used                                          |    
| **Container**            | replace this with the container tag (Docker/Singularity) you used                                          |
| **System**            | what system did you run on? local machine (Linux/MacOS)? server/cluster? AWS? Flywheel? etc.                                          |    
| **Description**     | replace this with a brief description of your pipeline run                              |
| **Results**     | did the pipeline complete successfully? any problems? any missing outputs?                              |

**Include:**
- [ ] Run Command:

||
| :-------------------------------------------------------------------------------------- |
| (the command-line command you used to start the run)                                                     |

- [ ] Pipeline Config (can drag file directly into issue)
- [ ] Data Config (can drag file directly into issue)

**Developers only:**
- [ ] Default Pipeline Diff:

||
| :-------------------------------------------------------------------------------------- |
| (print-out from [cpac_pipe_diff.py](https://github.com/sgiavasis/CPAC_regtest_pack/blob/master/cpac_pipe_diff.py))                                                     |

- [ ] Screenshots of brain extraction and registration wireframe overlays from QC pages (if available):

||
| :-------------------------------------------------------------------------------------- |
| screenshots here                                                    |

- [ ] Node timing information:

||
| :-------------------------------------------------------------------------------------- |
| (print-out from [callback_log_time_parse.py](https://github.com/sgiavasis/CPAC_regtest_pack/blob/master/callback_log_time_parse.py))                                                     |

- [ ] Extracted time series 1D and nuisance regressors 1D correlations against previous version or some benchmark (can use [corr_two_1D.py](https://github.com/sgiavasis/CPAC_regtest_pack/blob/master/corr_two_1D.py) but heatmaps or other visualizations are good too):

||
| :-------------------------------------------------------------------------------------- |
| correlations here                                                    |
