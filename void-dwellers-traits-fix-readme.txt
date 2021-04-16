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
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=683230077]NSC2 Modjam Freebooters Origin[/url]
[/list]

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix

Makes following planet classes fully habitable for Void Dwellers:

# Custom flag for mods to use. Set on your planet.
has_planet_flag = voiddwellerstraitsfix

# Vanilla
# is_planet_class = pc_habitat
uses_district_set = habitat
uses_district_set = ring_world

# Planetary Diversity - Planetary Habitats
has_planet_flag = pdhab# failsafe flag
uses_district_set = pdplanethab

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

This mod will not remove negative trait from your existing pops. You can gene-mod them to your starting pops easily.

Overwrites [b]origin.1[/b] event (present in events/origin_events_1.txt).

This Void Dwellers Ring World fix started as a part of my [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url] but since it requires modifying core file I separated it and added support for additional mods.

If you want to add your custom planet class to the list just drop a comment below.

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix