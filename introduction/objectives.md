# Objectives of WP6 within CASCADE [^1]


The Workpackage 6 is targeted at developing models of catastrophic shifts in Drylands. In particular, these models aim at 

- Improving the realism of current ecosystem models of drylands by including detailed ecological mechanisms (based on WB 3 and 4)
- Investigating how this increased realism affects the way ecosystems responds to external pressure, in particular the emergence of catastrophic shifts
- Identifying clear trends toward desertification in the models
- Validating the identified indicators


## Description of work and role of partners
### Summary and linkages
The main objective of WB6 is to develop models that predict sudden regime shifts in dryland ecosystems. Up till now models that predict indicators of the proximity of catastrophic shifts in drylands have revealed a remarkably good match with observations on mesocosm scales. The assumed mechanisms underlying thresholds and shifts are however insufficiently established; hence many crucial input parameters in these models lack an empirical justification. Therefore, these parameter values will be established in WB3 and WB4. This will allow fulfilling the objective of this WB, i.e. the development of a new generation of models, based on sound empirical information, which will be tested through WB4 and WB5. Data from WB 2-5 will be used for validation.

### Task 1: Improving the realism of dryland models

Using results of WB 3, 4 and 5, the first task of this WB will be to increase the realism of current models of drylands step by step. In particular:
- More detailed biogeochemical processes driving the facilitative and competitive interactions between plants will be included
- In current models, grazing is commonly included as an additional mortality. Grazing will be explicitly taken into account, with spatial movement and foraging strategies of the herbivores, in particular how grazers spread their efforts among vegetation patches of different sizes and species composition; Grazing might also affect the biogeochemical processes (e.g. trampling), Additionally, effects of other pressures like wildfires will receive the required attention also.
- Most models of drylands typically include one vegetation type. Different plant functional types based on  different plant strategies identified in previous WBs will be considered (different biotic interactions with other species, different types of impact on the local abiotic conditions, different preferences in terms of grazing). The formulation of the model equations will be realized in close collaboration with field experts, in particular with the members of the WBs 2, 3 and 4.

We will develop a probabilistic cellular automata aiming at describing the dynamics of the vegetation in Mediterranean ecosystems. We will expand on Kéfi et al. 2007 by adding explicit water movement in the model, different plant strategies and explicit grazing.  More precisely, an ecosystem is described by a grid of sites, each of which can be in a different state: occupied by a plant of a given strategy (reproduction, water use, life expectancy), bare soil or degraded soil. In addition, for each cell we will track of two informations:
 1. the water content in the site (after a rain event, water will run off and infiltrate in the soil based on given rules which will depend on soil type); 
 2. the presence or absence of a herbivore (a site can host at most a large herbivore and individuals can move between sites based on foraging theory). These models can also provide information of shifts that occur only after a lag.

The plot studies of WP 3 will allow us to parametrize the major ecological mechanisms of the model (e.g. the intensity of plant species interactions). Emergent properties of the model - namely shape and size of the patterns and the vegetation cover under different water/grazing scenarios - will be compared to the mesocosm experiments and aerial pictures of WP 4 and WP 5.

### Task 2: Investigating the role of these detailed ecological mechanisms for system's behaviour

Simulations of the models will be performed to investigate the system's response to increasing external pressure. External pressure is considered to be e.g. rainfall/drought, temperature, wildfire frequency, or grazing pressure. Ecosystem response is considered to be e.g. vegetation cover, total biomass, species diversity; species identity and spatial structure (size of vegetation patches in the system, maximum patch size, and patch size distribution), and dynamic changes in these. We will especially look for shift behaviors. In systems with only one vegetation type, a shift is usually considered to be the sudden loss of the vegetation cover. When several vegetation types are included in models, several types of shifts may occur: e.g. extinction of one or several species, invasion of a species, drop in species diversity, drop in total biomass. We will identify which type of shift occurs under which circumstances.  More particularly, we will investigate how the ecological mechanisms included in Task 1 affect the response of the ecosystem to stress and the occurrence of shift behavior.

### Task 3: Identification of trends toward degradation
For each of the ecological mechanisms included in Task 1, we will analyze the time series obtained in Task 2 to identify specific trends in the ecosystem response that occur just before a shift occurs. Previous models (of different ecosystems) have suggested the existence of generic early-warning signals that may indicate for a wide class of systems if a critical threshold is approached, the so-called general leading indicators. Based on the model developed in task 1, we can develop the indicators that can then be tested in the field studies. We will study the "behaviour" of the model under different scenarios that lead to shift. By "behaviour" we mean:
 - cover
 - diversity
 - a number of spatial metrics: spatial variance, spatial autocorrelation, distribution of patch sizes, characteristics of the time series (see Scheffer et al. 2009). 
 
The behavior of all of these can be followed and the ones that show consistent trends toward a shift will be identified. These behaviors will be compared to field data (if we can get data of system that are evolving toward a shift). Additionally, indicators related to the spatial structure of the system have been proposed (patch size distribution, flowlength). We intend to calculate all these indicators and compare their performances.Some of these indicators might be general, while others might depend on underlying ecological mechanisms or on the type of ecosystem shift. We will also evaluate how early these trends occur before a shift.

### Task 4: Validation of indicators
The indicators used in task 3 will be validated using field data that have been collected by WB2-5.


[^1]: Extracted from [CASCADE Description of Work](http://www.cascade-project.eu/index.php/downloads/file/1-cascade-description-of-work)