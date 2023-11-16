# NormModThalamicNuclei
 Code for manuscript "Lifespan development of thalamic nuclei and characterizing thalamic nuclei abnormalities in psychotic disorders using normative modeling"

 Included in this repository is the code used to produce results for the manuscript. 

## Outline

Code is organized into:
- Data Organization
	- In folder "01_DataOrganization"
	- Code used to combine and organize data HCP S1200, HCP Development, HCP Aging and Schizophrenia Cohorts
	- Code for data harmonization using neuroCOMBAT https://github.com/Jfortin1/neuroCombat
- Normative Modeling
	- In folder "02_NormativeModeling"
	- Code used to run GAMLSS models for the HCP Lifespan datasets
	- Code used to calculate centile scores for Schizophrenia Cohort based on GAMLSS models
- Association with cognition over development
	- In folder "03_DevelopmentEffectsAndCognition"
	- Code used to run GEE models to examine association between thalamic nuclei volumes and executive function scores from several NIH toolbox subscales in the developmental, young adult and aging samples from the HCP Lifespan dataset
- Individual deviation in schizophrenia
	- In folder "04_DeviationsSchizophreniaCohort"
	- Code used to calculate proportions of individuals that show infra-normal, normal and supra-normal in the Schizophrenia Cohrt. 
	- Code used to calculate association between centile scores, raw volumes and cognitive function (Screen for Cognitive Impairment in Psychiatry total scores)