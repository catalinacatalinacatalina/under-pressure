# Basic Distortion Pedal - Wampler Design

A complete documentation of designing and building an analog distortion pedal for electric guitars, based on Brian Wampler's minimal parts-count circuit design.

## 🎯 Project Overview

This project is divided into **two distinct phases**, each with its own workflow and deliverables:

1. **Phase 01: Breadboard Prototype** - Testing and validation on solderless breadboard
2. **Phase 02: PCB Design** - Professional PCB layout and manufacturing
3. **Phase 03: PCB Soldering** - Attaching the components to the designed PCB

## 📐 Circuit Architecture

- ⚡ **Stage 1**: 9V battery with virtual ground (Vref) biasing
- 📈 **Stage 2**: implements two gain stages with clipping diodes to shape the distortion character
- 🎚️ **Stage 3**: provides final amplification with impedance buffering for clean output

## 📂 Project Structure

TODO - FILL

## 🚀 Quick Start

### For Breadboard (Phase 01)

1. Understand the schematics
2. Buy the needed components
3. Replicate the circuit on a breadboard
4. Plug your guitar, test audio and tone
5. Confirm ready for PCB

### For PCB Design (Phase 02)

1. Use KiCad to create schematics
2. Design PCB layout
3. Generate Gerber files
4. Order from PCB manufacturer
5. Solder components to PCB

### For PCB Soldering (Phase 03)
...


## 📚 Documentation Roadmap

```
PHASE 01: Breadboard                    PHASE 02: PCB Design                    PHASE 03: PCB Soldering
├── ✅ Understand circuit               ├── ✅ Verify breadboard values         ├── ✅ Prepare soldering tools
├── ✅ Source components                ├── ✅ Create schematic in KiCad        ├── ✅ Solder components
├── ✅ Build on breadboard              ├── ✅ Design PCB layout                ├── ✅ Inspect solder joints
├── ✅ Test audio and tone              ├── ✅ Run design rule check (DRC)      └── ✅ Test PCB functionality
├── ✅ Document final values            ├── ✅ Generate Gerber files
└── ✅ Confirm ready for PCB            └── ✅ Order PCB
```

## 🔗 References

- **Main Tutorial**: [How to Design a Basic Distortion Pedal Circuit](https://www.wamplerpedals.com/blog/lifestyle-hobby/2024/08/how-to-design-a-basic-distortion-pedal-circuit/) - Brian Wampler
- **Main Component Sourcing**: Electronica Embajadores - https://www.electronicaembajadores.com/es/

## 📊 Project Status

| Phase | Status | Progress |
|-------|--------|----------|
| Phase 01: Breadboard | 🔄 In Progress | Components staged, building |
| Phase 02: PCB Design | ⏳ Pending | Waiting for Phase 01 completion |
| Phase 03: PCB Soldering | ⏳ Pending | - |
| Phase 04: PCB Test | ⏳ Pending | - |

## 🛠️ Tools Needed

**Phase 01 (Breadboard)**:
- Solderless breadboard
- Multimeter (for voltage/continuity testing)
- 22 AWG hookup wire
- Guitar & amplifier (for audio testing)

**Phase 02 (PCB Design)**:
- KiCad (free) or Eagle CAD software
- Gerber viewer
- PCB manufacturer (JLCPCB, PCBWay, Elecrow, etc.)

**Phase 03 (PCB Soldering)**:
- Soldering iron
- Lead-free solder (0.8-1.0mm)
- Solder sucker or desoldering wick
- Brass cleaner or damp sponge
- Helping hands tool

---

**Last Updated**: April 7, 2026 | **Design Based On**: Wampler Basic Distortion Circuit (Aug 2024) | **Build Status**: Phase 02 - breadboard building
