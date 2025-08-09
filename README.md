# Root-Cause-Integrity-Analysis-of-Oil-and-Gas-Pipes-Wall-Thinning

![Dashboard Screenshot](dashboard_screenshot.png)

## Overview
This Power BI dashboard analyzes **wall thickness loss in oil and gas pipelines**, identifying **root causes**, **material degradation trends**, and **corrosion impacts** to support **maintenance and integrity management decisions**.

The analysis is based on the dataset [`pipe_thickness_loss_dataset.xlsx`](./pipe_thickness_loss_dataset.xlsx), containing **1,000 pipe records** with details such as material type, grade, operating conditions, degradation rate, corrosion impact, and environmental factors.

---

## Dashboard Features
- **Average Thickness Loss by Grade** – Compares pipeline grades **A–E** based on mean thickness loss (mm).
- **Sum of Thickness Loss by Material** – Highlights which materials contribute most to total thickness loss.
- **Pipe Condition Table** – Lists individual pipes with **condition severity**, material, thickness loss, service time, and corrosion impact.
- **KPI Cards**:
  - Average Degradation Time (years)
  - Average Temperature (°C)
  - Average Thickness Loss (mm)
  - Average Corrosion Impact (%)
  - Number of Pipes
  - Average Max. Pressure (Bar)
- **Interactive Filters** – Slice data by **Grade, Material, and Condition**.

---

## Key Insights
1. **Material Susceptibility**
   - **Copper (1,045 mm)** and **Aluminum (1,035 mm)** show the **highest total thickness loss**.
   - **Steel (954 mm)** performs better but still shows notable degradation.

2. **Grade Performance**
   - Grades **C (5.1 mm)** and **B (5.1 mm)** have the **highest average thickness loss**.
   - Grade **A (4.8 mm)** performs slightly better.

3. **Pipe Conditions**
   - **Critical pipes** are mostly **PVC, Aluminum, and Cast Iron**.
   - Some critical pipes show **>9 mm loss** in just **1 year**.

4. **Environmental Impact**
   - **Average corrosion impact** is **10.09%**, with peaks over **17%**.
   - **Average temperature** of ~39°C could accelerate corrosion.

5. **Operating Pressure**
   - **Average max pressure** is **104.85 Bar**, increasing wall thinning risk.

---

## Recommendations
1. **Prioritize Maintenance for Critical Pipes**
   - Replace or reinforce **PVC, Aluminum, and Cast Iron** in **critical condition**.
   - Schedule **6–12 month inspections** for high-risk materials.

2. **Material Selection Optimization**
   - Prefer **Steel** or **Grade A** for high-pressure zones.
   - Avoid **Copper and Aluminum** in corrosive environments unless coated.

3. **Corrosion Control**
   - Apply **protective coatings** and **cathodic protection**.
   - Track **corrosion impact %** to measure protection effectiveness.

4. **Pressure & Temperature Management**
   - Reduce operational pressures where possible.
   - Install **temperature monitoring** for hotspot detection.

5. **Predictive Maintenance**
   - Use historical data to **forecast degradation**.
   - Schedule replacements based on predicted service life.
