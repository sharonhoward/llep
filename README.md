# London Lives Pauper Examinations

In all data **ll_img** is the image reference that can be used to locate individuals on the [London Lives](http://www.londonlives.org) website (using the reference search). Alternatively, if present, **ll_url** will take you straight to the relevant page when pasted into a browser. **name_id** or **nid** is the unique identifier for individual names.

## LL_BAEP_bastardy

Approximately 1000 individuals identified in the St Botolph Aldgate pauper examinations as women who gave birth to illegitimate children, their illegitimate offspring, or putative fathers.

**LL_BAEP_bastardy_v1_201602.csv**

###Notes

The accuracy of the data is not guaranteed; some errors in the data are likely, because most entries have not been individually checked. Apart from errors in the original London Lives data, some will have been introduced in the creation of this dataset (especially age data and examination dates, as these have been extracted from complex narrative texts

###Data fields

Most of these should be self-explanatory but note:

* **fam_id** is used to group related individuals together; it's normally the same as the **LL img** but sometimes there were multiple examinations on one page, or an examination covered several pages.
* **examinant**:
  * 1: this individual was the examinant, usually the mother
  * 2: the examinant (not named in this dataset) was a witness, often a parish official, who gave evidence on behalf of the child or mother, or about the case 
  * 0: individual (usually child or father) named by the examinant

(Fuller documentation, as well as data for St Clement Danes, is in preparation.)


## LL_EP_examinants

This is a rudimentary dataset of examinants identified in London Lives 18th-century settlement and bastardy examinations for St Botolph Aldgate and St Clement Danes. 

**LL_EP_examinants_v1_201602.csv**

###Notes

* not all examinants are themselves paupers; though the majority are, some will be local officials and others examined concerning the circumstances of individual cases. 
* the examinations contain many more plebeian names - parents, children, siblings, employers, the alleged fathers of bastards, and so on.
* the dataset currently does not contain any text from the examinations or further information about their contents.

Fuller documentation to follow (eventually).

## More information about the source

* [London Lives: Pauper Examinations](http://www.londonlives.org/static/EP.jsp)

## Acknowledgments

All data derived from, and with many thanks to, the London Lives project.

## Licensing 

* [Creative Commons Attribution-ShareAlike (CC-BY-SA)](http://creativecommons.org/licenses/by-sa/4.0/)
