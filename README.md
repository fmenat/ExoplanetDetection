# :computer: Exoplanet Detection with Classical Machine Learning
---
Refining Exoplanet Detection Using Supervised Learning and Feature Engineering
By
* Margarita Bugueño - margarita.bugueno@usm.cl

* Francisco Mena - francisco.menat@usm.cl

* Mauricio Araya - mauricio.araya@usm.cl

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

This table shows some of the predictions of our best representation of data, a Random Forest classifier for the task of exoplanet detection (Confirmed), and a SVM RBF for the task of non-exoplanet detection (False Positive). It should be mentioned that the Confirmed column on that system counts the number of confirmed exoplanets at the date of the study (September 2017), as long as Star is the name of the Parent star in the system; The ones with no information doesn’t show this value.

# :floppy_disk: Source

* Preliminary work in a conference
  * :lock: [Final published version](https://doi.org/10.1109/CLEI.2018.00041)
  * :unlock: [Preprint](https://www.researchgate.net/publication/334992434_Refining_Exoplanet_Detection_Using_Supervised_Learning_and_Feature_Engineering)
  * [Poster](https://github.com/fmenat/fmenat/blob/main/posters/2018_ChileWIC_exoplanet.pdf) (in Spanish)
  * [Presentation](https://github.com/fmenat/fmenat/blob/main/presentations/2018_SLIOA-CLEI_Exoplanet.pdf)
* Extended work in a journal
  * :unlock: [Final published version](https://doi.org/10.19153/cleiej.22.3.3)

# 🖊️ Citation

Bugueno, Margarita, Francisco Mena, and Mauricio Araya. "*Refining exoplanet detection using supervised learning and feature engineering*." 2018 XLIV Latin American Computer Conference (CLEI). IEEE, 2018.
```bibtex
@inproceedings{bugueno2018refining,
  title={Refining exoplanet detection using supervised learning and feature engineering},
  author={Bugueno, Margarita and Mena, Francisco and Araya, Mauricio},
  booktitle={2018 XLIV Latin American Computer Conference (CLEI)},
  pages={278--287},
  year={2018},
  organization={IEEE},
  doi={10.1109/CLEI.2018.00041}
}
```
> Reference of our initial work 


Mena, Francisco, Bugueño,Margarita and Araya, Mauricio. "*Classical machine learning techniques in the search of extrasolar planets*." CLEI electronic journal 22.3, 2019.
```bibtex
@article{mena2019classical,
  title={Classical machine learning techniques in the search of extrasolar planets},
  author={Mena, Francisco and Bugue{\~n}o, Margarita and Araya, Mauricio},
  journal={CLEI electronic journal},
  volume={22},
  number={3},
  pages={3--1},
  year={2019},
  doi={10.19153/cleiej.22.3.3}
}
```
> Reference to our extended work in a journal
