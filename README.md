# Exoplanet Detection
---
Refining Exoplanet Detection Using Supervised Learning and Feature Engineering
By
* Margarita Bugueño - margarita.bugueno.13@sansano.usm.cl

* Francisco Mena - francisco.mena.13@sansano.usm.cl

* Mauricio Araya - maray@inf.utfsm.cl

Data: http://archive.stsci.edu/kepler/koi/search.php

## Results:
---
Disposition over a few of the 1791 candidates of Kepler Mission in 2017.

|**KOI name**|**Disposition**|Confirmed on that system|**Star**|
|-----|-----|-----|-----|
|K00601.02|*FALSE POSITIVE*|2/3|Kepler 619|
|-|-|-|-|
| K00750.02 |*UNCLASSIFIED*| 1/3 | Kepler 662 |
|-|-|-|-|
| K01082.01 |*CONFIRMED*|  |  |
| K01082.02 |*FALSE POSITIVE*| 1/4 | Kepler 763 |
| K01082.04 |*CONFIRMED*|  |  |
|-|-|-|-|
| K01236.04 |*CONFIRMED*| 2/3 | Kepler 279 |
|-|-|-|-| 
| K01358.01 |*CONFIRMED*|  |  |
| K01358.02 |*CONFIRMED*| 0/4 | - |
| K01358.03 |*CONFIRMED*|  |  |
| K01358.04 |*CONFIRMED*|  | |
|-|-|-|-|
| K01750.02 |*CONFIRMED*| 1/2 | Kepler 948 |
|-|-|-|-|
| K02064.01 |*UNCLASSIFIED*| 0/1 | - |
|-|-|-|-|
| K02420.02 |*CONFIRMED*| 1/2 | Kepler 1231 |
|-|-|-|-|
| K02578.01 |*FALSE POSITIVE*| 0/1 | - |
|-|-|-|-|
| K02828.02 |*FALSE POSITIVE*| 1/2 | Kepler 1259 |
|-|-|-|-|
| K03444.03 |*UNCLASSIFIED*| 0/4 | - |
|-|-|-|-|
| K03451.01 |*UNCLASSIFIED*| 0/1 | - |
|-|-|-|-|
| K04591.01 |*FALSE POSITIVE*| 0/1 | - |
|-|-|-|-|
| K05353.01 |*FALSE POSITIVE*| 0/1 | - |
|-|-|-|-|
| K06267.01 |*CONFIRMED*| 0/1 | - |
|-|-|-|-|
| K06983.01 |*CONFIRMED*| 0/1 | - |
|-|-|-|-|
| K07279.01 |*CONFIRMED*| 0/1 | - |
|-|-|-|-|
| K07378.01 |*CONFIRMED*| 0/2 | - |
| K07378.02 |*CONFIRMED*| 0/2 | - |
|-|-|-|-|
| K07434.01 |*FALSE POSITIVE*| 0/1 | - |
|-|-|-|-|
| K08082.01 |*CONFIRMED*| 0/1 | - |

This table show some of the predictions of our best representation of data, a Random Forest classifier for the task of exoplanet detection (Confirmed), and a SVM RBF for the task of non-exoplanet detection (False Positive). It should be mentioned that the column Confirmed on that system count the ammount of confirmed exoplanets on the date of the study (September 2017), as long as Star is the name of the Parent star in the system; The ones with no information doesn’t show this value.
