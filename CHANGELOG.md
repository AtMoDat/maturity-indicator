# Changelog

## v06.0 -> v07.0 (2020-XX-XX):

* added GUF example (Geospatial User Feedback?)
* modifications of the Maturity Indicator:
** 
** 
** 


## v05 -> v06.0 (2020-07-16):

* new "description" field (maturityCheckDescription)
* removed "Data" from the name be open for software and other non-data products
* renamed several metadata fields
* Added the version number of the metadata schema as a metadata field to have it in the document (can be removed later on but helps for now)
* change hierarchie of the representation of "result"s
** "metric" (past: "indicator") is located on the top level now and no sub-property of "result" anymore; "metric" got an own optional ExternalIdentifier
** date, on which the check was performed, now located at top level
* "ResultReportSummary" allows providing a prose summary of the result report
* added example values
* added some CVs
* extended description


## v04 -> v05 (2020-05-01)

* removed "repository certification"
* merged "QualityMetric" and "FAIRnessEvaluation" into "DataMaturityCheck"
** merged sub-properties
** renamed most sub-properties


## v03 -> v04 (2020-04-23)

* minor version change; actually v2.2
* publication in GitHub repository


## v02 -> v03 (2020-04-23)

* minor version change; actually v2.1
* renamed concept to "DataMaturityIndicator"


## v01 -> v02 (2020-04-15)

* formalization of the Quality Indicator
* three key properties: "FAIRnessEvaluation", "QualityMetric" and "RepositoryCertification"


## v01 (Nov/Dec 2019)

* name: Quality indicator
* textual description of the concept
* predefined quality levels
* need for discipline-specific add-on/extension
