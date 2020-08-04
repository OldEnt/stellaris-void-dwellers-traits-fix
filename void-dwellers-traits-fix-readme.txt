Void Dwellers will no longer receive negative trait when settling Ring World or custom habitats from supported mods:
[list]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1878751971]Planetary Diversity - Planetary Habitats[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1743133825]Starborn: Improved Voidtouched[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1624127196]Dyson Swarm - colonizing space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1510731495]Habitation[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2049549075]Living Space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1121692237]Gigastructural Engineering & More[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1644767570]Ascendancy Ringworlds[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2079398322]Twinks Atlanteans[/url]
[/list]

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix

Makes following planet classes fully habitable for Void Dwellers:
[b]# Vanilla[/b]
pc_habitat
pc_ringworld_habitable

[b]# Planetary Diversity - Planetary Habitats (2.7.2)[/b]
uses_district_set = pdplanethab
# pc_pd_barren_cold_hab
# pc_pd_barren_hab
# pc_pd_frozen_hab
# pc_pd_gas_giant_hab
# pc_pd_hothouse_hab
# pc_pd_molten_hab
# pc_pd_asteroid_hab
# pc_pd_toxic_hab

[b]# Planetary Diversity - Planetary Habitats (2.6.3)[/b]
pc_gghab
pc_tmhab
pc_tmhab2
pc_mmhab
pc_mmhab2
pc_bhab
pc_bchab
pc_mhab
pc_fhab
pc_fmhab
pc_mehab

[b]# Starborn: Improved Voidtouched[/b]
pc_starborn_habitat_start

[b]# Dyson Swarm - colonizing space[/b]
pc_dyson_swarm

[b]# Living Space[/b]
pc_gas_giant_habitat		
pc_asteroid_habitat			
pc_ice_asteroid_habitat
pc_rare_crystal_asteroid_habitat
pc_molten_habitat
pc_barren_habitat
pc_barren_cold_habitat
pc_toxic_habitat
pc_frozen_habitat
pc_b_star_habitat
pc_a_star_habitat
pc_f_star_habitat
pc_g_star_habitat
pc_k_star_habitat
pc_m_star_habitat
pc_m_giant_star_habitat
pc_t_star_habitat
pc_black_hole_habitat
pc_neutron_star_habitat
pc_pulsar_habitat

[b]# Habitation[/b]
pc_hab_gas_giant_energy
pc_hab_gas_giant_science
pc_hab_gas_giant_minerals
pc_hab_asteroid
pc_hab_ice_asteroid
pc_hab_rare_crystal_asteroid
pc_hab_molten
pc_hab_barren
pc_hab_barren_cold
pc_hab_toxic
pc_hab_frozen

[b]# Gigastructural Engineering & More[/b]
pc_ringworld_city
pc_ringworld_machine
pc_ringworld_hive
pc_birch
pc_flat_world
pc_habitable_m_star
pc_habitable_k_star
pc_habitable_g_star
pc_ringworld_alloys
pc_giga_planetary_computer
pc_city_ringworld_habitable
pc_habitable_gas_giant
pc_ll_temperate
pc_ll_foggy
pc_ll_torrid
pc_virtual_world
pc_squareworld_habitable
pc_giga_ringworld_habitable
pc_gigaorbital_ring
pc_interstellar_habitat
pc_interstellar_ringworld_habitable
pc_virtual_reality
pc_virtual_industry
pc_virtual_stellar_industry
pc_alderson_slice_gaia
pc_alderson_slice_pc
pc_alderson_slice_ecu

[b]# Ascendancy Ringworlds[/b]
pc_ringworld_city
pc_ringworld_eco_city
pc_ringworld_energy_city
pc_ringworld_machine
pc_ringworld_hive
pc_ringworld_shrouded_paradise
pc_square_ringworld_city
pc_square_ringworld_energy_city
pc_square_ringworld_machine
pc_square_ringworld_hive
pc_ringworld_assimilated
pc_ringworld_assimilated2
pc_ringworld_assimilated3
pc_ringworld_assimilated4
pc_ringworld_machine_factory
pc_ringworld_bioforge
pc_ringworld_mining
pc_ringworld_energy
pc_ringworld_trade
pc_ringworld_training
pc_ringworld_training_shielded
pc_ringworld_eco
pc_ringworld_farming
pc_ringworld_razed_city
pc_ringworld_razed_energy
pc_ringworld_razed_farming
pc_ringworld_razed_mining
pc_ringworld_razed_training
pc_ringworld_razed_eco	

[b]# Twinks Atlanteans[/b]
pc_skypalace

This mod will not remove negative trait from your existing pops. You can gene-mod them to your starting pops easily.

Overwrites [b]origin.1[/b] event (present in events/origin_events_1.txt).

This Void Dwellers Ring World fix started as a part of my [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url] but since it requires modifying core file I separated it and added support for additional mods.

If you want to add your custom planet class to the list just drop a comment below.

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix

[url=https://steamcommunity.com/linkfilter/?url=https://discordapp.com/invite/CMjnnET][img]https://i.imgur.com/4Und3QN.png[/img][/url]