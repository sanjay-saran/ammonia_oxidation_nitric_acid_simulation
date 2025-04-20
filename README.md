# 🧪 Aspen Simulation – Ammonia Oxidation for Nitric Acid Production

## 📌 Objective
To simulate the industrial production of nitric acid from ammonia via catalytic oxidation using Aspen Plus. The process includes feed preheating, reactor modeling, separation, and product purification.

## 🛠️ Simulation Highlights
- **Software**: Aspen Plus
- **Thermodynamic Model**: Peng-Robinson
- **Major Units**: Mixer, Heater, CSTR Reactor, Flash Drum, Separators
- **Key Streams**: NH3, AIR, FVAPO (vapour), FLIQ (liquid), PURENO2 (Product)

## 📂 Files Included
| File | Description |
|------|-------------|
| `ammonia_nitric_acid_simulation.bkp` | Aspen Plus simulation file |
| `ammonia_oxidation_flowsheet.png` | Main process flowsheet |
| `stream_results.xlsx` | Output data from simulation |
| `ammonia_simulation_report.pdf` | Process description, assumptions, and results |
| `README.md` | Project documentation |

## 🔬 Process Overview
- **Step 1**: Ammonia and air mixed in `MXER`
- **Step 2**: Preheated in `PREHEAT`
- **Step 3**: Sent to `CSTR` for oxidation
- **Step 4**: Products separated via `FLASH` and `SEP1`, with NO₂ purified in `SEP2IN`

## 📊 Results
- **Reactor Temp**: 1000°C  
- **Pressure**: 7.5 bar  
- **NO₂ Purity**: ~98%  
- **NH₃ Conversion**: ~90%  

## 🖥️ How to Use
1. Open Aspen Plus
2. Load `ammonia_nitric_acid_simulation.bkp`
3. Run simulation
4. Explore result tables or exported Excel data

## 📺 Source Reference
Simulation inspired by [this YouTube video](https://www.youtube.com/watch?v=SkXo-hMYg88)

## 📧 Contact
**Sanjay – Chemical Engineering Student**  
[LinkedIn Profile](www.linkedin.com/in/sanjay-senthilkumar-45190a24b)

