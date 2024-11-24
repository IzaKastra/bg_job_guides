This page contains links to a collection of combat-based gear sets for all jobs, including sets for weapon skills, spells, and occasionally TP sets. If you are interested in "utility" sets, such as a Healing set, or an Enmity set, then please see one of the many proper community job guides available.

The sets presented in each job-specific page were calculated automatically using a Python code built based on our understanding of how damage is calculated in FFXI. The details of the code are described in [https://www.ffxiah.com/forum/topic/57175/all-jobs-damage-simulator-and-gear-sets/ FFXIAH]. The code is open source and is available for viewing and downloading at [https://github.com/IzaKastra/wsdist_beta GitHub]


Each set was tested/built against a custom enemy with '''1350 Evasion, 1500 Defense, 340 VIT, 340 AGI, 280 INT, and 280 MND'''. This is close to a Lv140 Apex enemy.

Sets were tested in two buff situations:
* '''Mid-buff''' (standard buffs) sets should apply for most situations where you are not attack capped and not severely under attack cap. [[Damage Limit+|PDL]] should not apply in these situations.
** Grape Daifuku
** WHM Dia2 (+Light Shot)
** BRD Songs+7 [Honor March, Victory March, Minuet5, Minuet4]
** COR Rolls+7 with job bonuses active [10-Chaos (Crooked) 9-Samurai]
* '''High-buff''' sets should apply for situations where you are approaching attack cap, such that you would benefit from at least a bit of [[Damage Limit+|PDL]].
** Grape Daifuku
** WHM Dia2 (+Light Shot)
** BRD Songs+7 [Honor March (Marcato), Victory March, Minuet5, Minuet4]
** COR Rolls+7 with job bonuses active [10-Chaos (Crooked) 9-Samurai]
** GEO Bubbles+10 [Indi-Fury, Geo-Frailty (BoG, 20% potency)]


The code ignores a few pieces of gear when automatically building sets. The following items were not tested:
* Nyame Rank 30
* Nyame Path A
* Empyrean+2 earrings from [https://www.bg-wiki.com/ffxi/Category:Sortie_Rewards Sortie] (+1 earrings were tested)
* [https://www.bg-wiki.com/ffxi/Category:Prime_Weapons Stage 5 Prime weapons] (stage 4 was tested)
* [[The_Voracious_Resurgence_Mission_11-2|Voracious Resurgence rings]]
* Various "common" equipment: Karieyh Ring +1, Balder Earring +1


{| class="wikitable"
|-
| [[:All Jobs Gear Sets/Warrior]] || [[:All Jobs Gear Sets/Monk]] || [[:All Jobs Gear Sets/White Mage]] || [[:All Jobs Gear Sets/Black Mage]] || [[:All Jobs Gear Sets/Red Mage]]
|-
| [[:All Jobs Gear Sets/Thief]] || [[:All Jobs Gear Sets/Paladin]] || [[:All Jobs Gear Sets/Dark Knight]] || [[:All Jobs Gear Sets/Beastmaster]] || [[:All Jobs Gear Sets/Bard]]
|-
| [[:All Jobs Gear Sets/Ranger]] || [[:All Jobs Gear Sets/Summoner]] || [[:All Jobs Gear Sets/Samurai]] || [[:All Jobs Gear Sets/Ninja]] || [[:All Jobs Gear Sets/Dragoon]]
|-
| [[:All Jobs Gear Sets/Blue Mage]] || [[:All Jobs Gear Sets/Corsair]] || [[:All Jobs Gear Sets/Puppetmaster]] || [[:All Jobs Gear Sets/Dancer]] || [[:All Jobs Gear Sets/Scholar]]
|-
| [[:All Jobs Gear Sets/Geomancer]] || [[:All Jobs Gear Sets/Rune Fencer]] ||  ||  ||  
|}


Disclaimer:
There will be many small changes to these sets that would be better in an in-game situation, such as a set that provides more defensive utility, or avoids PDL in favor of WSD for fights where debuffs/buffs may drop. However, the code must output a single "best" set based only on the final number, even if that number is only 0.1% "better". The code itself can output "next best" equipment in each slot based on the user's inputs. Consider playing with the code yourself to see how similar gear compares.


Author: Kastra (Asura). However, significant contribution from the community and information available on BGWiki have improved the accuracy and usefulness of the code and allowed us to create this collection of sets.
