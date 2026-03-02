# 555-timer-IC-Mini-Piano
Built a mini electronic piano using a 555 timer IC in astable mode to generate multiple musical tones with push-button keys.
# Mini Analog Piano 🎹 using NE555 Timer IC

## Overview
A functional 7-key analog piano circuit built using the NE555 timer IC 
configured in astable mode. Each key produces a distinct musical tone 
by varying the oscillation frequency through unique resistor values.

## Components Used
| Component        | Value/Type         |
|------------------|--------------------|
| Timer IC         | NE555              |
| Resistors        | 1kΩ (×10), 4.7kΩ  |
| Capacitors       | 100nF, 10µF        |
| Push Buttons     | 7× Momentary Switch|
| Speaker/Buzzer   | 12V                |
| PCB              | Zero PCB           |

## Working Principle
- NE555 configured in *astable mode* generates continuous square waves
- Each push button introduces a *unique resistor* into the timing circuit
- Changing resistance changes the *oscillation frequency* → changes pitch
- Output drives a buzzer/speaker to produce the corresponding musical note

## Project Workflow
1. 📐 Circuit designed and simulated in *LTSpice*
2. 🔌 Prototyped and tested on *breadboard*
3. 🔧 Final circuit soldered onto *Zero PCB*

## Simulation
> LTSpice simulation files included in /simulation folder

## Output
✅ 7 distinct audio tones successfully generated  
✅ Stable output verified through LTSpice waveform analysis  
✅ Final circuit fabricated and tested on Zero PCB  

## Learnings
- Astable mode configuration of NE555 timer
- Relationship between RC values and output frequency
- PCB soldering and hardware debugging
