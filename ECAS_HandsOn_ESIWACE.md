# ECAS Hands On (Demo) 14.09.2018 (Draft)

The ENES Climate Analytics Service (ECAS) will enable scientific end-users to perform data analysis experiments on large volumes of climate data, by exploiting a PID-enabled, server-side, and parallel approach.

It aims at providing a paradigm shift for the ENES community with a strong focus on data intensive analysis, provenance management, and server-side approaches as opposed to the current ones mostly client-based, sequential and with limited/missing end-to-end analytics workflow/provenance capabilities.

During this Hands On session, we will demonstrate how to use the *ECAS* service.

**Trainers** Alessandro D'Anca & Sofiane Bendoukha

## Plan
- How to access *ECAS* and log in to the JupyterHub instance
- Open and execute jupyter notebooks
- Compute and visualize **climate indices**
- Share files with B2DROP (**experimental?**)


## Organization

* Please fill in the evaluation forms at the end of the session and give them nack to the trainers.
* Link to this training is [here](https://github.com/ECAS-Lab/ecas-training/blob/master/ECAS_HandsOn_ESIWACE.md)
## Setup

**ECAS/ECASLab** is deployed on two sites:

- CMCC: https://ophidialab.cmcc.it/jupyter/
- DKRZ: https://ecaslab.dkrz.de/jupyter/


To log in, please use the credentials that you received when you registered.

---
**NOTE**

If you haven't registered yet, pick one of the default accounts (**not recommanded!**).

---

**B2DROP shared repository** https://b2drop.eudat.eu/s/gDyJjMeJ2Xiapwi

## Explore the Jupyter environment

When you log in to JupyterHub, a workspace is created for you with following directories:

- **data:** input data required for the workflows
- **notebooks:** implemented use cases
- **workflows:** script-based workflows
- **quickstart:** how to start working with **ECAS**



## Use cases: Computing Climate Indices

### 1. Tropical Nights

Starting from the daily minimum temperature (1980-1990) TN, the Tropical Nights index is the number of days where TN > T (T is a reference temperature, e.g. 20°C)

### 2. Daily Temperature Range (DTR)

The daily temperature range is the arithmetic difference between daily maximum and daily minimum temperature.

## Exercise

Starting from the daily maximum temperature (1980-1990), the Summer Days index is the annual count of days number of days where TX (daily maximum temperature) > 25°C

Based on the definition, try to calculate the number of Summer Days.

Useful information:

**Input NetCDF:** E63_kp40_198001_199012_T2m_daymax_merged.nc

**25°C:** 298.15 Kelvin



## Wraps-Up

+ Access and Log in to *ECAS/ECASLab*
+ Compute climate indices
+ Visualize results
+ Share files with B2DROP
