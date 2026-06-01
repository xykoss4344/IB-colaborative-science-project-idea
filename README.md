# Project HELIOS-NET: Planetary Geoengineering & Thermal Regulation Workstation

An interactive, single-file systems engineering simulation and data visualization dashboard for a planetary energy harvesting and thermal export swarm named **Project HELIOS-NET**.

## System Architecture

HELIOS-NET is a 3-tier planetary energy harvesting and cooling swarm designed to counteract positive radiative forcing:

1. **Tier 1 (Ground Surface)**: Industrial complexes coupled with ground-based Thermophotovoltaic (TPV) micro-arrays to scavenge waste heat.
2. **Tier 2 (Stratosphere, ~20km)**: Autonomous stratospheric aerostat mesh intercepting convective thermal plumes rising through the lower atmosphere.
3. **Tier 3 (Low Earth Orbit, LEO, ~420km)**: Orbiting constellation of Dyson swarm micro-nodes. Each node features an Earth-facing metamaterial absorber (tuned to the 8–13 µm atmospheric window) and a space-facing dilution radiator sink.

### Energy Mechanics
- **70% Off-World Export**: Fired via solid-state Nd:YAG lasers into deep space coordinates (planetary cooling).
- **30% Terrestrial Feed**: Beamed to Earth ground stations via 5.8 GHz microwaves (power grid feed).

---

## Technical Visualizations & Physics Models

- **Atmospheric Cross-Section**: Real-time 2D canvas simulation mapping industrial heat plumes, aerostats, the greenhouse gas barrier, the 8-13 µm atmospheric window, LEO orbit nodes, and continuous laser/microwave streams.
- **Stefan-Boltzmann Radiant Heat Flux**: Live calculation of upwelling thermal flux ($j^* = \epsilon \sigma T^4$) based on dynamic Earth temperatures.
- **Carnot Thermal limit**: Computes thermoelectric Seebeck limit efficiency ($\eta = 1 - T_c / T_h$) between Earth and deep space vacuum.
- **Dynamic Climate Telemetry**: Tracks intercepted energy (GW), net planetary forcing (W/m²), and global equilibrium temp delta (°C).
- **Self-Healing Simulation**: Periodic anomaly detection triggers a de-orbit parabolic burn of the compromised node, followed by a ground payload rocket launch to insert a replacement.

---

## File Contents

- `index.html`: Fully self-contained single-file dashboard containing embedded Tailwind CSS, styling configurations, 3D math projection utilities, and the canvas physics loop.

## How to Run

Simply clone this repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/<username>/IB-collaborative-science-project-idea.git
cd IB-collaborative-science-project-idea
open index.html
```
