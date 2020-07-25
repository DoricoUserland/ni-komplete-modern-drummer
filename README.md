# Dorico configuration to work with Komplete - Abbey Road Modern Drummer

## Overview

Dorico 3.5 mappings for Komplete Abbey Road Modern Drummer

The template contains two mappings, one for white kit and one for sparkle kit. Depending on what kit you use, you need to select the right mapping.

Instruments which are in one but not the other kit play wrong (although they are not mapped, they are not silent).

## Installation

You should be able to open sample project as a template for your needs (delete al the flows but keep the player). 

You can manually install percussion kit and percussion map, as per below, but in this case you will not be able to use some custom playing techniques.

1. In Dorico setup, create a new player and click "Import Kit" and import percussion-kit.doricolib
2. In Play menu, go to play->Percussion maps and import percussion-map-white.doricolib and percussion-map-sparkle.doricolib
3. Create Kontakt VST player, load your instruments
4. Map player instruments to kontakt, picking the right channel
5. Click settings next to Kontakt VST and select "Komplete - Abbey Road Modern Drummer" map

## Example project

See sample-project.dorico

## Mapping


| Drum       | Articulation           | MIDI Note - Spark | MIDI Note - White | Midi Note Studio Stadium | Dorico  Instrument | Dorico playing technique | Dorico example |
| ------------- |-------------| -----| ---- | --- | ------------- | ------------- | ------------- |
| Kick Drum | Dampened | 36 | % | % | Kick Drum (Low) | Natural | ![image-20200723142455451](README.assets/image-20200723142455451.png) |
|  | Half Open | 82| % |  | |  |  |
|  | Open | 82| % |  | |  |  |
| Snare | Center Right/Left Alternating | 38 | % | % | Snare Drum | Natural| ![image-20200723143044372](README.assets/image-20200723143044372.png) |
|  | Rimshot | 39 | % | % | Snare Drum | Rim shot | ![image-20200723143106420](README.assets/image-20200723143106420.png) |
| | Sidestick | 37 | % | % | Snare Drum | Cross stick| ![image-20200723145609345](README.assets/image-20200723145609345.png) |
|  | Rim only | 61 | % | % | Snare Drum | Rim only| ![image-20200723145621063](README.assets/image-20200723145621063.png) |
| | Roll | 63 | % | % |  | |  |
| | Flam | 62 | % | % |  | |  |
| Hi-Hat | Closed Tight Tip Right/Left Alternating | 66 | % | % | Hi-hat | Closed tight | ![image-20200724152032966](README.assets/image-20200724152032966.png) |
| | Closed Shank Right/Left Alternating | 68 | % | % | Hi-hat | Natural | ![image-20200724134454660](README.assets/image-20200724134454660.png) |
| | Closed Tip Right/Left Alternating | 42 | % | % | Hi-hat | Tip | ![image-20200724135844471](README.assets/image-20200724135844471.png) |
| | Open Quarter | 76 | % | % | Hi-hat | Open Quarter | ![image-20200724142219007](README.assets/image-20200724142219007.png) |
| | Open Half | 77 | % | % | Hi-hat | Half-open | ![image-20200723150532143](README.assets/image-20200723150532143.png) |
| | Open Three-Quarters | 78 | % | % | Hi-hat | Open 3 Quarters | ![image-20200724142822987](README.assets/image-20200724142822987.png) |
| | Open Loose | 79 | % | % | Hi-hat | Open Loose | ![image-20200724143837784](README.assets/image-20200724143837784.png) |
| | Open Full | 80 | % | % | Hi-hat | Open 2 | ![image-20200723150542069](README.assets/image-20200723150542069.png) |
| | Closed Pedal | 44 | % | % | Hi-hat (pedal) | Natural | ![image-20200723154413102](README.assets/image-20200723154413102.png) |
| | Open Pedal | 70 | % | % | Hi-hat (pedal) | Open 2 | ![image-20200723154353499](README.assets/image-20200723154353499.png) |
| Tom 1 | Center Right/Left Alternating | 47 | % | % | Tom (High) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 71 | % | % | Tom (High) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 75 | % | % | Tom (High) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 2 | Center Right/Left Alternating | 45 | % | % | Tom (Medium-high) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 69 | % | % | Tom (Medium-high) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only | 74 | % | % | Tom (Medium-high) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 3 | Center Right/Left Alternating | 43 | % | % | Tom (Medium-low) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 67 | % | % | Tom (Medium-low) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 73 | % | % | Tom (Medium-low) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 4 | Center Right/Left Alternating | 41 | % | % | Tom (Low) | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 65 | % | % | Tom (Low) | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 72 | % | % | Tom (Low) | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Cymbal 1 (High Crash) | Edge | 49 | % | % | Crash Cymbal (High) | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 50 | % | % | Crash Cymbal (High) | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 48        | %       | %      | Crash Cymbal (High) | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 22 | % | % | Crash Cymbal (High) | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 2 (Low Crash) | Edge | 55 | % | % | Crash Cymbal (Low) | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 56 | % | % | Crash Cymbal (Low) | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 54        | %       | %      | Crash Cymbal (Low) | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 24 | % | % | Crash Cymbal (Low) | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 3 (Ride) | Tip | 51 | % | % | Ride Cymbal | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 53 | % | % | Ride Cymbal | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Edge | 52 | % | % | Ride Cymbal | Crush | ![image-20200723195812447](README.assets/image-20200723195812447.png) |
|  | Choke | 23 | % | % | Ride Cymbal | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 4 (China) | Edge | 57 | % | % | China Cymbal | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Tip                                     | 58        | %       | %      | China Cymbal | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 25 | % | % | China Cymbal | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 5 (Splash) | Edge | 59 | % | % | Splash Cymbal | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Choke | 26 | % | % | Splash Cymbal | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Perc 1 (Stick) | Hit | 35 | % | % | Claves | Natural | ![image-20200724161528366](README.assets/image-20200724161528366.png) |
| Perc 2 (Clap) | Solo | 33 | % | % | Hand Claps | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Multi | 34 | % | % | Hand Claps | Chorus | ![image-20200724161603769](README.assets/image-20200724161603769.png) |
| Perc 3 (Cowbell) High | Open | 19 | 29 | NA | Cowbell (High) | Natural | ![image-20200724161620549](README.assets/image-20200724161620549.png) |
|  | Muted | 21 | 30 |  | Cowbell (High) | Muted | ![image-20200724161642875](README.assets/image-20200724161642875.png) |
| Perc 3 (Cowbell) LOW | Open | 16 | 27 | 27 | Cowbell (Low) | Natural | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Muted | 17 | 28 | 28 | Cowbell (Low) | Muted | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| | Open Double |  |  | 29 |  |  |  |
| Perc 3 (Chopper) | High | 29 | 21 | NA | Sizzle Cymbal | Up | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Mid | 28 | 19 | NA | Sizzle Cymbal | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
|  | Low| 27 | 17 | NA | Sizzle Cymbal | Down | ![image-20200724161738346](README.assets/image-20200724161738346.png) |
| Tambourine | Tap | 31 | NA | 31 | Tambourine | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Shake | 32 | NA | 32 | Tambourine | Shake | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| Spiral | Stick | NA | 31 | NA | Suspended Cymbal | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Mallet | NA | 32 | NA | Suspended Cymbal | Shake | ![image-20200724161637285](README.assets/image-20200724161637285.png) |

