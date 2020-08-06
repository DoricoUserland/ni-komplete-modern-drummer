# Dorico configuration to work with Komplete - Abbey Road Modern Drummer

## Overview

Dorico 3.5 mappings for Komplete Abbey Road Modern Drummer

The template contains two mappings, one for white kit and one for sparkle kit. Depending on what kit you use, you need to select the right mapping.

Instruments which are in one but not the other kit play wrong (although they are not mapped, they are not silent).

## Installation

You should be able to open sample project as a template (delete all the flows but keep the player). 

You can manually install percussion kit and percussion map, as follows:

1. In Dorico setup, create a new player and click "Import Kit" and import percussion-kit-white.doricolib or percussion-kit-sparkle.doricolib
2. Go to Play->Playback template,  import and apply plaback-template.dorico_pt
3. This will create Kontakt VST instrument with Sparkle kit at channel 1 and White kit at channel 2, with the appropriate mappings applied. Just make sure your kit is using the right channe

## Example project

See sample-project.dorico

## Mapping


| Drum       | Articulation           | MIDI Note - Spark | MIDI Note - White | Vintage Drummer Ebony | Midi Note Studio Stadium | Dorico  Instrument | Dorico playing technique | Dorico notehea | Dorico example |
| ------------- |-------------| -----| ---- | --- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Kick Drum | Dampened | 36 | % | 60/82 | % | Kick Drum (Low) | Natural | ![image-20200723142455451](README.assets/image-20200723142455451.png) |  |
|  | Half Open | 82| % | NA |  | |  |  |  |
|  | Open | 82| % | 36 |  | |  |  |  |
| Snare | Center Right/Left Alternating | 38 | % | % | % | Snare Drum | Natural| ![image-20200723143044372](README.assets/image-20200723143044372.png) |  |
|  | Halfway Right/Left Alternating |  |  | 40 |  | Snare Drum | Edge (drums) | ![image-20200806072657086](README.assets/image-20200806072657086.png) |  |
|  | Rimshot | 39 | % | % | % | Snare Drum | Rim shot | ![image-20200723143106420](README.assets/image-20200723143106420.png) |  |
| | Sidestick | 37 | % | % | % | Snare Drum | Cross stick| ![image-20200723145609345](README.assets/image-20200723145609345.png) |  |
|  | Rim only | 61 | % | % | % | Snare Drum | Rim only| ![image-20200723145621063](README.assets/image-20200723145621063.png) |  |
| | Roll | 63 | % | % | % |  | |  |  |
| | Flam | 62 | % | % | % |  | |  |  |
| | Brush Tap Left Hand |  |  | 81 |  |  | Brush Tap L | ![image-20200806073712664](README.assets/image-20200806073712664.png) |  |
| | Brush Tap Right Hand |  |  | 83 |  |  | Brush Tap R | ![image-20200806073724247](README.assets/image-20200806073724247.png) |  |
| | Brush Dig In |  |  | 84 |  |  | Brush Tip | ![image-20200806073735333](README.assets/image-20200806073735333.png) |  |
| | Brush Swish |  |  | 86 |  |  | Brush Sweep | ![image-20200806073746874](README.assets/image-20200806073746874.png) |  |
| Hi-Hat | Closed Tight Tip Right/Left Alternating | 66 | % | % | % | Hi-hat | Closed tight | ![image-20200803085321163](README.assets/image-20200803085321163.png) | ![image-20200724152032966](README.assets/image-20200724152032966.png) |
| | Closed Shank Right/Left Alternating | 68 | % | % | % | Hi-hat | Natural | ![image-20200724134454660](README.assets/image-20200724134454660.png) |  |
| | Closed Tip Right/Left Alternating | 42 | % | % | % | Hi-hat | Tip | ![image-20200803085503089](README.assets/image-20200803085503089.png) | ![image-20200724135844471](README.assets/image-20200724135844471.png) |
| | Open Quarter | 76 | % | % | % | Hi-hat | Open Quarter | ![image-20200803090016463](README.assets/image-20200803090016463.png) | ![image-20200724142219007](README.assets/image-20200724142219007.png) |
| | Open Half | 77 | % | % | % | Hi-hat | Half-open | ![image-20200803090026939](README.assets/image-20200803090026939.png) | ![image-20200723150532143](README.assets/image-20200723150532143.png) |
| | Open Three-Quarters | 78 | % | % | % | Hi-hat | Open 3 Quarters | ![image-20200803090037321](README.assets/image-20200803090037321.png) | ![image-20200724142822987](README.assets/image-20200724142822987.png) |
| | Open Loose | 79 | % | % | % | Hi-hat | Open Loose | ![image-20200803090049074](README.assets/image-20200803090049074.png) | ![image-20200724143837784](README.assets/image-20200724143837784.png) |
| | Open Full | 80 | % | % | % | Hi-hat | Open 2 | ![image-20200803090108032](README.assets/image-20200803090108032.png) | ![image-20200723150542069](README.assets/image-20200723150542069.png) |
| | Closed Pedal | 44 | % | % | % | Hi-hat (pedal) | Natural | ![image-20200723154413102](README.assets/image-20200723154413102.png) |  |
| | Open Pedal | 70 | % | 70 | % | Hi-hat (pedal) | Open 2 | ![image-20200803090108032](README.assets/image-20200803090108032.png) | ![image-20200723154353499](README.assets/image-20200723154353499.png) |
| | Brush Closed Bell |  |  | 85 |  |  | Brush Sweep | ![image-20200806182951477](README.assets/image-20200806182951477.png) |  |
| | Brush Closed Tip |  |  | 87 |  |  | Brush Tip | ![image-20200806183001937](README.assets/image-20200806183001937.png) |  |
| | Brush Open |  |  | 90 |  |  | Brush | ![image-20200806183012042](README.assets/image-20200806183012042.png) |  |
| Tom 1 | Center Right/Left Alternating | 47 | % | 45 | % | Tom (High) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |  |
|  | Rimshot | 71 | % | 69 | % | Tom (High) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |  |
|  | Rim Only| 75 | % | 73 | % | Tom (High) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |  |
| | Brush Tap |  |  | 91 |  |  |  |  |  |
| | Brush Dig |  |  | 93 |  |  |  |  |  |
| Tom 2 | Center Right/Left Alternating | 45 | % | 41 | % | Tom (Medium-high) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |  |
|  | Rimshot | 69 | % | 65 | % | Tom (Medium-high) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |  |
|  | Rim Only | 74 | % | 72 | % | Tom (Medium-high) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |  |
| | Brush Tap |  |  | 88 |  |  |  |  |  |
| | Brush Dig |  |  | 89 |  |  |  |  |  |
| Tom 3 | Center Right/Left Alternating | 43 | % |  | % | Tom (Medium-low) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |  |
|  | Rimshot | 67 | % |  | % | Tom (Medium-low) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |  |
|  | Rim Only| 73 | % |  | % | Tom (Medium-low) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |  |
| Tom 4 | Center Right/Left Alternating | 41 | % |  | % | Tom (Low) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |  |
|  | Rimshot | 65 | % |  | % | Tom (Low) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |  |
|  | Rim Only| 72 | % |  | % | Tom (Low) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |  |
| Cymbal 1 (High Crash) | Edge | 49 | % | % | % | Crash Cymbal (High) | Natural | ![image-20200803201303464](README.assets/image-20200803201303464.png) |  |
|  | Bell | 50 | % | % | % | Crash Cymbal (High) | Bell | ![image-20200803201057535](README.assets/image-20200803201057535.png) | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 48        | %       | %   | %      | Crash Cymbal (High) | Tip                      | ![image-20200803201316467](README.assets/image-20200803201316467.png) | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 22 | % | % | % | Crash Cymbal (High) | Choke | ![image-20200803202330875](README.assets/image-20200803202330875.png) | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| | Brush |  |  | 92 |  |  |  |  |  |
| Cymbal 2 (Low Crash) | Edge | 55 | % | % | % | Crash Cymbal (Low) | Natural | ![image-20200803201303464](README.assets/image-20200803201303464.png) | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 56 | % | % | % | Crash Cymbal (Low) | Bell | ![image-20200803201057535](README.assets/image-20200803201057535.png) | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 54        | %       | %     | %      | Crash Cymbal (Low) | Tip                      | ![image-20200803201316467](README.assets/image-20200803201316467.png) | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 24 | % | % | % | Crash Cymbal (Low) | Choke | ![image-20200803202320183](README.assets/image-20200803202320183.png) | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| | Brush |  |  | 94 |  |  |  |  |  |
| Cymbal 3 (Ride) | Tip | 51 | % | % | % | Ride Cymbal | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |  |
|  | Bell | 53 | % | % | % | Ride Cymbal | Bell | ![image-20200803201057535](README.assets/image-20200803201057535.png) | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Edge | 52 | % | % | % | Ride Cymbal | Crush | ![image-20200803201303464](README.assets/image-20200803201303464.png) | ![image-20200723195812447](README.assets/image-20200723195812447.png) |
|  | Choke | 23 | % | % | % | Ride Cymbal | Choke | ![image-20200803202320183](README.assets/image-20200803202320183.png) | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| | Brush Tip |  |  | 95 |  |  |  |  |  |
| | Brush Sweep |  |  | 96 |  |  |  |  |  |
| Cymbal 4 (China) | Edge | 57 | % |  | % | China Cymbal | Natural |  | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Tip                                     | 58        | %       |       | %      | China Cymbal | Tip                      |  | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 25 | % |  | % | China Cymbal | Choke |  | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 5 (Splash) | Edge | 59 | % |  | % | Splash Cymbal | Natural | ![image-20200803203924111](README.assets/image-20200803203924111.png) | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Choke | 26 | % |  | % | Splash Cymbal | Choke | ![image-20200803203934453](README.assets/image-20200803203934453.png) | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Perc 1 (Stick) | Hit | 35 | % | % | % | Claves | Natural |  | ![image-20200724161528366](README.assets/image-20200724161528366.png) |
| Perc 2 (Clap) | Solo | 33 | % | % | % | Hand Claps | Natural |  | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Multi | 34 | % | % | % | Hand Claps | Chorus |  | ![image-20200724161603769](README.assets/image-20200724161603769.png) |
| Perc 3 (Cowbell) High | Open | 19 | 29 | 28 | NA | Cowbell (High) | Natural |  | ![image-20200724161620549](README.assets/image-20200724161620549.png) |
|  | Muted | 21 | 30 | 29 |  | Cowbell (High) | Muted |  | ![image-20200724161642875](README.assets/image-20200724161642875.png) |
| Perc 3 (Cowbell) LOW | Open | 16 | 27 |  | 27 | Cowbell (Low) | Natural |  | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Muted | 17 | 28 |  | 28 | Cowbell (Low) | Muted |  | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| | Open Double |  |  |  | 29 |  |  |  |  |
| Perc 3 (Chopper) | High | 29 | 21 |  | NA | Sizzle Cymbal | Up |  | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Mid | 28 | 19 |  | NA | Sizzle Cymbal | Natural |  | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
|  | Low| 27 | 17 |  | NA | Sizzle Cymbal | Down |  | ![image-20200724161738346](README.assets/image-20200724161738346.png) |
| Tambourine | Tap | 31 | NA | 31 | 31 | Tambourine | Natural |  | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Shake | 32 | NA | 32 | 32 | Tambourine | Shake |  | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| Spiral | Stick | NA | 31 |  | NA | Suspended Cymbal | Natural |  | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Mallet | NA | 32 |  | NA | Suspended Cymbal | Shake |  | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| Sand Paper | Scratch |  |  | 26 |  |  |  |  |  |

