The following ships have been removed from their unique group and changed to vanilla game groups (X --> Y)

## Argon & Antigone ##
- Aamon - xxx_centaur_xl ==> arg_battleship_xl and ant_battleship_xl  
  * Weight: 50
- Griffon - ant_griffon_xl ==> ant_battleship_xl
  * Weight: 50
- Paracel - xxx_paracel_l ==> arg_destroyer_l and ant_destroyer_l
  * Weight: 35 and 45
- Erebus - xxx_basilisk_l ==> arg_destroyer_l and ant_destroyer_l
  * Weight: 45 and 40
- Basilisk - xxx_nasilisk_l ==> arg_destroyer_l, ant_destroyer_l, and sca_pirate_l
  * Weight: 40, 35, 45
- Manticore - xxx_manticore_l ==> arg_frigate_m, ant_frigate_m, and sca_pirate_l
  * Weight: 60, 50, 40
- Mandalay - xxx_manticore_l ==> arg_frigate_m and ant_frigate_m
  * Weight: 30 and 40
- Skiron - ant_manticore_l ==> ant_frigate_m
  * Weight: 40

## Paranid ##
- Tartarus - xxx_tartarus_xl ==> par_battleship_xl, hol_battleship_xl, and tri_battleship_xl
  * Weight: 50 (x3)
- Pallas - xxx_pallas_l ==> par_frigate_m, hol_frigate_m, and tri_frigate_m
  * Weight: 45 (x3)

## Teladi ##
- Razorbill - xxx_razorbill_l ==> tel_frigate_m
  * Weight: 55

## Split ##
- Copperhead - xxx_gharial_xl ==> spl_battleship_xl
  * Weight: 40
- Python - xxx_python_l ==> spl_destroyer_l
  * Weight: 60
- Taipan - spl_taipan_l ==> spl_destroyer_l
  * Weight: 35
- Caiman - spl_caiman_l ==> spl_frigate_m
  * Weight: 35
- Scorpion - xxx_sorpion_m ==> frf_corvette_m and cub_frigate_m
  * Weight: 80 and 60

Several of these ships are fully removed in SVE_VRO_Trimmed but my intention was to correct these here for anyone who does not want to use the Trimmed version but still use the other job heavy mods. What follows below is a raw paste of the jobs which are removed. TL:DR nearly every "military" related job has been removed **EXCEPT** Kha'ak and Xenon as they need all the help they can and the jobs are (mostly) defensive. All jobs for BUC/HAT/SCA remain due to minimal world impact. 

- sel="//jobs/job[@id='argon_centaur_patrol_xl_center_galaxy']
- sel="//jobs/job[@id='teladi_kea_patrol_m_border_cluster']
- sel="//jobs/job[@id='ministry_kea_police_patrol_m'] 
- sel="//jobs/job[@id='tartarus_PAR_patrol_xl_cluster']
- sel="//jobs/job[@id='tartarus_HOP_patrol_xl_cluster']
- sel="//jobs/job[@id='tartarus_trinity_patrol_xl_cluster']
- sel="//jobs/job[@id='fallensplit_caiman_mixed_cluster']
- sel="//jobs/job[@id='fallensplit_scorpion_mixed_cluster']
- sel="//jobs/job[@id='freefamilies_scorpion_mixed_cluster']
- sel="//jobs/job[@id='zyarth_heavyfrigate_patrol_l_border_sector']
- sel="//jobs/job[@id='freesplit_heavyfrigate_patrol']
- sel="//jobs/job[@id='zyarth_gharial_patrol_xl_center']
- sel="//jobs/job[@id='court_gharial_patrol_xl_center']
- sel="//jobs/job[@id='court_heavyfrigate_patrol_l_border_sector']
- sel="//jobs/job[@id='teladi_fulmar_patrol_xl_cluster']
- sel="//jobs/job[@id='argon_heavyfrigate_patrol_l_sector']
- sel="//jobs/job[@id='antigone_heavyfrigate_patrol_l_border_sector']
- sel="//jobs/job[@id='fallensplit_taipan_mixed_cluster']
- sel="//jobs/job[@id='court_taipan_patrol_l_border_sector']
- sel="//jobs/job[@id='freesplit_taipan_patrol']
- sel="//jobs/job[@id='zyarth_taipan_patrol_l_border_sector']
- sel="//jobs/job[@id='argon_heavydestroyer_patrol_l_sector']
- sel="//jobs/job[@id='antigone_heavydestroyer_patrol_l_border_sector']
- sel="//jobs/job[@id='scaleplate_plunderer_heavydestroyer_basilisk_cluster']
- sel="//jobs/job[@id='antigone_griffon_patrol_xl_border_sector']
- sel="//jobs/job[@id='paranid_heavyfrigate_patrol_l_sector_exp']
- sel="//jobs/job[@id='holyorder_heavyfrigate_patrol_l_cluster_exp']
- sel="//jobs/job[@id='trinity_heavyfrigate_patrol_l_sector_exp']
- sel="//jobs/job[@id='teladi_heavyfrigate_patrol_l_border_cluster']
- sel="//jobs/job[@id='ministry_heavyfrigate_patrol_l']
- sel="//jobs/job[@id='scaleplate_plunderer_heavyfrigate_manticore_cluster']  
- sel="//jobs/job[@id='zyarth_viper_patrol_l_border_sector']
- sel="//jobs/job[@id='court_viper_patrol_l_border_sector']
- sel="//jobs/job[@id='zyarth_python_patrol_l_border_sector']
- sel="//jobs/job[@id='court_python_patrol_l_border_sector'] 
- sel="//jobs/job[@id='argon_paracel_patrol_l_sector']
- sel="//jobs/job[@id='antigone_paracel_patrol_l_border_sector']
- sel="//jobs/job[@id='kea_teladi_escort_m']
- sel="//jobs/job[@id='ministry_fighter_escort_s_kea']
- sel="//jobs/job[@id='argon_fighter_escort_s_centaur']
- sel="//jobs/job[@id='argon_frigate_escort_m_centaur']
- sel="//jobs/job[@id='zyarth_heavyfrigate_escort_l_noescort']
- sel="//jobs/job[@id='court_heavyfrigate_escort_l_noescort']
- sel="//jobs/job[@id='argon_heavyfrigate_escort_l_escort']
- sel="//jobs/job[@id='ter_heavyfrigate_patrol_l']" />
- sel="//jobs/job[@id='ter_heavygunship_patrol_l']" />
- sel="//jobs/job[@id='ter_heavygunship_patrol_l_sector']" />
- sel="//jobs/job[@id='terran_heavygunship_escort_l']" />    
- sel="//jobs/job[@id='teladi_tech_trader_xl_trader']" />
- sel="//jobs/job[@id='paranid_construction_trader_xl_trader']" />
- sel="//jobs/job[@id='argon_tech_trader_xl_trader']" />
- sel="//jobs/job[@id='antigone_equipment_trader_xl_trader']" />
- sel="//jobs/job[@id='antigone_equipment_trader_bio_xl_trader']" />
- sel="//jobs/job[@id='zyarth_equipment_trader_l_sve']" />  
- sel="//jobs/job[@id='zyarth_tech_trader_l_sve']" />
- sel="//jobs/job[@id='zyarth_ship_construction_trader_m_sve']" />
- sel="//jobs/job[@id='zyarth_free_miner_m_mineral_sve']" />
- sel="//jobs/job[@id='freesplit_equipment_trader_m_sve']" />
- sel="//jobs/job[@id='freesplit_ship_construction_trader_l_sve']" />
- sel="//jobs/job[@id='freesplit_tech_trader_l_sve']" />
- sel="//jobs/job[@id='freesplit_free_miner_m_mineral_sve']" /> 
- sel="//jobs/job[@id='holyorder_ship_construction_trader_m_extra']" />
- sel="//jobs/job[@id='holyorder_free_miner_m_mineral_extra']" />
- sel="//jobs/job[@id='argon_medical_trader_baku']" />
- sel="//jobs/job[@id='antigone_medical_trader_baku']" />  
