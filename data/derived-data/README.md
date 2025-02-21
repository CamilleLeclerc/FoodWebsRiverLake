# derived-data/

## Folder content
This folder contains the following files:  
- `community_lake.rda` – (4,305 lines x 5 columns) – includes the sampling event ID (`id_campagne`), the species code (`species`) and the associated biomass (`biomass`) and length (`length`) as well as the number of individuals with these attributes (`nind`).  

- `community_lake_metrics.rda` – (4,305 lines x 8 columns) – contains the same variables as `community_lake.rda`, along with detailed information about the biomass of the species caught during the sampling event (`data`, `sp_vector`, `rel_bm`).  

- `community_stream.rda` – (48,879 lines x 7 columns) – includes the sampling event ID (`opcod`), the species code (`species`) and the associated biomass (standardised or not: `bm_std`, `biomass`) and length (`length`) as well as the number of individuals with these attributes (standardised or not: `nind_std`, `nind`).  

- `community_stream_metrics.rda` – (6,358 lines x 11 columns) – contains the same variables as `community_stream.rda`, along with detailed information about the biomass of the species caught during the sampling event, the richness of the community, and the surface used to standardise metrics (`richness`, `surface`, `rich_std`, `data`, `sp_vector`, `rel_bm`).  

- `dataset_lake_stream.rda` – (3,188 lines x 21 columns) – includes the ecosystem type (`type`), the code of the sampling station (`station`), the sampling event ID (`opcod`), the sampling year (`year`), the latitude (`lat`) and the longitude (`long`) of the sampling station, information related to hydrographic basins and topographic watersheds (`CdBH`, `LbBH`, `CdOH`, `TopoOH`) as well as the associated BOD value (`dbo`), temperature (`temp`), connectance (`connectance`), richness (`richness`), number of nodes (`nbnode`), average of trophic level weighted by the biomass (`w_trph_lvl_avg`), maximum trophic level (`max_troph_lvl`), altitude (`altitude`), dissolved oxygen (`oxgen`), total nitrogen (`nitrogen`), total phosphorus (`phosphore`).  

- `env_lake.rda` – (397 lines x 9 columns) – includes the ecosystem type (`type`), the code of the sampling station (`station`), the sampling event ID (`opcod`), the sampling year (`year`), as well as the associated BOD value (`dbo`), temperature (`temp`), dissolved oxygen (`oxgen`), total nitrogen (`nitrogen`), total phosphorus (`phosphore`).  

- `env_stream.rda` – (2,794 lines x 9 columns) – includes the code of the sampling station (`station`), the sampling event ID (`opcod`), the sampling year (`year`), a combined code of the sampling station and year (`station_date`) as well as the associated BOD value (`dbo`), temperature (`temp`), dissolved oxygen (`oxgen`), total nitrogen (`nitrogen.rda`), total phosphorus (`phosphore`).  

- `metaweb_lake.rda` – is a list object of 7 – `metaweb` (403 lines x 403 columns), `species` (44 characters), `resource` (7 characters), `nb_class` (9 numerics), `size_class` (396 lines x 4 columns), `piscivory_index` (396 lines x 3 columns), `th_prey_size` (396 lines x 4 columns).  

- `metaweb_stream.rda` – is a list object of 7 – `metaweb` (412 lines x 412 columns), `species` (45 characters), `resource` (7 characters), `nb_class` (9 numerics), `size_class` (405 lines x 4 columns), `piscivory_index` (405 lines x 3 columns), `th_prey_size` (405 lines x 4 columns).  

- `network_lake.rda` – (451 lines x 3 columns) – includes the sampling event ID (`id_campagne`), the `data` (a list containing species code [`species`] and associated class size [`class_id`] and length [`fish`]) and the `network` (a list containing trophic interactions between predators [`to`] and preys [`from`]).  

- `network_lake_metrics.rda` – (451 lines x 8 columns) – includes the sampling event ID (`id_campagne`), the `network` (a list containing trophic interactions between each trophic species and resources), the `metrics` (a list containing some food-web metrics), the food-web connectance (`connectance`), number of nodes (`nbnode`), `obs_troph_level` (a list containing for each trophic species and resources, the associated trophic level), average of trophic level weighted by the biomass (`w_trph_lvl_avg`), maximum trophic level (`max_troph_lvl`).  

- `network_stream.rda` – (6,358 lines x 3 columns) – includes the sampling event ID (`opcod`), the `data` (a list containing species code [`species`] and associated class size [`class_id`] and length [`length`]) and the `network` (a list containing trophic interactions between predators [`to`] and preys [`from`]).  

- `network_stream_metrics.rda` – (6,358 lines x 10 columns) – includes the sampling event ID (`opcod`), the `data` (a list containing species code [`species`] and associated class size [`class_id`] and length [`length`]) , the `network` (a list containing trophic interactions between each trophic species and resources), the `metrics` (a list containing some food-web metrics), the food-web connectance (`connectance`), number of nodes (`nbnode`), `troph` (a list containing for each trophic species and resources, the associated trophic level and omnivory index), `obs_troph_level` (a list containing for each trophic species and resources, the associated trophic level), average of trophic level weighted by the biomass (`w_trph_lvl_avg`), maximum trophic level (`max_troph_lvl`).  

- `weight_fish_lake.rda` – (751,129 lines x 4 columns) – includes the sampling event ID (`id_campagne`), the species code (`species`) and the associated length (`fish`) and estimated weight (`weight`).  

- `weight_fish_stream.rda` – (3,152,334 lines x 4 columns) – includes the sampling event ID (`opcod`), the species code (`species`) and the associated length (`length`) and estimated weight (`weight`).  
