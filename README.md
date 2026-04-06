# Basic Distortion Pedal - Wampler Design

A complete documentation of designing and building an analog distortion pedal for electric guitars, based on Brian Wampler's minimal parts-count circuit design.

## 🎯 Project Overview

This project is divided into **two distinct phases**, each with its own workflow and deliverables:

1. **Phase 01: Breadboard Prototype** - Testing and validation on solderless breadboard
2. **Phase 02: PCB Design** - Professional PCB layout and manufacturing

## 📐 Circuit Architecture

- ⚡ **Power Supply**: 9V battery with virtual ground (Vref) biasing
- 📈 **Stage 1**: 
- 🔴 **Stage 2**: 
- 🎚️ **Stage 3**: 

## 📂 Project Structure

TODO - FILL

## � Quick Start

### For Breadboard (Phase 01)

1. Understand the schematics
2. Buy the needed components
3. Replicate the circuit on a breadboard
4. Plug your guitar, test audio and tone
5. Confirm ready for PCB

### For PCB Design (Phase 02)

⏳ **Start after Phase 01 is complete and validated**

1. Read: [phase-02-pcb-design/README.md](phase-02-pcb-design/README.md)
2. Use KiCad to create schematics
3. Design PCB layout
4. Generate Gerber files
5. Order from PCB manufacturer

## 📚 Documentation Roadmap

```
PHASE 01: Breadboard                    PHASE 02: PCB Design
├── ✅ Understand circuit               ├── ✅ Verify breadboard values
├── ✅ Source components                ├── ✅ Create schematic in KiCad
├── ✅ Build on breadboard              ├── ✅ Design PCB layout
├── ✅ Test audio & tone                ├── ✅ Run design rule check (DRC)
├── ✅ Document final values            ├── ✅ Generate Gerber files
└── ✅ Confirm ready for PCB            └── ✅ Order & assemble
```

## 🔗 References

**Main Tutorial**: [How to Design a Basic Distortion Pedal Circuit](https://www.wamplerpedals.com/blog/lifestyle-hobby/2024/08/how-to-design-a-basic-distortion-pedal-circuit/) - Brian Wampler

**Main Component Sourcing**: Electronica Embajadores: https://www.electronicaembajadores.com/es/

## 📊 Project Status

| Phase | Status | Progress |
|-------|--------|----------|
| Phase 01: Breadboard | 🔄 In Progress | Components staged, awaiting build |
| Phase 02: PCB Design | ⏳ Pending | Waiting for Phase 01 completion |

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

## 📝 License

See LICENSE file for details.

---

**Last Updated**: April 7, 2026
**Design Based On**: Wampler Basic Distortion Circuit (Aug 2024)
**Build Status**: Phase 01 preparation
