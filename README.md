# Modeling Levelized Cost of Charging & Levelized Cost of Battery Swapping

## Project Description
This project aim to model the levelized cost of charging (LCOCS) and levelized cost of battery swapping (LCOBS) for electric vehicles. By simulating the charging and battery swapping processes, we calculate the associated costs and provide insights into the economic aspects of these operations.

Our research result: LCOC_LCOBS_analysis.ipynb 

### What is Levelized Cost of Charging (LCOC)?

The levelized cost of charging (LCOC) is a concept introduced by Borlaug et al. (2020), addressing the need for a comprehensive evaluation of electric vehicle (EV) charging costs. LCOC takes into account the variations in EV recharging and usage patterns, distributing all upfront and operating costs over the total energy supplied throughout the EVSE's (Electric Vehicle Supply Equipment) lifespan.

#### Borlaug et al. (2020) Study:

Borlaug et al. conducted a groundbreaking study that provided a framework for evaluating EV charging costs, with a particular focus on the United States. Their work fills a crucial gap in understanding the economic aspects of EV charging infrastructure by considering diverse factors such as charging patterns, upfront investments, and ongoing operational expenses.

### What is Levelized Cost of Battery Swapping (LCOBS)?

Base on the LCOC concept, our research team model the Levelized Cost of Battery Swapping (LCOBS) which represents the comprehensive evaluation of costs associated with owning and operating a public battery swapping infrastructure designed for electric vehicles (EVs). 

The LCOC and LCOBS provides a comprehensive perspective on the economic aspects of EV recharging, allowing stakeholders to assess the long-term sustainability and feasibility of charging infrastructure investments.

#### Breakdown of LCOC & LCOBS Components:

**Capital Costs:**
- Equipment costs: chargers, cables, connectors, transformers, etc.
- Installation costs: labor, permits, trenching, etc.
- Land costs: purchase or lease of the charging station site.

**Operating and Maintenance Costs:**
- Electricity costs: power consumed by the charging station itself and losses during transmission.
- Maintenance costs: repairs, replacements, software updates, etc.

**Financial Costs:**
- Discount rate: reflects the time value of money.
  
**Other factors:**
- EVSE efficiency 
- Vechile kilometer travel
- Transaction fees
- Fuel consumption rate 
  
## How to Use Our Model

### Prerequisites

Before using the model, ensure you have the following prerequisites installed:

- Python (version X.X.X)
- NumPy
- (Add any other specific libraries or tools required)

### Getting Started

Follow these steps to utilize our model:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo


