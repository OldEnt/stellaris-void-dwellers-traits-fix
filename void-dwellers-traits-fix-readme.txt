Void Dwellers will no longer receive negative trait when settling Ring World or custom habitats from supported mods:
[list]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1878751971]Planetary Diversity - Planetary Habitats[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1743133825]Starborn: Improved Voidtouched[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1624127196]Dyson Swarm - colonizing space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1510731495]Habitation[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2049549075]Living Space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1121692237]Gigastructural Engineering & More[/url]
[*][strike][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1644767570]Ascendancy Ringworlds[/url][/strike] (no longer supported, use [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2441264233]Legacy[/url] version)
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2079398322]Twinks Atlanteans[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=683230077]NSC2 Modjam Freebooters Origin[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=727000451]More Events Mod[/url]
[*][url=https://steamcommunity.com/workshop/filedetails/?id=2178603631]Acquisition of Technology[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2536057864]Planetary Ringworlds[/url]
[/list]

Counts habitable_structure = yes (very useful with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2458836869]The Merger of Rules mod[/url]). Exclusion planet flag: voiddwellerstraitsfix_forbidden.

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix

Supports [url=https://steamcommunity.com/workshop/filedetails/?id=2458024521]Dynamic Mod Menu (3.0.*)[/url] and uses its menu template. Use it to switch ecumenopolis habitability off. Alternatively, execute the following command:
[code]effect set_global_flag = voiddwellerstraitsfix_ecumenopolises_prohibited[/code]

Mod has the following check for exclusion flag before checking list below:
NOT = { has_planet_flag = voiddwellerstraitsfix_forbidden }

Makes following planet classes fully habitable for Void Dwellers:

# Custom flag for mods to use. Set on your planet.
has_planet_flag = voiddwellerstraitsfix

# Vanilla
uses_district_set = habitat
uses_district_set = ring_world
habitable_structure = yes						# Very useful with The Merger of Rules mod.
# is_planet_class = pc_city
NOT = { has_global_flag = voiddwellerstraitsfix_ecumenopolises_prohibited }
uses_district_set = city_world

# Planetary Diversity - Planetary Habitats
has_planet_flag = pdhab# failsafe flag
uses_district_set = pdplanethab

NOT = { has_global_flag = voiddwellerstraitsfix_ecumenopolises_prohibited }
uses_district_set = pdarchive # Archive World
uses_district_set = pdecocity # Eco-Arcology
uses_district_set = pdnecropolis # Necropolis
uses_district_set = pdpalacearc # Palace and Capital Arcology
uses_district_set = pdmilarc # Fortress Arcology
uses_district_set = pdshroudarc # Shrouded Arcology
is_planet_class = pc_technoorganic # Techno-Organic World

# Planetary Diversity - Planetary Habitats - old classes for backwards compatibility # unsupported in Stellaris 3.*, use Legacy fix version

# Starborn: Improved Voidtouched
uses_district_set = starborn_start

# Dyson Swarm - colonizing space
uses_district_set = Dyson_swarm

# Living Space
has_planet_flag = stpg_planetary_habitat

# Habitation
has_planet_flag = hab_init

# Gigastructural Engineering & More
uses_district_set = giga_planet
uses_district_set = giga_alderson
uses_district_set = giga_birch
uses_district_set = giga_habitat
uses_district_set = interstellar_ring
uses_district_set = penrose_ring
uses_district_set = virtual_ring

# # Ascendancy Ringworlds # unsupported in Stellaris 3.*, use Legacy fix version

# Twinks Atlanteans
uses_district_set = skypalace

# NSC2 Modjam Freebooters Origin
uses_district_set = nsc_freebooter_habitat

# More Events Mod
is_planet_class = pc_mem_vazuran_habitat

# Acquisition of Technology
uses_district_set = dm_habitat
uses_district_set = ae_habitat
uses_district_set = sigma_habitat

# Planetary Ringworlds
is_planet_class = pc_planetary_ringworld
is_planet_class = pc_planetary_ringworld_machine
is_planet_class = pc_planetary_ringworld_hive
is_planet_class = pc_planetary_ringworld_city

This mod will not remove negative trait from your existing pops. You can gene-mod them to your starting pops easily.

Overwrites [b]origin.1[/b] event (present in events/origin_events_1.txt).

This Void Dwellers Ring World fix started as a part of my [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url] but since it requires modifying core file I separated it and added support for additional mods.

If you want to add your custom planet class to the list just drop a comment below.

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix