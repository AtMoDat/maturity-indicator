# Data Maturity Indicator

The Data Maturity Indicator is a draft extension to the DataCite Metadata Schema. The Data Maturity Indicator would allow to place the results of data maturity checks in the DataCite Metadata in a standardized format. Currently (DataCite Metadata Schema v4.3), such information can only be provided via `relatedIdentifier`.

The conept does only provide metadata fields to insert maturity information. No maturity matrix/metric/measure is suggested. Thus, this concept is open to any kind of maturity measure.

The draft containing the definition of metadata property and sub-properties is provided in the [formalization_DataMaturityIndicator.csv](formalization_DataMaturityIndicator.csv) file.

This Readme will be extended during May and June 2020 and further examples will be added.


# Examples

Also three example cases are provided -- each as `xml` and as `csv` file. The files are:

* `datacite-example_DataMaturityIndicator_*.xml`
* `datacite-example_DataMaturityIndicator_*.csv`

The three examples are:

| metric                                       | file suffix      | URL                                                         |
|----------------------------------------------|------------------|-------------------------------------------------------------|
|  FAIRsFAIR Draft Recommendation ... FAIR ... | `_FAIRsFAIR`     | https://doi.org/10.5281/zenodo.3678716                      |
| WDCC Quality Maturity Matrix (QMM)           | `_WDCC_Maturity` | https://doi.org/10.2312/WDCC/TR_QMM_Checkl_Levels_4-5_Prots |
| ANDS FAIR data assessment tool               | `_ANDS_FAIR`     | https://www.ands-nectar-rds.org.au/fair-tool                |



# Contributors:

In alphabetic order:

* [Anette Ganske](https://github.com/anganske)
* Angelina Kraft
* [Daniel Neumann](https://github.com/neumannd)
* Hannes Thiemann
* Heinke Hoeck


# Acknowledgements:

The Data Maturity Indicator draft was created within the AtMoDat project (**At**mospheric **Mo**del **Dat**a, https://www.atmodat.de). AtMoDat is funded by the German Federal Ministry for Education and Research within the framework of *Atmosph�ren-Modelldaten: Datenqualit�t, Kurationskriterien und DOI-Branding* (FKZ 16QK02A).