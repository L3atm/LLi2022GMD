# Key Data to LLi et al. (2022): LLi2022GMD.model.output.tar.gz and LLi2022GMD.Albani2014JAMES.tar.gz

Title for the paper: 

Importance of different parameterization changes for the updated dust cycle modelling in the Community Atmosphere Model (version 6.1)

Authors: 

Longlei Li, Natalie M Mahowald, Jasper F Kok, Xiaohong Liu, Mingxuan Wu, Danny M. Leung, Douglas S Hamilton, Louisa K. Emmons, Yue Huang, Jun Meng, Neil Sexton, and Jessica Wan

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Model output 

LLi2022GMD.model.output.tar.gz

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Model casenames below corresponding to those described in Table 4 in order

EXP01: cam6_bulk_pz10AspBRIFTS5_001_soilMoisture_01

EXP02: p2_k_bulk_pd_5size

EXP03: p2_k_bulk_pd_6size

EXP04: p2_k_bulk_pd_6size_5sigma

EXP05: cam6_bulk_z01SphDEADS6_tuned

EXP06: cam6_mineral_c1999_z01NonAsph_dead_noHemsilt_001

EXP07: cam6_c1999_z01Sph_kok_noHemsilt_soilMoistureOn

EXP08: cam6_c1999_z01Asph_kok_noHemsilt_soilMoistureOn

EXP09: cam6_c1999_pz01Asph_kok_noHemsilt_soilMoistureOn

Data filename describtions

LLiGMD2022_dust_quantity_"casenames".nc: dust quantities including dust aerosol optical depth, deposition fluxes (wet, dry, and total), and burdens

LLiGMD2022_dust_DRE_"casenames".nc: dust direct radiative effect at the top of the atmosphere under all-sky conditions

Note dust quantities and direct radiative effects from EXP03 and EXP04 are rescaled in Li et al. (2022), but this dataset cotains unscaled numbers.

Descriptions of variables

toaforcingnt (W/m2): net (SW+LW) direct radiative effect

AODDUST (unitless): dust aerosol optical depth at the visible band centered at 0.53 µm

dst_aSF (Kg/m2/s): surface dust emission rate

dst_ttDDF (Kg/m2/s): dry deposition rate of dust aerosol

dst_ttDep (Kg/m2/s): total deposition (dry+wet) rate of dust aerosol

dst_ttSFWET (Kg/m2/s): wet deposition rate of dust aerosol

dust_burden (kg/m2): dust burden

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Data from Albani et al. (2014) archived here

LLi2022GMD.Albani2014JAMES.tar.gz

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

conc.Fe.exclude: surface dust concentrations

samuel.dep.approxlessthan10.northamerica: dust total (dry+wet) deposition fluxes

stations.dust.uselatlon.opta: filtered dust aerosol optical depth

See Albani et al. (2014) for details about the data

