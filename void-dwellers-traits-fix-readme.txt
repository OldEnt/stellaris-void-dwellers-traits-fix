Void Dwellers will no longer receive negative trait when settling Ring World or custom habitats from supported mods:
[list]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1878751971]Planetary Diversity - Planetary Habitats[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1743133825]Starborn: Improved Voidtouched[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1624127196]Dyson Swarm - colonizing space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1510731495]Habitation[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2049549075]Living Space[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1121692237]Gigastructural Engineering & More[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2079398322]Twinks Atlanteans[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=683230077]NSC2 Modjam Freebooters Origin[/url]
[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=727000451]More Events Mod[/url]
[/list]

Legacy Stellaris 2.* version is available here: https://steamcommunity.com/sharedfiles/filedetails/?id=2441264233

Makes following planet classes fully habitable for Void Dwellers:
[b]# any planet with custom mod flag[/b
has_planet_flag = voiddwellerstraitsfix

[b]# Vanilla[/b]
uses_district_set = habitat
uses_district_set = ring_world

[b]# Planetary Diversity - Planetary Habitats[/b]
has_planet_flag = pdhab
uses_district_set = pdplanethab

[b]# Starborn: Improved Voidtouched[/b]
uses_district_set = starborn_start

[b]# Dyson Swarm - colonizing space[/b]
uses_district_set = Dyson_swarm

[b]# Living Space[/b]
has_planet_flag = stpg_planetary_habitat

[b]# Habitation[/b]
has_planet_flag = hab_init

[b]# Gigastructural Engineering & More[/b]
uses_district_set = giga_planet
uses_district_set = giga_alderson
uses_district_set = giga_birch
uses_district_set = giga_habitat
uses_district_set = interstellar_ring
uses_district_set = penrose_ring
uses_district_set = virtual_ring

[b]# Twinks Atlanteans[/b]
uses_district_set = skypalace

[b]# NSC2 Modjam Freebooters Origin[/b]
uses_district_set = nsc_freebooter_habitat

[b]# More Events Mod[/b]
is_planet_class = pc_mem_vazuran_habitat

This mod will not remove negative trait from your existing pops. You can gene-mod them to your starting pops easily.

Overwrites [b]origin.1[/b] event (present in events/origin_events_1.txt).

This Void Dwellers Ring World fix started as a part of my [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1961367151]Void Dwellers Expanded[/url] but since it requires modifying core file I separated it and added support for additional mods.

If you want to add your custom planet class to the list just drop a comment below.

Source on GitHub: https://github.com/OldEnt/stellaris-void-dwellers-traits-fix