# Road network validation: Ottawa Hintonburg

- Nodes: 1549, edges: 1890, total length: 100.58 km
- Connected components: 19 (largest has 914 nodes)
- Largest strongly connected component: 858 nodes
- Dead ends: bbox_edge 103, declared_noexit 8, likely_real 59, suspicious 0, parking 290
- Ramp problems: 0; one-way traps: 0 (plus 4 one-way stubs that simply dead-end, counted under dead ends)
- Defaulted fields: lanes 742, speed_kph 833, width 1890

## Edge classes

| Class | Edges |
|---|---|
| living_street | 6 |
| motorway | 18 |
| motorway_link | 24 |
| parking | 523 |
| primary | 26 |
| primary_link | 9 |
| residential | 557 |
| secondary | 247 |
| secondary_link | 4 |
| service | 283 |
| tertiary | 53 |
| trunk | 29 |
| trunk_link | 12 |
| unclassified | 99 |

## Connected components

| Nodes | Edges | Likely cause | Classes | Sample names | Sample way ids |
|---|---|---|---|---|---|
| 914 | 1159 | main network | living_street 1, motorway 18, motorway_link 24, parking 298, primary 26, primary_link 9, residential 388, secondary 181, secondary_link 3, service 181, tertiary 22, unclassified 8 | Autoroute Guy-Lafleur, Booth Street, Boulevard Alexandre-Taché, Boulevard Saint-Joseph, Boulevard des Allumettières, Impasse du Cuvier, Pont de la Chaudière, Promenade du Lac-des-Fées | 1315581, 9589680, 9896832, 9896843, 9896892, 9896966, 9896995, 9897006 |
| 581 | 694 | cut by bbox edge | parking 207, residential 158, secondary 66, secondary_link 1, service 99, tertiary 31, trunk 29, trunk_link 12, unclassified 91 | Albert Street, Armstrong Street, Bayswater Avenue, Bayview Station Road, Breezehill Avenue North, Bullman Street, Burnside Avenue, Carruthers Avenue | 4852253, 39451252, 64880469, 76417603, 76417606, 76417707, 76417713, 76417735 |
| 8 | 7 | cut by bbox edge | residential 6, service 1 | Rue Edgar-Chénier, Rue Saint-Henri, Rue Saint-Hyacinthe | 10319862, 39421978, 197067071, 455744982 |
| 7 | 6 | cut by bbox edge | residential 4, service 2 | Chaudière Private | 207595979, 551942811, 551942815, 594753553, 1447769240 |
| 6 | 5 | cut by bbox edge | living_street 5 | Walnut Court | 76423869, 305081739, 305081740 |
| 5 | 4 | cut by bbox edge | parking 4 | - | 162116776, 162116778, 162116786 |
| 4 | 3 | cut by bbox edge | parking 3 | - | 161997154 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 115656783 |
| 2 | 1 | cut by bbox edge | residential 1 | Rue Émile-Bond | 12373789 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 1310620256 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 162116779 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 162116789 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 104403014 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 104403018 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 681914199 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 681974181 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 693578293 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 701099225 |
| 2 | 1 | cut by bbox edge | parking 1 | - | 752026260 |

## Dead ends

### bbox_edge (103)

103 entries; listed in the JSON report only.

### declared_noexit (8)

| Node | Way | Class | Name |
|---|---|---|---|
| 112401142 | 1358236375 | unclassified | Rue Wìgwàs |
| 1205617993 | 104491839 | residential | Rue Sainte-Bernadette |
| 1205729173 | 334582796 | residential | Rue Charles-Bagot |
| 1236348529 | 107602616 | residential | Hintonburg Place |
| 1357270714 | 121187582 | service | - |
| 472497817 | 39451325 | residential | Rue Morin |
| 5329702256 | 950057423 | service | - |
| 901059715 | 76421343 | residential | Manchester Avenue |

### likely_real (59)

59 entries; listed in the JSON report only.

### suspicious (0)

none

### parking (290)

| Node | Way | Class | Name |
|---|---|---|---|
| 0 | 115656783 | parking | - |
| 0 | 792755517 | parking | - |
| 0 | 793034675 | parking | - |
| 0 | 834841319 | parking | - |
| 0 | 1310620256 | parking | - |
| 0 | 1310620256 | parking | - |
| 0 | 161971140 | parking | - |
| 0 | 161971140 | parking | - |
| 0 | 161997153 | parking | - |
| 0 | 161997153 | parking | - |
| 0 | 161997154 | parking | - |
| 0 | 161997154 | parking | - |
| 0 | 161997154 | parking | - |
| 0 | 162116776 | parking | - |
| 0 | 162116778 | parking | - |
| 0 | 162116779 | parking | - |
| 0 | 162116786 | parking | - |
| 0 | 162116789 | parking | - |
| 0 | 484816105 | parking | - |
| 0 | 104403014 | parking | - |
| 0 | 104403018 | parking | - |
| 0 | 681423187 | parking | - |
| 0 | 681423188 | parking | - |
| 0 | 681914199 | parking | - |
| 0 | 681974172 | parking | - |
| 0 | 681974181 | parking | - |
| 0 | 693578293 | parking | - |
| 0 | 693578293 | parking | - |
| 0 | 694104402 | parking | - |
| 0 | 701099225 | parking | - |
| 0 | 752026260 | parking | - |
| 1124860808 | 97094182 | parking | - |
| 11284579247 | 1217873589 | parking | - |
| 11497032327 | 1237763313 | parking | - |
| 11522109069 | 1240183270 | parking | - |
| 11522112823 | 1240186671 | parking | - |
| 11524101907 | 1240361013 | parking | - |
| 11620243604 | 1250092552 | parking | - |
| 11620243607 | 1250092553 | parking | - |
| 11620243610 | 1250092554 | parking | - |
| 11620243613 | 1250092555 | parking | - |
| 11620243616 | 1250092556 | parking | - |
| 11620243620 | 1250092557 | parking | - |
| 11620243624 | 1250092558 | parking | - |
| 11620243627 | 1250092559 | parking | - |
| 11620243629 | 1250092560 | parking | - |
| 11620243633 | 1250092561 | parking | - |
| 11620243636 | 1250092562 | parking | - |
| 11620243640 | 1250092563 | parking | - |
| 11620243643 | 1250092564 | parking | - |
| 12029612438 | 1298616498 | parking | - |
| 12029612442 | 1298616499 | parking | - |
| 12029653776 | 1298616504 | parking | - |
| 12029653779 | 1298616505 | parking | - |
| 12029653782 | 1298616506 | parking | - |
| 12029653840 | 1298616511 | parking | - |
| 12029653887 | 1298616518 | parking | - |
| 12029653893 | 1298616520 | parking | - |
| 12029653897 | 1298616521 | parking | - |
| 12029653899 | 1298616522 | parking | - |
| 12029653908 | 1298616525 | parking | - |
| 12029653911 | 1298616526 | parking | - |
| 12029653920 | 1298616528 | parking | - |
| 1204582876 | 104403014 | parking | - |
| 12049654354 | 1300945902 | parking | - |
| 12049654355 | 1300945902 | parking | - |
| 12049654357 | 1300945904 | parking | - |
| 12049654358 | 1300945904 | parking | - |
| 12055235935 | 484816100 | parking | - |
| 1205756665 | 104508146 | parking | - |
| 12063772924 | 1302578076 | parking | - |
| 12063772927 | 1302578077 | parking | - |
| 12063777824 | 1302578108 | parking | - |
| 12063777829 | 1302578109 | parking | - |
| 12063777833 | 1302578110 | parking | - |
| 12063777835 | 1302578111 | parking | - |
| 12120627842 | 1308854935 | parking | - |
| 12132192239 | 1310620231 | parking | - |
| 12132192242 | 1310620232 | parking | - |
| 12132192255 | 1310620235 | parking | - |
| 12132211938 | 1310620257 | parking | - |
| 12192932651 | 1317404612 | parking | - |
| 12245199336 | 1323303067 | parking | - |
| 12245199337 | 1323303067 | parking | - |
| 12569810467 | 1358236368 | parking | - |
| 12569810469 | 1358236369 | parking | - |
| 12569810473 | 1358236370 | parking | - |
| 12647604561 | 1365737448 | parking | - |
| 1306054455 | 104403018 | parking | - |
| 1306054483 | 115656783 | parking | - |
| 1314305615 | 116622279 | parking | - |
| 1314327971 | 116624786 | parking | - |
| 1314328053 | 116624783 | parking | - |
| 13204197171 | 1436607672 | parking | - |
| 13204197173 | 1436607673 | parking | - |
| 13204197175 | 1436607674 | parking | - |
| 13204207906 | 1436607684 | parking | - |
| 13204207908 | 1436607685 | parking | - |
| 13526174367 | 1474397368 | parking | - |
| 1357270557 | 121187584 | parking | - |
| 13763760802 | 1504037632 | parking | - |
| 13763760804 | 1504037633 | parking | - |
| 13768789401 | 1504736356 | parking | - |
| 13894950763 | 1524491743 | parking | - |
| 13894980083 | 1524492047 | parking | - |
| 13894980092 | 1524492055 | parking | - |
| 13895020489 | 1524495325 | parking | - |
| 13895032085 | 1524494904 | parking | - |
| 13895032087 | 1524494905 | parking | - |
| 13895032088 | 1524494906 | parking | - |
| 13895032089 | 1524494906 | parking | - |
| 13895032522 | 1524493495 | parking | - |
| 13895032524 | 1524493496 | parking | - |
| 13895032890 | 1524494568 | parking | - |
| 13898671734 | 1524872097 | parking | - |
| 13898671737 | 1524872098 | parking | - |
| 13898671739 | 1524872099 | parking | - |
| 13898713750 | 1524875909 | parking | - |
| 13964945279 | 1532276770 | parking | - |
| 14044846823 | 630768647 | parking | - |
| 14173472799 | 1560055746 | parking | - |
| 14190791291 | 1560055728 | parking | - |
| 14190815825 | 1560055738 | parking | - |
| 14190815826 | 1560055739 | parking | - |
| 14190815849 | 1560055746 | parking | - |
| 14210958679 | 1561869674 | parking | - |
| 14210958689 | 1561869676 | parking | - |
| 14210958693 | 1561869677 | parking | - |
| 14210958700 | 1561869679 | parking | - |
| 14210968882 | 1561868928 | parking | - |
| 14210968886 | 1561868929 | parking | - |
| 14210968890 | 1561868930 | parking | - |
| 14210968891 | 1561868931 | parking | - |
| 14210968895 | 1561868932 | parking | - |
| 14210983870 | 1561869265 | parking | - |
| 14210983883 | 1561869267 | parking | - |
| 14210993806 | 1561869680 | parking | - |
| 1725346213 | 211285778 | parking | - |
| 1729485848 | 161373268 | parking | - |
| 1740501005 | 162116789 | parking | - |
| 1740501013 | 162116779 | parking | - |
| 1746693075 | 162862923 | parking | - |
| 1746693090 | 162862917 | parking | - |
| 1746693176 | 162862917 | parking | - |
| 1746693187 | 162862923 | parking | - |
| 2213066991 | 211285779 | parking | - |
| 2990991052 | 295393164 | parking | - |
| 3121580901 | 305081636 | parking | - |
| 3268378677 | 320332654 | parking | - |
| 3268378689 | 320332656 | parking | - |
| 4056648168 | 403305812 | parking | - |
| 4574147492 | 461979370 | parking | - |
| 4775687036 | 484816103 | parking | - |
| 4775687064 | 484816100 | parking | - |
| 5606026855 | 97094176 | parking | - |
| 5629747801 | 589550114 | parking | - |
| 5629747820 | 589550117 | parking | - |
| 5853855714 | 619459480 | parking | - |
| 5853855715 | 619459479 | parking | - |
| 5853855718 | 619459480 | parking | - |
| 5853855721 | 619459481 | parking | - |
| 5853855722 | 619459482 | parking | - |
| 5853855724 | 619459483 | parking | - |
| 5853855729 | 619459484 | parking | - |
| 5853855730 | 619459485 | parking | - |
| 5853855734 | 619459487 | parking | - |
| 5955536148 | 630768649 | parking | - |
| 5963220044 | 631433836 | parking | - |
| 5963250625 | 631438365 | parking | - |
| 5964554995 | 631621722 | parking | - |
| 6020186589 | 638808568 | parking | - |
| 6313560473 | 674164467 | parking | - |
| 6343830188 | 677518486 | parking | - |
| 6343830189 | 677518487 | parking | - |
| 6381286568 | 681423190 | parking | - |
| 6386116880 | 681914199 | parking | - |
| 6386214685 | 681923552 | parking | - |
| 6386214691 | 681923553 | parking | - |
| 6386214695 | 681923555 | parking | - |
| 6386214701 | 681923556 | parking | - |
| 6386214702 | 681923557 | parking | - |
| 6386333340 | 681935300 | parking | - |
| 6386333343 | 681935302 | parking | - |
| 6386565658 | 681974176 | parking | - |
| 6386565659 | 681974176 | parking | - |
| 6386565675 | 681974181 | parking | - |
| 6386569885 | 116622278 | parking | - |
| 6386569887 | 681974184 | parking | - |
| 6386569889 | 681974185 | parking | - |
| 6386922429 | 682019095 | parking | - |
| 6462515177 | 688954353 | parking | - |
| 6462515179 | 688954354 | parking | - |
| 6462515181 | 688954355 | parking | - |
| 6462517338 | 688954415 | parking | - |
| 6462545131 | 688956744 | parking | - |
| 6462545133 | 688956748 | parking | - |
| 6462559713 | 688957746 | parking | - |
| 6462559715 | 688957747 | parking | - |
| 6462559716 | 688957748 | parking | - |
| 6462559726 | 688957750 | parking | - |
| 6462559729 | 688957751 | parking | - |
| 6463032906 | 689000978 | parking | - |
| 6463033129 | 689000993 | parking | - |
| 6463033130 | 689000995 | parking | - |
| 6465280512 | 689188911 | parking | - |
| 6465280563 | 689188917 | parking | - |
| 6465313765 | 689191863 | parking | - |
| 6465313770 | 689191865 | parking | - |
| 6465313772 | 689191866 | parking | - |
| 6465313774 | 689191866 | parking | - |
| 6465313775 | 689191867 | parking | - |
| 6465313820 | 689191873 | parking | - |
| 6465313826 | 689191874 | parking | - |
| 6511668876 | 693578273 | parking | - |
| 6511668879 | 693578274 | parking | - |
| 6511668882 | 693578275 | parking | - |
| 6511669098 | 693578278 | parking | - |
| 6511669110 | 693578283 | parking | - |
| 6511669127 | 693578288 | parking | - |
| 6511714965 | 693582481 | parking | - |
| 6511714968 | 693582482 | parking | - |
| 6511714969 | 693582483 | parking | - |
| 6511714971 | 693582484 | parking | - |
| 6511714974 | 693582485 | parking | - |
| 6511714978 | 693582486 | parking | - |
| 6516589664 | 694095958 | parking | - |
| 6516589665 | 694095958 | parking | - |
| 6516674052 | 694104401 | parking | - |
| 6516674062 | 694104403 | parking | - |
| 6516674066 | 694104404 | parking | - |
| 6567901296 | 699422837 | parking | - |
| 6584252837 | 701099225 | parking | - |
| 6872396974 | 733781160 | parking | - |
| 6925265266 | 739626291 | parking | - |
| 6936173783 | 740864638 | parking | - |
| 6936181586 | 740864639 | parking | - |
| 6936181708 | 740864684 | parking | - |
| 6936181714 | 740864686 | parking | - |
| 6936181717 | 740864687 | parking | - |
| 6936181720 | 740864688 | parking | - |
| 6936181723 | 740864689 | parking | - |
| 6936181726 | 740864690 | parking | - |
| 6936181729 | 740864691 | parking | - |
| 6936181731 | 740864692 | parking | - |
| 6936181734 | 740864693 | parking | - |
| 6936181737 | 740864694 | parking | - |
| 6936181740 | 740864695 | parking | - |
| 6936181743 | 740864696 | parking | - |
| 6936181746 | 740864697 | parking | - |
| 6975277838 | 745149754 | parking | - |
| 6975277840 | 745149755 | parking | - |
| 6975277939 | 97094164 | parking | - |
| 6994002537 | 747466079 | parking | - |
| 6994002542 | 747466080 | parking | - |
| 7029854165 | 752026260 | parking | - |
| 7089553014 | 759011059 | parking | - |
| 7090084471 | 759089043 | parking | - |
| 7123078380 | 762329416 | parking | - |
| 7123078381 | 762329417 | parking | - |
| 7147704792 | 765281022 | parking | - |
| 7267148567 | 778631631 | parking | - |
| 7267170090 | 778631637 | parking | - |
| 7267170099 | 778631640 | parking | - |
| 7386124854 | 790008157 | parking | - |
| 7386124856 | 790008158 | parking | - |
| 7412941162 | 792755506 | parking | - |
| 7412941165 | 792755507 | parking | - |
| 7412941169 | 792755508 | parking | - |
| 7412945398 | 792755511 | parking | - |
| 7412945449 | 792755522 | parking | - |
| 7412945453 | 792755523 | parking | - |
| 7412945454 | 792755524 | parking | - |
| 7412945593 | 792755540 | parking | - |
| 7412945594 | 792755541 | parking | - |
| 7412989538 | 792761394 | parking | - |
| 7414818296 | 792943727 | parking | - |
| 7414818640 | 792946165 | parking | - |
| 7415615763 | 793034678 | parking | - |
| 7423828545 | 793638058 | parking | - |
| 7423828549 | 793638059 | parking | - |
| 7423847896 | 793638070 | parking | - |
| 7423847907 | 793638074 | parking | - |
| 7423847912 | 793638076 | parking | - |
| 8095168044 | 868474367 | parking | - |
| 8095168045 | 868474368 | parking | - |
| 8095168048 | 868474369 | parking | - |
| 8095168049 | 868474370 | parking | - |
| 8095168051 | 868474371 | parking | - |
| 8307992882 | 893877529 | parking | - |
| 979866760 | 84235216 | parking | - |

## Ramp connectivity

Every *_link chain connects a major road at two or more points.

## One-way traps

No traps: every node inside the bbox can reach and be reached from the main network.

## Junction clusters

- 89 merged junctions; each road keeps its own line through them. Largest arm offsets from the centroid:
  - c1314327975 (OSM 80387543, 84758327, 1314327975, 1314328052): 16.232 m
  - c1203185609 (OSM 472497793, 1203185609, 1203185626, 1203185655, 1746681420, 3707404331): 14.883 m
  - c2251075615 (OSM 287909522, 2251075615, 2251075617, 2251075620, 2251075623): 12.931 m
  - c5629747803 (OSM 5629747803, 6462559718, 6462559732): 11.722 m
  - c13528235619 (OSM 7423828540, 13528235619, 13528235624, 13528235627): 11.658 m
  - c12192932694 (OSM 7412945591, 7412945596, 12192932694): 11.313 m
  - c13269512838 (OSM 13269512838, 13269512850, 13890953930): 10.567 m
  - c11620243615 (OSM 11620243615, 11620243631, 11620243634): 9.916 m
  - c1124860829 (OSM 1124860829, 1234289171): 8.984 m
  - c12132192256 (OSM 901045795, 12132192256): 8.82 m

## Water

- Polygons written: 6; relations or ways skipped: 0

## Barriers

- curb 1244, parapet 52, median 17, guardrail 12, roadblock 128

## Buildings

- Footprints written: 3771; height from tag/levels/default: {'default': 3470, 'levels': 301, 'tag': 2}

## Elevation

- Road height range: 42.993 m to 83.256 m
- Bridge/tunnel (fixed) vertices: 97; approach vertices raised or lowered to meet them: 104
- Conflicting bridge constraints: 1; bridge chains without a ground anchor: 0
- Vertices under a bridge footprint refilled from neighbours (DTM keeps decks): 128
- Worst residual grade: 0.1202; edges still over their class limit: 4
  w1334530420.0, w457921474.0, w76423548.0, w76423892.0
- Shared heights: 36 deck and 110 ground vertices; largest step before 0.652 m, left after 0.174 m
- Span chains raised again for clearance after sharing: 0
- Decks short of their clearance over a road: 0
- Bridges inferred from untagged crossings: 0
