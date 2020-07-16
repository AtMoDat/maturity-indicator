# Maturity Indicator (MI)

previouly named _Data Maturity Indicator_ (until 2020-07-16), previously named _Generic Quality Indicator_(until 2020-04-23)

The Maturity Indicator is a draft extension to the DataCite Metadata Schema. The Maturity Indicator would allow to place the results of data maturity checks in the DataCite Metadata in a standardized format. Currently (DataCite Metadata Schema v4.3), such information can only be provided via `relatedIdentifier`.
The Maturity Indicator is a draft extension to the DataCite Metadata Schema. The Maturity Indicator would allow to place the results of (meta)data maturity checks in the DataCite Metadata in a standardized format. Currently (DataCite Metadata Schema v4.3), such information can only be provided via `relatedIdentifier`.

The conept does only provide metadata fields to insert maturity information. No maturity matrix/metric/measure is suggested. Thus, this concept is open to any kind of maturity measure.

The draft containing the definition of metadata property and sub-properties is provided in the [formalization_DMI.csv](formalization_DMI.csv) file.

This Readme will be extended during May and June 2020 and further examples will be added.


# Examples

Also three example cases are provided -- each as `xml` and as `csv` file. The files are:

* `example_DMI_*.xml`
* `example_DMI_*.csv`

The three examples are:

| metric                                       | file suffix      | URL                                                         |
|----------------------------------------------|------------------|---------------------------------------------------------------------------------------|
|  FAIRsFAIR Draft Recommendation ... FAIR ... | `_FAIRsFAIR`     | https://doi.org/10.5281/zenodo.3678716                                                |
| WDCC Quality Maturity Matrix (QMM)           | `_WDCC_Maturity` | https://doi.org/10.2312/WDCC/TR_QMM_Checkl_Levels_4-5_Prots                           |
| ARDC FAIR data assessment tool               | `ARDC_FAIR`      | https://ardc.edu.au/resources/working-with-data/fair-data/fair-self-assessment-tool/ |



# Contributors:

In alphabetic order:

* [Amandine Kaiser](https://github.com/am-kaiser), [ORCID: 0000-0002-2756-9964](https://orcid.org/0000-0002-2756-9964)
* [Anette Ganske](https://github.com/anganske), [ORCID: 0000-0003-1043-4964 
](https://orcid.org/0000-0003-1043-4964)
* Angelina Kraft, [ORCID: 0000-0002-6454-335X](https://orcid.org/0000-0002-6454-335X)
* [Daniel Heydebreck](https://github.com/neumannd), [ORCID: 0000-0001-8574-9093](https://orcid.org/0000-0001-8574-9093)
* Hannes Thiemann, [ORCID: 0000-0002-2329-8511](https://orcid.org/0000-0002-2329-8511)
* Heinke Hoeck, [ORCID: 0000-0002-0131-1404](https://orcid.org/0000-0002-0131-1404)


# Acknowledgements:

The Maturity Indicator draft was created within the AtMoDat project (**At**mospheric **Mo**del **Dat**a, https://www.atmodat.de). AtMoDat is funded by the German Federal Ministry for Education and Research within the framework of *Atmosph�ren-Modelldaten: Datenqualit�t, Kurationskriterien und DOI-Branding* (FKZ 16QK02A).
