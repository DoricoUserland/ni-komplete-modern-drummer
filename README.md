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


| Drum       | Articulation           | MIDI Note  | Dorico playing technique | Dorico example |
| ------------- |-------------| -----| ---- | --- |
| Kick Drum | Dampened | 36 | Natural | ![image-20200723142455451](README.assets/image-20200723142455451.png) |
|  | Half Open | 82|  |  |
|  | Open | 82|  |  |
| Snare | Center Right/Left Alternating | 38 | Natural| ![image-20200723143044372](README.assets/image-20200723143044372.png) |
|  | Rimshot | 39 | Rim shot | ![image-20200723143106420](README.assets/image-20200723143106420.png) |
| | Sidestick | 37 | Cross stick| ![image-20200723145609345](README.assets/image-20200723145609345.png) |
|  | Rim only | 61 | Rim only| ![image-20200723145621063](README.assets/image-20200723145621063.png) |
| | Roll | 63 | |  |
| | Flam | 62 | |  |
| Hi-Hat | Closed Tight Tip Right/Left Alternating | 66 | Closed tight | ![image-20200724152032966](README.assets/image-20200724152032966.png) |
| | Closed Shank Right/Left Alternating | 68 | Natural | ![image-20200724134454660](README.assets/image-20200724134454660.png) |
| | Closed Tip Right/Left Alternating | 42 | Tip | ![image-20200724135844471](README.assets/image-20200724135844471.png) |
| | Open Quarter | 76 | Open Quarter | ![image-20200724142219007](README.assets/image-20200724142219007.png) |
| | Open Half | 77 | Half-open | ![image-20200723150532143](README.assets/image-20200723150532143.png) |
| | Open Three-Quarters | 78 | Open 3 Quarters | ![image-20200724142822987](README.assets/image-20200724142822987.png) |
| | Open Loose | 79 | Open Loose | ![image-20200724143837784](README.assets/image-20200724143837784.png) |
| | Open Full | 80 | Open 2 | ![image-20200723150542069](README.assets/image-20200723150542069.png) |
| | Closed Pedal | 44 | Natural | ![image-20200723154413102](README.assets/image-20200723154413102.png) |
| | Open Pedal | 70 | Open 2 | ![image-20200723154353499](README.assets/image-20200723154353499.png) |
| Tom 1 | Center Right/Left Alternating | 47 | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 71 | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 75 | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 2 | Center Right/Left Alternating | 45 | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 69 | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only | 74 | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 3 | Center Right/Left Alternating | 43 | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 67 | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 73 | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Tom 4 | Center Right/Left Alternating | 41 | Natural | ![image-20200723193619650](README.assets/image-20200723193619650.png) |
|  | Rimshot | 65 | Rim Shot | ![image-20200723194341274](README.assets/image-20200723194341274.png) |
|  | Rim Only| 72 | Rim Only | ![image-20200723194400645](README.assets/image-20200723194400645.png) |
| Cymbal 1 (High Crash) | Edge | 49 | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 50 | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 48        | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 22 | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 2 (Low Crash) | Edge | 55 | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 56 | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Tip                                     | 54        | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 24 | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 3 (Ride) | Tip | 51 | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Bell | 53 | Bell | ![image-20200724121859868](README.assets/image-20200724121859868.png) |
|  | Edge | 52 | Crush | ![image-20200723195812447](README.assets/image-20200723195812447.png) |
|  | Choke | 23 | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 4 (China) | Edge | 57 | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Tip                                     | 58        | Tip                      | ![image-20200725063853715](README.assets/image-20200725063853715.png) |
|  | Choke | 25 | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Cymbal 5 (Splash) | Edge | 59 | Natural | ![image-20200723195754390](README.assets/image-20200723195754390.png) |
|  | Choke | 26 | Choke | ![image-20200723195829114](README.assets/image-20200723195829114.png) |
| Perc 1 (Stick) | Hit | 35 | Natural (Claves) | ![image-20200724161528366](README.assets/image-20200724161528366.png) |
| Perc 2 (Clap) | Solo | 33 | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Multi | 34 | Chorus | ![image-20200724161603769](README.assets/image-20200724161603769.png) |
| Perc 3 (Cowbell) High | Open | 19/29 | Natural | ![image-20200724161620549](README.assets/image-20200724161620549.png) |
|  | Muted | 21/30 | Muted | ![image-20200724161642875](README.assets/image-20200724161642875.png) |
| Perc 3 (Cowbell) LOW | Open | 16/27 | Natural | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Muted | 17/28 | Muted | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| Perc 3 (Chopper) | High | 29/21 | Up | ![image-20200724161624424](README.assets/image-20200724161624424.png) |
|  | Mid | 28/19 | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
|  | Low| 27/17 | Down | ![image-20200724161738346](README.assets/image-20200724161738346.png) |
| Tambourine | Tap | 31/ | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Shake | 32/ | Shake | ![image-20200724161637285](README.assets/image-20200724161637285.png) |
| Spiral | Stick | 31 | Natural | ![image-20200724161535337](README.assets/image-20200724161535337.png) |
| | Mallet | 32 | Shake | ![image-20200724161637285](README.assets/image-20200724161637285.png) |

