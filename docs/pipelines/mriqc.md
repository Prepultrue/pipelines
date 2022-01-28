---
source_file: australianimagingservice/mri/neuro/mriqc.py
title: mriqc
weight: 10

---

MRIQC extracts no-reference IQMs (image quality metrics) from structural (T1w and T2w) and functional MRI (magnetic resonance imaging) data.

### Info
|Key|Value|
|---|-----|
|Version|0.1.5|
|App version|0.16.1|
|Image|`poldracklab/mriqc:0.16.1`|
|Maintainer|thomas.close@sydney.edu.au|
|Info URL|http://mriqc.readthedocs.io|
|Frequency|Session|

### Inputs
|Name|Bids path|Data type|
|----|---------|---------|
|`T1w`|`anat/T1w`|`niftix_gz`|
|`T2w`|`anat/T2w`|`niftix_gz`|
|`fMRI`|`func/bold`|`niftix_gz`|

### Outputs
|Name|Data type|
|----|---------|
|`mriqc`|`directory`|

### Parameters
None

