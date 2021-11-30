# Maturity Indicator (MI)

previously named _Data Maturity Indicator_ (until 2020-07-16), previously named _Generic Quality Indicator_(until 2020-04-23)

The Maturity Indicator is a draft extension to the DataCite Metadata Schema. The Maturity Indicator would allow to place the results of data maturity checks in the DataCite Metadata in a standardised format. Currently (DataCite Metadata Schema v4.3), such information can only be provided via `relatedIdentifier`.

This concept only provides metadata fields to insert maturity information. No maturity matrix/metric/measure is suggested. Thus, this concept is open to any kind of maturity measure.
Please also have a look at https://www.atmodat.de/f-output/f-mi.

The draft containing the definition of metadata properties and sub-properties is provided in the [formalization_MI.csv](formalization_MI.csv) file.

## Examples

Also three example cases are provided -- each as `xml` and as `json` file. The files are:

* `example_MI_*.xml`
* `example_MI_*.json` (Schema.org JSON)

The examples are:

| metric                                       | file suffix      | URL                                                         |
|----------------------------------------------|------------------|---------------------------------------------------------------------------------------|
| FAIRsFAIR Draft Recommendation ... FAIR ...  | `_FAIRsFAIR`     | https://doi.org/10.5281/zenodo.3678716                                                |
| WDCC Quality Maturity Matrix (QMM)           | `_WDCC_Maturity` | https://doi.org/10.2312/WDCC/TR_QMM_Checkl_Levels_4-5_Prots                           |
| ARDC FAIR data assessment tool               | `ARDC_FAIR`      | https://ardc.edu.au/resources/working-with-data/fair-data/fair-self-assessment-tool/  |
| NOAA Data Stewardship Maturity Matrix (DSMM) | `NOAA_DSMM`      | https://doi.org/10.2481/dsj.14-049                                                    |

Note: the examples are currently not up to date.

## Contributors

In alphabetic order:

* [Amandine Kaiser](https://github.com/am-kaiser), [ORCID: 0000-0002-2756-9964](https://orcid.org/0000-0002-2756-9964)
* [Anette Ganske](https://github.com/anganske), [ORCID: 0000-0003-1043-4964 
](https://orcid.org/0000-0003-1043-4964)
* Angelina Kraft, [ORCID: 0000-0002-6454-335X](https://orcid.org/0000-0002-6454-335X)
* [Daniel Heydebreck](https://github.com/neumannd), [ORCID: 0000-0001-8574-9093](https://orcid.org/0000-0001-8574-9093)
* Ge Peng, [ORCID: 0000-0002-1986-9115](http://orcid.org/0000-0002-1986-9115)
* Hannes Thiemann, [ORCID: 0000-0002-2329-8511](https://orcid.org/0000-0002-2329-8511)
* Heinke Hoeck, [ORCID: 0000-0002-0131-1404](https://orcid.org/0000-0002-0131-1404)
* Ted Habermann, [ORCID: 0000-0003-3585-6733](https://orcid.org/0000-0003-3585-6733)

## Acknowledgements

The Maturity Indicator draft was created within the AtMoDat project (**At**mospheric **Mo**del **Dat**a, https://www.atmodat.de). AtMoDat is funded by the German Federal Ministry for Education and Research within the framework of *Atmosphaeren-Modelldaten: Datenqualitaet, Kurationskriterien und DOI-Branding* (FKZ 16QK02A).
