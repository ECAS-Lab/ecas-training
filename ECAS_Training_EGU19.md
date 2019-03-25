# Data Analysis made easy with the ENES Climate Analytics Service (ECAS) -- Draft

## Training on ECAS at EGU19

Co-organized as ESSI1.18/GI2.15

Convener: **Sofiane Bendoukha**

Co-conveners: **Donatello Elia**, **Fabrizio Antonio**, Alessandro D'Anca, Tobias Weigel

Wed, 10 Apr, 08:30–10:15 (105 mins) Room -2.31

The ENES Climate Analytics Service (ECAS) enables scientific end-users to perform data analysis experiments on large volumes of climate data, by exploiting a PID-enabled, server-side, and parallel approach.

It aims at providing a paradigm shift for the European Network for Earth System Modelling (ENES) community with a strong focus on data intensive analysis, provenance management, and server-side approaches as opposed to the current ones mostly client-based, sequential and with limited/missing end-to-end analytics workflow/provenance capabilities.


## Plan
- How to access *ECAS* and log in to the JupyterHub instance at DKRZ/CMCC
- Open and execute jupyter notebooks
- Compute and visualize **climate indices**
- (Optional) share results with B2DROP



## Organization

* Please fill in the evaluation forms at the end of the session and give them back to the trainers.

* To log in, please use the credentials that you received when you registered.

---
**NOTE**

If you haven't registered yet, pick one of the default accounts (**not recommanded!**).

---

## Setup / useful links

**ECAS Portal**

- DKRZ: https://ecaslab.dkrz.de
- CMCC: https://ophidialab.cmcc.it

**ECASLab / JupyterHub** is deployed on two sites:
- DKRZ: https://ecaslab.dkrz.de/jupyter/
- CMCC: https://ecaslab.cmcc.it/jupyter/

**Documentation**

- [Ophidia framework documentation](http://ophidia.cmcc.it/documentation/users/index.html)
- [ECASLab documentation](https://ee-docs.readthedocs.io/en/latest/)

**Github**

- https://github.com/ECAS-Lab
- https://github.com/OphidiaBigData/PyOphidia


## Explore the Jupyter environment

When you log in to JupyterHub, a workspace is created for you with following directories:

- **data:** input data required for the workflows
- **notebooks:** implemented use cases
- **workflows:** script-based workflows
- **quickstart:** how to instantiate clients 



## Demo
All notebooks are available in the *notebooks* directory.

### 1. Subset/Aggregate (simple)

**Notebooks**
* Aggregated_map.ipynb
* Subsetted_map.ipynb

### 2. Computing Climate Indices (e.g Tropical Nights) (medium)

Starting from the daily minimum temperature (1980-1990) TN, the Tropical Nights index is the number of days where TN > T (T is a reference temperature, e.g. 20°C).

**Notebook** Tropical+Nights.ipynb


### 3. Daily Temperature Range (DTR) (complex)

The daily temperature range is the arithmetic difference between daily maximum and daily minimum temperature.

**Notebook** DTR.ipynb

## Hands on

---
**NOTE**

All notebooks are available under /notebooks in your jupyter workspace.

---

The following notebooks cover more details on data processing operations using ECAS/Ophidia.
They provide a step-by-step instructions on how to use the Ophidia operators as well as the PyOPhidia library.

**Notebook** ECASLab-Training.ipynb

## Exercise (Optional)

Starting from the daily maximum temperature (1980-1990), the Summer Days index is the annual count of days number of days where TX (daily maximum temperature) > 25°C

Based on the definition, try to calculate the number of Summer Days.

Useful information:

**Input NetCDF:** E63_kp40_198001_199012_T2m_daymax_merged.nc

**25°C:** 298.15 Kelvin



## Wraps-Up

+ Access and Log in to *ECAS/ECASLab*
+ Compute climate indices
+ Visualize results

