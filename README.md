# README
# ViPAA 1.3 Armed Actors Colombia

**Violent Presence of Armed Actors in Colombia**

**ViPPA v1.3**

**Javier Osorio, University of Arizona**

**05/01/2021**


This repository contains the Violent Presence of Armed Actors in Colombia (ViPAA) 1.3 event database.

ViPAA provides geo-referenced data at the daily municipal level related to the violent presence of armed actors in Colombia between **1988 and 2019**.

The data categorizes armed actors in four main types:

* Government forces
* Insurgent organizations
* Paramilitary groups
* Criminal organizations
* Criminal organizations
* FARC Dissidents

Each of these types of actors is further disaggregated in a multitude of specific organizations.   

ViPAA is generated using computerized text annotation with Eventus ID, a protocol for supervised event coding capable of geo-referencing actors mentioned in text written in Spanish (Osorio & Reyes 2016).

The information used as an input for the computerized coding came from Noche y Niebla, a collection of narratives of human rights violations published by the Centro de Investigación y Educación Popular, CINEP.

More detials available at https://www.colombiaarmedactors.org/



<br>

## 1. Event Coding 

Users can find further details about the event coding process of ViPAA using Eventus ID (Osorio & Reyes 2016) as discussed in ViPAA version 1.2 available at:
https://github.com/javierosorio/Eventus_ID_2.0 



<br>

## 2. Summary of Changes 

ViPAA 1.3 includes the following changes with respect to version 1.2

* Release date: 05/01/2021
* Total number of observations: 80,121
* Temporal coverage: 1/1/1988-12/31/2019
* Data updated with Noche y Niebla narratives until December 31, 2019
* **New actor categories**:
   * FARC Dissidents.
* **Changes in the Actors Dictionary**: 
   *  FARC Dissidents (code 07) and related sub-actor codes.
   *  There were several other minor changes in the codes at the sub-actor level.
   *  The actors dictionary increased from 7,560 (8/28/2018) entities to 7,631 (7/8/2020). entities.
* **Changes in the Filters Dictionary**: 
   *  Filters Dictionary increased from 11,139 (8/28/2018) entries to 11,255 (7/8/2020). 
* **Geo-location issues**. There were three considerable geo-location errors in ViPAA 1.2:
   *  The municipality of "Santa fe de Antioquia" was getting confused with the department of "Antioquia." 
      *  This caused a hyper-inflation of 11,247 cases in ViPAA 1.2. 
      *  The current version of ViPAA 1.3 only has 76 cases in this locality.
   *  There were issues with "Nariño."
      *  The municipality of "Nariño, Nariño" was hyper-inflating matching the municipality and the department of "Nariño" and several other locations (e.g. schools, hospitals, boniness) carrying the name "Nariño." This caused a hyper-inflation of 3,161 cases in ViPAA 1.2. 
      *  The current version of ViPAA 1.3 only has 2 cases in this locality.
   *  There were issues with "Bogota."
      *  The capital of the country "Bogota" has a special designation as "District Capital" similar to Washington D.C. in the U.S. For that reason, it was considered as a "department" in ViPAA 1.2 but was erroneously not included in the dictionary of municipalities. This omission caused ViPAA 1.2 not to report any data in Bogota. 
      *  After fixing the problem and including "Bogota" in the list of municipalities, ViPAA 1.3 now reports 2,865 entries located in the city of Bogota.


<br>

## 3. Methodology and Codebook


The "Methodology_ViPAA_v1.3.pdf" contains the metodological details and codebook.

<br>

## 4. How to Cite

Please cite as:

Osorio, Javier, Mohamed Mohamed, Viveca Pavon, and Susan Brewer-Osorio. (2019). "Mapping Violent Presence of Armed Actors in Colombia", *Advances of Cartography and GIScience of the International Cartographic Association*, 1(16):1-9, https://www.adv-cartogr-giscience-int-cartogr-assoc.net/1/16/2019/


BibTeX:
```
@article{Osorio2019,
author = {Osorio, Javier and  Mohamed, Mohamed and  Pavon, Viveca and 
Brewer-Osorio, Susan},
title = {{Mapping Violent Presence of Armed Actors in Colombia}},
url = {https://www.adv-cartogr-giscience-int-cartogr-assoc.net/1/16/2019/},
Journal = {Advances of Cartography and GIScience of the International 
Cartographic Association},
Number = {1},
Volume = {16},
Pages = {1--9},
year = {2019}
}
```

