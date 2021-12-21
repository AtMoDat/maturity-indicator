# Maturity Indicator (MI) Linking with Related Identifiers

Currently (DataCite Metadata Schema v4.3), Maturity and assessment report information can be provided via `relatedIdentifier.`. Using relationTypes such as `HasMetadata` the Datcite provides mechanisms to identify and query assessment reports in DOI metadata unambiguously. 

## Examples

Also three example cases are provided -- each as `xml`  file. The files are:

* [RelatedIdentifier to ARDC;s FAIR report](/maturity_indicator_w_relatedIdentifiers/example_MI_ARDC_FAIR.xml)
* [RelatedIdentifier to FAIR'sFAIR report](/maturity_indicator_w_relatedIdentifiers/example_MI_FAIRsFAIR.xml)
* [RelatedIdentifier to NOAA's FAIR report](/maturity_indicator_w_relatedIdentifiers/example_MI_NOAA_DSMM.xml)
* [RelatedIdentifier to WDDCC assessment report](/maturity_indicator_w_relatedIdentifiers/example_MI_WDCC_Maturity.xml)

The examples are:

| metric                                       | file suffix      | URL Scheme                                                         | Example Query |
|----------------------------------------------|------------------|---------------------------------------------------------------------------------------|---|
| FAIRsFAIR Draft Recommendation ... FAIR ...  | `_FAIRsFAIR`     | https://doi.org/10.5281/zenodo.3678716                                                | `query: related_identifiers.relatedMetadataScheme:"FAIRsFAIR"` |
| WDCC Quality Maturity Matrix (QMM)           | `_WDCC_Maturity` | https://doi.org/10.2312/WDCC/TR_QMM_Checkl_Levels_4-5_Prots                           | `query: related_identifiers.relatedMetadataScheme:"WDCC_Maturity"` |
| ARDC FAIR data assessment tool               | `ARDC_FAIR`      | https://ardc.edu.au/resources/working-with-data/fair-data/fair-self-assessment-tool/  | `query: related_identifiers.relatedMetadataScheme:"ARDC_FAIR"` |
| NOAA Data Stewardship Maturity Matrix (DSMM) | `NOAA_DSMM`      | https://doi.org/10.2481/dsj.14-049                                                    | `query: related_identifiers.relatedMetadataScheme:"NOAA_DSMM"` |




Note: the examples are currently not up to date.


## Acknowledgements

The Maturity Indicator draft was created within the AtMoDat project (**At**mospheric **Mo**del **Dat**a, https://www.atmodat.de). AtMoDat is funded by the German Federal Ministry for Education and Research within the framework of *Atmosphaeren-Modelldaten: Datenqualitaet, Kurationskriterien und DOI-Branding* (FKZ 16QK02A).
