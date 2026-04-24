# Shipping Speed Optimization Under Oil Price Volatility

This project analyzes how bunker fuel price volatility affects cost-minimizing vessel speed for long-haul container shipping. It compares a theoretical voyage-level optimum with a fleet-constrained operational optimum, where weekly service requirements can make slow steaming costly if an additional vessel is needed.

## Project Files

| File | Description |
|---|---|
| `code/vessel_speed_simulation.py` | Python simulation code for vessel speed optimization, fleet sizing, and break-even analysis |
| `report/vessel_speed_optimization_report.pdf` | Final written report explaining the model, assumptions, results, and interpretation |
| `slides/vessel_speed_optimization_slides.pdf` | Final presentation slides |
| `requirements.txt` | Python packages needed to run the simulation |

## Research Question

What is the cost-minimizing vessel speed as oil prices change, and how does the weekly fleet-frequency constraint shift that optimum?

## Key Idea

The model shows that while higher bunker fuel prices theoretically encourage slower sailing, operational constraints can make vessel speed sticky. Slowing down may require adding another vessel to maintain weekly service, and that fixed cost can outweigh fuel savings.

## How to Run the Code

Install the required packages:

```bash
pip install -r requirements.txt
